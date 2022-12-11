# Zadanie domowe 4

<a href="https://sim-mag.github.io/goit-markup-hw-05/">Podgląd strony</a>

## Projekt
<ol>
<li>Wszystkie style są zapisane w jednym pliku styles.css, który znajduje się w folderze css.</li>

<li>Kod źródłowy jest sformatowany za pomocą Prettier.</li>

<li>Wszystkie obrazy i zawartość tekstowa są z układu.</li>

<li>Wszystkie strony HTML mają normalizator stylu modern-normalize.</li>

<li>Kod jest napisany zgodnie z tutorialem.</li>

<li>Skrypt do okna modalnego jest zawarty w HTML w oddzielnym pliku modal.js.</li>
</ol>

## Znaczniki HTML
<ol>
<li>Wykonane jest oznaczenie znacznikami HTML wszystkich elementów układu.</li>

<li>Tagi są używane zgodnie z ich znaczeniem semantycznym.</li>
</ol>

## Stylizacja
<ol>
<li>Dla wszystkich efektów najechania kursorem i focusu (kolor, tło, cień) wykonywany jest transition. Czas - 250ms, funkcja rozkładu czasu - cubic-bezier(0.4, 0, 0.2, 1).</li>

<li>Właściwości, które będą animowane są wyraźnie określone w przejściach i animacjach. Nigdzie nie ma wartości all.</li>

<li>W sekcji Czym się zajmujemy tekst z tłem jest umieszczony nad obrazem.</li>

<li>W głównej nawigacji, używając pseudoelementu ::after, podkreślono link do bieżącej strony (na której obecnie jest użytkownik).</li>

<li>Niebieska nakładka z tekstem na kartach strony Portfolio pojawia się po najechaniu kursorem w dowolne miejsce na karcie. W każdej karcie jest tekst jak w pierwszym przykładzie.</li>

<li>Niebieska nakładka na kartach strony Portfolio wysuwa się z dołu.</li>

<li>Pseudoelementy nie mają treści tekstowej we właściwości content. Używane są wyłącznie do celów dekoracyjnych.</li>
</ol>

## Okno modalne
<ol>
<li>Ukończono oznaczanie i dekoracja «backdrop» (ciemnego półprzezroczystego tła) okna modalnego.</li>

<li>«Backdrop» (tło) wypełnia 100% wysokości i szerokości okna przeglądarki i jest w nim stałe.</li>

<li>Ukończono oznaczenie znacznikami HTML i dekorację okna modalnego.</li>

<li>Okno modalne jest umieszczone pionowo i poziomo na środku tła (backdrop).</li>

<li>Ukończono oznaczenie znacznikami HTML i dekorację przycisku do zamykania okna modalnego w prawym górnym rogu.</li>

<li>Początkowo okno modalne i backdrop są ukrywane za pomocą klasy is-hidden w backdropie, w selektorze tego elementu używa się właściwości visibility, opacity i pointer-events.</li>

<li>Jeśli usuniesz klasę is-hidden z backdrop - pojawi się backdrop i okno modalne.</li>

<li>Pojawienie się i zniknięcie okna modalnego jest animowane przy użyciu przejścia z dowolnym efektem, takim jak scale lub translate, i opacity.</li>
</ol>