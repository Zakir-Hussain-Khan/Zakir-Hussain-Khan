import React from "react";

const Profile = () => {
  return (
    <div style={{ maxWidth: "900px", margin: "auto", padding: "20px" }}>
      <h1 style={{ textAlign: "center" }}>Hi 👋, I'm Muhammad Zakir Hussain</h1>
      <h3 style={{ textAlign: "center" }}>
        A passionate MERN Developer from Pakistan
      </h3>
      <img
        style={{ float: "right", width: "300px" }}
        src="https://camo.githubusercontent.com/5046cb083418fd1922b7f5990e594c3bb06f5d87e5516cd8839ae0aa48b3aec4/68747470733a2f2f696d616765732e73717561726573706163652d63646e2e636f6d2f636f6e74656e742f76312f3537363966633430316236333162616231616464623261622f313534313538303631313632342d5445363451474b524a4738535741495553374e532f6b6531375a77644742546f6464493870446d34386b506f73776c7a6a53564d4d2d53784f703743563539425a772d7a505067646e346a557756634a45315a7657515578776b6d794578676c4e714770304976544a5a616d574c49327a76595748384b332d735f3479737a63703272795449304871544f6161556f68724938504936465879386339505774426c7141566c555335697a7064634958445a71445976707252715a32395077306f2f636f64696e672d667265616b2e676966"
        alt="Profile"
      />

      <p>
        <img
          src="https://komarev.com/ghpvc/?username=zakir-hussain-khan&label=Profile%20views&color=0e75b6&style=flat"
          alt="Profile views"
        />
      </p>

      <ul>
        <li>
          💻 I’m currently working on <b>Building dynamic Web Applications using MERN stack, integrating MongoDB, Express, React & Node.js</b>
        </li>
        <li>
          📚 I’m currently learning <b>Advanced React, Node.js, RESTful API integration & Redux</b>
        </li>
        <li>
          👨‍💻 All of my projects are available at <a href="https://github.com/Zakir-Hussain-Khan">GitHub</a>
        </li>
        <li>📫 How to reach me <b>zakirkhan23443@gmail.com</b></li>
        <li>⚡ Fun fact <b>I love bringing humor into problem-solving 😅</b></li>
      </ul>

      <h3>Connect with me:</h3>
      <a href="https://linkedin.com/in/zakir-hussain-b594a0245/overlay/about-this-profile/" target="_blank" rel="noreferrer">
        <img
          src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg"
          alt="LinkedIn"
          height="30"
          width="40"
        />
      </a>

      <h3>Languages and Tools:</h3>
      <div style={{ display: "flex", flexWrap: "wrap", gap: "10px" }}>
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="HTML5" width="40" height="40" />
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="CSS3" width="40" height="40" />
        <img src="https://logos-world.net/wp-content/uploads/2023/02/JavaScript-Symbol.png" alt="JS" width="55" height="40" />
        <img src="https://www.logotypes101.com/logos/203/272663FA02DE2DAA2BBAE2FC39F14783/php.png" alt="PHP" width="40" height="40" />
        <img src="https://cdn.worldvectorlogo.com/logos/laravel-3.svg" alt="Laravel" width="40" height="40" />
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="MySQL" width="50" height="50" />
        <img src="https://cdn.iconscout.com/icon/free/png-256/free-jquery-logo-icon-download-in-svg-png-gif-file-formats--wordmark-programming-langugae-freebies-pack-logos-icons-1175153.png" alt="jQuery" width="40" height="40" />
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTEAmAZJkl49wqGmS0dWhlGo-CYpaAT-g_WCA&s" alt="Bootstrap" width="40" height="40" />
        <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="Git" width="40" height="40" />
      </div>

      <div style={{ display: "flex", marginTop: "20px", gap: "10px", flexWrap: "wrap" }}>
        <img src="https://github-readme-stats.vercel.app/api/top-langs?username=zakir-hussain-khan&show_icons=true&locale=en&layout=compact" alt="Top Languages" />
        <img src="https://github-readme-stats.vercel.app/api?username=zakir-hussain-khan&show_icons=true&locale=en" alt="GitHub Stats" />
        <img src="https://github-readme-streak-stats.herokuapp.com/?user=zakir-hussain-khan" alt="Streak Stats" />
      </div>
    </div>
  );
};

export default Profile;
