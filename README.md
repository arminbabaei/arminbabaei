 > <h1 align='center'>
  > Hi there 👋 I'm Armin 👨‍💻
</h1>


  ``` js
  async function getJob() {
  try {
    const developer = get({
      nickName: 'armin',
      birthday: '1991-01-01',
      city: 'Tehran',
      job: 'Front-End Developer',
      level: 'Junior',
      slills: {
          all: 'HTML5, CSS3, JavaScript, TailwindCSS, ReactJS'
      }
    });
    const response = await developer.response;
    console.log('GET call succeeded: ', response);
  } catch (e) {
    console.log('GET call failed: ', JSON.parse(e.response.body));
  }
}
  ```
</p>
<p align='center'>
  <a href="#"><img src="https://github-readme-stats.vercel.app/api?username=arminbabaei&show_icons=true&count_private=true&theme=tokyonight" width="400"></a>
 <a href="#"><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=arminbabaei&hide_progress=true" width="440"></a>
</p>
<p align='center'>
  📫 How to reach me : <a href='mailto:armin6911y@gmail.com.com'>Email</a>
</p>


