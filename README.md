# [React を使った Todo アプリケーションの作り方 - React アプリケーションチュートリアル](https://www.youtube.com/watch?v=vvPJQjIdZlw&t=2410s)

| file                    | Original | props                     | useState                                 | useEffect |
| ----------------------- | -------- | ------------------------- | ---------------------------------------- | --------- |
| index.js                |          |                           |                                          |           |
| App.js                  |          |                           | [taskList, setTaskList] = useState([])   |           |
| components/InputForm.js |          | { taskList, setTaskList } | [inputText, setInputText] = useState("") |           |
| components/Title.js     |          |                           |                                          |           |
| components/TodoList.js  |          | { taskList, setTaskList } |                                          |           |

pass data from parent to child is standard props
we can't pass data from child to parent, instead we can write function `Callback props`

| props          | Data            | way      |
| -------------- | --------------- | -------- |
| props          | parent to child | Data     |
| Callback props | child to parent | Function |
