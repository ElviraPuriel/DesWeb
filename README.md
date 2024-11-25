<html>
<head>
   
    <title>Formulario</title>
    <style>

.contenedor-formulario {
            width: 400px;
            margin: 0 auto;
            background-color: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.3);
        }
        input[type=text], select{ 
        width: 100%;
            padding: 12px 20px;
            margin: 8px 0;
            display: inline-block;
            border: 1px solid #ccc;
            border-radius: 8px;
            box-sizing: border-box;
        }
p{
text-align:center;
}
h1{
text-align:center;
}

  button[type=submit]{ 
        width: 100%;
            background-color: #4CAF50;
            color: white;
            padding: 14px 20px;
            margin: 8px 0; 
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        
        button[type=submit]:hover{
            background-color: #0C5115;
        }
   input, textarea, select {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 4px;
            box-sizing: border-box;
 }
        div{
            border-radius: 8px;
            background-color: #f2f2f2;
            padding: 20px;
        }
        
    </style>
        </head>
    <body>
        <h1>Formulario de Contacto</h1>
<p>Por favor, complete el siguiente formulario:</p> 
        <div class= "contenedor-formulario">
        <form action="#" method="post">
            <label for="fname">Nombre:</label>
            <input type="text" id="fname" name="fname" placeholder="Your name.." required>

            <label for="email">Correo Electrónico:</label>
            <input type="email" id="email" name="email" placeholder="Your email.." required>
            
            <label for="tel">Teléfono:</label>
            <input type="tel" id="telefono" name="telefono" placeholder="Your number..">
          
            
<label for="pais">País</label>
            <select id="pais" name="pais">
            <option value="">Seleccione un país</option>
            <option value="autralia">Australia</option>
            <option value="canada">Canada</option>
            <option value="usa">USA</option>
            <option value="mexico">México</option>
            </select>
            
            <label for="comentarios">Comentarios</label>
            <textarea id="comentarios" name="comentarios" placeholder="Escriba sus comentarios aquí"></textarea>

            <button type="submit">Enviar</button>
             </form>
        
        </div>
        
    </body>
</html>

