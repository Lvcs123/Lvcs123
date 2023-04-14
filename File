- 👋 Hi, I’m @Lvcs123
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Lvcs123/Lvcs123 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
$("#music").click(function(){
  play();
});

var player = document.getElementById("audio");
play();
function play(){
swal("Bạn có muốn bật nhạc 🎶 và vừa nghe nhạc vừa xem không ❓\n" ,{
        buttons: {
          allowcancel: "Tắt Nhạc",
            allow: "Bật Nhạc"
        }
    }).then(function(value) {
        if (value == "allow") {
          player.play()
        } else {
          player.pause()
      
        }
    });
}
