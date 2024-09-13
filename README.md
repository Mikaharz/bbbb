.cartao__conteudo__resposta{
    transform: rotateY(180deg);
    background-color: rgba(0, 244, 191, 0.2);
    border: 4px solid var(--card-back-color);
}
.cartao_conteudo_pergunta,
.cartao_conteudo_resposta {
    backface-visibility: hidden;
    position: absolute;
    height: 100%;
    width: 100%;
    box-sizing: border-box;
}
.cartao__conteudo p {
    margin-top: 1rem;
    padding: 2rem;
    margin-top: 4rem;
    font-size: 1.4vw;
}
@media (max-width: 560 px) {

    body {
        background: url('img/bd-mobile.webp');
    }

}
.cartao {
        flex: 1 0 calc(100% - 1rem);
    }
    .cartao__conteudo h3 {
    font-size: 3vw;
}
.cartao__conteudo p {
    font-size: 3.8vw;
}
