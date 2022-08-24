<template>
  <div class="design-page">
    <div class="circle">
      <div class="card-1">
        <div class="card-title">Tags Used</div>
        <button class="btn-tags">Card UI</button>
        <button class="btn-tags">Free UI</button>
        <button class="btn-tags">UI Design Daily</button>
        <button class="btn-tags">UI Components</button>
        <button class="btn-tags">UI Design</button>
      </div>
      <div class="card-2">
        <div class="card-title">Authors</div>
        <div class="users">
          <div class="user">
            <div class="user-page">
              <img src="../image/image2.jpg" class="circular-page" />
            </div>
            <div class="user-info">
              <div class="user-name">Polly Lawson</div>
              <div class="city">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="20"
                  height="20"
                  viewBox="0 0 24 24"
                  fill="none"
                  stroke="#fbc292"
                  stroke-width="3"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  class="feather feather-map-pin"
                >
                  <path
                    d="M21 10c0 7-9 13-9 13s-9-6-9-13a9 9 0 0 1 18 0z"
                  ></path>
                  <circle cx="12" cy="10" r="3"></circle></svg
                >Bergen,Norway
              </div>
            </div>
            <button class="btn-follow">Follow</button>
          </div>
          <div class="user">
            <div class="user-page">
              <img src="../image/image1.jpg" class="circular-page" />
            </div>
            <div class="user-info">
              <div class="user-name">Kathryn Reyes</div>
              <div class="city">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="20"
                  height="20"
                  viewBox="0 0 24 24"
                  fill="none"
                  stroke="#fbc292"
                  stroke-width="3"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  class="feather feather-map-pin"
                >
                  <path
                    d="M21 10c0 7-9 13-9 13s-9-6-9-13a9 9 0 0 1 18 0z"
                  ></path>
                  <circle cx="12" cy="10" r="3"></circle></svg
                >Bergen,Norway
              </div>
            </div>
            <button class="btn-follow">Follow</button>
          </div>
        </div>
      </div>
      <div class="card-3">
        <div class="card-title">Day 13010- People List UI Design</div>
        <div class="box">
          <div class="icon">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              fill="none"
              stroke="currentColor"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
              class="feather feather-thumbs-up"
            >
              <path
                d="M14 9V5a3 3 0 0 0-3-3l-4 9v11h11.28a2 2 0 0 0 2-1.7l1.38-9a2 2 0 0 0-2-2.3zM7 22H4a2 2 0 0 1-2-2v-7a2 2 0 0 1 2-2h3"
              ></path>
            </svg>
            <div class="icon-title">47</div>
          </div>
          <div class="icon">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              fill="none"
              stroke="currentColor"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
              class="feather feather-eye"
            >
              <path d="M1 12s4-8 11-8 11 8 11 8-4 8-11 8-11-8-11-8z"></path>
              <circle cx="12" cy="12" r="3"></circle>
            </svg>
            <div class="icon-title">3877</div>
          </div>
          <div class="icon">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              fill="none"
              stroke="currentColor"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
              class="feather feather-message-square"
            >
              <path
                d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"
              ></path>
            </svg>
            <div class="icon-title">3877</div>
          </div>
        </div>
        <button class="btn-like">Like this project</button>
      </div>
    </div>
  </div>
</template>
<style lang="scss" scoped>
.design-page {
  background-color: #fbebe3;
  position: fixed;
  width: 100%;
  height: 100%;
  margin-top: -10px;
  margin-left: -10px;
}
.circle {
  background-color: #fbc292;
  border-radius: 250px;
  width: 500px;
  height: 500px;
  margin-left: 500px;
  margin-top: 150px;
}
.card-1 {
  width: 60%;
  height: 24%;
  background-color: #fff;
  border-radius: 8px;
  margin-left: -50px;
}
.card-2 {
  width: 70%;
  height: 45%;
  background-color: #fff;
  border-radius: 8px;
  margin-left: 200px;
  margin-top: -70px;
}
.card-3 {
  width: 65%;
  height: 45%;
  background-color: #fff;
  border-radius: 8px;
  margin-left: 55px;
  margin-top: -18px;
}
.user {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-top: 10px;
}
.circular-page {
  border-radius: 50%;
  height: 60px;
  width: 60px;
  object-fit: cover;
  margin-left: 10px;
}
.btn-follow {
  cursor: pointer;
  border-radius: 4px;
  display: inline-block;
  font-size: 12px;
  font-weight: bold;
  height: 30px;
  transition-duration: 0.5s;
  background-color: #fbc292;
  margin-left: 60px;
  margin-right: 10px;
  border-color: rgb(198, 177, 177);
}
.btn-tags {
  cursor: pointer;
  border-radius: 4px;
  display: inline-block;
  font-size: 12px;
  font-weight: bold;
  height: 30px;
  transition-duration: 0.5s;
  background-color: #fff;
  margin-left: 4px;
  margin-top: 4px;
  border-color: rgb(198, 177, 177);
}
.btn-like {
  cursor: pointer;
  border-radius: 4px;
  display: inline-block;
  font-size: 12px;
  font-weight: bold;
  height: 35px;
  transition-duration: 0.5s;
  background-color: #fbc292;
  margin-top: 35px;
  margin-left: 10px;
  border-color: rgb(198, 177, 177);
}
.users {
  display: flex;
  flex-direction: column;
  margin-top: 30px;
}
.city {
  font-size: 12px;
  margin-top: -3px;
}
.user-name {
  font-size: 15px;
  font-weight: 600;
}
.box {
  border-style: solid;
  border-color: rgb(222, 222, 222);
  border-width: 1px;
  border-radius: 2px;
  display: flex;
  justify-content: space-between;
  width: 300px;
  height: 50px;
  margin-top: 70px;
  margin-left: 10px;
}
.icon {
  display: flex;
  justify-content: space-between;
  margin-top: 10px;
}
.icon-title {
  font-size: 13px;
  margin-left: 4px;
  margin-top: 4px;
}
</style>
