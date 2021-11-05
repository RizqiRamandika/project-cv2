<template>
  <div class="a">
    <h1 style="text-align: center">CV-2</h1>
    <div v-for="cd in cvDua" :key="cd">
      <div class="bg"></div>
      <div class="res">{{ cd.cv1 }}</div>
      <div class="jud" style="font-family: 'Courier New', Courier, monospace">
        <div class="gb">
          <div style="text-align: right">
            <img
              class="gm"
              src="https://img.lovepik.com/free_png/28/90/69/74a58PICS3mJdfM7ZU5ef_PIC2018.png_860.png"
              width="200"
              height="200"
              style="border-radius: 100px"
            />
            <h3 style="color: black; text-align: right">{{ cd.cv2 }}</h3>
            <hr
              style="
                border: 1px dashed black;
                padding-left: 10px;
                padding-right: 10px;
              "
            />
            <p style="color: black">
              <b>{{ cd.cv4 }}</b
              ><br />{{ cd.cv5 }}
            </p>
            <p style="color: black">
              <b>{{ cd.cv6 }}</b
              ><br />{{ cd.cv7 }}
            </p>
            <p style="color: black">
              <b>{{ cd.cv8 }}</b
              ><br />{{ cd.cv9 }}
            </p>
            <p style="color: black">
              <b>{{ cd.cv10 }}</b
              ><br />{{ cd.cv11 }}
            </p>
            <h3 style="color: black; text-align: right">{{ cd.cv12 }}</h3>
            <hr
              style="
                border: 1px dashed black;
                padding-left: 10px;
                padding-right: 10px;
              "
            />
            <p style="color: black">
              <b>{{ cd.cv13 }}</b
              ><br />{{ cd.cv14 }}
            </p>
            <p style="color: black">
              <b>{{ cd.cv15 }}</b
              ><br />{{ cd.cv16 }}
            </p>
            <h3 style="color: black; text-align: right">{{ cd.cv17 }}</h3>
            <hr
              style="
                border: 1px dashed black;
                padding-left: 10px;
                padding-right: 10px;
              "
            />
            <p style="color: black">
              <b>{{ cd.cv18 }}</b
              ><br />{{ cd.cv19 }}
            </p>
            <p style="color: black">
              <b>{{ cd.cv20 }}</b
              ><br />{{ cd.cv19 }}
            </p>
            <p style="color: black">
              <b>{{ cd.cv21 }}</b
              ><br />{{ cd.cv22 }}
            </p>
            <h3 style="color: black; text-align: right">{{ cd.cv23 }}</h3>
            <hr
              style="
                border: 1px dashed black;
                padding-left: 10px;
                padding-right: 10px;
              "
            />
            <p style="color: black">
              <b>{{ cd.cv24 }}</b
              ><br />{{ cd.cv25 }}
            </p>
            <p style="color: black">
              <b>{{ cd.cv26 }}</b
              ><br />{{ cd.cv27 }}
            </p>
          </div>
        </div>
        <div class="cb" style="font-family: 'Courier New', Courier, monospace">
          <h2>{{ cd.cv28 }}<br />{{ cd.cv29 }}</h2>
        </div>
      </div>
      <br /><br />
      <div style="margin-left: 320px">
        <h2>
          {{ cd.cv30 }}
          <hr style="border: 1px solid black" />
        </h2>
        <div
          style="
            margin-left: 20px;
            margin-right: 20px;
            background-color: rgb(212, 209, 209);
          "
        >
          <br /><br />
          <h2 style="margin-left: 20px">{{ cd.cv31 }}</h2>
          <hr
            style="
              border: 1px dashed black;
              padding-left: 10px;
              padding-right: 10px;
              margin-left: 20px;
              margin-right: 20px;
            "
          />
          <div style="display: flex; margin-left: 20px; margin-right: 20px">
            <p>
              <b>{{ cd.cv32 }}</b
              ><br />{{ cd.cv33 }}
            </p>
            <div style="margin-left: 50px">
              <p>
                <b>{{ cd.cv34 }}</b
                ><br />Lorem ipsum dolor sit amet consectetur adipisicing elit.
              </p>
            </div>
          </div>
          <div style="display: flex; margin-left: 20px; margin-right: 20px">
            <p><b>CREATIVE</b><br />Feb 2013 - Jun 2014</p>
            <div style="margin-left: 50px">
              <p>
                <b>SENIOR ART DIRECTOR</b><br />Lorem ipsum dolor sit amet
                consectetur adipisicing elit.
              </p>
            </div>
          </div>
          <div style="display: flex; margin-left: 20px; margin-right: 20px">
            <p><b>CREATIVE</b><br />Feb 2013 - Jun 2014</p>
            <div style="margin-left: 50px">
              <p>
                <b>SENIOR ART DIRECTOR</b><br />Lorem ipsum dolor sit amet
                consectetur adipisicing elit.
              </p>
            </div>
          </div>
        </div>
        <br />
        <div
          style="
            margin-left: 20px;
            margin-right: 20px;
            background-color: rgb(212, 209, 209);
          "
        >
          <br />
          <h2 style="margin-left: 20px">EDUCATION</h2>
          <hr
            style="
              border: 1px dashed black;
              padding-left: 10px;
              padding-right: 10px;
              margin-left: 20px;
              margin-right: 20px;
            "
          />
          <br />
          <div style="display: flex; margin-left: 20px; margin-right: 20px">
            <p><b>MASTER DEGREE</b><br />Feb 2011 - Jun 2014</p>
            <div style="margin-left: 50px">
              <p>
                <b>UNIVERSITY OF CREATIVE MINDS</b><br />Jakarta, Indonesia.
              </p>
            </div>
          </div>
          <div style="display: flex; margin-left: 20px; margin-right: 20px">
            <p><b>MASTER DEGREE</b><br />Feb 2011 - Jun 2014</p>
            <div style="margin-left: 50px">
              <p>
                <b>UNIVERSITY OF CREATIVE MINDS</b><br />Jakarta, Indonesia.
              </p>
            </div>
          </div>
          <div style="display: flex; margin-left: 20px; margin-right: 20px">
            <p><b>MASTER DEGREE</b><br />Feb 2011 - Jun 2014</p>
            <div style="margin-left: 50px">
              <p>
                <b>UNIVERSITY OF CREATIVE MINDS</b><br />Jakarta, Indonesia.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "CvDua",
  computed: {
    cvDua() {
      return this.$store.state.cvDua;
    },
  },
};
</script>