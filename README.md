# UD-Japanese-GSDPUD-CaboCha

## ファイル形式

- #! DOC 行 ＜文番号＞
- #! DOCID 行
  - <ID> 文番号
  - <newdoc_id> 元の newdoc id (PUD のみ)
  - <sent_id> 元の sent id
  - <text> 元の text
  - <english_text> 元の english_text
  - <non_projective> 交差ありか否か
  - <Dynagon_corpusName> 国語研所内サーバにおけるデータベース名
  - <Dynagon_file> 国語研所内サーバにおけるファイル名
  - <Dynagon_start> 国語研所内サーバにおけるオフセット値

- 係り受け情報行
  - 文節ID
  - 係り先文節ID
  - 係り受け関係ラベル
  - 自立語主辞オフセット（要修正）
  - 付属語主辞オフセット（要修正）
  - SVM 出力値（要修正）

- EOS 行
  - 文末情報

- 形態素行

  - 1列目：出現形

  - 2列目：短単位形態論情報

    - (0):  pos1
    - (1):  pos2
    - (2):  pos3
    - (3):  pos4
    - (4):  cType
    - (5):  cForm
    - (6):  lForm
    - (7):  lemma
    - (8):  orth
    - (9):  pron
    - (10): orthBase
    - (11): pronBase
    - (12): goshu
    - (13): iType
    - (14): iForm
    - (15): fType
    - (16): fForm
    - (17): iConType
    - (18): fConType
    - (19): type
    - (20): kana
    - (21): kanaBase
    - (22): form
    - (23): formBase
    - (24): aType
    - (25): aConType
    - (26): aModType
    - (27): lid
    - (28): lemma_id

 - 3列目：長単位書字形出現形

 - 4列目：長単位形態論情報

   - (0):  l_pos1
   - (1):  l_pos2
   - (2):  l_pos3
   - (3):  l_pos4
   - (4):  l_cType
   - (5):  l_cForm
   - (6):  l_reading
   - (7):  l_lemma

 - 5列目：文節境界情報
