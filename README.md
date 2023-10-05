# The Quest

Každá dvojica bude pracovať s pridelenou dátovou sadou od 3. týždňa.   
Vašou úlohou je predikovať závislé hodnoty premennej **“ack”** (predikovaná premenna) pomocou metód strojového učenia.  
Budete sa musieť pritom vysporiadať s viacerými problémami, ktoré sa v dátach nachádzajú ako formáty dát, chýbajúce, vychýlené hodnoty a mnohé ďalšie.  

## Očakavaným výstupom projektu  je:

  1. najlepší model strojového učenia
  2. data pipeline pre jeho vybudovanie na základe vstupných dát.
  
## Popis produktov: premenné (variable, feature), ktoré sa môžu vyskytnúť v datasetoch  

  - product_ean 
  - store_name 
  - code 
  - location 
  
## Popis používateľa: premenné (variable, feature), ktoré sa môžu vyskytnúť v datasetoch

  -	user_id
  - username
  - name
  - address	
  - current_location		
  - residence	
  - birthdate
  - registration	
  - race	
  - sex	
  - mail
  - job

## Popis sedenia (session): premenné (variable, feature), ktoré sa môžu vyskytnúť v datasetoch
  - session_id
  - session_start
  - session_duration
  - total_load_time
  - screen_width
  - screen_height
  - browser_name

## Interakcie počas sedenia

  - page_activity_duration          - trvanie aktivity používateľa na stránke
  - wild_mouse_duration             - trvanie rýchleho pohybu myši,
  - mouse_move_total_rel_distance   - normalizovaná na výšku a šírku obrazovky
  - scroll_move_total_rel_distance  - normalizovaná na výšku a šírku obrazovky
    
## (pct_) pomer počtu interakcií daného typu k celkovému počtu nasobený bázovou hodnotou

  - pct_scroll_move_duration		- normonovaná hodnota na celkový čas rolovania
  - pct_mouse_move			        - záznamy o pohybe myši
  - pct_scroll_move 			      - záznamy o rolovaní
  - pct_wild_mouse 			        - záznamy o rýchlom pohybe myši
  - pct_click				            - záznamy o klikaní používateľa
  - pct_double_click 			      - záznamy o dvojitom kliknutí používateľa
  - pct_rage_click				      - záznamy o zúrivom kliknutí na stránke
  - pct_input				            - záznamy o zadávaní vstupov používateľom
  - pct_scrandom				        - záznamy o rýchlom presúvaní na stránke
  - pct_click_product_info		  - záznamy o klikaní na informácie produktu

Popis sedenia, zoznam interakcií, (pct_) sú redukované z väčšieho množstva monitorovaných popisov a interakcií v e-shope.  
Originálne dáta (logy) majú veľkosť GB v formáte JSON.  

