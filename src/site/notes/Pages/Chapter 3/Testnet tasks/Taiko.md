---
{"dg-publish":true,"permalink":"/pages/chapter-3/testnet-tasks/taiko/"}
---


![1 22.png](/img/user/Images/1%2022.png)

> [!info]
> _Taiko_ — это децентрализованный Ethereum-эквивалент ZK-EVM и ZK-Rollup. Его цель - позволить разработчикам и пользователям dApps, созданных для Ethereum L1, использовать их на Taiko без каких-либо изменений. Проект собрал 22млн$ инвестиций от крупных проектов, таких как OKX и KuCoin.

![2 18.png](/img/user/Images/2%2018.png)

## Testnet

1. Для начала нам нужно добавить две тестовых сети. Первая Holesky - [тут](https://chainlist.org/chain/17000)  
    ![3 17.png](/img/user/Images/3%2017.png)
    ![4 14.png](/img/user/Images/4%2014.png)
    Вторая - [тут](https://chainlist.org/chain/167008)  
    ![5 14.png](/img/user/Images/5%2014.png)
2. Теперь нам нужно получить тестовые токены Holesky [тут](https://faucetlink.to/). Выбираем Holesky  
    ![6 10.png](/img/user/Images/6%2010.png)
    ![7 8.png](/img/user/Images/7%208.png)
3. Переходим на данный сайт и майним себе токены  
    ![8 7.png](/img/user/Images/8%207.png)

---

4. После того, как намайнили токены, мы советуем майнить около 0,5-1 (чтобы точно хватило ETH), жмем Stop Mining и забираем награды  
    ![9 6.png](/img/user/Images/9%206.png)
    ![10 5.png](/img/user/Images/10%205.png)

---

5. Подключаем наш метамаск к сети Holesky  
    ![11 5.png](/img/user/Images/11%205.png)

### Оф. мост

1. Видим токены на балансе, теперь нам нужно отправить наш ETH из сети Holesky в Katla - [тут](https://bridge.katla.taiko.xyz/)  
    ![12 6.png](/img/user/Images/12%206.png)

---

2. После подключения кошелька, отправляем примерно половину наших токенов в сеть Katla  
    ![13 4.png](/img/user/Images/13%204.png)

---

3. После отправки переходим в ветку _Faucet_  
    ![14 4.png](/img/user/Images/14%204.png)

---

4. Запрашиваем токен Horse  
    ![15 4.png](/img/user/Images/15%204.png)

---

5. После подтверждения в Метамаске возвращаемся на мост  
    ![16 4.png](/img/user/Images/16%204.png)

---

6. Выбираем токены Horse  
    ![17 3.png](/img/user/Images/17%203.png)

---

7. И отправляем примерно половину токенов  
    ![18 3.png](/img/user/Images/18%203.png)
    ![19 3.png](/img/user/Images/19%203.png)
    ![20 2.png](/img/user/Images/20%202.png)

---

8. После отправки токенов меняем сеть на Katla, нажав на значок стрелок  
    ![21 2.png](/img/user/Images/21%202.png)

---

9. И отправляем назад в сеть Holesky немного Eth.

Важно из KATLA отправляем только с агрессивным газом, так транзакции будут проходить быстрее!

![22 4.png](/img/user/Images/22%204.png)

![23 4.png](/img/user/Images/23%204.png)

![24 3.png](/img/user/Images/24%203.png)

---

10. То же самое делаем с токеном Horse. Апрув и бридж , все как обычно:)  
    ![25 3.png](/img/user/Images/25%203.png)

---

11. Теперь свапаем токены [тут](https://swap.katla.taiko.xyz/#/swap?chain=taiko-katla). Обязательно в сети Katla 
    ![26 3.png](/img/user/Images/26%203.png)

---

12. И, также, делаем с другой парой токенов примерно половину от того, что получили  
    ![27 3.png](/img/user/Images/27%203.png)

---

13. После свапов переходим в ветку _Pool_  
    ![28 3.png](/img/user/Images/28%203.png)
    ![29 3.png](/img/user/Images/29%203.png)

---

14. Выбираем пару токенов  
    ![30 3.png](/img/user/Images/30%203.png)
    ![31 3.png](/img/user/Images/31%203.png)

---

15. Колесиком мыши прокручиваем вниз и выставляем сумму  
    ![32 3.png](/img/user/Images/32%203.png)

---

16. Аппруваем токены и отправляем транзакцию  
    ![33 2.png](/img/user/Images/33%202.png)
    ![34 4.png](/img/user/Images/34%204.png)
    ![35 2.png](/img/user/Images/35%202.png)

_Pool_ мы добавили - отлично!  

![36 3.png](/img/user/Images/36%203.png)

---

17. Теперь нажимаем на наш Pool и выводим часть токенов  
    ![37 3.png](/img/user/Images/37%203.png)
    ![38 3.png](/img/user/Images/38%203.png)

## Смарт-контракт

1. После вывода части токенов, нам нужно развернуть смарт-контракт [тут](https://remix.ethereum.org/)
    
    Важно, вы должны быть в сети Katla!!!
    

![39 4.png](/img/user/Images/39%204.png)

---

2. Нажимаем _Contracts_ - _Storage.sol_ - и на значок _Solidity compiler_  
    ![40 3.png](/img/user/Images/40%203.png)
    После перехода на другую страницу, жмем _Compile 1_ (синяя кнопка)

---

3. Должна появиться зеленая галочка слева  
    ![41 3.png](/img/user/Images/41%203.png)

---

4. Переходим в эту вкладку  
    ![42 3.png](/img/user/Images/42%203.png)

---

5. Выбираем наш Метамаск  
     ![43 3.png](/img/user/Images/43%203.png)
    Жмем _Deploy_  
    ![44 2.png](/img/user/Images/44%202.png)
    Убеждаемся, что сеть Katla и отправляем транзакцию  
    ![45 1.png](/img/user/Images/45%201.png)

---

6. Видим, что контракт мы развернули  
    ![46 1.png](/img/user/Images/46%201.png)

## NFT

1. Осталось совсем чуть чуть) идем сюда - [тык](https://thirdweb.com/dashboard/contracts/deploy).  
    Подключаем наш Метамаск в сети Katla.  
    ![47 1.png](/img/user/Images/47%201.png)
    ![48 1.png](/img/user/Images/48%201.png)
    ![49 1.png](/img/user/Images/49%201.png)

![50 1.png](/img/user/Images/50%201.png)

![51 1.png](/img/user/Images/51%201.png)

---

2. Вписываем в пустые поля любые значения и жмем _Upload file_, выбираем любую картинку  
---

3. Спускаемся ниже и жмем _Deploy Now_ подтверждаем действия в кошельке  
    ![53.png](/img/user/Images/53.png)

---

4. После создания NFT переходим во вкладку _NFT_  
    ![55.png](/img/user/Images/55.png)

---

5. Пишем любой текст и вставляем любую картинку  
    Жмем _Lazy MINT_, после подтверждения в Метамаске видим нашу NFT

---

6. Переходим во вкладку "Claim Conditions". Далее нажимаем на синюю кнопку с надписью "Add Phase"
    ![61.png](/img/user/Images/61.png)

---

7. В этих двух строках вписываем любые значения  
    ![62.png](/img/user/Images/62.png)

---

9. После жмем _Save Phases_ и отправляем транзакцию в Метамаске.  
    ![63.png](/img/user/Images/63.png)

---

10. Жмем кнопку "Claim" и после подтверждаем
    ![65.png](/img/user/Images/65.png)

## Оф. мост

1. Теперь нам нужно вернуться сюда - [тык](https://bridge.katla.taiko.xyz/)и перейти во вкладку _NFT_  
    ![66.png](/img/user/Images/66.png)

---

2. Жмем _SCAN FOR NFT_
3. Выбираем нашу NFT и жмем _Continue_ и подтверждаем.
4. Жмем _Bridge_  
    ![69.png](/img/user/Images/69.png)

---

Вот и все мы отправили с вами NFT, а с этим и закончили проходить данный тестнет  

![70.png](/img/user/Images/70.png)

Все было просто, правда? 🙃

---

## Galxe Passport

Теперь минтим [Galxe Passport](https://galxe.com/passport)

- Простая KYC верификация
- Отдаем 7$ в BNB

Заходим [сюда](([https://galxe.com/taiko/campaign/GCwEqUSZqQ](https://galxe.com/taiko/campaign/GCwEqUSZqQ)) и забираем 2500 поинтов.

---

Далее [[Pages/Chapter 3/Testnet tasks/Berachain\|Berachain]]