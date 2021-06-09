<script>
    import Lais from '../assets/images/lais.jpg';
    import Biel from '../assets/images/biel.jpg';
    import Ana from '../assets/images/ana.jpg';
    import Djuly from '../assets/images/djuly.jpg';
    import Gui from '../assets/images/gui.png';
    import Lucas from '../assets/images/lucas.jpg';
    import Gaby from '../assets/images/gaby.png';
    import Berreta from '../assets/images/berreta.jpg';


</script>

<style>
	main {
		color: black;
		background-color: white;
		width: 90%;
		max-width: 720px;
		margin: auto;
	}

	h1 {
		color: maroon;
	}

	h1 {
		text-align: center;
	}

	p {
		text-align: justify;
	}

    .card {
        background-color: white;
        padding: 32px;
        box-sizing: border-box;
        display: flex;
        border-radius: 16px;
        box-shadow: 2px 2px 8px rgba(0, 0, 0, 0.4);
        place-content: center;
        place-items: center;
        margin: 32px auto;
    }

    img {
        height: 256px;
        margin: 0 16px;
        border-radius: 16px;
    }

    em {
        font-weight: normal;
    }

    @media only screen and (max-width: 400px) {
    .card {
        flex-direction: column;
    }

    .card:nth-of-type(even) {
        flex-direction: column-reverse;
    }
}

</style>

<title>Arkanna - Grupo de Aventureiros</title>

<main>
    <h1>
        Grupo de Aventureiros
    </h1>
    <div class="card">
        <img src={Lais} alt="Cora Bombarril">
        <div class="info">
            <h3>Cora Bombarril <em>(Laís)</em></h3>
            <h4>Halfling - Ladino</h4>
            <p>
                Desdecendente de uma tradicional familia de ladrões, também herdou o ofício da família. Quando ela era bebê, seus pais foram pegos tentando roubar da Guilda de brandeville, como punição eles e seus descendentes precisam prestar 150 anos de serviços, como ladrões e caçadores de tesouros.
            </p>
        </div>
    </div>
    <div class="card">        
        <div class="info">
            <h3>Alatreon <em>(Gabriel)</em></h3>
            <h4>Tiefling - Bardo</h4>
            <p>
                Pouco se sabe sobre o misterioso e tímido bardo. Ele viaja de cidade em cidade fazendo o bem e buscando por aventuras. Tocando sua gaita de fóleo sempre que possível. Agora está junto com um grupo de rebeldes que pretende derrubar a Guilda.
            </p>
        </div>
        <img src={Biel} alt="Alatreon">
    </div>
    <div class="card">
        <img src={Djuly} alt="Elanor">
        <div class="info">
            <h3>Elanor <em>(Djuly)</em></h3>
            <h4>Meia-Elfa - Clériga</h4>
            <p>
                Filha da elfa Elbereth Liadon e do humano Gregor Brightwater. Sua mãe foi capturada quando Elanor tinha apenas 6 anos e levada pela guilda pela Guilda para a capiutão de Brandeville. Ela cresceu escondida no templo com seu pai. Por ter similaridades com a deusa MAlvys acredita que tem um potencial maior a cumprir nesse mundo, por isso se uniu à resistência contra a Guilda.
            </p>
        </div>
    </div>
    <!-- <div class="card">        
        <div class="info">
            <h3>Melkior <em>(Gui)</em></h3>
            <h4>Humano - Bruxo</h4>
            <p>
                Um poderoso bruxo, seus pais fizeram um trato com Titrus, agora Melkior é imortal e ainda está pagando pelo contrato feito por seus falecidos pais. Há 300 anos atrás foi capturado pela Guilda enquanto tentava roubar uma ampulheta mágica, a mando de seu patrono, foi preso e esquartejado. Seus pedaços foram espalhados por Arkanna, mas ele continua planejando sua vingança até hoje.
            </p>
        </div>
        <img src={Gui} alt="Melkior">
    </div> -->
    <div class="card">        
        <div class="info">
            <h3>Likha Konka <em>(Lucas)</em></h3>
            <h4>Halfling - Ranger</h4>
            <p>
                Integrante da liga de Artesãos, essa talentosa halfling desenvolveu uma avançadíssima arma de fogo. Após roubar materiais de sua própria guilda voltou para Querizania, sua cidade natal, onde busca aperfeiçoar sua arma e um dia voltar para a Guilda, para pagar seu débito para com eles, e ganhar seu respeito, com sua arma avançada.
            </p>
        </div>
        <img src={Lucas} alt="Likha Konka">
    </div>
    <div class="card">
        <img src={Ana} alt="Vanessah">
        <div class="info">
            <h3>Vanessah <em>(Ana)</em></h3>
            <h4>Meia-Orc - Bárbaro</h4>
            <p>
                Filha de uma humana  com um orc. Morava na floresta com os orcs, mas tinha curiosidade pelos humanos. Começou a pegar trabalhos na cidade e viver como aventureira.
            </p>
        </div>
    </div>
    <div class="card">        
        <div class="info">
            <h3>Gilger <em>(Berreta)</em></h3>
            <h4>Anão - Paladino</h4>
            <p>
                Um paladino que fez o Juramento da Vingança. Sempre em busca de justiça a qualquer custo, não póde permitir que malfeitores saiam impunes.
            </p>
        </div>
        <img src={Berreta} alt="Gilger">
    </div>    
    <div class="card">
        <img src={Gui} alt="Haroldo">
        <div class="info">
            <h3>Haroldo <em>(Gui)</em></h3>
            <h4>Draconato - Guerreiro</h4>
            <p>
                Membro de um clã de draconatos que tem como juramento proteger os dragões de Arkanna. Encontrou primeiro Ayla e depois o restante do grupo enquanto procurava pelo filhote de dragão negro perdido.
            </p>
        </div>
    </div>
    <div class="card">        
        <div class="info">
            <h3>Ayla <em>(Gaby)</em></h3>
            <h4>Elfa - Druída</h4>
            <p>
                Essa misteriosa elfa é uma integrante do Clã da Lua, e se sente tão confortável em um corpo de lobo quanto no seu corpo de nascimento. Ela busca poder e conhecimento e não confia muito na humanidade em geral.
            </p>
        </div>
        <img src={Gaby} alt="Ayla">
    </div>
    
</main>