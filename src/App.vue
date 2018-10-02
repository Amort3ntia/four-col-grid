<template>
    <div id="app">
        <header class="header">
            <span class="logo">
                LOGO
            </span>
            <a href="something" class="button1">Login</a>
            <a href="something" class="button1">Create Account</a>
        </header>
        <section class="wrapper">
            <div class="responsive-one-col-grid">
                <div>
                    <b>Main content width: 1200px</b>
                </div>
            </div>
            <div class="responsive-two-col-grid">
                <div>
                    Three Rings for the Elven-kings under the sky, <br>
                    Seven for the Dwarf-lords in halls of stone, <br>
                    Nine for Mortal Men, doomed to die, <br>
                </div>
                <div>
                    One for the Dark Lord on his dark throne <br>
                    In the Land of Mordor where the Shadows lie. <br>
                    One Ring to rule them all, One Ring to find them, <br>
                    One Ring to bring them all and in the darkness bind them. <br>
                </div>
            </div>
            <div class="responsive-three-col-grid">
                <div>
                    Three Rings for the Elven-kings under the sky, <br>
                    Seven for the Dwarf-lords in halls of stone, <br>
                    Nine for Mortal Men, doomed to die,
                </div>
                <div>
                    One for the Dark Lord on his dark throne <br>
                    In the Land of Mordor where the Shadows lie.
                </div>
                <div>
                    One Ring to rule them all, One Ring to find them, <br>
                    One Ring to bring them all and in the darkness bind them.
                </div>
            </div>
            <div class="responsive-four-col-grid">
                <div>
                    Three Rings for the Elven-kings under the sky,
                </div>
                <div>
                    Seven for the Dwarf-lords in halls of stone, <br>
                    Nine for Mortal Men, doomed to die,
                </div>
                <div>
                    One for the Dark Lord on his dark throne <br>
                    In the Land of Mordor where the Shadows lie.
                </div>
                <div>
                    One Ring to rule them all, One Ring to find them, <br>
                    One Ring to bring them all and in the darkness bind them.
                </div>
            </div>
        </section>
        <footer class="footer">Bottom Nav</footer>
    </div>
</template>

<script>

  export default {
    name: 'app',
    components: {}
  }
</script>

<style lang="scss">
    @import "grid";

    #app {
        font-family: 'Avenir', Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #2c3e50;
        background: #cba550;
    }

    .wrapper > div {
        background: #ffe2ea;
        padding: 1em;
        margin: 4.23em;
    }
    .logo {
        float: left;
        padding: .5em;
    }

    .header {
        text-align: right;
        padding: .6em;
        background: #B2B2B2;
    }

    .wrapper {
        padding: 30px;
        text-align: left;
        background: #FFCCCC;
    }

    .footer {
        padding: 20px;
        background: #B2B2B2;
        text-align: center;
    }

    a.button1 {
        display: inline-block;
        padding: 0.35em 1.2em;
        border: 0.1em solid #FFFFFF;
        margin: 0 0.5em 0.1em 0;
        border-radius: 0.12em;
        box-sizing: border-box;
        text-decoration: none;
        font-family: 'Roboto', sans-serif;
        font-weight: 300;
        color: #FFFFFF;
        text-align: center;
        transition: all 0.2s;
    }

    a.button1:hover {
        color: #000000;
        background-color: #FFFFFF;
    }

    @media all and (max-width: 30em) {
         a.button1 {
            display: block;
            margin: 0.4em auto;
        }
    }
</style>
