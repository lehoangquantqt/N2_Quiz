######
hãy đọc file PDF trên và generate file json có cấu trúc tương tự bên dưới từ câu 1 đến câu 42:
{
id: 1,
c: "文字・語彙",
p: 2,
q: "祖父は濃い味のものを好む。下線部「濃い」の読み方はどれですか。",
o: ["からい", "うすい", "あまい", "こい"],
a: 3,
e: "「濃い」đọc là こい, nghĩa là đậm. 「濃い味」là vị đậm, được nêm nếm đậm đà.",
om: [
"からい: Cay, có vị cay hoặc nồng. Đây không phải cách đọc của 「濃い」.",
"うすい: Nhạt, loãng, không đậm. Đây không phải cách đọc của 「濃い」.",
"あまい: Ngọt. Đây không phải cách đọc của 「濃い」.",
"こい: Đậm, đặc; 「濃い味」là vị đậm.",
],
} 

####
bạn hãy generate từ câu 43 đến câu 47 theo cấu trúc bên dưới
{
id: 47,
c: "文法",
p: 12,
q: "私の部屋のたんすには、いつかまた＿＿ ＿＿ ★ ＿＿たくさんしまってある。",
o: ["と思って", "着るかもしれない", "古い服が", "捨てられずにいる"],
a: 3,
e: "Thứ tự đúng: 着るかもしれない → と思って → 捨てられずにいる → 古い服が. Câu hoàn chỉnh: 「私の部屋のたんすには、いつかまた着るかもしれないと思って捨てられずにいる古い服がたくさんしまってある。」Nghĩa là: Trong tủ quần áo phòng tôi có rất nhiều quần áo cũ được cất giữ vì tôi nghĩ rằng có thể một ngày nào đó sẽ mặc lại nên không nỡ vứt đi. ★ nằm ở cụm 「捨てられずにいる」.",
om: [
"と思って: Nghĩ rằng..., vì nghĩ rằng... Dùng để diễn tả suy nghĩ hoặc lý do cho hành động phía sau.",
"着るかもしれない: Có thể sẽ mặc. 「～かもしれない」diễn tả khả năng xảy ra.",
"古い服が: Những bộ quần áo cũ. 「古い服」là quần áo cũ, 「が」đánh dấu chủ ngữ.",
"捨てられずにいる: Vẫn không thể vứt đi, vẫn chưa nỡ vứt. 「～ずにいる」diễn tả trạng thái tiếp tục không thực hiện một hành động.",
],
},  

#####

bạn hãy generate từ câu 48 đến câu 51 theo cấu trúc bên dưới:
const passage48_51 = `以下は、雑誌のコラムである。

漫画で学ぶビジネス書

近年、社会人の学びを目的としたビジネス書の分野で、漫画形式のものが多く出版されるようになった。経済、経営、IT、法律、心理学、哲学など、様々な分野のものがあり、入門者にもわかりやすいと人気だ。難しい専門的な内容も、漫画だとわかりやすいと感じる。これはなぜか。

漫画の特徴は文字と絵によって内容が語られることだ。文字数の少なさから、情報も少ないと思うかもしれないが、（48）研究によると、漫画は文字だけの文章と比べて、1分間の脳に伝える情報量が約2倍になるという。「漫画を読む」と言ったとき、読むのは文字だけではなく、絵そのものなのだ。

脳の働きの点からいうと、実は漫画と日本語は似ている。人間の脳は機能が右と左で分かれており、絵は「右脳」で、音声は「左脳」で処理される。日本語の文字には、ひらがな、カタカナ、漢字があるが、音を表すひらがなとカタカナを読むときは、左脳がよく働く。（49）漢字は意味を表すものだ。漢字を見ると意味やイメージが連想されるが、私たちの脳は、漢字を絵として右脳で処理している。漫画で読むほうがわかりやすい。（50）、ひらがなやカタカナだけの文よりも漢字も使われた文のほうが、内容を理解しやすいというのと同じ理由だ。

入門者にとって、わかりやすさは魅力だ。漫画形式のビジネス書をまだ読んだことがない人、難しそうでなかなか勉強が始められない分野があるという人は、一度読んでみてはいかがだろうか。新しい学びの体験と（51）。
`;
{
id: 48,
c: "文法",
p: 13,
passageId: "N2_T7_2026_READING_48_51",
passage: passage48_51,
q: "文字数の少なさから、情報も少ないと思うかもしれないが、（48）研究によると、漫画は文字だけの文章と比べて、1分間の脳に伝える情報量が約2倍になるという。",
o: ["この", "その", "ある", "以下の"],
a: 2,
e: "「ある研究によると」nghĩa là theo một nghiên cứu nào đó. 「ある」được dùng khi đề cập đến một đối tượng không xác định cụ thể. Trong đoạn văn, tác giả lần đầu giới thiệu nghiên cứu này nên 「ある研究によると」là cách diễn đạt phù hợp.",
om: [
"この: Này. Dùng để chỉ một đối tượng gần người nói hoặc đang được xác định cụ thể. 「この研究」không phù hợp bằng cách giới thiệu một nghiên cứu chưa được nhắc đến.",
"その: Đó. Dùng để chỉ đối tượng đã được đề cập hoặc được xác định trong ngữ cảnh. Ở đây nghiên cứu chưa được giới thiệu trước đó.",
"ある: Một... nào đó. 「ある研究によると」là theo một nghiên cứu nào đó. Đây là đáp án đúng.",
"以下の: Dưới đây, sau đây. 「以下の研究」không phù hợp với cấu trúc và ngữ cảnh câu này.",
],
}, 
generate cả passage48_51 luôn nhé