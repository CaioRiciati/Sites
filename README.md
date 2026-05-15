<img width="1152" height="648" alt="image" src="https://github.com/user-attachments/assets/1854a429-f64b-40f0-887c-5b9b20e95c3e" /># Sites
 Meus estudos e projetos
<a href= "https://caioriciati.github.io/Sites/html-css/Exercicios/Desafios/HotBurgers/index.html"> Site HotBurguers </a>
<br>
<a href= "https://caioriciati.github.io/Sites/html-css/Exercicios/Desafios/Front/index.html"> Site Front </a>

<a href= "https://caioriciati.github.io/Sites/feira/index.html"> Site Feira </a>



<a href= "https://caioriciati.github.io/Sites/projetin/index.html"> Site projetin </a>


float raizq(float numero)
{
    float estimativa = 1.0;
    float precisao = 0.001; // Define a precisão do cálculo

    if (numero < 0) {
        printf("Não é possível calcular a raiz de um número negativo.\n");
        return 1;
    }

    while ((estimativa * estimativa - numero) > precisao || (numero - estimativa * estimativa) > precisao) {
        estimativa = (estimativa + numero / estimativa) / 2.0;
    }

    return estimativa;

    return 0;
}
