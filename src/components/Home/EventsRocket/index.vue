<template>
  <section class="container">
    <div class="container__events">
      <div class="container__events__text">
        <div class="container__events__text__title">
          <h3>
            Eventos feitos pela Rocketseat
          </h3>
        </div>
        <div>
          <div class="container__events__text__border"></div>
          <p>
            Participe de eventos alinhados com seu momento na programação e
            evolua junto com a comunidade. Fique por dentro dos principais
            eventos da Rocketseat e outros inéditos.
          </p>
        </div>
      </div>
      <div class="container__events__content">
        <div class="container__events__content__discover">
          <div class="container__events__content__discover__span">
            <span>Aprenda programação do zero, e de graça.</span>
          </div>
          <img src="@/assets/discover.png" alt="" />
          <h3>Maratona Discover</h3>
          <p>
            Impulso extra para começar sua jornada, construir os alicerces na
            prática e avançar na direção certa rumo aos seus objetivos.
          </p>
        </div>
        <div class="container__events__content__nlw">
          <div class="container__events__content__nlw__span">
            <span>Avance para o próximo nível.</span>
          </div>
          <img src="@/assets/nlw.png" alt="" />
          <h3>Next Level Week</h3>
          <p>
            Um evento para toda a comunidade evoluir junto, na prática. São dias
            intensos com hacks de carreira e muita mão na massa.
          </p>
        </div>
        <div class="container__events__content__dowhile">
          <div class="container__events__content__dowhile__span">
            <span>Never Stop Learning</span>
          </div>
          <img src="@/assets/dowhile.png" alt="" />
          <h3>Do While</h3>
          <p>
            Reunimos todo ecossistema com um único objetivo: o aprendizado
            contínuo. Evento plural de comunidades, tecnologias e empresas.
          </p>
        </div>
      </div>

      <div class="container__events__contact">
        <div class="container__events__contact__title">
          <h3>Receba informações sobre nossos eventos em primeira mão</h3>
        </div>
        <div class="container__events__contact__bottom">
          <div class="container__events__contact__bottom__box">
            <div class="container__events__contact__bottom__box__input">
              <svg
                stroke="currentColor"
                fill="rgba(255, 255, 255, 0.122)"
                stroke-width="0"
                viewBox="0 0 24 24"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M20 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4l-8 5-8-5V6l8 5 8-5v2z"
                ></path>
              </svg>
              <input type="text" placeholder="E-mail" />
            </div>
            <div class="container__events__contact__bottom__box__checkbox">
              <input type="checkbox" />
              <p>Concordo em receber comunicações</p>
            </div>
            <button class="container__events__contact__bottom__box__button">
              ME INSCREVER
            </button>
          </div>

          <div class="container__events__contact__bottom__information">
            <img src="@/assets/icone.png" alt="" />
            <p>Suas informações estão seguras</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.container {
  &__events {
    display: flex;
    max-width: 1120px;
    margin: 0 auto;
    justify-content: center;
    flex-direction: column;

    &__text {
      display: flex;
      margin-top: 10%;
      justify-content: space-between;
      font-family: "Roboto", sans-serif;
      &__title {
        width: 400px;
        h3 {
          color: #e1e1e6;
          font-size: 48px;
          font-family: "Roboto", sans-serif;
        }
      }
      &__border {
        display: flex;
        align-items: flex-end;
        margin-right: 50px;
        width: 50px;
        border-bottom: 1px solid rgba(255, 255, 255, 0.123);
      }
      p {
        margin-right: 50px;
        margin-top: 40px;
        width: 625px;
        color: #a8a8b3;
        font-family: "Roboto", sans-serif;
      }
    }
    &__content {
      display: flex;
      margin: 50px 0;
      &__discover {
        width: 352px;
        height: 400px;
        margin: 0 30px 10px 0;
        img {
          border-radius: 5px;
        }
        &__span {
          width: 200px;
          margin: 10% 0;
          font-size: 20px;
          font-family: "Roboto", sans-serif;
          color: #8257e5;
          font-weight: normal;
        }
        p {
          color: #a8a8b3;
          font-family: "Roboto", sans-serif;
          line-height: 150%;
        }
        h3 {
          margin: 25px 0;
          font-size: 32px;
          color: #e1e1e6;
          font-family: "Roboto", sans-serif;
        }
      }
      &__nlw {
        width: 352px;
        height: 400px;
        margin: 0 30px 10px 0;
        font-family: "Roboto", sans-serif;
        img {
          border-radius: 5px;
        }
        &__span {
          margin: 10% 0;
          width: 200px;
          font-size: 20px;
          color: #04d361;
        }
        p {
          color: #a8a8b3;
          font-family: "Roboto", sans-serif;
          line-height: 150%;
        }
        h3 {
          margin: 25px 0;
          font-size: 32px;
          color: #e1e1e6;
        }
      }
      &__dowhile {
        width: 352px;
        height: 400px;
        margin: 0 30px 10px 0;
        font-family: "Roboto", sans-serif;
        img {
          border-radius: 5px;
        }
        &__span {
          margin: 10% 0;
          width: 150px;
          font-size: 20px;
          color: #ff248a;
        }
        p {
          color: #a8a8b3;
          font-family: "Roboto", sans-serif;
          line-height: 150%;
        }
        h3 {
          margin: 25px 0;
          font-size: 32px;
          color: #e1e1e6;
        }
      }
    }
    &__contact {
      border-top: 1px solid rgba(255, 255, 255, 0.123);
      margin-top: 20px;
      font-family: "Roboto", sans-serif;
      &__title {
        margin: 65px 0 30px 0;
        width: 500px;
        h3 {
          font-size: 32px;
          color: #e1e1e6;
        }
      }
      &__bottom {
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin-bottom: 13%;
        &__box {
          display: flex;
          align-items: center;
          justify-content: space-around;
          width: 928px;
          height: 128px;
          margin-top: 10px;
          padding: 32px 40px;
          background: var(--darke-gradient);
          border-radius: 5px;
          &__input {
            display: flex;
            align-items: center;
            background: #121214;
            border: none;
            border-radius: 5px;
            font-family: "Roboto", sans-serif;
            padding-left: 20px;
            input {
              width: 316.08px;
              height: 64px;
              font-size: 16px;
              border: none;
              background: transparent;
              font-family: "Roboto", sans-serif;
              padding: 18px 20px;
            }
            svg {
              width: 23.92px;
              height: 26px;
            }
          }
          &__checkbox {
            display: flex;
            align-items: center;
            margin: 0 20px;
            padding: 16px 0px;
            border-top: 1px solid #29292e;
            border-bottom: 1px solid #29292e;
            // input::after {
            //   width: 20px;
            //   background: #121214;
            //   height: 20px;
            //   border-radius: 3px;
            //   border: 1px solid #04d361;
            // }
            // input::before {
            //   width: 20px;
            //   background: #04d361;
            //   height: 20px;
            //   border-radius: 3px;
            // }
            p {
              font-family: "Roboto", sans-serif;
              margin-left: 8px;
              color: #a8a8b3;
              font-size: 14px;
            }
          }
          &__button {
            width: 180px;
            height: 56px;
            background: #8257e5;
            border-radius: 5px;
            border: none;
            font-family: "Roboto", sans-serif;
            font-size: 14px;
            color: #ffffff;
            cursor: pointer;
            font-weight: bold;
          }
        }
        &__information {
          display: flex;
          width: 152.88px;
          align-items: center;
          justify-content: space-between;
          padding: 38px 0;
          margin-top: 10px;
          border-top: 1px solid #29292e;
          border-bottom: 1px solid #29292e;
          img {
            margin-right: 16px;
            width: 24px;
            height: 24px;
          }
          p {
            font-family: "Roboto", sans-serif;
            color: #a8a8b3;
            font-size: 14px;
            line-height: 22px;
          }
        }
      }
    }
  }
}
</style>
