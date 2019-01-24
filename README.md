# google_oauth_4d
Oauth2認証にてGoogle APIを使用するための[4D](https://us.4d.com/)用コンポーネントです。4D v16およびv17に対応しています。  
( Oauth2 component for [4D](https://us.4d.com/) to use Google APIs. There are structures for 4D v16 and v17. )  
  
---
[Google API Console](https://console.developers.google.com)でクライアント用のJSONを取得し、何らかのテキストエディタでその本文をコピーしてください。  
( Visit [Google API Console](https://console.developers.google.com) to get JSON for clients. Open the JSON by any text editor and copy its source. )  
  
---
"google_json" メソッドのコメント部をそのJSONの内容で上書きしてください。  
( Overwrite the comment of "google_json" method with the JSON from Google. )  
![client_id_json_paste](https://user-images.githubusercontent.com/4927926/51669201-51c16700-2007-11e9-8cb1-8c9a9a8f1e10.gif)
  
---
上記作業を行わない場合は "google_oauth_json" メソッドでJSONを設定する必要があります。  
( Without the configuration above, "google_oauth_json" method is required to execute to set the JSON. )
  
---
認証はAPIを限定するようになっていませんが、このコンポーネント内のメソッドはDrive APIに特化したものとなっています。
( Authentication method of this component is possible for any Google APIs, but almost other methods are specialized for Drive API. )
