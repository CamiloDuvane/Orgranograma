<html><head><base href="https://camiloduvane.github.io/Orgranograma/" />
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Organograma DMTT</title>
<style>
.back-button {
  position: fixed;
  top: 20px;
  left: 20px;
  padding: 10px 20px;
  background-color: #4CAF50;
  color: white;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  font-size: 16px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.2);
  transition: all 0.3s ease;
  text-decoration: none;
  display: inline-block;
}

.back-button:hover {
  background-color: #45a049;
  transform: translateY(-2px);
  box-shadow: 0 4px 8px rgba(0,0,0,0.2);
}

body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  margin: 0;
  padding: 20px;
  background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
  min-height: 100vh;
}

.org-chart {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 50px;
  padding: 20px;
}

.level {
  display: flex;
  justify-content: center;
  gap: 40px;
  position: relative;
  width: 100%;
}

.box {
  background: white;
  border-radius: 15px;
  padding: 20px;
  width: 200px;
  text-align: center;
  box-shadow: 0 10px 20px rgba(0,0,0,0.1);
  transition: all 0.3s ease;
  position: relative;
}

.box:hover {
  transform: translateY(-5px);
  box-shadow: 0 15px 30px rgba(0,0,0,0.2);
}

.avatar {
  width: 100px;
  height: 100px;
  border-radius: 50%;
  margin: 0 auto 15px;
  overflow: hidden;
  border: 3px solid #4CAF50;
  transition: transform 0.3s ease;
}

.avatar img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.name {
  font-size: 1.2em;
  font-weight: bold;
  color: #2c3e50;
  margin-bottom: 5px;
}

.position {
  font-size: 0.9em;
  color: #7f8c8d;
  margin-bottom: 10px;
}

.contact-info {
  font-size: 0.8em;
  color: #95a5a6;
  display: none;
  margin-top: 10px;
}

.box:hover .contact-info {
  display: block;
}

.connector {
  position: absolute;
  border: 2px solid #4CAF50;
  z-index: -1;
}

.vertical {
  width: 2px;
  background: #4CAF50;
  position: absolute;
  left: 50%;
  transform: translateX(-50%);
}

.horizontal {
  height: 2px;
  background: #4CAF50;
  position: absolute;
  top: -25px;
}

@media (max-width: 768px) {
  .level {
    flex-direction: column;
    align-items: center;
    gap: 30px;
  }
  
  .box {
    width: 80%;
    max-width: 300px;
  }
}
</style>
</head>
<body>

<a href="https://camiloduvane.github.io/DMTT/" class="back-button">← Voltar</a>

<div class="org-chart">
  <div class="level">
    <div class="box" onclick="showDetails(this)">
      <div class="avatar">
        <img alt="headshot photo of Fernando Uache, professional style" src="fernandouache.jpg" width="100" height="100">
      </div>
      <div class="name">Fernando Uache</div>
      <div class="position">Vereador</div>
      <div class="contact-info">
        Email:fernando.uache@CamiloDuvane.com<br>
        Tel: (258) 84 000 0000
      </div>
    </div>
  </div>

  <div class="level">
    <div class="box" onclick="showDetails(this)">
      <div class="avatar">
        <img alt="headshot photo of Nelson Massango, professional style" src="nelsonmassango.jpg" width="100" height="100">
      </div>
      <div class="name">Nelson Massango</div>
      <div class="position">Director</div>
      <div class="contact-info">
        Email:
nelson.massangos@CamiloDuvane.com<br>
        Tel: (258) 84 000 0000
      </div>
    </div>
  </div>

  <div class="level">
    <div class="box" onclick="showDetails(this)">
      <div class="avatar">
        <img alt="headshot photo of Carlos Vilanculos, professional style" src="carlosvilanculos.jpg" width="100" height="100">
      </div>
      <div class="name">Carlos Vilanculos</div>
      <div class="position">DARHF</div>
      <div class="position">Departamento de Administração de Recursos Humanos e Finanças</div>
      <div class="contact-info">
        Email: carlos.vilanculos@CamiloDuvane.com<br>
        Tel: (258) 84 000 0000
      </div>
    </div>
    
    <div class="box" onclick="showDetails(this)">
      <div class="avatar">
        <img alt="headshot photo of Amilton Tembe, professional style" src="amiltontembe.jpg" width="100" height="100">
      </div>
      <div class="name">Amilton Tembe</div>
      <div class="position">DL</div>
      <div class="position">Departamento de Licenciamento</div>
      <div class="contact-info">
        Email: hamilton.tembe@CamiloDuvane.com<br>
        Tel: (258) 84 000 0000
      </div>
    </div>

    <div class="box" onclick="showDetails(this)">
      <div class="avatar">
        <img alt="headshot photo of Vasco Nhaquila, professional style" src="vasconhaquila.jpg" width="100" height="100">
      </div>
      <div class="name">Vasco Nhaquila</div>
      <div class="position">DTP</div>
      <div class="position">Departamento de Transportes Públicos</div>
      <div class="contact-info">
        Email: vasco.nhaquila@CamiloDuvane.com<br>
        Tel: (258) 84 000 0000
      </div>
    </div>

    <div class="box" onclick="showDetails(this)">
      <div class="avatar">
        <img alt="headshot photo of Baltazar Hilario, professional style" src="baltazar-hilario.jpg" width="100" height="100">
      </div>
      <div class="name">Baltazar Hilario</div>
      <div class="position">DOT</div>
      <div class="position">Departamento de Operações e Trânsito</div>
      <div class="contact-info">
        Email: baltazar.hilario@CamiloDuvane.com<br>
        Tel: (258) 84 000 0000
      </div>
    </div>
  </div>
</div>

<script>
function showDetails(element) {
  const contactInfo = element.querySelector('.contact-info');
  contactInfo.style.display = contactInfo.style.display === 'block' ? 'none' : 'block';
}

// Add connecting lines
document.addEventListener('DOMContentLoaded', function() {
  const levels = document.querySelectorAll('.level');
  
  for(let i = 0; i < levels.length - 1; i++) {
    const currentLevel = levels[i];
    const nextLevel = levels[i + 1];
    const currentBoxes = currentLevel.querySelectorAll('.box');
    const nextBoxes = nextLevel.querySelectorAll('.box');
    
    currentBoxes.forEach((box, index) => {
      const connector = document.createElement('div');
      connector.className = 'connector vertical';
      connector.style.height = '50px';
      connector.style.top = '100%';
      box.appendChild(connector);
    });
  }
});
</script>

</body></html>
