
<H1>FORM 1</H1>

<form action="https://www.litv.tv/vod/movie/list.do" method="GET">
<input type="text" name="category_id">
<input type="submit" value="搜尋">
</form>
<H1>FORM 2</H1>
<form action="https://www.litv.tv/vod/movie/list.do" method="GET">
<select name="category_id">
<option value="124">熱門排行</option>
<option value="123">最新上架</option>
<option value="312" selected>韓國電影</option>
<option value="392">動畫電影瘋</option>
<option value="557">金馬盛典</option>
</select>
<input type="submit" value="搜尋">
</form>

<H1>FORM 3</H1>
<form action="https://www.litv.tv/search/search.do" method="GET">
<input type="text" name="search_input">

<input type="submit" value="搜尋">
</form>

<H1>FORM 4 HTML5</H1>

<input type="datetime-local" min="2015-10-01T00:00" max="2015-10-31T00:00">

<input type="tel" pattern="[0][9][0-9]{8}" placeholder="09xxxxxxxx">
<input type="url" placeholder="http://it-life-wyx.blogspot.tw/">
<input type="email" name="email value="信箱">
<input type="url" name="url" value="網址">
<input type="color" name="color">

<H1>HTML5 時間/日期/電話</H1>
<input type="date" name="date">
<input type="time" name="time">
<input type="tel" name="tel" value="電話">
