# Desafio 23: Hito 7 (Pizzería Mamma Mía)

1. Implementa useParams para obtener el id de la pizza en la página de Pizza.jsx. Con el id obtenido, realiza una petición a la API para obtener la información de la pizza y mostrarla en la página (2 ptos) ---> Check
2. Crea un UserContext para almacenar el token (simulado) que estamos utilizando en el Navbar.jsx. Por ahora este context tiene que tener las siguientes características (2 ptos)
    - Un estado que almacene el token, por defecto, en true ---> Check
    - Un método logout que cambie el estado del token a false ---> Check
3. Utiliza el UserContext en el Navbar.jsx, al hacer click en el botón de logout, se debe ejecutar el método logout (2 ptos) ---> Check
4. Utiliza el UserContext en la página de Cart.jsx, deshabilita el botón "pagar" en caso de que el token sea false (1 pto) ---> Check
5. Implementa la ruta protegida para "/profile". Si el token es false, redirige a "/login". Además, si el token es true, los usuarios no deberían poder acceder a la página de login y register (los puedes redigir al home) (3 ptos) ---> Check