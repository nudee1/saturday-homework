<template>
  <div class="container">
    <h1 class="title is-1">👩‍💻 👨‍💻 Saturday Homeworks.</h1>
    <iframe src="https://ghbtns.com/github-btn.html?user=saturday-js&repo=saturday-homework&type=fork&count=true&size=large" frameborder="0" scrolling="0" width="158px" height="30px"></iframe>
    <br><br>
    <table class="table is-striped is-hoverable is-fullwidth">
      <thead>
        <tr>
          <th>รหัสนักศึกษา</th>
          <th>ชื่อ-นามสกุล</th>
          <th>การบ้าน</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>6066260000312</td>
          <td>เนติ นามวงศ์</td>
          <td>
            <router-link to="/nati">Manchester United 2017/18 Squad Numbers.</router-link>
          </td>
        </tr>
        <tr>
          <td>5806021633010</td>
          <td>ชลธิชา สูริผัส</td>
          <td>
            <router-link to="/Chonticha">Review Dink</router-link>
           </td>
        </tr>
        <tr> 
          <td>5806021631122</td>
          <td>วราคณา ปั้นทอง</td>
          <td>
          <router-link to="/warakana">Ghibli Studio</router-link>
        </td>
      </tr>
      <tr>
          <td>5806021632013</td>
          <td>กิตติธัช เพิ่มรุ่งเรือง</td>
          <td>
            <router-link to="/Kittitah">Popular Star Actors</router-link>
          <td>5806021622123</td>
          <td>นันทวัฒน์ พรหมศร</td>
          <td>
            <router-link to="/nanthawad">FIFA WORLD CUP 2014 All Players.</router-link>
          </td>
        </tr>
        <tr>
          <td>5806021630126</td>
          <td>พีรพล สวัสดี</td>
          <td>
            <router-link to="/Fuse">World Time</router-link>
        </tr>
          <td>5806021631041</td>
          <td>ณัฐพล ไชยภา</td>
          <td>
            <router-link to="/jack">Hero of storm.</router-link>
          </td>
         </tr>
         <tr>
          <td>5806021630151</td>
          <td>ศิลวัต ลีลาศ</td>
          <td>
            <router-link to="/Sillawat">Movie is Coming</router-link>
          </td>
        </tr>
        <tr>
          <td>5806021622051</td>
          <td>รชต ทองภักดี</td>
          <td>
            <router-link to="/Rachata">Giphy Search</router-link>
          </td>
        </tr>
        <tr>
          <td>5806021622140</td>
          <td>ฤทธิพร โพธิ์อรุณ</td>
          <td>
            <router-link to="/Rittiphon">Dota 2 Heroes</router-link>
          </td>
        </tr>
         <tr>
          <td>5806021612047</td>
          <td>สหพัฒ แก้วนิล</td>
          <td>
            <router-link to="/Sahapat">NASA Search image</router-link>
          </td>
        </tr>
        <tr>
          <td>5806021612039</td>
          <td>ศิรินันท์  การบรรจง</td>
          <td>
            <router-link to="/Sirinun">Sports News </router-link>
          </td>
        </tr>
        <tr>
          <td>5806021620082</td>
          <td>เบญจรงค์ เรืองศิลป์ </td>
          <td><router-link to="/benjarong">dog</router-link></td>
        </tr>
      </tbody>
    </table>
  </div>
</template>

<script>
export default {
  name: 'Home',
  data () {
    return {}
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
