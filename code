import pynini
import csv
import string

with open("shupamem_nouns_corpus.tsv", 'w', encoding = 'utf8', newline = '') as tsv_file:
    tsv_writer = csv.writer(tsv_file, delimiter = '\t', lineterminator = '\n')
    tsv_writer.writerow(["IPA", "For parsing", "Tone", "POS", "Translation"])
    tsv_writer.writerow(["pɛ́n", "pHɛn", "H", "N;NOM;SG;NC5;PPSG1", "fufu"])
    tsv_writer.writerow(["pɛ̂n pɛ̀n", "pFɛn pLɛn", "FL", "N;NOM;PL;NC5;PPPL1", "fufus"])
    tsv_writer.writerow(["nʃá","nʃHa", "H", "N;NOM;SG;NC1b;PPSG1" , "fish"])
    tsv_writer.writerow(["pà nʃá", "pLa nʃHa", "LH", "N;NOM;PL;NC1b;PPPL1", "fishes"])
    tsv_writer.writerow(["pwɔ́", "pwHɔ", "H", "N;NOM;SG;NC3;PPSG1", "hand"])
    tsv_writer.writerow(["mbwɔ́", "mbwHɔ", "H", "N;NOM;PL;NC3;PPPL1", "hands"])
    tsv_writer.writerow(["lí", "lHi", "H", "N;NOM;SG;NC3;PPSG1", "eye"])
    tsv_writer.writerow(["mí", "mHi", "H", "N;NOM;PL;NC3;PPPL1", "eyes"])
    tsv_writer.writerow(["kjɛ́t", "kjHɛt", "H", "N;NOM;SG;NC3;PPSG1", "arrow"])
    tsv_writer.writerow(["ŋkjɛ́t", "ŋkjHɛt", "H", "N;NOM;PL;NC3;PPPL1", "arrows"])
    tsv_writer.writerow(["nsɛ́n", "nsHɛm", "H", "N;NOM;SG;NC5;PPSG1", "forest"])
    tsv_writer.writerow(["nsɛ̂n nsɛ̀n", "nsFɛm nsLɛm", "FL", "N;NOM;PL;NC5;PPPL1", "forests"])
    tsv_writer.writerow(["nsə́m", "nsHəm", "H", "N;NOM;SG;NC5;PPSG1", "farm"])
    tsv_writer.writerow(["nsə̂m nsə̀m", "nsFəm nsLəm", "FL", "N;NOM;PL;NC5;PPPL1", "farms"])
    tsv_writer.writerow(["ntɛ́n", "ntHɛn", "H", "N;NOM;SG;NC5;PPSG1", "market"])
    tsv_writer.writerow(["ntɛ̂n ntɛ̀n", "ntFɛn ntLɛn", "FL", "N;NOM;PL;NC5;PPPL1", "markets"])
    tsv_writer.writerow(["ɣám", "ɣHam", "H", "N;NOM;SG;NC5;PPSG1", "baobab"])
    tsv_writer.writerow(["ɣâm ɣàm", "ɣFam ɣLam", "FL", "N;NOM;PL;NC5;PPPL1", "baobabs"])
    tsv_writer.writerow(["tám", "tHam", "H", "N;NOM;SG;NC5;PPSG1", "hole"])
    tsv_writer.writerow(["tâm tàm", "tFam tLam", "FL", "N;NOM;PL;NC5;PPPL1", "holes"])
    tsv_writer.writerow(["nʒə́m", "nʒHəm", "H", "N;NOM;SG;NC5;PPSG1", "obscurity"])
    tsv_writer.writerow(["nʒə̂m nʒə̀m", "nʒFəm nʒLəm", "FL", "N;NOM;PL;NC5;PPPL1", "obscurities"])
    tsv_writer.writerow(["ŋgwə́n","ŋgwHən", "H", "N;NOM;SG;NC5;PPSG1", "village" ])
    tsv_writer.writerow(["ŋgwə̂n ŋgwə̀n","ŋgwFən ŋgwLən", "FL", "N;NOM;PL;NC5;PPPL1", "villages" ])
    tsv_writer.writerow(["nsám", "nsHam", "H", "N;NOM;SG;NC5;PPSG1", "trench"])
    tsv_writer.writerow(["nsâm nsàm", "nsFam nsLam", "FL", "N;NOM;PL;NC5;PPPL1", "trenches"])
    tsv_writer.writerow(["mɘ̀.tɔ́ʔ", "mLə.tHɔʔ", "LH", "N;NOM;SG;NC1;PPSG1", "can"])
    tsv_writer.writerow(["pə̂.tɔ̀ʔ", "pFə.tLɔʔ", "FL", "N;NOM;PL;NC1;PPPL1", "cans"])
    tsv_writer.writerow(["mɘ̀.mví", "mLə.mvHi", "LH", "N;NOM;SG;NC1;PPSG1", "goat"])
    tsv_writer.writerow(["pə̂.mvì", "pFə.mvLi", "FL", "N;NOM;PL;NC1;PPPL1", "goats"])
    tsv_writer.writerow(["mɘ̀.mvɨ́", "mLə.mvHɨ", "LH", "N;NOM;SG;NC1;PPSG1", "dog"])
    tsv_writer.writerow(["pə̂.mvɨ̀", "pFə.mvLɨ", "FL", "N;NOM;PL;NC1;PPPL1", "dogs"])
    tsv_writer.writerow(["mə́.ní", "mHə.nHi", "HH", "N;NOM;SG;NC1;PPSG1", "knife"])
    tsv_writer.writerow(["pə̂.nì", "pFə.nLi", "FL", "N;NOM;PL;NC1;PPPL1", "knives"])
    tsv_writer.writerow(["mə́.sí", "mHə.sHi", "HH", "N;NOM;SG;NC1;PPSG1", "bird"])
    tsv_writer.writerow(["pə̂.sì", "pFə.sLi", "FL", "N;NOM;PL;NC1;PPPL1", "birds"])
    tsv_writer.writerow(["mɔ́n", "mHɔn", "H", "N;NOM;SG;NC1;PPSG2", "child"])
    tsv_writer.writerow(["pɔ́n", "pHɔn", "H", "N;NOM;PL;NC1;PPPL1", "children"])
    tsv_writer.writerow(["nsún", "nsHun", "H", "N;NOM;SG;NC1a;PPSG2", "friend"])
    tsv_writer.writerow(["sún", "sHun", "H", "N;NOM;PL;NC1a;PPPL1", "friends"])
    tsv_writer.writerow(["ndàp", "ndLap", "L", "N;NOM;SG;NC5a;PPSG2", "thread"])
    tsv_writer.writerow(["ndǎp ndàp", "ndRap ndLap", "RL", "N;NOM;PL;NC5a;PPPL2", "threads"])
    tsv_writer.writerow(["pùm", "pLum", "L", "N;NOM;SG;NC3;PPSG2", "egg"])
    tsv_writer.writerow(["mbùm", "mbLum", "L", "N;NOM;PL;NC3;PPPL2", "eggs"])
    tsv_writer.writerow(["ntàp", "ntLap", "L", "N;NOM;SG;NC5a;PPSG2", "tent"])
    tsv_writer.writerow(["ntǎp ntàp", "ntRap ntLap", "RL", "N;NOM;PL;NC5a;PPPL2", "tents"])
    tsv_writer.writerow(["kàm", "kLam", "L", "N;NOM;SG;NC5a;PPSG2", "game"])
    tsv_writer.writerow(["kǎm kàm", "kRam kLam", "RL", "N;NOM;PL;NC5a;PPPL2", "games"])
    tsv_writer.writerow(["mə̀n.ʒɛ̀t", "mLən.ʒLɛt", "LL", "N;NOM;SG;NC1;PPSG2", "newphew"])
    tsv_writer.writerow(["pə̂n.ʒɛ̀t", "pFən.ʒLɛt", "FL", "N;NOM;PL;NC1;PPPL2", "newphews"])
    tsv_writer.writerow(["kɨ̀.pɛ̀n", "kLɨ.pLɛn", "LL", "N;NOM;SG;NC7;PPSG2", "hatred"])
    tsv_writer.writerow(["kɨ̌.pɛ̀n", "kRɨ.pLɛn", "RL", "N;NOM;PL;NC7;PPPL2", "hatreds"])
    tsv_writer.writerow(["pə̀.rɛ̀n", "pLə.rLɛn", "LL", "N;NOM;SG;NC7;PPSG2", "sheet"])
    tsv_writer.writerow(["pə̌.rɛ̀n", "pRə.rLɛn", "RL", "N;NOM;PL;NC7;PPPL2", "sheets"])
    tsv_writer.writerow(["nsà.sɨ̀", "nsLa.sLɨ", "LL", "N;NOM;SG;NC1a;PPSG2", "older sibling"])
    tsv_writer.writerow(["nsǎ.sɨ̀", "nsRa.sLɨ", "RL", "N;NOM;PL;NC1a;PPPL2", "older siblings"])
    tsv_writer.writerow(["mà.pàm", "mLa.pLam", "LL", "N;NOM;SG;NC7;PPSG2", "coat"])
    tsv_writer.writerow(["mǎ.pàm", "mRa.pLam", "RL", "N;NOM;PL;NC7;PPPL2", "coats"])
    tsv_writer.writerow(["kù", "kLu", "L", "N;NOM;SG;NC3;PPSG3", "spear"])
    tsv_writer.writerow(["ŋkù", "ŋkLu", "L", "N;NOM;PL;NC3;PPPL2", "spears"])
    tsv_writer.writerow(["kà", "kLa", "L", "N;NOM;SG;NC5a;PPSG3", "onion"])
    tsv_writer.writerow(["kǎ kà", "kRa kLa", "RL", "N;NOM;PL;NC5a;PPPL2", "onions"])
    tsv_writer.writerow(["là", "lLa", "L", "N;NOM;SG;NC5a;PPSG3", "trap"])
    tsv_writer.writerow(["lǎ là", "lRa lLa", "RL", "N;NOM;PL;NC5a;PPPL2", "traps"])
    tsv_writer.writerow(["tà", "tLa", "L", "N;NOM;SG;NC1a;PPSG3", "insect"])
    tsv_writer.writerow(["pà tà", "pLa tLa", "LL", "N;NOM;PL;NC1a;PPPL2", "insects"])
    tsv_writer.writerow(["ŋkù.mbà", "ŋkLu.mbLa", "LL", "N;NOM;SG;NC7;PPSG3", "cane"])
    tsv_writer.writerow(["ŋkǔ.mbà", "ŋkRu.mbLa", "RL", "N;NOM;PL;NC7;PPPL2", "canes"])
    tsv_writer.writerow(["ndà.pàʔ", "ndLa.pLaʔ", "LL", "N;NOM;SG;NC11;PPSG3", "cigarette"])
    tsv_writer.writerow(["ndǎ.pàʔ", "ndRa.pLaʔ", "RL", "N;NOM;PL;NC11;PPPL2", "cigarettes"])
    tsv_writer.writerow(["mfè.ʃə̀", "mfLe.ʃLə", "LL", "N;NOM;SG;NC7;PPSG3", "needle"])
    tsv_writer.writerow(["mfě.ʃə̀", "mfRe.ʃLə", "RL", "N;NOM;PL;NC7;PPPL2", "needles"])
    tsv_writer.writerow(["sà.sɛ̀.rè", "sLa.sLɛ.rLe", "LLL", "N;NOM;SG;NC9;PPSG3", "Eurpean mantis"])
    tsv_writer.writerow(["sǎ.sɛ́.rè", "sRa.sHɛ.rLe", "RHL", "N;NOM;PL;NC9;PPPL2", "Eurpean mantises"])
    tsv_writer.writerow(["mà.lɔ̀.rì", "mLa.lLɔ.rLi", "LLL", "N;NOM;SG;NC9;PPSG3", "rice"])
    tsv_writer.writerow(["mǎ.lɔ́.rì", "mRa.lHɔ.rLi", "RHL", "N;NOM;PL;NC9;PPPL2", "rices"])
    tsv_writer.writerow(["ʃɛ̀.kɛ̀.rɛ̀" ,"ʃLɛ.kLɛ.rLɛ", "LLL", "N;NOM;SG;NC9;PPSG3", "shaker"])
    tsv_writer.writerow(["ʃɛ̌.kɛ́.rɛ̀" ,"ʃRɛ.kHɛ.rLɛ", "RHL", "N;NOM;PL;NC9;PPPL2", "shakers"])
    tsv_writer.writerow(["mà.kà.βà", "mLa.kLa.βLa", "LLL", "N;NOM;SG;NC9;PPSG3", "yam"])
    tsv_writer.writerow(["mǎ.ká.βà", "mRa.kHa.βLa", "RHL", "N;NOM;PL;NC9;PPPL2", "yams"])
    tsv_writer.writerow(["kùt", "kLut", "Lc", "N;NOM;SG;NC3;PPSG3", "leg"])
    tsv_writer.writerow(["ŋkǔt", "ŋkRut", "R", "N;NOM;PL;NC3;PPPL2", "legs"])
    tsv_writer.writerow(["tɨ̀t", "tLɨt", "Lc", "N;NOM;SG;NC3;PPSG3", "ear"])
    tsv_writer.writerow(["ntɨ̌t", "ntRɨt", "R", "N;NOM;PL;NC3;PPPL2", "ears"])
    tsv_writer.writerow(["pɛ̀", "pLɛ", "Lc", "N;NOM;SG;NC3;PPSG3", "thigh"])
    tsv_writer.writerow(["mbɛ̌", "mbRɛ", "R", "N;NOM;PL;NC3;PPSG3", "thighs"])
    tsv_writer.writerow(["wúp.mà", "wHup.mLa", "HL", "N;NOM;NC11;PPSG3", "thought"])
    tsv_writer.writerow(["mɨ́.mʃə̀", "mHɨ.mʃLə", "HL", "N;NOM;NC11;PPSG3", "patience"])
    tsv_writer.writerow(["sáp.mà", "sHap.mLa", "HL", "N;NOM;NC11;PPSG3", "anger"])
    tsv_writer.writerow(["mbà.mbɨ́.lɛ̀", "mbLa.mbHɨ.lLɛ", "LHL", "N;NOM;SG;NC11;PPSG3", "potato"])
    tsv_writer.writerow(["mbǎ.mbɨ́.lɛ̀", "mbRa.mbHɨ.lLɛ", "RHL", "N;NOM;PL;NC11;PPPL2", "potatoes"])
    tsv_writer.writerow(["là.mí.ndà", "lLa.mHi.ndLa", "LHL", "N;NOM;NC11;PPSG3", "parfume"])
    tsv_writer.writerow(["ká.mín.dà", "kHa.mHin.dLa", "HHL", "N;NOM;SG;NC1b;PPSG3", "carpenter"])
    tsv_writer.writerow(["pà ká.mín.dà", "pLa kHa.mHin.dLa", "LHHL", "N;NOM;PL;NC1b;PPPL2", "carpenters"])
    tsv_writer.writerow(["má.ʃɨ́.ndʒà", "mHa.ʃHɨ.ndʒLa", "HHL", "N;NOM;SG;NC1b;PPSG3", "messenger"])
    tsv_writer.writerow(["pà má.ʃɨ́.ndʒà", "pLa mHa.ʃHɨ.ndʒLa", "LHHL", "N;NOM;PL;NC1b;PPPL2", "messengers"])
    tsv_writer.writerow(["gà.tɔ̂", "gLa.tFɔ", "LF", "N;NOM;SG;NC7a;PPSG3", "cake"])
    tsv_writer.writerow(["gǎ.tɔ̂", "gRa.tFɔ", "RF", "N;NOM;PL;NC7a;PPPL2", "cakes"])
    tsv_writer.writerow(["kà.kâ", "kLa.kFa", "LF", "N;NOM;SG;NC7a;PPSG3", "cocoa"])
    tsv_writer.writerow(["kǎ.kâ", "kRa.kFa", "RF", "N;NOM;PL;NC7a;PPPL2", "cocoas"])
    tsv_writer.writerow(["mà.twâ", "mLa.twFa", "LF", "N;NOM;SG;NC7a;PPSG3", "car"])
    tsv_writer.writerow(["mǎ.twâ", "mRa.twFa", "RF", "N;NOM;PL;NC7a;PPPL2", "cars"])
    tsv_writer.writerow(["wǎ","wRa", "R", "N;NOM;SG;NC1b;PPSG3", "father"])
    tsv_writer.writerow(["pà wǎ","pLa wRa", "LR", "N;NOM;PL;NC1b;PPPL2", "fathers"])
    tsv_writer.writerow(["nǎ", "nRa", "R", "N;NOM;SG;NC1b;PPSG3", "mother"])
    tsv_writer.writerow(["pà nǎ", "pLa nRa", "LR", "N;NOM;PL;NC1b;PPPL2", "mothers"])
    tsv_writer.writerow(["tǔ", "tRu", "R", "N;NOM;NC1b;PPSG3", "navel"])
    tsv_writer.writerow(["sá", "sHa", "H", "N;NOM;SG;NC5;PPSG3", "fly trap"])
    tsv_writer.writerow(["sâ sà", "sFa sLa", "FL", "N;NOM;PL;NC5;PPPL1", "fly traps"])
    tsv_writer.writerow(["pá", "pHa", "H", "N;NOM;SG;NC5;PPSG3", "path"])
    tsv_writer.writerow(["pâ pà", "pFa pLa", "FL", "N;NOM;PL;NC5;PPPL1", "paths"])
    tsv_writer.writerow(["mú", "mHu", "H", "N;NOM;SG;NC5;PPSG3", "fire"])
    tsv_writer.writerow(["mû mù", "mFu mLu", "FL", "N;NOM;PL;NC5;PPPL1", "fires"])
    tsv_writer.writerow(["lɔ́n", "lHɔn", "H", "N;NOM;SG;NC1b;PPSG3", "pants (SG)"])
    tsv_writer.writerow(["pà lɔ́n", "pLa lHɔn", "LH", "N;NOM;PL;NC1b;PPSG3", "pants (PL)"])
    tsv_writer.writerow(["kám", "kHam", "H", "N;NOM;SG;NC5;PPSG3", "crab"])
    tsv_writer.writerow(["kâm kàm", "kFam kLam", "FL", "N;NOM;PL;NC5;PPPL1", "crabs"])
    tsv_writer.writerow(["kún", "kHun", "H", "N;NOM;SG;NC5;PPSG3", "bed"])
    tsv_writer.writerow(["kûn kùn", "kFun kLun", "FL", "N;NOM;PL;NC5;PPPL1", "beds"])
    tsv_writer.writerow(["lá.páʔ", "lHa.pHaʔ", "HH", "N;NOM;NC11;PPSG3", "shoe" ])
    tsv_writer.writerow(["tá.sá", "tHa.sHa", "HH", "N;NOM;NC11;PPSG3", "plate"])
    tsv_writer.writerow(["pá.rɨ́", "pHa.rHɨ", "HH", "N;NOM;NC11;PPSG3", "craziness"])
    tsv_writer.writerow(["á", "0a", "0", "PN;GEN;1SG;PPSG1", "my"])
    tsv_writer.writerow(["ú", "0u", "0", "PN;GEN;3SG;PPSG1", "your"])
    tsv_writer.writerow(["í", "0i", "0", "PN;GEN;3SG;PPSG1", "his/her"])
    tsv_writer.writerow(["ú.pwà", "Hu.pwLa", "HL", "PN;GEN;1PL.INCL;PPSG1", "our"])
    tsv_writer.writerow(["ý", "0y", "0", "PN;GEN;1PL.EXCL;PPSG1", "our"])
    tsv_writer.writerow(["ú.t̀a", "Hu.tLa", "HL", "PN;GEN;1PL.DUAL;PPSG1", "our"])
    tsv_writer.writerow(["ɨ́n", "0ɨn", "0", "PN;GEN;2PL;PPSG1", "your"])
    tsv_writer.writerow(["áp", "0ap", "0", "PN;GEN;3PL;PPSG1", "their"])
    tsv_writer.writerow(["á", "La", "L", "PN;GEN;1SG;PPSG2", "my"])
    tsv_writer.writerow(["ú", "Lu", "L", "PN;GEN;3SG;PPSG2", "your"])
    tsv_writer.writerow(["í", "Li", "L", "PN;GEN;3SG;PPSG2", "his/her"])
    tsv_writer.writerow(["ú.pwà", "Hu.pwLa", "HL", "PN;GEN;1PL.INCL;PPSG2", "our"])
    tsv_writer.writerow(["ý", "Ly", "L", "PN;GEN;1PL.EXCL;PPSG2", "our"])
    tsv_writer.writerow(["ú.t̀a", "Hu.tLa", "HL", "PN;GEN;1PL.DUAL;PPSG2", "our"])
    tsv_writer.writerow(["ɨ́n", "Lɨn", "L", "PN;GEN;2PL;PPSG2", "your"])
    tsv_writer.writerow(["áp", "Lap", "L", "PN;GEN;3PL;PPSG2", "their"])
    tsv_writer.writerow(["á", "Ha", "H", "PN;GEN;1SG;PPSG3", "my"])
    tsv_writer.writerow(["ú", "Hu", "H", "PN;GEN;3SG;PPSG3", "your"])
    tsv_writer.writerow(["í", "Hi", "H", "PN;GEN;3SG;PPSG3", "his/her"])
    tsv_writer.writerow(["ú.pwà", "Hu.pwLa", "HL", "PN;GEN;1PL.INCL;PPSG3", "our"])
    tsv_writer.writerow(["ý", "Hy", "H", "PN;GEN;1PL.EXCL;PPSG3", "our"])
    tsv_writer.writerow(["ú.t̀a", "Hu.tLa", "HL", "PN;GEN;1PL.DUAL;PPSG3", "our"])
    tsv_writer.writerow(["ɨ́n", "Hɨn", "H", "PN;GEN;2PL;PPSG3", "your"])
    tsv_writer.writerow(["áp", "Hap", "H", "PN;GEN;3PL;PPSG3", "their"])
    tsv_writer.writerow(["á", "Ha", "H", "PN;GEN;1SG;PPPL", "my"])
    tsv_writer.writerow(["ú", "Hu", "H", "PN;GEN;3SG;PPPL", "your"])
    tsv_writer.writerow(["í", "Hi", "H", "PN;GEN;3SG;PPPL", "his/her"])
    tsv_writer.writerow(["ú.pwà", "Hu.pwLa", "HL", "PN;GEN;1PL.INCL;PPPL", "our"])
    tsv_writer.writerow(["ý", "Hy", "H", "PN;GEN;1PL.EXCL;PPPL", "our"])
    tsv_writer.writerow(["ú.t̀a", "Hu.tLa", "HL", "PN;GEN;1PL.DUAL;PPPL", "our"])
    tsv_writer.writerow(["ɨ́n", "Hɨn", "H", "PN;GEN;2PL;PPPL", "your"])
    tsv_writer.writerow(["áp", "Hap", "H", "PN;GEN;3PL;PPPL", "their"])
    
with open("shupamem_nouns_corpus.tsv") as tsv_file:
    corpus = csv.reader(tsv_file, delimiter='\t')
    # the lists below contain tuples of 2nd, 3rd and 4th column of the corpus data; nouns and pronouns are together
    # in an appropriate group
    group1 = []
    group2 = []
    group3 = []
    
    for ipa, word, tone, pos, trans in corpus:
        if not "N;NOM;PL" in pos:
            if pos[-1].endswith("3"):
                pair = word, tone, pos
                group3.append(pair)
            if pos[-1].endswith("2"):
                pair = word, tone, pos
                group2.append(pair)
            if pos[-1].endswith("1"):
                pair = word, tone, pos
                group1.append(pair)
     
nouns_group1 = []
pronouns_group1 = []

for item in group1:
    word = item[0]
    tone = item[1]
    tag = item[2]
    if tag.startswith("PN"):
        #since the tag info won't be useful anymore for pronouns I'm getting rid of it. Now each tuple contains 
        # the simplified version of a pronouns with its UR tones and just tones
        phrase = word, tone
        pronouns_group1.append(phrase)
    else:
        # for nouns I would need at one point tag info, therefore it stays put
        nouns_group1.append(item)
        
nouns_group2 = []
pronouns_group2 = []

for item in group2:
    word = item[0]
    tone = item[1]
    tag = item[2]
    if tag.startswith("PN"):
        phrase = word, tone
        pronouns_group2.append(phrase)
    else:
        nouns_group2.append(item)
        
nouns_group3 = []
pronouns_group3 = []

for item in group3:
    word = item[0]
    tone = item[1]
    tag = item[2]
    if tag.startswith("PN"):
        # I'm appending only pronoun without a tag 
        phrase = word, tone
        pronouns_group3.append(phrase)
    else:
        # In later analysis, we need noun and its tag, therefore I'm appending 'whole item'
        nouns_group3.append(item)
        
def nouns1_UR(group):
    """returns a tuple: the first item is a noun with its surface form and the second solely tone in the UR"""
    
    UR_tones = []
    sigma_star = pynini.union(*string.ascii_lowercase, "L", "H", ".", "ə", "ɔ", "ɛ", "ɨ", "I", "β", "ŋ", "ʃ",
                          "ʒ", "ɣ", "ʔ", "~", "0", "|", "F", "R").optimize().closure()
    # unattaching H tone where needed
    floatH = pynini.transducer("H", "~H")
    
    for item in group:
        noun = item[0]
        tone = item[1]
        pos_tag = item[2]
        
        if tone == "HH":
            floatingH = pynini.cdrewrite(floatH, "H", "", sigma_star).optimize()
            tone = (tone @ floatingH).stringify()
            phrase = noun, tone
            UR_tones.append(phrase)
        if (tone == "LH" or tone == "H"):
            floatingH = pynini.cdrewrite(floatH, "", "", sigma_star).optimize()
            tone = (tone @ floatingH).stringify()
            phrase = noun, tone
            UR_tones.append(phrase)
    return UR_tones
    
# saving the output of the function under "UR_nouns_group1" variable, which is a list of tuples.
UR_nouns_group1 = nouns1_UR(nouns_group1)

def nouns2_UR(group):
    """returns a tuple: the first item is a noun with its surface form and the second solely tone in the UR"""
    UR_tones = []
    sigma_star = pynini.union(*string.ascii_lowercase, "L", "H", ".", "ə", "ɔ", "ɛ", "ɨ", "I", "β", "ŋ", "ʃ",
                          "ʒ", "ɣ", "ʔ", "~", "0", "|", "F", "R").optimize().closure()
    #unattaching H tone
    floatH = pynini.transducer("H", "~H")
    #multiple linked L tone. "|" indicates multiple linking to the first tone on the right
    multiple_linkL = pynini.transducer("L", "|")
    
    for item in group:
        noun = item[0]
        tone = item[1]
        pos_tag = item[2]
        if tone == "H":
            if "NC1" and not ("NC1a" or "NC1b") in pos_tag:
                floatingH = pynini.cdrewrite(floatH, "", "", sigma_star).optimize()
                tone = (tone @ floatingH).stringify()
                phrase = noun, tone
                UR_tones.append(phrase)
            else:
                phrase = noun, tone
                UR_tones.append(phrase)
        if tone == "LL":
            multiple_linkingL = pynini.cdrewrite(multiple_linkL, "", "L", sigma_star).optimize()
            tone = (tone @ multiple_linkingL).stringify()
            phrase = noun, tone
            UR_tones.append(phrase)
        if tone == "L":
            phrase = noun, tone
            UR_tones.append(phrase)
    return UR_tones
    
UR_nouns_group2 = nouns2_UR(nouns_group2)

def nouns3_UR(group):
    """returns a tuple: the first item is a noun with its surface form and the second solely tone in the UR"""
    UR_tones = []
    sigma_star = pynini.union(*string.ascii_lowercase, "L", "H", ".", "ə", "ɔ", "ɛ", "ɨ", "I", "β", "ŋ", "ʃ",
                          "ʒ", "ɣ", "ʔ", "~", "0", "|", "F", "R").optimize().closure()
    # mulitple linked L tone
    multiple_linkL = pynini.transducer("L", "|")
    # multiple linked H tone
    multiple_linkH = pynini.transducer("H", "|")
    # L tone in the UR only in certain tonal combinations
    no_L = pynini.transducer("L", "0")
    
    for item in group:
        noun = item[0]
        tone = item[1]
        pos_tag = item[2]
        if "HH" in tone:
            multiple_linkingH = pynini.cdrewrite(multiple_linkH, "", "H", sigma_star)
            no_L_rule = pynini.cdrewrite(no_L, "", "", sigma_star)
            tone = (tone @ multiple_linkingH @ no_L_rule).stringify()
            phrase = noun, tone
            UR_tones.append(phrase)
        elif (tone == "L" or tone == "LL" or tone == "LLL" or tone == "Lc"):
            multiple_linkingL = pynini.cdrewrite(multiple_linkL, "", "L", sigma_star)
            tone = (tone @ multiple_linkingL).stringify()
            phrase = noun, tone
            UR_tones.append(phrase)     
        else:
            no_L_rule = pynini.cdrewrite(no_L, "", "", sigma_star)
            tone = (tone @ no_L_rule).stringify()
            phrase = noun, tone
            UR_tones.append(phrase)            
    return UR_tones
    
UR_nouns_group3 = nouns3_UR(nouns_group3)

def poss_group1(UR_noun, UR_pronoun):
    """returns a lits of tuples with a noun(lexical tone) + pronoun(UR tone) and the tones after the derivation"""
    vowels = ["a", "ə", "ɔ", "o", "ɛ", "e", "ɨ", "i", "u"]
    noun = UR_noun[0]
    Tnoun = UR_noun[1]
    pronoun = UR_pronoun[0]
    Tpronoun = UR_pronoun[1]
    sigma_star = pynini.union(*string.ascii_lowercase, "L", "H", ".", "ə", "ɔ", "ɛ", "ɨ", "I", "β", "ŋ", "ʃ",
                          "ʒ", "ɣ", "ʔ", "~", "0", "|", "F", "R", "+").optimize().closure()
    # The spreading rule (Rightward H-Spreading) in my paper, needs to be divided into 2 parts using FSTs. 
    # 1. spreading the floating H from the noun onto possessive pronoun, so bascically changing "0" - no tone
    # to "H"
    spread1 = pynini.transducer("0", "H")
    # 2. we need to make sure that noun in now toneless, therefore, the floating H needs to turn into no tone "0"
    spread2 = pynini.transducer("~H", "0")
    # postlexical rule (L-default Insertion) replaces "0" with "L", which in "real life" gives L tone to a toneless
    # syllable
    insertL = pynini.transducer("0", "L")
    phrase = noun + "+" + pronoun
    tones = Tnoun + "+" + Tpronoun
    spreading1 = pynini.cdrewrite(spread1, "", "", sigma_star).optimize()
    spreading2 = pynini.cdrewrite(spread2, "", "", sigma_star).optimize()
    L_inserting = pynini.cdrewrite(insertL, "", "", sigma_star).optimize()
    SR_tones = (tones @ spreading1 @ spreading2 @ L_inserting).stringify()
    result = phrase, SR_tones
    return result
    
list1 = []

for noun in range(len(UR_nouns_group1)):
    list1.append(poss_group1(UR_nouns_group1[noun], pronouns_group1[1]))
    
def poss_group2(UR_noun, UR_pronoun):
    """returns a lits of tuples with a noun(lexical tone) + pronoun(UR tone) and the tones after the derivation"""
    vowels = ["a", "ə", "ɔ", "o", "ɛ", "e", "ɨ", "i", "u"]
    noun = UR_noun[0]
    Tnoun = UR_noun[1]
    pronoun = UR_pronoun[0]
    Tpronoun = UR_pronoun[1]
    phrase = noun + "+" + pronoun
    tones = Tnoun + "+" + Tpronoun 
    sigma_star = pynini.union(*string.ascii_lowercase, "L", "H", ".", "ə", "ɔ", "ɛ", "ɨ", "I", "β", "ŋ", "ʃ",
                          "ʒ", "ɣ", "ʔ", "~", "0", "|", "F", "R", "+").optimize().closure()
    # floating H is linked with TBU
    attach = pynini.transducer("~H", "H")
    UAC = pynini.cdrewrite(attach, "", "", sigma_star).optimize()
    return phrase, (tones @ UAC).stringify()
    
list2 = []

for noun in range(len(UR_nouns_group2)):
    list2.append(poss_group2(UR_nouns_group2[noun], pronouns_group2[1]))
    
def poss_group3(UR_noun, UR_pronoun):
    """returns a lits of tuples with a noun(lexical tone) + pronoun(UR tone) and the tones after the derivation"""
    vowels = ["a", "ə", "ɔ", "o", "ɛ", "e", "ɨ", "i", "u"]
    noun = UR_noun[0]
    Tnoun = UR_noun[1]
    pronoun = UR_pronoun[0]
    Tpronoun = UR_pronoun[1]
    # possessive structure
    phrase = noun + "+" + pronoun
    # tones on possessive structure
    tones = Tnoun + "+" + Tpronoun 
    sigma_star = pynini.union(*string.ascii_lowercase, "L", "H", ".", "ə", "ɔ", "ɛ", "ɨ", "I", "β", "ŋ", "ʃ",
                          "ʒ", "ɣ", "ʔ", "~", "0", "|", "C", "R", "F", "+").optimize().closure()
    # Special H-spreading is special because it goes leftwards, it is blocked by closed syllables, and it can 
    # spread onto multiple linked structures (attaching H to the its closest link on the left). Computationally,
    # it needs to be broken into 2 rules:
    # 1. replacing final L tone with "L|" where "|" means that there is multiply linking to the first tone 
    # on the right (in this case the H on the pronoun)
    H_spread1 = pynini.transducer("L", "L|")
    H_spread2 = pynini.transducer("0", "H")
    L_insert = pynini.transducer("0", "L")
    # after spreading was done, we don't need to mark up codas any more. It's done solely for the esthetic reasons.
    coda_del = pynini.transducer("c", "")
    
    if Tnoun.endswith("L"):
        phrase = noun + "+" + pronoun
        tones = Tnoun + "+" + Tpronoun
        H_spreading1 = pynini.cdrewrite(H_spread1, "", "", sigma_star)
        SR_tones = (tones @ H_spreading1).stringify()
        result = phrase, SR_tones
    elif "0" in Tnoun:
        phrase = noun + "+" + pronoun
        tones = Tnoun + "+" + Tpronoun
        H_spreading2 = pynini.cdrewrite(H_spread2, "", "+", sigma_star)
        L_inserting = pynini.cdrewrite(L_insert, "", "", sigma_star)
        SR_tones = (tones @ H_spreading2 @ L_inserting).stringify()
        result = phrase, SR_tones
    # the "c" markes coda in a final syllable
    elif Tnoun.endswith("c"):
        phrase = noun + "+" + pronoun
        tones = Tnoun + "+" + Tpronoun
        coda_deleting = pynini.cdrewrite(coda_del, "", "", sigma_star)
        SR_tones = (tones @ coda_deleting).stringify()
        result = phrase, SR_tones
    else:
        result = phrase, tones    
    return result
    
list3 = []

for noun in range(len(UR_nouns_group3)):
    list3.append(poss_group3(UR_nouns_group3[noun], pronouns_group3[1]))
    
with open("shupamem_nouns_corpus.tsv") as tsv_file:
    corpus = csv.reader(tsv_file, delimiter='\t')
    nouns_group1_PL = []
    nouns_group2_PL = []
    pronouns_PL = []
    
    for ipa, word, tone, pos, trans in corpus:
        if not "N;NOM;SG" in pos:
            if not "PN" in pos:
                if pos[-1].endswith("2"):
                    pair = word, tone, pos
                    nouns_group2_PL.append(pair)
                if pos[-1].endswith("1"):
                    pair = word, tone, pos
                    nouns_group1_PL.append(pair)
        if "PPPL" in pos:
            if "PN" in pos:
                phrase = word, tone
                pronouns_PL.append(phrase)
                
def nouns1_UR_PL(group):
    """returns a tuple: the first item is a noun with its surface form and the second solely tone in the UR"""
    UR_tones = []
    sigma_star = pynini.union(*string.ascii_lowercase, "L", "H", ".", "ə", "ɔ", "ɛ", "ɨ", "I", "β", "ŋ", "ʃ",
                          "ʒ", "ɣ", "ʔ", "~", "0", "|", "F", "R").optimize().closure()
    floatH = pynini.transducer("H", "~H")
    no_L = pynini.transducer("L", "0")
    
    for item in group:
        noun = item[0]
        tone = item[1]
        pos_tag = item[2]     
        if "H" in tone: 
            if "NC1" and not ("NC1a" or "NC1b") in pos_tag:
                floatingH = pynini.cdrewrite(floatH, "", "", sigma_star).optimize()
                tone = (tone @ floatingH).stringify()
                phrase = noun, tone
                UR_tones.append(phrase)
            else:
                phrase = noun, tone
                UR_tones.append(phrase)
        else:
            no_L_rule = pynini.cdrewrite(no_L, "", "", sigma_star).optimize()
            tone = (tone @ no_L_rule).stringify()
            phrase = noun, tone
            UR_tones.append(phrase)
    
    return UR_tones
    
UR_nouns_group1_PL = nouns1_UR_PL(nouns_group1_PL)

def poss_group1_PL(UR_noun, UR_pronoun):
    """returns a lits of tuples with a noun(lexical tone) + pronoun(UR tone) and the tones after the derivation"""
    vowels = ["a", "ə", "ɔ", "o", "ɛ", "e", "ɨ", "i", "u"]
    noun = UR_noun[0]
    Tnoun = UR_noun[1]
    pronoun = UR_pronoun[0]
    Tpronoun = UR_pronoun[1]
    sigma_star = pynini.union(*string.ascii_lowercase, "L", "H", ".", "ə", "ɔ", "ɛ", "ɨ", "I", "β", "ŋ", "ʃ",
                          "ʒ", "ɣ", "ʔ", "~", "0", "|", "F", "R", "+").optimize().closure()
    fusion = pynini.transducer("~H", "0")
    insertL = pynini.transducer("0", "L")
    phrase = noun + "+" + pronoun
    tones = Tnoun + "+" + Tpronoun
    fusing = pynini.cdrewrite(fusion, "", "+H", sigma_star).optimize()
    L_inserting = pynini.cdrewrite(insertL, "", "", sigma_star).optimize()
    SR_tones = (tones @ fusing @ L_inserting).stringify()
    result = phrase, SR_tones
    
    return result
    
list1_PL = []

for noun in range(len(UR_nouns_group1_PL)):
    list1_PL.append(poss_group1_PL(UR_nouns_group1_PL[noun], pronouns_PL[1]))
    
def nouns2_UR_PL(group):
    """returns a tuple: the first item is a noun with its surface form and the second solely tone in the UR"""
    UR_tones = []
    sigma_star = pynini.union(*string.ascii_lowercase, "L", "H", ".", "ə", "ɔ", "ɛ", "ɨ", "I", "β", "ŋ", "ʃ",
                          "ʒ", "ɣ", "ʔ", "~", "0", "|", "F", "R").optimize().closure()
    floatH = pynini.transducer("H", "~H")
    no_L = pynini.transducer("L", "0")
    multiple_linkL = pynini.transducer("L", "|")
    multiple_linkH = pynini.transducer("H", "|")
    
    
    for item in group:
        noun = item[0]
        tone = item[1]
        pos_tag = item[2]  
        if "RL" in tone: 
            no_L_rule = pynini.cdrewrite(no_L, "", "", sigma_star).optimize()
            tone = (tone @ no_L_rule).stringify()
            phrase = noun, tone
            UR_tones.append(phrase)
        elif "RHL" or "LHHL" in tone:
            no_L_rule = pynini.cdrewrite(no_L, "H", "", sigma_star).optimize()
            multiple_linkingH = pynini.cdrewrite(multiple_linkH, "", "H", sigma_star).optimize()
            tone = (tone @ no_L_rule @ multiple_linkingH).stringify()
            phrase = noun, tone
            UR_tones.append(phrase)
        
    return UR_tones
    
UR_nouns_group2_PL = nouns2_UR_PL(nouns_group2_PL)

def poss_group2_PL(UR_noun, UR_pronoun):
    """returns a lits of tuples with a noun(lexical tone) + pronoun(UR tone) and the tones after the derivation"""
    vowels = ["a", "ə", "ɔ", "o", "ɛ", "e", "ɨ", "i", "u"]
    noun = UR_noun[0]
    Tnoun = UR_noun[1]
    pronoun = UR_pronoun[0]
    Tpronoun = UR_pronoun[1]
    sigma_star = pynini.union(*string.ascii_lowercase, "L", "H", ".", "ə", "ɔ", "ɛ", "ɨ", "I", "β", "ŋ", "ʃ",
                          "ʒ", "ɣ", "ʔ", "~", "0", "|", "F", "R", "+").optimize().closure()
    spreadH1 = pynini.transducer("L", "R")
    spreadH2 = pynini.transducer("0", "H")
    phrase = noun + "+" + pronoun
    tones = Tnoun + "+" + Tpronoun
    spreadingH1 = pynini.cdrewrite(spreadH1, "", "+H", sigma_star).optimize()
    spreadingH2 = pynini.cdrewrite(spreadH2, "", "+H", sigma_star).optimize()
    SR_tones = (tones @ spreadingH1 @ spreadingH2).stringify()
    result = phrase, SR_tonesz
    return result
    
list2_PL = []

for noun in range(len(UR_nouns_group2_PL)):
    list2_PL.append(poss_group2_PL(UR_nouns_group2_PL[noun], pronouns_PL[1]))
    
with open("shupamem_poss_output.tsv", 'w', encoding = 'utf8', newline = '') as tsv_file:
    tsv_writer = csv.writer(tsv_file, delimiter = '\t', lineterminator = '\n')
    tsv_writer.writerow(["Lexical_rep", "Number", "Final_poss_tones"])
    sigma_star = pynini.union(*string.ascii_lowercase, "L", "H", ".", "ə", "ɔ", "ɛ", "ɨ", "I", "β", "ŋ", "ʃ",
                          "ʒ", "ɣ", "ʔ", "~", "0", "|", "C", "R", "F", "+").optimize().closure()


    for item in list3:
        word = item[0]
        tag = item[1]
        if "|L" in tag:
            tag = tag.replace("|L", "LL")    
        if "|H" in tag:
            tag = tag.replace("|H", "HH")  
        if "|+" in tag:
            tag = tag.replace("|+", "H+")   
        if "|L" in tag:
            tag = tag.replace("|L", "LL")
        tsv_writer.writerow([word, "SG", tag]) 
        
    for item in list2:
        word = item[0]
        tag = item[1]
        if "|L" in tag:
            tag = tag.replace("|L", "LL")    
        if "|H" in tag:
            tag = tag.replace("|H", "HH")  
        if "|+" in tag:
            tag = tag.replace("|+", "H+")  
        if "|L" in tag:
            tag = tag.replace("|L", "LL")
        tsv_writer.writerow([word, "SG", tag])
     
    for item in list1:
        word = item[0]
        tag = item[1]
        if "|L" in tag:
            tag = tag.replace("|L", "LL")    
        if "|H" in tag:
            tag = tag.replace("|H", "HH")  
        if "|+" in tag:
            tag = tag.replace("|+", "H+")   
        if "|L" in tag:
            tag = tag.replace("|L", "LL")
        tsv_writer.writerow([word, "SG", tag])

    for item in list1_PL:
        word = item[0]
        tag = item[1]
        if "|H" in tag:
            tag = tag.replace("|H", "HH")
        tsv_writer.writerow([word, "PL", tag]) 
        
    for item in list2_PL:
        word = item[0]
        tag = item[1]
        if "|H" in tag:
            tag = tag.replace("|H", "HH")
        tsv_writer.writerow([word, "PL", tag]) 
