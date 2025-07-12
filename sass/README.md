# Main file

1. Crear proyecto vite: npm create vite
2. Instalar nmp install
4. Instalar dependencias npm i(solo este)
3. Instalar modulo de sass para que vite pueda compilar npm i -d sass
4. Para ver la ventana npm run dev
5. Para archivos finales npm ruin buid 




Ejemplo para importar mixins 
h1{
    color: indigo;

    @include breakpoint('mobile') {
        color: aquamarine;
    }

    @include breakpoint('tablet') {
        color: rgb(255, 127, 232);
    }

    @include breakpoint('tablet_horizontal') {
        color: rgb(232, 127, 255);
    }

    @include breakpoint('desktop') {
        color: rgb(255, 180, 127);
    }

    @include breakpoint('desktop_xl') {
        color: aquamarine;
    }
}
