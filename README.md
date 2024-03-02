Udemy課程練習 #click #Alert #input # keydown #keyup

1.點擊button顯示alert

    <!-- html -->
    <button v-on:click="showAlert">Show Alert</button>

1-1 alert 彈跳視窗寫法

    // JavaScript
    methods: {
      showAlert() {
        alert("Show Alert");       
      },
    }

2.keydown 監聽鍵盤按鍵按下的事件

    <!-- html -->
    v-on:keydown="saveInput"

2-1 event 事件  target 觸發 value 數值

    // JavaScript
    methods: {
      saveInput(event) {
        this.userInput = event.target.value;
      },
    }

2-2  v-on:keyup.enter 監聽鍵盤按下特定按鍵 這裡為enter

     v-on:keyup.enter="confirmInput"

