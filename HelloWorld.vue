<template>
  <div class="page">
    <section class="live-vedio">
      <div class="container p-0">
        <div class="vedio-content">
          <div class="vedio-container">
            <img src="../assets/mask_group_109.png" />
          </div>
          <div class="info">
            <h2 class="title uppercase font-semibold">Watermelon Tuna</h2>
            <p class="description font-medium">
              But I must explain to you how all this mistaken idea of denouncing
              pleasure and praising pain was born and I will give you a complete
              account of the system, and expound the actual….
            </p>
            <div class="time">time</div>
            <div class="video-status">
              <div class="start">
                <button>
                  <p>start live</p>
                  <div class="icon-start-container">
                    <img src="../assets/icon_awesome-play-circle.png" />
                  </div>
                </button>
                <button>
                  <p>start</p>
                  <div class="icon-start-container">
                    <img src="../assets/icon_awesome-play-circle.png" />
                  </div>
                </button>
              </div>
              <div class="path">
                <button>
                  <p>path live</p>
                  <div class="icon-path-container">
                    <img src="../assets/path_5862.png" />
                  </div>
                </button>
                <button>
                  <p>path</p>
                  <div class="icon-path-container">
                    <img src="../assets/path_5862.png" />
                  </div>
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  },
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
@import url("https://use.typekit.net/qee3pci.css");

* {
  font-family: "proxima-nova", sans-serif;
}
@media (min-width: 1400px) {
  .container-xxl,
  .container-xl,
  .container-lg,
  .container-md,
  .container-sm,
  .container {
    /* max-width: 1358px; */
    min-width: 1348px !important;
  }
  h1,
  h2,
  h3,
  h4,
  h5,
  h6,
  p {
    padding: 0;
    margin: 0;
  }
}
$background: #333;
$body-color: #eee;

.page {
  background-color: black;
}
body,
html {
  // background-color: $background;
  padding: 0;
  margin: 0;
  color: $body-color !important;
}
.vedio-content {
  display: flex;
  gap: 1.875rem;
  .vedio-container {
    width: 69.4%;
    img {
      width: 100%;
      height: 100%;
    }
  }
  .info {
    width: 30.6%;
    .title {
      font-size: 1.5rem;
      color: rgba(255, 255, 255, 1);
      margin: 0;
    }
    .description {
      font-size: 1rem;
      color: rgba(255, 255, 255, 1);
      margin: 1.25rem 0 0;
    }
    .time {
      margin: 6rem 0 3.875rem;
      display: flex;
      flex-direction: column;
      align-items: center;
    }
    .video-status {
      display: flex;
      flex-direction: column;
      align-items: center;
    }
    .video-status .start {
      display: flex;
      gap: 26px;
      margin-bottom: 12px;
    }
    .video-status .path {
      display: flex;
      gap: 1.625rem;
    }
    .video-status button {
      display: flex;
      justify-content: space-around;
      align-items: center;
      p {
        margin: 0;
        font-size: 0.875rem;
        color: rgba(255, 255, 255, 1);
        text-transform: uppercase;
        font-weight: 700;
      }
    }
    .video-status button:nth-of-type(1),
    .video-status button:nth-of-type(3) {
      height: 2.5rem;
      width: 8.75rem;
      background-color: transparent;
      border: 0.125rem solid rgba(255, 255, 255, 1);
      border-radius: 1.25rem;
    }
    .video-status button:nth-of-type(2),
    .video-status button:nth-of-type(4) {
      height: 2.5rem;
      width: 6.25rem;
      background-color: transparent;
      border: 0.125rem solid rgba(255, 255, 255, 1);
      border-radius: 1.25rem;
    }
  }
}
.bg-gray {
  background: $background;
}
h1 {
  color: #eee !important;
}

.font-medium {
  font-weight: 500;
}

.font-semibold {
  font-weight: 600;
}

.font-bold {
  font-weight: bold;
}

.uppercase {
  text-transform: uppercase;
}
.capitalize {
  text-transform: capitalize;
}
.lowercase {
  text-transform: lowercase;
}
.main-header {
  font-size: 6.25rem;
  @media (max-width: 992px) {
    font-size: 5.8rem;
  }
  @media (max-width: 768px) {
    font-size: 5rem;
  }
}
.title {
  font-size: 3.5rem;
  margin-left: -5rem;
  margin-bottom: 2rem;
}
// .subtitle{
//   font-size: 3.5rem;
// }
.description {
  font-size: 1.875rem;
  // @media (max-width: 768px) {
  //   font-size: 2rem;
  // }
}
.boxes-title {
  font-size: 2rem;
}
.boxes-description {
  font-size: 1.8rem;
}
.linkes {
  font-size: 1.625rem;
  @media (max-width: 768px) {
    font-size: 1.4rem;
  }
}
.floating-section-title {
  font-size: 1.875rem;
  z-index: 8888;
}
.wrap {
  @media (max-width: 768px) {
    padding: 0 !important;
  }
}
.margin-t {
  @media (max-width: 992px) {
    margin-top: 10rem !important;
  }
  @media (max-width: 768px) {
    margin-top: 8.75rem !important;
  }
}
.margin-b {
  @media (max-width: 992px) {
    margin-bottom: 10rem !important;
  }
  @media (max-width: 768px) {
    margin-bottom: 8.75rem !important;
  }
}
</style>
