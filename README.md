# 微免牌
微免牌 遊戲規則介紹

# 遊戲目標
開局時即分成兩隊，紅隊和藍隊。玩家間大多彼此不互相知道對方屬於哪一隊，除了隊長之外。
遊戲目標為利用 pathogen 殲滅所有敵對的人，殲滅成功者獲勝。
# 分隊方式
若遊戲人數為N且N為偶數，則準備N/2-1張紅牌和N/2-1張藍牌以及2張空白牌。
若遊戲人數為N且N為奇數，則準備 (N-1)/2-1 張紅牌和(N-1)/2-1張藍牌以及3張空白牌。
所有玩家盲抽這些分隊牌，抽到藍牌者為藍隊，紅牌者為紅隊，空白者待定未知。除待定者外其餘玩家皆不能讓其他玩家知道自己屬於何隊。
若未分隊者有3人，則準備紅、藍、白牌各一張，共3張，請他們3人抽這3張牌。
若未分隊者有2人，則準備紅、藍牌各一張，共2張，請他們2人抽這2張牌。
此次抽牌結果可讓所有玩家看到。抽到藍牌者為藍隊隊長，抽到紅牌者為紅隊隊長。隊長在遊戲中並沒有其他特別的功能，只是讓大家知道你是哪一隊的，所以隊長有可能一直被敵對攻擊，然後掛掉。
對一般玩家而言，遊戲開始時只能知道2個隊的隊長屬於哪一隊，其他人都是不知身分。
如果遊戲人數為奇數且你拿到白色的牌，那麼你的任務就是要殲滅所有藍隊和紅隊的隊員才能取得勝利。
你覺得這樣很難嗎?
如果覺得太難就請考慮直接退出遊戲。誰叫你跟奇數個人一起玩而且你邊緣。(正在考慮增加秘密任務)
# 血
每個人一開始時有5滴血，遊戲過程中可能會喪失血，等到剩0滴血的時候就會死亡。
# 發牌及抽牌
遊戲開始時，每人發5張牌。其餘的牌堆置在一起背面朝上，稱作抽牌區。
發牌後由隨機一人開始逆時鐘輪流出牌。每個人在輪到自己的時候可以做很多事，稱作自己的回合。
玩家在自己回合結束時可以從抽牌區抽2張牌。
每個人的手牌數量上限為自己的血量的兩倍。若你的回合結束時(抽牌後)，你的手牌數量超過自己血量的2倍，你就必須棄置一些手牌，直到你的手牌數量等於你的血量的2倍為止。
# 牌簡介
遊戲中的牌有4種花色。Organ, Pathogen, Disease, Immunity。
# Organs
如果你在發牌或抽牌後得到了器官(Organ)牌，你必須立刻將該牌正面朝上擺在前面，讓所有玩家看到你獲得了一個器官。
雖然那張器官牌不在你手上而是擺在你前面，但是它仍算作你的手牌。也就是說，如果你剩下1滴血，而且你有2個器官，那麼當你的回合結束後你的手上不能剩任何一張牌。
器官一直擺在你前面，屬於你的，直到器官壞死為止。
綜合以上介紹，你會認為擁有器官只有壞處沒有好處。
# Media
遊戲中的 Media 有6張。Air, Food, Soil, Arthropod, Sex, Contact.
遊戲開始時隨機抽取其中一張擺在抽牌區旁邊。
Media 是遊戲中規定唯一的疾病傳播媒介。他也有可能在遊戲過程中被其他玩家改變。
# Pathogen attack
若你看到你想攻擊的對象獲得了一個器官，你就可能可以用 pathogen 攻擊他，但要發動攻擊必須符合一些條件，列舉如下：
1. 你的攻擊對象必須擁有一個你出的 pathogen 可以攻擊的器官。
2. 放在抽牌區旁邊的 media 必須能夠傳播你的 pathogen
例如：某個人拿到了一個 stomach 而且你手上剛好有一張 Helicobacter pylori ，而且此時的 media 剛好是 Food，你就可以利用 Helicobacter pylori 攻擊他。但若他拿到了 Small intestine 而且 media 是 air，你就甭想攻擊他了。
# 扣血
被攻擊的人可以發動「以毒攻毒」或「免疫反應」。若兩者皆失敗，就會被扣一滴血。
每個人在自己的回合只能發動一次攻擊。
# 以毒攻毒
如果你被 Pathogen 攻擊，且你手上剛好有此 pathogen 對應的 disease，你可以使用該 disease 以毒攻毒該pathogen，然後(若成功)攻擊你的人就會失一滴血。
例如，小明用 Staphylococcus aureus 攻擊小美，若小美不做任何反應，則小美失一滴血，但若小美以 Staphylococcal food poisoning 的牌反擊，小明就會失一滴血。
Pathogen和disease不一定是一對一的，而且有些pathogen較廣義，有些較狹義。
例如有一張牌叫做 Escherichia coli pathogenic serotype，對應到他的disease就有 ETEC, EPEC, EHEC。但另一某張牌 Escherichia coli O157:H7卻只能對應到EHEC。
又如Salmonella可以對應到 Typhoid fever 和 Salmonellosis，但較狹義的 Salmonella enterica Typhi 只能對應到 Typhoid fever。
Disease 也有一些較廣義的，能夠對應到多種 pathogen。
例如 Inflammatory gastroenteritis 可以對應到 Vibrio cholerae, Clostridium difficile, Listeria monocytogenes, Vibrio parahaemolyticus, Vibrio vulnificus ……. 等。/*但不能對應到 Campylobacter jejuni ，因為Campylobacteriosis是invasive。*/而較狹義的Cholera就只能對應到Vibrio cholerae。
