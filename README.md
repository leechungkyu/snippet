![main](https://user-images.githubusercontent.com/18473861/108994491-34c45a00-76df-11eb-80c1-6f023dac08d6.png)
# SeleniumでDOM要素を選択する方法
## DOMの中から最初に見つかった要素を1つだけ取得

|メソッド名|説明|
|---|---|
|find_element_by_id(id)|id属性から要素を1つ取得|
|find_element_by_name(name)|name属性から要素を1つ取得|
|find_element_by_css_selector(query)|CSSセレクターを指定して要素を1つ取得|
|find_element_by_xpath(query)|XPathを利用して要素を1つ取得|
|find_element_by_tag_name(name)|タグ名nameの要素を1つ取得|
|find_element_by_partial_link_text(text)|リンクの子要素を含むテキストから要素を1つ取得|
|find_element_by_class_name(name)|クラス名nameから要素を1つ取得|

## DOMの中にある全ての要素を取得

|メソッド名|説明|
|---|---|
|find_elements_by_css_selector(query)|CSSセレクターを指定して全ての要素を取得|
|find_elements_by_xpath(query)|XPathを利用して全ての要素を取得|
|find_elements_by_tag_name(name)|タグ名nameの全ての要素を取得|
|find_elements_by_class_name(name)|クラス名nameから全ての要素を取得|
|find_elements_by_partial_link_text(text)|リンクの子要素を含むテキストから複数要素を取得|
|find_element_by_partial_link_text(text)|リンクの子要素を含むテキストから要素を取得|

# Seleniumで要素に対して行う操作

|メソッド名|説明|
|---|---|
|clear()|テキスト入力できる要素でテキストをクリアする．|
|click()|要素クリック|
|get_attribute(name)|要素の属性nameを取得する．|
|is_displayed()|要素がユーザから見える状態かどうか|
|is_enabled()|要素が有効になっているかどうか|
|text|要素のテキスト|
|is_selected()|チェックボックスなどの要素が選択された状態かどうか|
|screenshot(filename)|スクリーンショットを撮る|
|send_keys(value)|キーを送信する|
|submit()|フォームを送信する|
|value_of_css_property(name)|CSSのnameの値を取得する|
|id|id要素|
|location|要素の位置|
|parant|親要素|
|rect|サイズと位置の情報を辞書型で返す|
|screenshot_as_base64|スクリーンショットBase64で得る．|
|screenshot_as_png|スクリーンショットをPNG形式のバイナリデータで得る．|
|size|要素のサイズ|
|tag_name|タグの名前|
|text|要素のテキスト|

# Seleniumのドライバに対する操作

|メソッド名|説明|
|---|---|
|add_cookie(cookie_dict)|クッキーに値を辞書形式で追加|
|back()/forward()|履歴を見て１つ前のページに戻る/進む|
|close()|ブラウザを閉じる|
|current_url|現在のURL|
|delete_all_cookies()|全てのクッキーを削除する|
|delete_cookie(name)|指定のクッキー変数を削除する|
|title|現在のページのタイトルを返す|
|execute(command,params)|ブラウザ固有のコマンドを実行する|
|execute_async_script(script,*args)|非同期でJavaScriptを実行する|
|execute_script(script,*args)|同期的にJavaScriptを実行する|
|get(url)|Webページを読み込む|
|get_cookie(name)|クッキーの値を得る|
|get_cookies()|クッキーの値を全て辞書型で得る|
|get_log(type)|ログを得る(browser/driver/client/server)|
|get_screenshot_as_base64()|base64形式でスクリーンショットを得る|
|get_screenshot_as_file(filename)|スクリーンショットをファイルに保存|
|get_screenshot_as_png()|PNG形式でスクリーンショットのバイナリを得る|
|get_window_position(windowHandle='current')|ウィンドウの位置を得る|
|get_window_size(windowHandle='current')|ウィンドウのサイズを得る|
|implicitly_wait(sec)|最大待機秒を指定して処理が終わるのを待つ|
|quit()|ドライバを終了させ，各ウィンドウを閉じる|
|save_screenshot(filename)|スクリーンショットを保存する|
|set_page_load_timeout(time_to_wait)|読み込みタイムアウトする時間を指定|
|set_window_position(x,y,windowHandle='current')|ウィンドウの位置を指定|
|set_window_size(width,height,windowHandle='current')|ウィンドウのサイズを指定|
|title|現在のページのタイトルを返す|
