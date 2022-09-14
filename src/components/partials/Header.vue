<template>
    <header id="page-topbar">
      <div class="navbar-header">
        <div class="d-flex">
          <div class="navbar-brand-box">
            <a
              aria-current="page"
              href="/"
              class="router-link-active router-link-exact-active logo logo-dark"
              ><span class="logo-sm"
                ></span
              ><span class="logo-lg"
                ></span></a
            ><a
              aria-current="page"
              href="/"
              class="router-link-active router-link-exact-active logo logo-light"
              ><span class="logo-sm"
                ></span
              ><span class="logo-lg"
                ></span
            ></a>
          </div>
          <button
            id="vertical-menu-btn"
            type="button"
            class="btn btn-sm px-3 font-size-16 header-item"
          >
            <i class="fa fa-fw fa-bars"></i>
          </button>
          <form class="app-search d-none d-lg-block">
            <div class="position-relative">
              <input
                type="text"
                class="form-control"
                placeholder="Search..."
              /><span class="bx bx-search-alt"></span>
            </div>
          </form>
          <div class="btn-group dropdown-mega d-none d-lg-block ms-2">
            <button
              class="btn btn-black dropdown-toggle header-item"
              type="button"
              id="__BVID__201344___BV_dropdown__"
              data-bs-toggle="dropdown"
              aria-expanded="false"
            >
              Mega Menu <i class="mdi mdi-chevron-down"></i></button
            ><!---->
            <ul
              class="dropdown-menu dropdown-megamenu"
              aria-labelledby="__BVID__201344___BV_dropdown__"
              role="menu"
            >
              <div class="row">
                <div class="col-sm-8">
                  <div class="row">
                    <div class="col-md-4">
                      <h5 class="font-size-14 mt-0">UI Components</h5>
                      <ul class="list-unstyled megamenu-list">
                        <li><a href="javascript:void(0);">Lightbox</a></li>
                        <li><a href="javascript:void(0);">Range Slider</a></li>
                        <li><a href="javascript:void(0);">Sweet Alert</a></li>
                        <li><a href="javascript:void(0);">Rating</a></li>
                        <li><a href="javascript:void(0);">Forms</a></li>
                        <li><a href="javascript:void(0);">Tables</a></li>
                        <li><a href="javascript:void(0);">Charts</a></li>
                      </ul>
                    </div>
                    <div class="col-md-4">
                      <h5 class="font-size-14 mt-0">Applications</h5>
                      <ul class="list-unstyled megamenu-list">
                        <li><a href="javascript:void(0);">Ecommece</a></li>
                        <li><a href="javascript:void(0);">Calendar</a></li>
                        <li><a href="javascript:void(0);">Email</a></li>
                        <li><a href="javascript:void(0);">Projects</a></li>
                        <li><a href="javascript:void(0);">Tasks</a></li>
                        <li><a href="javascript:void(0);">Contacts</a></li>
                      </ul>
                    </div>
                    <div class="col-md-4">
                      <h5 class="font-size-14 mt-0">Extra Pages</h5>
                      <ul class="list-unstyled megamenu-list">
                        <li><a href="javascript:void(0);">Light Sidebar</a></li>
                        <li><a href="javascript:void(0);">Compact Sidebar</a></li>
                        <li>
                          <a href="javascript:void(0);">Horizontal Layout</a>
                        </li>
                        <li><a href="javascript:void(0);">Maintenance</a></li>
                        <li><a href="javascript:void(0);">Coming Soon</a></li>
                        <li><a href="javascript:void(0);">Timeline</a></li>
                        <li><a href="javascript:void(0);">FAQs</a></li>
                      </ul>
                    </div>
                  </div>
                </div>
                <div class="col-sm-4">
                  <div class="row">
                    <div class="col-sm-6">
                      <h5 class="font-size-14 mt-0">UI Components</h5>
                      <ul class="list-unstyled megamenu-list">
                        <li><a href="javascript:void(0);">Lightbox</a></li>
                        <li><a href="javascript:void(0);">Range Slider</a></li>
                        <li><a href="javascript:void(0);">Sweet Alert</a></li>
                        <li><a href="javascript:void(0);">Rating</a></li>
                        <li><a href="javascript:void(0);">Forms</a></li>
                        <li><a href="javascript:void(0);">Tables</a></li>
                        <li><a href="javascript:void(0);">Charts</a></li>
                      </ul>
                    </div>
                    <div class="col-sm-5">
                      <!-- <div><img src="/img/megamenu-img.913183e4.png" alt="" class="img-fluid mx-auto d-block"></div> -->
                    </div>
                  </div>
                </div>
              </div>
            </ul>
          </div>
        </div>
        <div class="d-flex">
          <div class="btn-group d-inline-block d-lg-none ms-2">
            <button
              class="btn btn-black dropdown-toggle header-item noti-icon"
              type="button"
              id="__BVID__855324___BV_dropdown__"
              data-bs-toggle="dropdown"
              aria-expanded="false"
            >
              <i class="mdi mdi-magnify"></i></button
            ><!---->
            <ul
              class="dropdown-menu dropdown-menu-lg p-0"
              aria-labelledby="__BVID__855324___BV_dropdown__"
              role="menu"
            >
              <form class="p-3">
                <div class="form-group m-0">
                  <div class="input-group">
                    <input
                      type="text"
                      class="form-control"
                      placeholder="Search ..."
                      aria-label="Recipient's username"
                    />
                    <div class="input-group-append">
                      <button class="btn btn-primary" type="submit">
                        <i class="mdi mdi-magnify"></i>
                      </button>
                    </div>
                  </div>
                </div>
              </form>
            </ul>
          </div>
          <select class="lang-dropdown border-0">
            <option value="en">English</option>
            <option value="fr">French</option>
            <option value="es">Spanish</option>
            <option value="zh">Chinese</option>
            <option value="ar">Arabic</option>
          </select>
          <div class="btn-group d-none d-lg-inline-block noti-icon">
            <button
              class="btn btn-black dropdown-toggle header-item"
              type="button"
              id="__BVID__689812___BV_dropdown__"
              data-bs-toggle="dropdown"
              aria-expanded="false"
            >
              <i class="bx bx-customize"></i></button
            ><!---->
            <ul
              class="dropdown-menu dropdown-menu-lg dropdown-menu-end"
              aria-labelledby="__BVID__689812___BV_dropdown__"
              role="menu"
            >
              <div class="px-lg-2">
                <div class="row no-gutters">
                  <div class="col">
                    <a class="dropdown-icon-item" href="javascript: void(0);"
                      ><img
                        src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACMAAAAeCAMAAACR41cYAAAABGdBTUEAALGPC/xhBQAAAAFzUkdCAK7OHOkAAAJ/UExURUdwTCEgIB8fHyAfHyAfHyAfHyAfHx8eHiAfHx8eHiAfHyAfHyAfHx8eHiAfH5jU5h8eHiAfHyAfHyAfHx8eHh8eHiAfHyAfIAQBAxgWFiEhISEgIAwCACAgIB0bGi40NhkVFCAfH5za8FBncENVXKTm95vZ8Jza8J7c8R0bGhMTEx0cHCAfHyEgH73//yEgIJ7c8QAAAIfF6TM7PwwJCh4cHHm45SAfHyAfH5za8CAfH5za8Jza8Jza8Jza8CAfH5za8G6VokRVWxIKCJza8JvY7pza8DtITTlFSZ3b8AMHCgAABJza8ElBPDA4PFVLRK3z/zEvLRcXGEVBPTA5PJza8AADB5vZ74XD6QIAAIrJ67T+/4HA6BAIByAfH4zK7IrI6zE4O7D5/yAfHwEAACIgIJza8BUWGAACBhoaGvXLsQ0PEZ/g957c8RATFf/oy1p4hfzRticqLIC+6Jrm///jxiMiIvDEq//Xu/bHq//fxG5eVRgXF////P/z0P/22lNHQv/gv//877H5/xcTEhUOC76cicyolCcjIf/avdivlpvY7mZaUQMHC1lNRfrNsPTJr//o0v/cwf3WuHtnXIshF4VuYvTEqfrcyM+oqOrW1PTm4v716zM7PqHf8v/t1SkpJsD//1RueGebxaPn/IXK/TVIV3OapbmXheK0mNuymv/GrdWZhu/Tx+u7pI54adymkf/658+dlMifn+S1mafq+7uhizYvLeLCufLs7/rk1mNVTf/NrtOskqeHd8aXlXFgVv/kwZU1LNW1neK9tJAuJsCMirJwa+nKv9zFx2CRtVuKronG6naszSUnKUZaZG+TmUFPU3agr3GkxIu8xSfH+3sAAABzdFJOUwD97RwqJTMat/4VL6DlCwmSOh2qV77yhGEIms8njIj9+xEk6wESA6CMcwRtUGQlwnjIs9iu9u3fsS5e3hvwhB66hguP9eJfotdT9nPf4o7mPNW62Kc/5MnTMeRzzcTG3/LkYv////////////////////54WQMpAAACTklEQVQYGXXABVMiYRgA4BdYdhkExa5TR8Xuvu7u7v5g2V06XFGxO7C72+vu7s74Qaczd87sIg/85yeUJMMCsUK+FFzIEEISvwSZxF8iSwpEczyBT4L4xMAXhniE4CIQ8QRgwCMWID458PgipEYag0ZD07TGYHCgOcuBI1GIWA3lqEcOrVbrUNdXUzSLfIHDB7EG7fXGi411tRdq6y7dedrl1KjTgGMNop3PSm+WGO35+fkNHSUlpT0U8geO4ABneUX7w9tXWxmGKXzU/7HyyX2tBLhCVT0vh/q7b7W3MW1Fb169H6p4TIXAP1IRQfiIMV/qRUXl8+4HHUwnY//w9l1lZ7kzHBP7EIRICpg3juMemLd2zGwcHOjrLbjB9PYNDI72sgYc88Bx3BsDQiSN9FQCpFDFxrKyVvO1KwXmwtGy0i4qBUDpGSkVEbDA73D5vYIGo/2y3Vhkfl28PQl4NoQABAdl79vV0lzc3LLnwP4dBPB4rbNkwbwM1byMRHAVk7qe3gIAyWpWIBCwKAgWFTS8dfdBQY5cIMsRsv6wuARLhIU+rUBhKCQgFNwIPrYkTR6uVqjD80LBvWxhIFKgsLxT4IYy9XyWJbo6ujo64tyJvbGwiM1H9OM/kalmosb0bXhct2m1F/DExpG6KZPqxy/Vd9XsrGriro5cEQVcUSSp05s+T0XU/HGM6T6Z9DqSjAcur7Vkk77KNjnzu+rrzKStSt9ErloGfOk7yRGr1Tb9ZdpmtY6QG+NWgivlofTMk2dyz+YeP5oZvy0GFvwFlSbPVswTomsAAAAASUVORK5CYII="
                        alt="Github"
                      /><span>GitHub</span></a
                    >
                  </div>
                  <div class="col">
                    <a class="dropdown-icon-item" href="javascript: void(0);"
                      ><img
                        src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABkAAAAdCAMAAABopjdHAAAAwFBMVEVHcEwAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4MAT4Mri5Y4AAAAP3RSTlMAIwhydxy28hIWIc+je6u9P/b9BUziKJcMxKdZAjyMXjfXu8Hm1eou2t0z+rKRRq+A7my6Qp/M34PrU1YPiL7YsJ9AAAABbUlEQVQYGW3Bh3aiQAAF0EedoSMiYu+isdcka7Lv//9qYTib3eR4LwB9b9yilWBtefeN2NFR6h3WJOfeLIqizn3REiQXgdaEMSdb5uiaWTLXc+mOH5+XOSlGaJDJDN+NSJ7QILn0zcegcJ2SpWUvaZcleFROk44d+jf/MF1sWHlHl895OPI5GyM+10bML97US/iXiazB2jIo8uJtzlqSQptQWZ6hxzoMQaU1gGVTCfUsbPnaR0hllkG2WUkCmCQDmFRuEk2TlcSESdJAQCVoAj0q4YfWXrRduaXyC0BKRQRAARwFK5sxAGdL5X0YW/HniUrkomQNWVt11lQ2swFq4+GK/7RsA7XrzkKWGu3Q/h3Z4c7YQw5yVHpiYTpAX1quJZuATKO1hsqLR+H556smc6mNH0c74dZBxbFZEuv77DLtTARLZx2Vvs+f4j6UIX+yUCte+V03R60/PvA/ouvii7N/m742yESsLrtejsofWqVrkBSdwYAAAAAASUVORK5CYII="
                        alt="bitbucket"
                      /><span>GitHub</span></a
                    >
                  </div>
                  <div class="col">
                    <a class="dropdown-icon-item" href="javascript: void(0);"
                      ><img
                        src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAB4AAAAeCAMAAAAM7l6QAAAA0lBMVEVHcEzEI2HDI2HDI2HEI2HDI2HDI2HEI2HDImHDI2HDI2HDImDDI2HEI2HDI2HDI2HDI2HEI2HDI2HDI2HDI2HDI2HDI2HDI2HDI2HDI2HDI2HEJGLDI2HDI2HDI2HqTInxU5C9HFq7GlnyVJHEI2HpS4jwUY/BIV/tTou3FlTCImDzVZK6GVfUNXPfP32+HVziQ4DaOnjrTYrFJWO/Hl3MLGrKKmjAH17uUI3cPXrXN3XSMnC1FFLoSYf1V5T4WpfPLm3mR4TIKGbQMG7wU5DqS4gW3fYwAAAAH3RSTlMAlnPA0mVNzNyLQuQo7zUfxPFVXWx6pPMCRX/1A3yvLDJKvgAAAk1JREFUGBllwIV2GmkUAOAbIUD8bCrp2v1dx10ZBmbf/5WW0DZtTz/44X518fzwef3pwyP87uZKiJhRSlns1iv41f2Vpk73bdumYVUwff0FfvKS07rUNJz4wrlJwpqJj/Dug2D5vNsHrPUS0Sx+rgqxhW/+EKxsuMpEoKWSiCj5rqTiTzh7EqzkSkof0WBPMkRpfORYIW7hzZrmjZKIGd8HrPUSCe8Cmx7pA5zcOpp4iYhSSRfkxvOxtDacUNeXALBmR45n0reUhSaMh7jlxnfsAeDJ0YRjZoxaiG8OsXBDsB95JtWs9S2s4spz1Rg5R+mxcrWu99Gi8ETt6RYu6qrr92WV18wOVuSFyHYZZojIU/YMVzkdBmstK0QVtpgUQTepE0KmhG5go8uwD8M0SkZD/LQrg7zrj8c+TJO0voMNjSa1ELIoY3jT9rlzwWCtHQZbizu4oinHN7LhyYENTNeHtG3bri+F28AFCwmeyKXpmaWHJAxytVsIX3YpfYZVcTAGUfLxYIND1ExzwVqOJ7ynW3hycUJQ8lnbuGu8yZrSlipDbEanvwCsWe8lH7XViTcSkXc2Hw1Kn7LPrwA3ukimLB/c6PGNSmIaEakyV/wDJ9e08v2gR49nBnPbEeP37K9XOLkX9UHTyP+HXy29LdWuY+4Gzl5EHKQTfsfTIDcp01v46vVSFOXsVYZnZK5FVegLeLcStAjnhpNlIZwkoo7dFn7yuNasLrs2itq0dE5sbuBXL2tHGY1jyqjeXP4Nv3m8/LS+u7v+9+MtvPsfo0R0DDqUOxMAAAAASUVORK5CYII="
                        alt="dribbble"
                      /><span>Dribbble</span></a
                    >
                  </div>
                </div>
                <div class="row no-gutters">
                  <div class="col">
                    <a class="dropdown-icon-item" href="javascript: void(0);"
                      ><img
                        src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACMAAAAhCAMAAABkz+JgAAAAxlBMVEVHcEwAfuYAfuYAfuYAfuYAfecAfuYAfuYAfuYAfuYAfuYAfuYAfuYAfuYAfuYAfuYAfuYAfuYAfuYAfuYAfuYAfuYAfuYAfuYAfuYAfuYAfuUAfuYAfuYAfuYAfuYAfuYAfuYAfuYAfuYAfuYAfuYAfuYAfuYAf+UAfuYAfuYAfuYAfuYAfuYAfuYAfuYAf+YAfuYAfuYAfuYAfuYAfuYAfuYAfuYAfuYAfuYAfuYAfuUAfuYAgOcAfuYAfeYAf+YAfuYAfuZXV9ysAAAAQXRSTlMACxEy+QLr/PX+2xgHGh58vjZgQeTHDu1k6RWMKIbTudej4Jipy0cFcPPvL3MkTBNn0HfFVq5Q6LVrOh8GnFk8kkQ6JVUAAAGsSURBVBgZfcEHgppAAAXQjw4Mgi5iD/Yu9o6uW/Lvf6kgiowmm/cQq3y1G0g0hvMKXuTaksESMdei2LhQaWuTIbOQxZW+9xnyJys8NMqCEVHXAYybPiNyOMNNZW3wYWBjVZeMmVsPocVOMiE3bl4yITdpYFSlShyKXZ8qs4ZcmYrSKIvxd4+KzQXQ+oJ31X4OV5VmlXdyYCM0rklGrLSOG/0tz4jcZnGz7JEMnCwS2sQiWSroiHlDnlY6nngDGjMo3tseXun9dyi8jiyn8MzeyamLh31A0ndSSKQmPZJBLYuI7kheZaouYpcWI7KJK+9T8M7sL3CVq5uMHS5ArkOFudeB4pSK0gWjElXiMOoKqn6tgVReMpEZvuUzTMjWBSGt1mMs8zmrp+uCselcw01uJxkRzqXDanouGJFlGw/jQsCQUThaJIPC0WAoOKeg0k6SRnHpM+I0LMrWAs/m6a/urCl4I7ru6ewV8KxtLO0uE3m7OG3j2dmXFlWdKZt44bYEVZlOEX/RagYTxsTGv1S6Pm/MfAM/+CiWeWUds/jZh1Oi8VvDf+mLbVrHsz8x4n90MIcLhQAAAABJRU5ErkJggg=="
                        alt="dropbox"
                      /><span>Dropbox</span></a
                    >
                  </div>
                  <div class="col">
                    <a class="dropdown-icon-item" href="javascript: void(0);"
                      ><img
                        src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAjCAMAAADCMPhoAAAABGdBTUEAALGPC/xhBQAAAAFzUkdCAK7OHOkAAAJAUExURUdwTGVPRGVPRHVeUGVPRGVPRGRPRWVPRGVPRGVPRGRQRWVPRWVPRGVPRGVPRGRPRWVPRGVPRGVPRGVPRGVPRGBVUmVPRGVPRGtUR2VPRGVPRGVPRGVPRGVPRGVPRGVPRF9LQ3NZSZ6IdmVPRGNVT3poX2VPRGVPRHlhRl9gZIFnR2VPRJBpTP3rzvTSqxIgNEme1yyDwhUiNY5oTGZQRGlSRfzoyf3qzffbuPXixZpzVfTVsGBMQ/PQqXpbSIRiSnFWRvjlyP///39fSW1URrKUeIhkSkM8Pe/Np4tmSyx8tvrgvv37+ZRtT5ZwUuPDn1VHQ595WnNYR5FqTVKCo2NOQ/vlxdrBpCEpN9y7mPXUrj1IWZV7ZzWKxqqTfunIo/PRq7mafsm/ubipoP338LispLyrmKWNeFtlcPzy55yBa/PNo9e2lCcsOO3AkO7Gm1lZXhUpQi6CvsilgzA8TaeCY0SZ05yDbysuOTExOvbYs/HdwaqHaeDBnc62nGJqeOXQtBspPLKch8ytj/327fjz7sO3r35sWb+yqbOObk5jdmNdXzR7sPHJnfDbvUVujVd1inhxcVJgb7+aeerXvDZ5qo2Aeyg0Rh9PdkhphShzq/fixBxFaRk1UZ97XjpznjZCUzQzO15LQydrnq6Vf829sPnn06GGcIRlTy4+UqCeoPLv7s7Hw+Hd2+zp546UnqCjpc62e7uoayhfiqmRSHWAjlBTROa+T9KxTFKFqe/HTp+XXllwgsW4a5e0njlHS3QagBcAAAArdFJOUwChif0QVMAFATnZ3hjoM8j3bbLSKPesC/SV9JpILoBY8Pz9kf3wgnaT/pqvGFBIAAACu0lEQVQ4y3WU5VsiURTGCZFBxcCu7ebOXBiQRgQBRbBwLbCwde3uWN1Ht7u7w+3u/df23mGYhcf1/fp776k5Z3i8CIklObm8rZWbndr9c+2QmCeOF22P34Tj+Ae/KX79/vHlQObeK+dPViRERWBCtOewQqH48/3rx3cvFmkIYX90RPLMbgVWyef3b/0Qc0hLw3hUwjmGN3741A1Z0bFhPBaHV0w8fP5mGdJI2DCV/Y/HMLzx1r1Fum7qvslkKuqH9A4xlz/67ATiI8P+MXraJA9quiiJC7DthFKJyoP+5TqM1XmWQq9dncZxyZBSqWwsgWN0EcJ5hSqA5eSaJGJOIUMJfRVWIOwCQVWV7UxnDaILiI8M05h7ASg1GEqrQFm9r1bGGmSXkeEahCi+HQCDdYbCMg8MxrCGVMRvQFiH8qPsZ3ynB44wluJww21IV6MCAHAYzYMMpuqbk1kD/7ry7oNqxOX5ACxQ6HlfOXovLE/gxjTkRbFdankhAKP4ce8kpXMbizNEoTkUoNpG51AEFSgzI4Oj13jJMa/R7+IHDfssoNJMNaARokDHWyjKWKMlrVqS1DYJgkW4QMBnRgacA1T21ZAh6RrisEFgAXMa3Roy2F2gcl4TwtqZZmEcW0NVYCmAP6HTUBziGl1LoC24MsRu1B9QMX1e1CGm17h1LStd6683pESw0aSMAm8eM8nxmyT56HFra+vLVx6bzXY0NCyxgFkSFSidJa0rT3ra23t6PDbPuj6LuwnWAGpJsulY++qqx7bR0WntEnFLkYYNFgDGSXK2s62jo61zQe+eD9/rRLxNTgD0bBc1bl+zMCXsMiQ4hN0JHCGHtl64P+L2RNihtqju1FoxXuqSC4jI442XYoe6IP/Z06ZJoTwradN5E/xEOafolP/9INIFyYxHKpNs+RMhUnIk4T+Gv3cNvzi99G5fAAAAAElFTkSuQmCC"
                        alt="mail_chimp"
                      /><span>Mail Chimp</span></a
                    >
                  </div>
                  <div class="col">
                    <a class="dropdown-icon-item" href="javascript: void(0);"
                      ><img
                        src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAB4AAAAeCAMAAAAM7l6QAAACplBMVEVHcEz////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////60uX///////////////////////////////9uytzmmQDpqCA+uZHgFWPkkQAWjnjODgjIAQNVwdYarX3XADfcAEj5/f3cAE7L7PN/1e7ppAuw49I2t42G1bjjFnJkyuXsqyX22qE8uJDyn75zzN70qcViegRUgh/ZAT245ddB2aIzACb34LAFgmbMAgpFsrj//vTS7/QVqnr+/PrppxwwvIzvw2Puu1BKvdT+8PXI7OEOqHaS1+XfA15cw9f96r7E6vFcz/pLdARCvZTw+fbfDV9lhhv/ryHpU4zhGmj2vtH7AlgdtIEYDjGm3+oKlG8bk3zrtwmd2+ggl4FSwpoIimozpJrIkgDe9PrPJQB12v/rtiT8//8rpoR/0N6v4/LtwBxSwtvlO3vI6+pgxqVGu9MLp3NzzLC95++Zkxzwibb/GW0bfWb33qvumwD+c6cUACE3ADAvs4k5UVo3EDnvzCxsxK/kfUb96vnSNgD+rBznnh81r4zUEil7ysTpf4H384miwZjWOxfcag395/cPjW714Hn3ynT6nABVvc9gx+D44rVkx9rbWhfkjxzmS4V3ih1Lj03fFV7TDCJmnV5staHhK2njMHNuxc0nn4Jv0e+wVX9dqo3sFmem6P9Eu9JtAC/IvG1Jfhxym1BsgQqh5/9AEjyoAErufqr01pXrsDYoDjQ4Gj0cy47Alw5wLFTuAVp6z7PYJWp43rueFVRmEkb0ZprVAEUgt4QsiG94nZYsIT9Gx5y9/+uQ18Ci3coAom6/ICZyAAAAKXRSTlMAP9pMoGFRR+eup71y+9DzuF0xoyLgFQKyWWadV4P2w5b+kQivDFtcxZCJTt8AAAKlSURBVBgZdcCDU2QBGADwrxXaai/76oTvvbdmNnezbetqsjHZOtu2bdvGf3K1u9NMN9cPFmPzOOtZsBQ6jiX5IxP+z5bjLxKJnprCP+wtGSwAsMJnpB9J4Vq2I8MeFliiZziuBLDBZJKixrNR5eaGxmBgrupNTx9ANoDj2HhxMXn3YZAsJUNlDno8z/4Ar7g0S1sWL4Z6NfQgtNuXIPpyeKC3zFMuEMR5861Vsbfu590LDbnYQpxIcbMDPXqBl1d+Yl1sZ5As90ZIUVHIhdxuWRUagZ4Test3tB+M9s0irl0pCgnNC+3obEIT0FlHw6Zd9WJxZIM7QRC5Z/PODDVmc5wtQIeNg0G+R8XianEt4SvLatnb6Fd85LA1GJjl9GUR7g311eLIaPeq2LaYbR6Uh1+8EVhZrAIA04yUIMI9OlJcu2ETzksiKYrMNuMickwAaDm3ZbJjxNV2QWIdzosgqdaaQwcCT196gubAxsGODDeVd0V+gDwN522s2b5/X6laqVYMcwCYNOQzzMLlAkGcN87ZsnmrRCoN8xGWhpWYwhwrG3AqCJgWJGowNbjERyGNkkh2+hQqFYE0MOC/f6kJGL0+olRmnpNIJNIodWZPMNJBh+7KDx+deTF5p1woFPqcl0qjmnevQBc66Lhi2ad3Wu3U80fCm4XqTEXzyVMee0wtQI8VXxKmLP9YOTtb+bhcfXm4rLWry8Mvxgj0lgUrCoUjHyqntJOvJ8qQtjyJpCgywhj0eIEKofDNZ+33ma8/2rhGsPq4KCFBFMEFPYfUnjBl6cS3Co3mS5ozAAuTRaLkeBYY2GFgcCr+rBAI5G/5awCM0d8fGbCAacxgmxR4TefLe9EGAJhcLhMWs8Vff9L7Pa1hCSb4eyAc2bAUBzOOCx0W+QuvxroExNCXxAAAAABJRU5ErkJggg=="
                        alt="slack"
                      /><span>Slack</span></a
                    >
                  </div>
                </div>
              </div>
            </ul>
          </div>
          <div class="dropdown d-none d-lg-inline-block ms-1">
            <button type="button" class="btn header-item noti-icon">
              <i class="bx bx-fullscreen"></i>
            </button>
          </div>
          <div class="btn-group">
            <button
              class="btn btn-black dropdown-toggle header-item noti-icon"
              type="button"
              id="__BVID__176704___BV_dropdown__"
              data-bs-toggle="dropdown"
              aria-expanded="false"
            >
              <i class="bx bx-bell bx-tada"></i
              ><span class="badge bg-danger rounded-pill">3</span></button
            ><!---->
            <ul
              class="dropdown-menu dropdown-menu-lg p-0 dropdown-menu-end"
              aria-labelledby="__BVID__176704___BV_dropdown__"
              role="menu"
            >
              <div class="p-3">
                <div class="row align-items-center">
                  <div class="col">
                    <h6 class="m-0">Notifications</h6>
                  </div>
                  <div class="col-auto">
                    <a href="#" class="small">View All</a>
                  </div>
                </div>
              </div>
              <div data-simplebar="init" style="max-height: 230px">
                <div class="simplebar-wrapper" style="margin: 0px">
                  <div class="simplebar-height-auto-observer-wrapper">
                    <div class="simplebar-height-auto-observer"></div>
                  </div>
                  <div class="simplebar-mask">
                    <div class="simplebar-offset" style="right: 0px; bottom: 0px">
                      <div
                        class="simplebar-content-wrapper"
                        tabindex="0"
                        role="region"
                        aria-label="scrollable content"
                        style="height: auto; overflow: hidden"
                      >
                        <div class="simplebar-content" style="padding: 0px">
                          <a
                            href="javascript: void(0);"
                            class="text-reset notification-item"
                          >
                            <div class="d-flex">
                              <div class="avatar-xs me-3">
                                <span
                                  class="avatar-title bg-primary rounded-circle font-size-16"
                                  ><i class="bx bx-cart"></i
                                ></span>
                              </div>
                              <div class="flex-grow-1">
                                <h6 class="mt-0 mb-1">Your order is placed</h6>
                                <div class="font-size-12 text-muted">
                                  <p class="mb-1">
                                    If several languages coalesce the grammar
                                  </p>
                                  <p class="mb-0">
                                    <i class="mdi mdi-clock-outline"></i> 3 min
                                    ago
                                  </p>
                                </div>
                              </div>
                            </div>
                          </a>
                          <a
                            href="javascript: void(0);"
                            class="text-reset notification-item"
                          >
                            <div class="d-flex">
                              <!-- <img src="/img/avatar-3.41a180f3.jpg" class="me-3 rounded-circle avatar-xs" alt="user-pic"> -->
                              <div class="flex-grow-1">
                                <h6 class="mt-0 mb-1">James Lemire</h6>
                                <div class="font-size-12 text-muted">
                                  <p class="mb-1">
                                    It will seem like simplified English.
                                  </p>
                                  <p class="mb-0">
                                    <i class="mdi mdi-clock-outline"></i> 1 hours
                                    ago
                                  </p>
                                </div>
                              </div>
                            </div>
                          </a>
                          <a
                            href="javascript: void(0);"
                            class="text-reset notification-item"
                          >
                            <div class="d-flex">
                              <div class="avatar-xs me-3">
                                <span
                                  class="avatar-title bg-success rounded-circle font-size-16"
                                  ><i class="bx bx-badge-check"></i
                                ></span>
                              </div>
                              <div class="flex-grow-1">
                                <h6 class="mt-0 mb-1">Your item is shipped</h6>
                                <div class="font-size-12 text-muted">
                                  <p class="mb-1">
                                    If several languages coalesce the grammar
                                  </p>
                                  <p class="mb-0">
                                    <i class="mdi mdi-clock-outline"></i> 3 min
                                    ago
                                  </p>
                                </div>
                              </div>
                            </div>
                          </a>
                          <a
                            href="javascript: void(0);"
                            class="text-reset notification-item"
                          >
                            <div class="d-flex">
                              <!-- <img src="/img/avatar-4.e0ab315a.jpg" class="me-3 rounded-circle avatar-xs" alt="user-pic"> -->
                              <div class="flex-grow-1">
                                <h6 class="mt-0 mb-1">Salena Layfield</h6>
                                <div class="font-size-12 text-muted">
                                  <p class="mb-1">
                                    As a skeptical Cambridge friend of mine
                                    occidental.
                                  </p>
                                  <p class="mb-0">
                                    <i class="mdi mdi-clock-outline"></i> 1 hours
                                    ago
                                  </p>
                                </div>
                              </div>
                            </div>
                          </a>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div
                    class="simplebar-placeholder"
                    style="width: 0px; height: 0px"
                  ></div>
                </div>
                <div
                  class="simplebar-track simplebar-horizontal"
                  style="visibility: hidden"
                >
                  <div
                    class="simplebar-scrollbar"
                    style="width: 0px; display: none"
                  ></div>
                </div>
                <div
                  class="simplebar-track simplebar-vertical"
                  style="visibility: hidden"
                >
                  <div
                    class="simplebar-scrollbar"
                    style="height: 0px; display: none"
                  ></div>
                </div>
              </div>
              <div class="p-2 border-top d-grid">
                <a
                  class="btn btn-sm btn-link font-size-14 text-center"
                  href="javascript:void(0)"
                  ><i class="mdi mdi-arrow-right-circle me-1"></i> View More..</a
                >
              </div>
            </ul>
          </div>
          <div class="btn-group">
            <button
              class="btn btn-black dropdown-toggle header-item"
              type="button"
              id="__BVID__580858___BV_dropdown__"
              data-bs-toggle="dropdown"
              aria-expanded="false"
            >
              <!-- <img class="rounded-circle header-profile-user" src="/img/avatar-1.67e2b9d7.jpg" alt="Header Avatar"> -->
              <span class="d-none d-xl-inline-block ms-1">
                <div>Henry</div>
              </span>
              <i class="mdi mdi-chevron-down d-none d-xl-inline-block"></i>
            </button>
            <!---->
            <ul
              class="dropdown-menu dropdown-menu-end"
              aria-labelledby="__BVID__580858___BV_dropdown__"
              role="menu"
            >
              <li role="presentation">
                <button class="dropdown-item" type="button" target="_self">
                  <span
                    ><i class="bx bx-user font-size-16 align-middle me-1"></i>
                    Profile</span
                  >
                </button>
              </li>
              <li role="presentation">
                <a
                  class="dropdown-item"
                  href="javascript: void(0);"
                  target="_self"
                  ><i class="bx bx-wallet font-size-16 align-middle me-1"></i> My
                  Wallet</a
                >
              </li>
              <li role="presentation">
                <a
                  class="dropdown-item"
                  href="javascript: void(0);"
                  target="_self"
                  ><span class="badge bg-success float-end">11</span
                  ><i class="bx bx-wrench font-size-16 align-middle me-1"></i>
                  Settings</a
                >
              </li>
              <li role="presentation">
                <a
                  class="dropdown-item"
                  href="javascript: void(0);"
                  target="_self"
                  ><i class="bx bx-lock-open font-size-16 align-middle me-1"></i>
                  Lock screen</a
                >
              </li>
              <li role="presentation">
                <hr
                  class="dropdown-divider"
                  role="separator"
                  aria-orientation="horizontal"
                />
              </li>
              <a href="/logout" class="dropdown-item text-danger"
                ><i
                  class="bx bx-power-off font-size-16 align-middle me-1 text-danger"
                ></i>
                Logout</a
              >
            </ul>
          </div>
          <div class="dropdown d-inline-block">
            <button
              type="button"
              class="btn header-item noti-icon right-bar-toggle toggle-right"
            >
              <i class="bx bx-cog bx-spin toggle-right"></i>
            </button>
          </div>
        </div>
      </div>
    </header>
  </template>
  <script setup>
      
  </script>