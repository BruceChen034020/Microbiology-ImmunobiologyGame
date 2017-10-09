# 微免牌
微免牌 遊戲規則介紹

# 遊戲目標
開局時即分成兩隊，紅隊和藍隊。玩家間大多彼此不互相知道對方屬於哪一隊，除了隊長之外。<br>
遊戲目標為利用 pathogen 殲滅所有敵對的人，殲滅成功者獲勝。<br>
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
例如 Inflammatory gastroenteritis 可以對應到 Vibrio cholerae, Clostridium difficile, Listeria monocytogenes, Vibrio parahaemolyticus, Vibrio vulnificus ……. 等。而較狹義的Cholera就只能對應到Vibrio cholerae。
# 以毒攻以毒攻毒(?)
若A攻擊B，B以一disease以毒攻毒A pathogen，但B disease 還可以對應到其他的 pathogen，而A也有那張牌，那麼A可以用其他pathogen以毒攻毒B disease， A就不會失血，而B會失一滴血。
例如A用 Bacteroides 攻擊B，B用Gingivitis以毒攻毒A，此時A可以再出Porphyromonas以毒攻毒Gingivitis，使B扣一滴血。如果B運氣夠好，可以再出Periodontitis以毒攻毒Porphyromonas，則B不會失血，而使A失一滴血。但若A再用Actinobacillus還擊，A就不會失血，而B會失一滴血。 
但要注意 pathogen 是和 disease 互相對應的，所以Streptococcus mutans不能夠以毒攻毒Streptococcus sobrinus，雖然他們都可以對應到 Dental caries。
# Immunity
若 A 以 pathogen 攻擊 B，則 A 為攻擊方，B 為防守方。
當防守方無法以毒攻毒時，就可以使用 immunity，並且可以請隊友幫忙。
防守方決定使用免疫後，從攻擊方右邊的那一個人開始逆時針輪流發動免疫反應。輪到自己發動時，可以選擇出一張 immunity card 或無視(pass)。
若過一輪回到攻擊方後免疫反應還是無法成功，防守方就會被扣一滴血。若成功，不會有人被扣血。
最後輪到攻擊方時，攻擊方也可以出一張 immunity，只是通常不會出而已。
Immunity 的出牌必須合乎常理。例如攻擊方使用 Haemophilus influenzae 時，可以出 Mucociliary clearance，但是不能出 Stomach acid，因為他不論感染 Throat, Ear 或 Lung，都不會經過胃。
又如攻擊方使用 Clostridium botulinum時，不能只出 Neutrophil，因為即使把菌體吞噬掉，他的 neurotoxin 還在。此時可以使用 IgG。
# 有效性
合理的免疫反應才能被發動，但是發動之後也不一定有效。
當某人出一張 immunity 的時候，他必須在抽牌區抽一張判定牌。每一張 immunity 上面都有寫此張牌判定生效的條件。例如 Lysozyme 上面寫 「3生效」就表示當判定牌為3時，lysozyme 殺菌成功，否則失敗。
若免疫反應無效，則繼續逆時針往下輪，直到某個免疫反應生效，或輪到攻擊方為止。
# 免疫的先後順序
若一個免疫反應無效，就表示在他之前的免疫反應都失效了。
例如某甲對 Yersinia enterocolitica 使用 Exfoliation of epithelia cells 失效，就表示細菌已經進入腸道了，才會需要用 exfoliation 排除，此時在某甲後面的某乙就不能使用 Salivary mucin，因為早就錯過了。但某乙可以使用 neutrophil 或啟動淋巴免疫反應。
又如某丙出了一張 Neutrophil 判定失效，就表示細菌已進入體內，在某丙後面的某丁就不能出 IgA。
# Helper dependent
某些 immunity card 必須被活化後才能參與免疫反應。本遊戲中需要被活化的牌有兩張：B cell, Killer T cell。
若某甲出了一張 B cell，在輪到攻擊方結束免疫挑戰(輪到攻擊方)之前必須有人出一張 Helper T cell 才能成功活化他，去抽判定牌。
本遊戲中視淋巴免疫為免疫反應的最後一道防線。若某甲出了一張 B cell，無論是否被活化，後面的人都不能夠再出其他任何非淋巴球的免疫牌。
Helper T cell 只能在出現需要活化的細胞後出，不能先出。
# Fair probability
為符合真實情況且增進遊戲公平，本遊戲設定 innate immunity 的有效機率均為 ¼ ，small lymphocyte immunity 的有效機率均為 ¾ ，其他 adaptive immunity 介於 2/4 ~ ¾ 之間。
# 改變 Media
任何玩家都可以在他的回合改面 media。
改變方式為:
出一張牌攻擊抽牌區，在抽牌區抽一張牌。若那張牌剛好以毒攻毒成功，就改變失敗，並且扣你一滴血。若那張牌是 immunity 且合理，則有效，改變失敗。
每個人在自己的回合只能攻擊一個人。所以你如果攻擊了抽牌區，無論改變成功與否，就不能夠再攻擊其他玩家。
# 性別一致
若女性玩家拿到 Prostate，他不能說因為她是女生所以不能被攻擊，她仍然會擁有prostate，而且可以被 Escherichia coli, Staphylococcus aureus, Proteus, Pseudomonas aeruginosa 等攻擊，因為本遊戲並沒有模擬性別的規則。
所以你在這個遊戲中有可能變成雙性人喔XD 不過不影響遊戲進行。
# List
欲知道總共有哪些牌，請參閱 微免排列表.xlsx
# 玩這個遊戲對課業有幫助嗎?
當然有的。依據遊戲發明者 Bruce Chen 的實測，在熟悉此遊戲的情況下可以答對微生物學課本中 40.0 % 的題目 (23 out of 59)
Chapter 10: 4 out of 12
Chapter 11: 7 out of 19
Chapter 12: 1 out of 10
Chapter 13: 11 out of 18
# 協作
If you want to change the rule of this game, and you think the change will make improvement to this game, please edit this file.

If you think some of the card in this game belongs to something(disease/pathogen) too rare for people to know, or if you see some components in this game irrelevant, you may deprecate that card by the following procedure:
1. Delete it from 微免排列表.xlsx
2. Add a parenthesis to the name of that card in 微免牌 disease - pathogen.md

If you want to add something to this game, be sure to edit these 3 files if necessary:
1. This file
2. 微免排列表.xlsx
3. 微免牌 disease - pathogen.md
