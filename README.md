<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Chit-chat</title>
  </head>
  <body style="background-color: lightblue">
    <header style="color: rosybrown">
      <h1 style="margin-bottom: 2px"><u>Welcome back!!</u></h1>
    </header>
    <table border="1" width="100%">
      <tr>
        <td style="background-color: rosybrown; text-align: center">
          LOGIN TO OPEN THE WORLD OF CHITCHAT
        </td>
      </tr>
    </table>
    <p style="text-align: center; font-family: fantasy; font-size: xx-large">
      <u>Chit-chat</u>
    </p>

    <div
      class="parent"
      style="
        display: grid;
        grid-template-columns: repeat(5, 1fr);
        grid-template-rows: repeat(5, 1fr);
        gap: 8px;
      "
    >
      <div
        class="div1"
        style="grid-column: span 2 / span 2; grid-row: span 2 / span 2"
      >
        <img src="aesthic.jpg" />
      </div>
      <div
        class="div2"
        style="
          grid-column: span 2 / span 2;
          grid-row: span 2 / span 2;
          grid-column-start: 1;
          grid-row-start: 3;
        "
      >
        <img src="aesthetic.jpg" />
      </div>
      <div
        class="div3"
        style="
          grid-column: span 2 / span 2;
          grid-row: span 4 / span 4;
          grid-column-start: 3;
          grid-row-start: 1;
        "
      >
        <form>
          <fieldset
            style="
              margin-left: 50%;
              background-color: rosybrown;
              width: 300px;
              height: 250px;
            "
          >
            <legend><strong>Login portal</strong><br /></legend>
            <br />
            <section style="align-content: center">
              <label for="Username or E-mail">Username or E-mail:</label>
              <input
                type="text"
                id="Username"
                placeholder="Enter your Username"
                required
              />
              <br /><br />
              <label for="Password"> Your Password here:</label>
              <input
                type="password"
                placeholder="Enter your Password"
                required
              /><br /><br />

              <label for="OTP"> An OTP sent to registered no.:</label>
              <input
                type="number"
                id="OTP"
                placeholder="An OTP is sent on the registered no."
                required
              />
              <br /><br />
              <button type="reset" style="background-color: brown">
                Reset
              </button>
              <button type="submit" style="background-color: green">
                Login
              </button>
            </section>
          </fieldset>
        </form>
      </div>
    </div>
  </body>
</html>
