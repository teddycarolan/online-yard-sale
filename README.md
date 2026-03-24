
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>~*~ Online Yard Sale ~*~</title>
  <style>
    body {
      background: #ffffff;
      color: #000000;
      font-family: "Times New Roman", Times, serif;
      margin: 0;
      padding: 0;
    }
 
    marquee {
      background: #000080;
      color: #ffffff;
      font-size: 13px;
      padding: 4px 0;
      font-family: "Times New Roman", Times, serif;
    }
 
    header {
      text-align: center;
      padding: 18px 10px 14px;
      border-bottom: 2px solid #000080;
    }
 
    .header-gifs {
      display: flex;
      justify-content: center;
      align-items: center;
      gap: 18px;
      margin-bottom: 10px;
    }
 
    .header-gifs img {
      height: 60px;
      image-rendering: pixelated;
      image-rendering: crisp-edges;
    }
 
    header h1 {
      font-size: 2rem;
      color: #000080;
      margin: 0 0 6px;
    }
 
    header p {
      font-size: 14px;
      margin: 3px 0;
    }
 
    .venmo-btn {
      display: inline-flex;
      align-items: center;
      gap: 7px;
      margin-top: 8px;
      background: #3d95ce;
      color: #ffffff;
      font-family: "Times New Roman", Times, serif;
      font-weight: bold;
      font-size: 14px;
      padding: 6px 14px;
      border: 2px solid #1a6fa8;
      border-radius: 4px;
      text-decoration: none;
      box-shadow: 2px 2px 0 #1a6fa8;
    }
 
    .venmo-btn svg {
      width: 18px;
      height: 18px;
      fill: #ffffff;
      flex-shrink: 0;
    }
 
    main {
      max-width: 960px;
      margin: 22px auto;
      padding: 0 14px 40px;
    }
 
    .gif-strip {
      display: flex;
      justify-content: center;
      align-items: center;
      gap: 24px;
      margin-bottom: 16px;
      flex-wrap: wrap;
    }
 
    .gif-strip img {
      height: 55px;
      image-rendering: pixelated;
      image-rendering: crisp-edges;
    }
 
    main h2 {
      font-size: 1.1rem;
      text-align: center;
      color: #000080;
      margin-bottom: 16px;
      border-bottom: 1px dashed #000080;
      padding-bottom: 6px;
    }
 
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(160px, 1fr));
      gap: 16px;
    }
 
    .item {
      border: 1px solid #999999;
      background: #f9f9f9;
      text-align: center;
      padding-bottom: 10px;
      font-size: 13px;
    }
 
    .item-img {
      width: 100%;
      aspect-ratio: 2 / 3;
      background: #dddddd;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 2.5rem;
      border-bottom: 1px solid #999;
      overflow: hidden;
    }
 
    .item-img img.cover {
      width: 100%;
      height: 100%;
      object-fit: cover;
      display: block;
    }
 
    .item-title {
      font-weight: bold;
      margin: 8px 6px 3px;
      line-height: 1.3;
    }
 
    .item-author {
      color: #555555;
      font-style: italic;
      margin: 0 6px 6px;
    }
 
    .item-price {
      color: #cc0000;
      font-weight: bold;
      font-size: 1rem;
    }
 
    .item.sold {
      opacity: 0.5;
      position: relative;
    }
 
    .item.sold .sold-label {
      display: block;
      color: #cc0000;
      font-weight: bold;
      font-size: 0.85rem;
      margin-top: 4px;
      text-decoration: line-through;
    }
 
    footer {
      text-align: center;
      font-size: 12px;
      color: #555;
      border-top: 1px solid #999;
      padding: 14px;
    }
 
    .footer-gifs {
      display: flex;
      justify-content: center;
      align-items: center;
      gap: 16px;
      margin: 10px 0 6px;
    }
 
    .footer-gifs img {
      height: 40px;
      image-rendering: pixelated;
      image-rendering: crisp-edges;
    }
  </style>
</head>
<body>
 
<marquee scrollamount="4">~*~ WELCOME TO MY ONLINE YARD SALE ~*~ cash or venmo only ~*~ message me to claim an item ~*~ first come first served ~*~</marquee>
 
<header>
  <div class="header-gifs">
    <img src="data:image/gif;base64,R0lGODlhFAAUAPIAAP///wB4ADK0Msj/yP/cAAAAAAAAAAAAACH/C05FVFNDQVBFMi4wAwEAAAAh+QQRDAAAACwAAAAAFAAUAAADLwi63P4wyrlIoCzofekVHQZ0IUaKyolyW0QAQpbCwDupIm7OHltSMdTiJ7IJj6IEACH5BBEMAAAALAAAAAAUABQAAAMtCLrc/jDKyQKtIetJgPVLJwnfJ1zltaSqp20tq8qo8o2rckrdq4m1Vk5ILBITACH5BBEMAAAALAAAAAAUABQAAAMvCLrc/jDKuUigLOh96RUdBnQhRorKiXIbIABEE7+LKtpmio66x5YU2o43hBWPlAQAIfkEEQwAAAAsAAAAABQAFAAAAy0Iutz+MMrJAq0h60mA9UsnCd8nXOW1pKqnbS2ryqjyjatySt2ribVWTkgsEhMAIfkEEQwAAAAsAAAAABQAFAAAAy8Iutz+MMq5SKAs6H3pFR0GdCFGisqJchsgAEQTv4sq2maKjrrHlhTajjeEFY+UBAAh+QQRDAAAACwAAAAAFAAUAAADLQi63P4wyskCrSHrSYD1SycJ3ydc5bWkqqdtLavKqPKNq3JK3auJtVZOSCwSEwAh+QQRDAAAACwAAAAAFAAUAAADLwi63P4wyrlIoCzofekVHQZ0IUaKyolyGyAARBO/iyraZoqOuseWFNqON4QVj5QEACH5BBEMAAAALAAAAAAUABQAAAMtCLrc/jDKyQKtIetJgPVLJwnfJ1zltaSqp20tq8qo8o2rckrdq4m1Vk5ILBITADs=" alt="dollar sign" style="height:45px">
    <img src="data:image/gif;base64,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" alt="yard sale" style="height:72px">
    <img src="data:image/gif;base64,R0lGODlhFAAUAPIAAP///wB4ADK0Msj/yP/cAAAAAAAAAAAAACH/C05FVFNDQVBFMi4wAwEAAAAh+QQRDAAAACwAAAAAFAAUAAADLwi63P4wyrlIoCzofekVHQZ0IUaKyolyW0QAQpbCwDupIm7OHltSMdTiJ7IJj6IEACH5BBEMAAAALAAAAAAUABQAAAMtCLrc/jDKyQKtIetJgPVLJwnfJ1zltaSqp20tq8qo8o2rckrdq4m1Vk5ILBITACH5BBEMAAAALAAAAAAUABQAAAMvCLrc/jDKuUigLOh96RUdBnQhRorKiXIbIABEE7+LKtpmio66x5YU2o43hBWPlAQAIfkEEQwAAAAsAAAAABQAFAAAAy0Iutz+MMrJAq0h60mA9UsnCd8nXOW1pKqnbS2ryqjyjatySt2ribVWTkgsEhMAIfkEEQwAAAAsAAAAABQAFAAAAy8Iutz+MMq5SKAs6H3pFR0GdCFGisqJchsgAEQTv4sq2maKjrrHlhTajjeEFY+UBAAh+QQRDAAAACwAAAAAFAAUAAADLQi63P4wyskCrSHrSYD1SycJ3ydc5bWkqqdtLavKqPKNq3JK3auJtVZOSCwSEwAh+QQRDAAAACwAAAAAFAAUAAADLwi63P4wyrlIoCzofekVHQZ0IUaKyolyGyAARBO/iyraZoqOuseWFNqON4QVj5QEACH5BBEMAAAALAAAAAAUABQAAAMtCLrc/jDKyQKtIetJgPVLJwnfJ1zltaSqp20tq8qo8o2rckrdq4m1Vk5ILBITADs=" alt="dollar sign" style="height:45px">
  </div>
 
  <h1>~*~ Online Yard Sale ~*~</h1>
  <p>msg me at (240) 234-5078 or teddyjjcarolan@gmail.com and tell me what you want</p>
  <p>book bundles: 5 for $6, 10 for $8</p>
  <p>cash in person or:</p>
  <a class="venmo-btn" href="https://venmo.com/Teddy-Carolan" target="_blank">
    <svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
      <path d="M19.07 2c.46 1.01.67 2.07.67 3.43 0 4.28-3.65 9.84-6.61 13.74H6.44L3 2.92l5.8-.55 1.8 7.25c1.68-2.75 3.75-7.08 3.75-10.04 0-1.62-.28-2.73-.73-3.63L19.07 2z"/>
    </svg>
    Venmo: @Teddy-Carolan
  </a>
</header>
 
<main>
 
  <div class="gif-strip">
    <img src="data:image/gif;base64,R0lGODlhFAAUAPIAAP///wB4ADK0Msj/yP/cAAAAAAAAAAAAACH/C05FVFNDQVBFMi4wAwEAAAAh+QQRDAAAACwAAAAAFAAUAAADLwi63P4wyrlIoCzofekVHQZ0IUaKyolyW0QAQpbCwDupIm7OHltSMdTiJ7IJj6IEACH5BBEMAAAALAAAAAAUABQAAAMtCLrc/jDKyQKtIetJgPVLJwnfJ1zltaSqp20tq8qo8o2rckrdq4m1Vk5ILBITACH5BBEMAAAALAAAAAAUABQAAAMvCLrc/jDKuUigLOh96RUdBnQhRorKiXIbIABEE7+LKtpmio66x5YU2o43hBWPlAQAIfkEEQwAAAAsAAAAABQAFAAAAy0Iutz+MMrJAq0h60mA9UsnCd8nXOW1pKqnbS2ryqjyjatySt2ribVWTkgsEhMAIfkEEQwAAAAsAAAAABQAFAAAAy8Iutz+MMq5SKAs6H3pFR0GdCFGisqJchsgAEQTv4sq2maKjrrHlhTajjeEFY+UBAAh+QQRDAAAACwAAAAAFAAUAAADLQi63P4wyskCrSHrSYD1SycJ3ydc5bWkqqdtLavKqPKNq3JK3auJtVZOSCwSEwAh+QQRDAAAACwAAAAAFAAUAAADLwi63P4wyrlIoCzofekVHQZ0IUaKyolyGyAARBO/iyraZoqOuseWFNqON4QVj5QEACH5BBEMAAAALAAAAAAUABQAAAMtCLrc/jDKyQKtIetJgPVLJwnfJ1zltaSqp20tq8qo8o2rckrdq4m1Vk5ILBITADs=" alt="dollar" style="height:35px">
    <img src="data:image/gif;base64,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" alt="yard sale">
    <img src="data:image/gif;base64,R0lGODlhFAAUAPIAAP///wB4ADK0Msj/yP/cAAAAAAAAAAAAACH/C05FVFNDQVBFMi4wAwEAAAAh+QQRDAAAACwAAAAAFAAUAAADLwi63P4wyrlIoCzofekVHQZ0IUaKyolyW0QAQpbCwDupIm7OHltSMdTiJ7IJj6IEACH5BBEMAAAALAAAAAAUABQAAAMtCLrc/jDKyQKtIetJgPVLJwnfJ1zltaSqp20tq8qo8o2rckrdq4m1Vk5ILBITACH5BBEMAAAALAAAAAAUABQAAAMvCLrc/jDKuUigLOh96RUdBnQhRorKiXIbIABEE7+LKtpmio66x5YU2o43hBWPlAQAIfkEEQwAAAAsAAAAABQAFAAAAy0Iutz+MMrJAq0h60mA9UsnCd8nXOW1pKqnbS2ryqjyjatySt2ribVWTkgsEhMAIfkEEQwAAAAsAAAAABQAFAAAAy8Iutz+MMq5SKAs6H3pFR0GdCFGisqJchsgAEQTv4sq2maKjrrHlhTajjeEFY+UBAAh+QQRDAAAACwAAAAAFAAUAAADLQi63P4wyskCrSHrSYD1SycJ3ydc5bWkqqdtLavKqPKNq3JK3auJtVZOSCwSEwAh+QQRDAAAACwAAAAAFAAUAAADLwi63P4wyrlIoCzofekVHQZ0IUaKyolyGyAARBO/iyraZoqOuseWFNqON4QVj5QEACH5BBEMAAAALAAAAAAUABQAAAMtCLrc/jDKyQKtIetJgPVLJwnfJ1zltaSqp20tq8qo8o2rckrdq4m1Vk5ILBITADs=" alt="dollar" style="height:35px">
    <img src="data:image/gif;base64,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" alt="yard sale">
    <img src="data:image/gif;base64,R0lGODlhFAAUAPIAAP///wB4ADK0Msj/yP/cAAAAAAAAAAAAACH/C05FVFNDQVBFMi4wAwEAAAAh+QQRDAAAACwAAAAAFAAUAAADLwi63P4wyrlIoCzofekVHQZ0IUaKyolyW0QAQpbCwDupIm7OHltSMdTiJ7IJj6IEACH5BBEMAAAALAAAAAAUABQAAAMtCLrc/jDKyQKtIetJgPVLJwnfJ1zltaSqp20tq8qo8o2rckrdq4m1Vk5ILBITACH5BBEMAAAALAAAAAAUABQAAAMvCLrc/jDKuUigLOh96RUdBnQhRorKiXIbIABEE7+LKtpmio66x5YU2o43hBWPlAQAIfkEEQwAAAAsAAAAABQAFAAAAy0Iutz+MMrJAq0h60mA9UsnCd8nXOW1pKqnbS2ryqjyjatySt2ribVWTkgsEhMAIfkEEQwAAAAsAAAAABQAFAAAAy8Iutz+MMq5SKAs6H3pFR0GdCFGisqJchsgAEQTv4sq2maKjrrHlhTajjeEFY+UBAAh+QQRDAAAACwAAAAAFAAUAAADLQi63P4wyskCrSHrSYD1SycJ3ydc5bWkqqdtLavKqPKNq3JK3auJtVZOSCwSEwAh+QQRDAAAACwAAAAAFAAUAAADLwi63P4wyrlIoCzofekVHQZ0IUaKyolyGyAARBO/iyraZoqOuseWFNqON4QVj5QEACH5BBEMAAAALAAAAAAUABQAAAMtCLrc/jDKyQKtIetJgPVLJwnfJ1zltaSqp20tq8qo8o2rckrdq4m1Vk5ILBITADs=" alt="dollar" style="height:35px">
  </div>
 
  <h2>💵 available if not listed as sold / going for mate rates 💵</h2>
 
  <div class="grid">
    
    <div class="item">
      <div class="item-img">💵</div>
      <div class="item-title">50 inch TV</div>
      <div class="item-author">w/remote</div>
      <div class="item-price">$40</div>
    </div>
    
    <div class="item">
      <div class="item-img">💵</div>
      <div class="item-title">Acoustic Guitar</div>
      <div class="item-author">Classical / nylon strings</div>
      <div class="item-price">$70</div>
    </div>
    
    <div class="item">
      <div class="item-img">💵</div>
      <div class="item-title">Monitor, 27 inch</div>
      <div class="item-price">$40</div>
    </div>
    
    <div class="item">
      <div class="item-img">💵</div>
      <div class="item-title">Monitor Stand</div>
      <div class="item-price">$5</div>
    </div>
    
    <div class="item">
      <div class="item-img">💵</div>
      <div class="item-title">Dumbell, 15lb</div>
      <div class="item-price">$5</div>
    </div>
    
    <div class="item">
      <div class="item-img">💵</div>
      <div class="item-title">Porch sofa</div>
      <div class="item-author">Bought for $110!</div>
      <div class="item-price">$45</div>
    </div>
    
    <div class="item">
      <div class="item-img">💵</div>
      <div class="item-title">Exercise Mat</div>
      <div class="item-price">$3</div>
    </div>
    
    <div class="item">
      <div class="item-img">💵</div>
      <div class="item-title">Plant #1</div>
      <div class="item-author">Pothos w/ pot</div>
      <div class="item-price">$20</div>
    </div>
    
    <div class="item">
      <div class="item-img">💵</div>
      <div class="item-title">Plant #2</div>
      <div class="item-author">Monstera w/ pot</div>
      <div class="item-price">$15</div>
    </div>
 
    <div class="item">
      <div class="item-img">💵</div>
      <div class="item-title">Plant #3</div>
      <div class="item-author">Bamboo? w/ pot Idk</div>
      <div class="item-price">$10</div>
    </div>
    
    <div class="item">
      <div class="item-img">💵</div>
      <div class="item-title">Plant #4</div>
      <div class="item-author">Baby pathos w/lovely pot</div>
      <div class="item-price">$8</div>
    </div>
    
    <div class="item">
      <div class="item-img">💵</div>
      <div class="item-title">Upright Piano</div>
      <div class="item-author">All keys work, in tune (acceptable, that is) Have to move yourself!</div>
      <div class="item-price">$25</div>
    </div>
    
    <div class="item">
      <div class="item-img">💵</div>
      <div class="item-title">All Fours</div>
      <div class="item-author">Miranda July</div>
      <div class="item-price">$2</div>
    </div>
    
    <div class="item">
      <div class="item-img">💵</div>
      <div class="item-title">Liberation Day</div>
      <div class="item-author">George Saunders</div>
      <div class="item-price">$2</div>
    </div>
 
    <div class="item">
      <div class="item-img">💵</div>
      <div class="item-title">The White Album</div>
      <div class="item-author">Joan Didion</div>
      <div class="item-price">$1</div>
    </div>
 
    <div class="item">
      <div class="item-img">💵</div>
      <div class="item-title">Bird by Bird</div>
      <div class="item-author">Anne Lamott</div>
      <div class="item-price">$1</div>
    </div>
 
    <div class="item sold">
      <div class="item-img">💵</div>
      <div class="item-title">A Lucky Man</div>
      <div class="item-author">Jamal Brinkley</div>
      <div class="item-price">$1</div>
      <span class="sold-label">~~SOLD~~</span>
    </div>
 
    <div class="item">
      <div class="item-img">💵</div>
      <div class="item-title">The Road</div>
      <div class="item-author">Cormac McCarthy</div>
      <div class="item-price">$2</div>
    </div>
 
    <div class="item">
      <div class="item-img">💵</div>
      <div class="item-title">The Idiot</div>
      <div class="item-author">Elif Batuman</div>
      <div class="item-price">$2</div>
    </div>
 
    <div class="item">
      <div class="item-img">💵</div>
      <div class="item-title">New American Stories</div>
      <div class="item-price">$2</div>
    </div>
 
    <div class="item">
      <div class="item-img">💵</div>
      <div class="item-title">The Brief Wondrous Life of Oscar Wao</div>
      <div class="item-author">Junot Diaz</div>
      <div class="item-price">$2</div>
    </div>
 
    <div class="item">
      <div class="item-img">💵</div>
      <div class="item-title">To the Lighthouse</div>
      <div class="item-author">Virginia Woolf</div>
      <div class="item-price">$1</div>
    </div>
 
    <div class="item">
      <div class="item-img">💵</div>
      <div class="item-title">Pigs in Heaven</div>
      <div class="item-author">Barbara Kingsolver</div>
      <div class="item-price">$2</div>
    </div>
 
    <div class="item">
      <div class="item-img">💵</div>
      <div class="item-title">Emergency</div>
      <div class="item-author">Kathleen Alcott</div>
      <div class="item-price">$1</div>
    </div>
 
    <div class="item">
      <div class="item-img">💵</div>
      <div class="item-title">PEN O'Henry Stories 2012</div>
      <div class="item-price">$1</div>
    </div>
  
    <div class="item">
      <div class="item-img">💵</div>
      <div class="item-title">The Argonauts</div>
      <div class="item-author">Maggie Nelson</div>
      <div class="item-price">$2</div>
    </div>
   
    <div class="item">
      <div class="item-img">💵</div>
      <div class="item-title">Falconer</div>
      <div class="item-author">John Cheever</div>
      <div class="item-price">$2</div>
    </div>
      
    <div class="item">
      <div class="item-img">💵</div>
      <div class="item-title">Paddy Clarke Ha Ha Ha</div>
      <div class="item-author">Roddy Doyle</div>
      <div class="item-price">$1</div>
    </div>
      
    <div class="item">
      <div class="item-img">💵</div>
      <div class="item-title">Chronicle of a Death Foretold</div>
      <div class="item-author">Gabriel Garcia Marquez</div>
      <div class="item-price">$1</div>
    </div>
      
    <div class="item">
      <div class="item-img">💵</div>
      <div class="item-title">Autumn</div>
      <div class="item-author">Ali Smith</div>
      <div class="item-price">$1</div>
    </div>
      
      <div class="item">
      <div class="item-img">💵</div>
      <div class="item-title">Vintage Book of Contemporary Irish Fiction</div>
      <div class="item-price">$1</div>
    </div>
          
      <div class="item">
      <div class="item-img">💵</div>
      <div class="item-title">Selected Stories</div>
      <div class="item-author">Alice Munro</div>
      <div class="item-price">$2</div>
    </div>
    
      <div class="item">
      <div class="item-img">💵</div>
      <div class="item-title">Angel</div>
      <div class="item-author">Elizabeth Taylor</div>
      <div class="item-price">$1</div>
    </div>
    
      <div class="item">
      <div class="item-img">💵</div>
      <div class="item-title">Island of the Color Blind</div>
      <div class="item-author">Oliver Sacks</div>
      <div class="item-price">$2</div>
    </div>
          
      <div class="item">
      <div class="item-img">💵</div>
      <div class="item-title">Close to Home</div>
      <div class="item-author">Michael Magee</div>
      <div class="item-price">$2</div>
    </div>
    
      <div class="item">
      <div class="item-img">💵</div>
      <div class="item-title">Anything is Possible</div>
      <div class="item-author">Elizabeth Strout</div>
      <div class="item-price">$2</div>
    </div>
    
  </div>
</main>
 
<footer>
  <div class="footer-gifs">
    <img src="data:image/gif;base64,R0lGODlhFAAUAPIAAP///wB4ADK0Msj/yP/cAAAAAAAAAAAAACH/C05FVFNDQVBFMi4wAwEAAAAh+QQRDAAAACwAAAAAFAAUAAADLwi63P4wyrlIoCzofekVHQZ0IUaKyolyW0QAQpbCwDupIm7OHltSMdTiJ7IJj6IEACH5BBEMAAAALAAAAAAUABQAAAMtCLrc/jDKyQKtIetJgPVLJwnfJ1zltaSqp20tq8qo8o2rckrdq4m1Vk5ILBITACH5BBEMAAAALAAAAAAUABQAAAMvCLrc/jDKuUigLOh96RUdBnQhRorKiXIbIABEE7+LKtpmio66x5YU2o43hBWPlAQAIfkEEQwAAAAsAAAAABQAFAAAAy0Iutz+MMrJAq0h60mA9UsnCd8nXOW1pKqnbS2ryqjyjatySt2ribVWTkgsEhMAIfkEEQwAAAAsAAAAABQAFAAAAy8Iutz+MMq5SKAs6H3pFR0GdCFGisqJchsgAEQTv4sq2maKjrrHlhTajjeEFY+UBAAh+QQRDAAAACwAAAAAFAAUAAADLQi63P4wyskCrSHrSYD1SycJ3ydc5bWkqqdtLavKqPKNq3JK3auJtVZOSCwSEwAh+QQRDAAAACwAAAAAFAAUAAADLwi63P4wyrlIoCzofekVHQZ0IUaKyolyGyAARBO/iyraZoqOuseWFNqON4QVj5QEACH5BBEMAAAALAAAAAAUABQAAAMtCLrc/jDKyQKtIetJgPVLJwnfJ1zltaSqp20tq8qo8o2rckrdq4m1Vk5ILBITADs=" alt="dollar" style="height:30px">
    <img src="data:image/gif;base64,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" alt="yard sale">
    <img src="data:image/gif;base64,R0lGODlhFAAUAPIAAP///wB4ADK0Msj/yP/cAAAAAAAAAAAAACH/C05FVFNDQVBFMi4wAwEAAAAh+QQRDAAAACwAAAAAFAAUAAADLwi63P4wyrlIoCzofekVHQZ0IUaKyolyW0QAQpbCwDupIm7OHltSMdTiJ7IJj6IEACH5BBEMAAAALAAAAAAUABQAAAMtCLrc/jDKyQKtIetJgPVLJwnfJ1zltaSqp20tq8qo8o2rckrdq4m1Vk5ILBITACH5BBEMAAAALAAAAAAUABQAAAMvCLrc/jDKuUigLOh96RUdBnQhRorKiXIbIABEE7+LKtpmio66x5YU2o43hBWPlAQAIfkEEQwAAAAsAAAAABQAFAAAAy0Iutz+MMrJAq0h60mA9UsnCd8nXOW1pKqnbS2ryqjyjatySt2ribVWTkgsEhMAIfkEEQwAAAAsAAAAABQAFAAAAy8Iutz+MMq5SKAs6H3pFR0GdCFGisqJchsgAEQTv4sq2maKjrrHlhTajjeEFY+UBAAh+QQRDAAAACwAAAAAFAAUAAADLQi63P4wyskCrSHrSYD1SycJ3ydc5bWkqqdtLavKqPKNq3JK3auJtVZOSCwSEwAh+QQRDAAAACwAAAAAFAAUAAADLwi63P4wyrlIoCzofekVHQZ0IUaKyolyGyAARBO/iyraZoqOuseWFNqON4QVj5QEACH5BBEMAAAALAAAAAAUABQAAAMtCLrc/jDKyQKtIetJgPVLJwnfJ1zltaSqp20tq8qo8o2rckrdq4m1Vk5ILBITADs=" alt="dollar" style="height:30px">
  </div>
  text or email to claim &nbsp;|&nbsp; venmo @Teddy-Carolan or cash in person<br>
</footer>
 
</body>
</html>
 
