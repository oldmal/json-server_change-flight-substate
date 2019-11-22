# json-server_change-flight-substate - Примеры substate-ов
Стучаться нужно в репозиторий json-server_change-flight-substate, после чего указывать либо db(получим весь файл), либо ключ обьекта, например flights

# Ограничения
Так как в db.json макимальное количество ключей - 5, проекты разбиты на файлы, если нужно использовать какой-либо - нужно скопировать данные в db.json

# example
const runTestFunc = function(interval) {
  $.ajax({
    url: `https://my-json-server.typicode.com/oldmal/json-server_change-flight-substate/flights`,
    type: 'GET'
  })
    .done(function(res) {
      console.log(res);
    };
};
