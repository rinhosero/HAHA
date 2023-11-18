
<div class="zag">
	<h2 class="rug">Регистрация</h2>
	<input class="vvod" type="text" placeholder="Фамилия" />
	<input class="vvod" type="text" placeholder="Имя" />
	<input class="vvod" type="text" placeholder="Отчество" />
	<input class="vvod" type="text" placeholder="Должность" />
	<input class="vvod" type="text" placeholder="Подразделение" />
	<input class="vvod" type="text" placeholder="Пароль" />
	<button class="regu">Зарегестрироваться</button>
</div>

<style>
	.zag {
		background: rgb(55, 55, 212);
		border-radius: 20px;
		width: 350px;
		height: 400px;
		display: flex;
		flex-direction: column;
		gap: 20px;
		border-radius: 50px;
	}
	.regu {
		border: none;
		background: aliceblue;
		opacity: 1;
}

	.rug{
		display: flex;
		align-items: center;
		justify-content: center;
	}
	.vvod{
		border-radius: 4px;
		grid-template-columns: 60%;
		border: none;
		height: 20px;
	}
</style>
