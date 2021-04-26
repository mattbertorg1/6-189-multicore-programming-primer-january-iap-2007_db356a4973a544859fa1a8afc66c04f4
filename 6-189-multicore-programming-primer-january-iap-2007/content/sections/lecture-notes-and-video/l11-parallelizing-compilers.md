---
about_this_resource_text: <p><strong>Topics covered:</strong> Parallelizing compilers</p><p><strong>Instructor:</strong>
  Saman Amarasinghe</p><p>Subtitles are provided through the generous assistance of
  Rohan Pai.</p>
course_id: 6-189-multicore-programming-primer-january-iap-2007
embedded_media:
- id: l11.jpg
  parent_uid: 9fbaa99532b1034d0db2098164665871
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-189-multicore-programming-primer-january-iap-2007/lecture-notes-and-video/l11-parallelizing-compilers/l11.jpg
  title: 'L11: Parallelizing Compilers'
  type: null
  uid: 3d8368e8bff95c3e1ff31254337d0ea2
- id: Video-YouTube-Stream
  media_location: sOiuF18PTIs
  parent_uid: 9fbaa99532b1034d0db2098164665871
  title: Video-YouTube-Stream
  type: Video
  uid: 0aa3f661b1b4426c1cc7ecf77ed234bc
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/sOiuF18PTIs/default.jpg
  parent_uid: 9fbaa99532b1034d0db2098164665871
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: a9d717de12fab305bd5376639c596edd
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id341597759
  parent_uid: 9fbaa99532b1034d0db2098164665871
  title: Video-iTunes U-MP4
  type: Video
  uid: c16b94c8b24f50ef47b5b1ad7d2e8ac1
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT6.189IAP07/ocw-6.189-iap07-lec11_300k.mp4
  parent_uid: 9fbaa99532b1034d0db2098164665871
  title: Video-Internet Archive-MP4
  type: Video
  uid: d5b27ff2d78d6bcacff0f1cf267c62ce
- id: Thumbnail-OCW-JPG
  parent_uid: 9fbaa99532b1034d0db2098164665871
  title: Thumbnail-OCW-JPG
  type: Thumbnail
  uid: 2760e5fce148c8ff0f03d52e4266602a
- id: 3Play-3PlayYouTubeid-MP4
  media_location: sOiuF18PTIs
  parent_uid: 9fbaa99532b1034d0db2098164665871
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 9824151e899b7e68e70190e93d03fe6f
- id: sOiuF18PTIs.srt
  parent_uid: 9fbaa99532b1034d0db2098164665871
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-189-multicore-programming-primer-january-iap-2007/lecture-notes-and-video/l11-parallelizing-compilers/sOiuF18PTIs.srt
  title: 3play caption file
  type: null
  uid: fa88f2b7a9f323b8f0eaa89f9280c41b
- id: sOiuF18PTIs.pdf
  parent_uid: 9fbaa99532b1034d0db2098164665871
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-189-multicore-programming-primer-january-iap-2007/lecture-notes-and-video/l11-parallelizing-compilers/sOiuF18PTIs.pdf
  title: 3play pdf file
  type: null
  uid: 4512369c70763a85792a4ec565409cda
- id: Caption-3Play YouTube id-SRT
  parent_uid: 9fbaa99532b1034d0db2098164665871
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 96ea627d372d22f5d0622ce3f3347aaf
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 9fbaa99532b1034d0db2098164665871
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: edde625f49676a283590f32f9cb7d466
inline_embed_id: 85096213l11:parallelizingcompilers30917452
layout: video
order_index: null
parent_uid: 69885f30bae5c69316fc5492e4404278
related_resources_text: <p>Lecture Notes (<a title="Open in a new window." target="_blank"
  href="./resolveuid/d8172b0d04b6bd462126dc552bccd52b">PDF</a>)</p>
short_url: l11-parallelizing-compilers
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-189-multicore-programming-primer-january-iap-2007/lecture-notes-and-video/l11-parallelizing-compilers
template_type: Tabbed
title: 'L11: Parallelizing Compilers'
transcript: '<p><span m=''30''>The</span> <span m=''120''>following</span> <span m=''540''>content</span>
  <span m=''1130''>is</span> <span m=''1240''>provided</span> <span m=''1710''>under</span>
  <span m=''1970''>a</span> <span m=''2030''>Creative</span> <span m=''2420''>Commons</span>
  <span m=''3070''>license.</span> <span m=''3850''>Your</span> <span m=''4120''>support</span>
  <span m=''4620''>will</span> <span m=''4790''>help</span> <span m=''5040''>MIT</span>
  <span m=''5460''>OpenCourseWare</span> <span m=''6280''>continue</span> <span m=''6780''>to</span>
  <span m=''6860''>offer</span> <span m=''7270''>high</span> <span m=''7540''>quality</span>
  <span m=''8030''>educational</span> <span m=''8660''>resources</span> <span m=''9250''>for</span>
  <span m=''9450''>free.</span> <span m=''10540''>To</span> <span m=''10670''>make</span>
  <span m=''10870''>a</span> <span m=''10920''>donation</span> <span m=''11600''>or</span>
  <span m=''11850''>view</span> <span m=''12310''>additional</span> <span m=''12740''>materials</span>
  <span m=''13250''>from</span> <span m=''13410''>hundreds</span> <span m=''13860''>of</span>
  <span m=''13940''>MIT</span> <span m=''14410''>courses,</span> <span m=''15370''>visit</span>
  <span m=''15850''>MIT</span> <span m=''15960''>OpenCourseWare</span> <span m=''17190''>at</span>
  <span m=''17610''>ocw.mit.edu.</span> </p><p><span m=''21390''>PROFESSOR:</span>
  <span m=''22110''>Let''s</span> <span m=''22260''>get</span> <span m=''22480''>started.</span>
  <span m=''23210''>So</span> <span m=''24210''>what</span> <span m=''24410''>we are</span>
  <span m=''24550''>going</span> <span m=''24760''>to</span> <span m=''24900''>do</span>
  <span m=''25050''>today</span> <span m=''25960''>is</span> <span m=''26360''>go</span>
  <span m=''26660''>about</span> <span m=''27090''>discovering</span> <span m=''27660''>other</span>
  <span m=''27860''>alternating</span> <span m=''28430''>methods.</span> <span m=''29650''>We</span>
  <span m=''29780''>know</span> <span m=''30350''>you</span> <span m=''30560''>guys</span>
  <span m=''30890''>are</span> <span m=''31000''>amazing</span> <span m=''31490''>hackers</span>
  <span m=''31760''>and</span> <span m=''32060''>you</span> <span m=''32140''>can
  actually</span> <span m=''32590''>do</span> <span m=''32700''>all</span> <span m=''32850''>those</span>
  <span m=''33020''>things</span> <span m=''33200''>by</span> <span m=''33310''>hand.</span>
  <span m=''34730''>But</span> <span m=''36100''>to</span> <span m=''36190''>make</span>
  <span m=''37960''>multi-core</span> <span m=''38830''>generally</span> <span m=''39170''>acceptable,</span>
  <span m=''40140''>can</span> <span m=''40440''>we</span> <span m=''40580''>do</span>
  <span m=''40780''>things</span> <span m=''40960''>automatically?</span> <span m=''41510''>Can</span>
  <span m=''41720''>we</span> <span m=''41810''>really</span> <span m=''41980''>reduce</span>
  <span m=''42100''>a</span> <span m=''42170''>burden</span> <span m=''43040''>from</span>
  <span m=''43230''>the</span> <span m=''43300''>programers?</span> </p><p><span m=''44880''>So</span>
  <span m=''46460''>at</span> <span m=''46630''>the</span> <span m=''46710''>beginning</span>
  <span m=''47040''>I''m</span> <span m=''47190''>going to</span> <span m=''47330''>talk</span>
  <span m=''47570''>about</span> <span m=''47940''>general</span> <span m=''48460''>parallelizing</span>
  <span m=''49150''>compilers.</span> <span m=''49600''>What</span> <span m=''49840''>people</span>
  <span m=''50100''>have</span> <span m=''50280''>done.</span> <span m=''50540''>What''s</span>
  <span m=''50730''>the</span> <span m=''50840''>state</span> <span m=''51070''>of</span>
  <span m=''51180''>the</span> <span m=''51270''>art.</span> <span m=''51800''>Kind</span>
  <span m=''51970''>of</span> <span m=''52040''>get</span> <span m=''52210''>your</span>
  <span m=''52350''>feel</span> <span m=''53090''>what</span> <span m=''53530''>is
  doable.</span> <span m=''55590''>Hopefully,</span> <span m=''56070''>that will</span>
  <span m=''56360''>be</span> <span m=''56550''>a</span> <span m=''56920''>little</span>
  <span m=''57210''>over</span> <span m=''57390''>an hour,</span> <span m=''57590''>and
  then</span> <span m=''58120''>we''ll</span> <span m=''58540''>go</span> <span m=''58850''>talk</span>
  <span m=''59140''>about</span> <span m=''59430''>StreamEd</span> <span m=''59550''>compiler,</span>
  <span m=''61550''>what</span> <span m=''61870''>we</span> <span m=''61990''>have</span>
  <span m=''62160''>done</span> <span m=''62560''>recently,</span> <span m=''63660''>and</span>
  <span m=''65090''>how</span> <span m=''65610''>this</span> <span m=''65810''>automation</span>
  <span m=''67210''>part can</span> <span m=''67620''>do.</span> </p><p><span m=''69140''>So,</span>
  <span m=''69830''>I''ll</span> <span m=''70070''>talk</span> <span m=''70480''>a</span>
  <span m=''70620''>little</span> <span m=''70910''>bit</span> <span m=''71080''>about</span>
  <span m=''71140''>parallel</span> <span m=''71210''>execution.</span> <span m=''71730''>This</span>
  <span m=''71840''>is</span> <span m=''72050''>kind</span> <span m=''72300''>of</span>
  <span m=''74030''>what</span> <span m=''74280''>you</span> <span m=''74410''>know
  already.</span> <span m=''76150''>Then</span> <span m=''76470''>go into</span> <span
  m=''76870''>parallelizing</span> <span m=''77200''>compilers,</span> <span m=''78310''>and</span>
  <span m=''78610''>talk</span> <span m=''78890''>about</span> <span m=''79220''>how
  to</span> <span m=''79980''>determine</span> <span m=''80270''>if</span> <span m=''80370''>something</span>
  <span m=''80680''>is</span> <span m=''80800''>parallel</span> <span m=''81190''>by</span>
  <span m=''81310''>doing</span> <span m=''81500''>data</span> <span m=''81670''>dependence</span>
  <span m=''82140''>analysis,</span> <span m=''83030''>and</span> <span m=''83830''>how</span>
  <span m=''84040''>to</span> <span m=''84210''>increase</span> <span m=''84640''>the</span>
  <span m=''84740''>amount of</span> <span m=''85020''>parallelism</span> <span m=''85550''>available</span>
  <span m=''85910''>in</span> <span m=''86070''>code</span> <span m=''86370''>loop,</span>
  <span m=''86680''>what</span> <span m=''86920''>kind</span> <span m=''87050''>of</span>
  <span m=''87110''>transformation.</span> <span m=''88610''>Then</span> <span m=''88780''>we</span>
  <span m=''89560''>go</span> <span m=''89760''>look</span> <span m=''89920''>at</span>
  <span m=''90170''>how</span> <span m=''90370''>to</span> <span m=''90530''>generate</span>
  <span m=''90830''>code,</span> <span m=''91530''>because</span> <span m=''92280''>once</span>
  <span m=''92570''>you</span> <span m=''92740''>see that</span> <span m=''92950''>something
  is</span> <span m=''93320''>parallel,</span> <span m=''93640''>how</span> <span
  m=''93750''>you actually</span> <span m=''94090''>get</span> <span m=''94280''>to</span>
  <span m=''94350''>run</span> <span m=''94560''>parallel.</span> <span m=''95270''>And</span>
  <span m=''95770''>finish</span> <span m=''96100''>up</span> <span m=''96310''>with</span>
  <span m=''96400''>actually</span> <span m=''96740''>how to</span> <span m=''97050''>do</span>
  <span m=''97290''>communication</span> <span m=''98010''>code</span> <span m=''98480''>in</span>
  <span m=''99170''>a</span> <span m=''99800''>machine</span> <span m=''100750''>such</span>
  <span m=''101030''>as</span> <span m=''101510''>a</span> <span m=''101570''>server.</span>
  </p><p><span m=''104330''>So</span> <span m=''104620''>in</span> <span m=''104770''>parallel</span>
  <span m=''104890''>execution,</span> <span m=''106440''>this</span> <span m=''106610''>is</span>
  <span m=''106760''>something --</span> <span m=''107650''>it''s</span> <span m=''107800''>a</span>
  <span m=''107940''>review.</span> <span m=''108660''>So</span> <span m=''108850''>there</span>
  <span m=''109030''>are</span> <span m=''109080''>many ways</span> <span m=''109570''>of</span>
  <span m=''109890''>parallelism,</span> <span m=''110170''>things</span> <span m=''110330''>like</span>
  <span m=''110460''>instruction level</span> <span m=''110910''>parallelism.</span>
  <span m=''111240''>It''s</span> <span m=''112270''>basically</span> <span m=''113430''>effected</span>
  <span m=''113980''>by</span> <span m=''114090''>hardware</span> <span m=''114790''>or</span>
  <span m=''115060''>compiler</span> <span m=''115680''>scheduling.</span> <span m=''117060''>As</span>
  <span m=''117390''>of</span> <span m=''117560''>today</span> <span m=''118000''>this</span>
  <span m=''118360''>is</span> <span m=''118620''>in</span> <span m=''118880''>abundance.</span>
  <span m=''119730''>In</span> <span m=''120020''>all</span> <span m=''120530''>for</span>
  <span m=''120700''>scalars</span> <span m=''120960''>we</span> <span m=''121100''>do</span>
  <span m=''121250''>that,</span> <span m=''121940''>in</span> <span m=''122310''>[OBSCURES]</span>
  <span m=''122850''>we</span> <span m=''123010''>do</span> <span m=''123140''>that.</span>
  <span m=''124560''>Then</span> <span m=''125050''>password</span> <span m=''125390''>parallelism,</span>
  <span m=''126070''>it''s</span> <span m=''126340''>what</span> <span m=''126790''>most</span>
  <span m=''127120''>of</span> <span m=''127240''>you</span> <span m=''127350''>guys</span>
  <span m=''127550''>are</span> <span m=''127630''>doing</span> <span m=''127910''>now.</span>
  <span m=''128860''>You</span> <span m=''129010''>probably</span> <span m=''129300''>find</span>
  <span m=''129590''>a</span> <span m=''129630''>program,</span> <span m=''130220''>you</span>
  <span m=''130340''>divide</span> <span m=''130480''>it into tasks,</span> <span
  m=''130610''>you</span> <span m=''131220''>get</span> <span m=''131370''>task level</span>
  <span m=''131630''>parallelism,</span> <span m=''132130''>mainly</span> <span m=''132460''>by</span>
  <span m=''132560''>hand.</span> <span m=''134200''>Some</span> <span m=''134500''>of</span>
  <span m=''134630''>you</span> <span m=''134720''>might</span> <span m=''134930''>be</span>
  <span m=''135030''>doing</span> <span m=''135280''>data</span> <span m=''135460''>level</span>
  <span m=''135690''>parallelism</span> <span m=''135910''>and</span> <span m=''136120''>also</span>
  <span m=''136200''>loop</span> <span m=''136540''>level</span> <span m=''137010''>parallelism.</span>
  <span m=''139300''>That</span> <span m=''139450''>can</span> <span m=''139630''>be</span>
  <span m=''139750''>the</span> <span m=''139870''>hand or</span> <span m=''140570''>compiler</span>
  <span m=''140930''>generated.</span> <span m=''142010''>Then,</span> <span m=''142210''>of</span>
  <span m=''142330''>course,</span> <span m=''142670''>pipeline</span> <span m=''143060''>parallelism</span>
  <span m=''143500''>is</span> <span m=''143700''>more</span> <span m=''143960''>mainly</span>
  <span m=''144300''>done in</span> <span m=''144560''>hardware</span> <span m=''145270''>and</span>
  <span m=''145660''>language</span> <span m=''145940''>extreme,</span> <span m=''146550''>do
  pipeline</span> <span m=''146860''>parallelism.</span> <span m=''148560''>Divide</span>
  <span m=''148720''>and</span> <span m=''148900''>conquer</span> <span m=''149100''>parallelism</span>
  <span m=''149600''>we</span> <span m=''149710''>went</span> <span m=''149850''>a</span>
  <span m=''150270''>little</span> <span m=''150550''>bit</span> <span m=''150820''>more</span>
  <span m=''151300''>than in</span> <span m=''151570''>hardware,</span> <span m=''151980''>mainly
  by</span> <span m=''152980''>hand</span> <span m=''153560''>for</span> <span m=''153920''>recursive</span>
  <span m=''154180''>functions.</span> </p><p><span m=''155170''>Today</span> <span
  m=''155940''>we are</span> <span m=''156100''>going to focus</span> <span m=''156950''>on</span>
  <span m=''158120''>loop</span> <span m=''158500''>level</span> <span m=''158860''>parallelism,</span>
  <span m=''159660''>particularly</span> <span m=''160040''>how</span> <span m=''160190''>do</span>
  <span m=''160790''>loop</span> <span m=''160890''>level</span> <span m=''161110''>parallelism</span>
  <span m=''161620''>by the</span> <span m=''161830''>compiler.</span> </p><p><span
  m=''163360''>So</span> <span m=''163550''>why</span> <span m=''163650''>loops?</span>
  <span m=''165090''>So loops</span> <span m=''165420''>is</span> <span m=''165530''>interesting</span>
  <span m=''166100''>because</span> <span m=''167260''>people</span> <span m=''167390''>observed</span>
  <span m=''167870''>in</span> <span m=''168000''>morse</span> <span m=''168290''>code,</span>
  <span m=''169030''>90%</span> <span m=''169760''>of</span> <span m=''169850''>execution</span>
  <span m=''170470''>time</span> <span m=''170800''>is in</span> <span m=''171030''>10%</span>
  <span m=''171550''>of the code.</span> <span m=''171910''>Almost</span> <span m=''172440''>99%</span>
  <span m=''173180''>of</span> <span m=''173270''>the</span> <span m=''173380''>execution</span>
  <span m=''173770''>time</span> <span m=''174010''>is in</span> <span m=''174260''>10%
  of the code.</span> <span m=''175690''>This</span> <span m=''175960''>called</span>
  <span m=''176220''>a</span> <span m=''176380''>loop,</span> <span m=''177020''>and</span>
  <span m=''177420''>it</span> <span m=''177580''>makes</span> <span m=''177930''>sense</span>
  <span m=''178320''>because</span> <span m=''179610''>running</span> <span m=''179960''>at</span>
  <span m=''180080''>3 gigahertz,</span> <span m=''180920''>if</span> <span m=''181340''>only</span>
  <span m=''181620''>run</span> <span m=''181920''>one</span> <span m=''182170''>instruction</span>
  <span m=''183380''>one,</span> <span m=''184530''>then</span> <span m=''185370''>you</span>
  <span m=''185640''>run</span> <span m=''185990''>through the</span> <span m=''186240''>hard</span>
  <span m=''186530''>drive</span> <span m=''187150''>in</span> <span m=''187540''>only</span>
  <span m=''187740''>a</span> <span m=''187780''>few</span> <span m=''187940''>minutes</span>
  <span m=''188260''>because</span> <span m=''189250''>you</span> <span m=''189800''>need
  to have</span> <span m=''190160''>repeatability.</span> <span m=''191370''>A</span>
  <span m=''191400''>lot</span> <span m=''191560''>of</span> <span m=''191660''>time</span>
  <span m=''191810''>repeatability</span> <span m=''192420''>thing</span> <span m=''192610''>loops.</span>
  <span m=''196070''>Loops,</span> <span m=''196270''>if</span> <span m=''196530''>you
  can</span> <span m=''196590''>parallelize,</span> <span m=''197150''>you</span>
  <span m=''197230''>can</span> <span m=''197370''>get</span> <span m=''197500''>really</span>
  <span m=''197810''>good</span> <span m=''197970''>performance</span> <span m=''198510''>because</span>
  <span m=''199020''>loops</span> <span m=''199600''>most</span> <span m=''199930''>of</span>
  <span m=''199990''>the</span> <span m=''200060''>time,</span> <span m=''200520''>each</span>
  <span m=''200890''>loop</span> <span m=''201190''>iteration</span> <span m=''201670''>have</span>
  <span m=''201890''>the</span> <span m=''201980''>same</span> <span m=''202270''>amount</span>
  <span m=''202550''>of</span> <span m=''202650''>work</span> <span m=''203300''>and</span>
  <span m=''203480''>you</span> <span m=''203550''>get</span> <span m=''203820''>nice</span>
  <span m=''204220''>good</span> <span m=''204420''>load</span> <span m=''204490''>balance,</span>
  <span m=''204950''>it''s</span> <span m=''205950''>somewhat</span> <span m=''206340''>easier</span>
  <span m=''206590''>to</span> <span m=''206850''>analyze,</span> <span m=''208240''>so</span>
  <span m=''208320''>that''s</span> <span m=''208620''>why</span> <span m=''208780''>the</span>
  <span m=''208900''>compiler</span> <span m=''209280''>start</span> <span m=''209520''>there.</span>
  <span m=''209750''>Whereas</span> <span m=''210320''>if</span> <span m=''210690''>you</span>
  <span m=''210940''>try to</span> <span m=''211170''>get</span> <span m=''211320''>task
  level</span> <span m=''211610''>parallelism,</span> <span m=''212560''>things</span>
  <span m=''212890''>have</span> <span m=''213070''>a lot</span> <span m=''213510''>more</span>
  <span m=''213650''>complexities</span> <span m=''214260''>that</span> <span m=''214800''>automatic</span>
  <span m=''215660''>compiler</span> <span m=''216030''>cannot do.</span> </p><p><span
  m=''218350''>So</span> <span m=''218550''>there</span> <span m=''218720''>are two</span>
  <span m=''219110''>types</span> <span m=''219400''>of</span> <span m=''219670''>parallel</span>
  <span m=''219780''>loops.</span> <span m=''221220''>One</span> <span m=''221500''>is</span>
  <span m=''221580''>a</span> <span m=''221710''>for all</span> <span m=''222000''>loop.</span>
  <span m=''223120''>That</span> <span m=''223400''>means</span> <span m=''223850''>there</span>
  <span m=''224010''>are</span> <span m=''224110''>no loop</span> <span m=''224480''>carried</span>
  <span m=''224860''>dependences.</span> <span m=''225720''>That</span> <span m=''225930''>means</span>
  <span m=''226160''>you</span> <span m=''226260''>can</span> <span m=''226490''>get</span>
  <span m=''226680''>the</span> <span m=''226770''>sequential</span> <span m=''227070''>code</span>
  <span m=''227440''>executing,</span> <span m=''228460''>run</span> <span m=''229030''>everything</span>
  <span m=''229360''>in parallel,</span> <span m=''230130''>and</span> <span m=''230510''>at
  the</span> <span m=''230600''>end</span> <span m=''230960''>you</span> <span m=''231050''>have</span>
  <span m=''231350''>a</span> <span m=''231640''>barrier</span> <span m=''232140''>and
  when</span> <span m=''232640''>everybody</span> <span m=''233030''>finishes</span>
  <span m=''233390''>you</span> <span m=''233500''>continue</span> <span m=''233650''>on</span>
  <span m=''233710''>the</span> <span m=''234010''>sequential</span> <span m=''234380''>code.</span>
  <span m=''235810''>That</span> <span m=''236020''>is</span> <span m=''236240''>how</span>
  <span m=''236590''>you</span> <span m=''236760''>do</span> <span m=''236870''>a</span>
  <span m=''236930''>for all</span> <span m=''237400''>loop.</span> <span m=''238300''>Some</span>
  <span m=''238450''>languages,</span> <span m=''238960''>in</span> <span m=''239120''>fact,</span>
  <span m=''239480''>have</span> <span m=''239920''>explicitly</span> <span m=''240500''>parallel</span>
  <span m=''241130''>construct,</span> <span m=''241510''>say</span> <span m=''241580''>OK,</span>
  <span m=''241950''>here''s</span> <span m=''242410''>a</span> <span m=''242470''>for
  all</span> <span m=''242770''>loop</span> <span m=''243420''>and</span> <span m=''244090''>go</span>
  <span m=''244300''>do</span> <span m=''244460''>that.</span> </p><p><span m=''246580''>The</span>
  <span m=''247130''>other type</span> <span m=''247760''>of loop</span> <span m=''248050''>is</span>
  <span m=''248180''>called</span> <span m=''248780''>a</span> <span m=''248990''>foracross</span>
  <span m=''249810''>or</span> <span m=''250140''>doacross</span> <span m=''250350''>loop.</span>
  <span m=''250990''>That</span> <span m=''251200''>says</span> <span m=''251550''>OK,</span>
  <span m=''251820''>while</span> <span m=''252030''>the</span> <span m=''252260''>loop</span>
  <span m=''252330''>is</span> <span m=''252620''>parallel,</span> <span m=''253300''>there</span>
  <span m=''253450''>are</span> <span m=''253550''>some</span> <span m=''253860''>dependences.</span>
  <span m=''254760''>That</span> <span m=''254970''>means</span> <span m=''255390''>some
  value</span> <span m=''255780''>generated</span> <span m=''256680''>here</span>
  <span m=''257120''>is</span> <span m=''257380''>used</span> <span m=''257670''>somewhere</span>
  <span m=''258180''>here.</span> <span m=''258720''>So</span> <span m=''258880''>you</span>
  <span m=''258940''>can</span> <span m=''259160''>run</span> <span m=''259370''>it</span>
  <span m=''259660''>parallel,</span> <span m=''260050''>but</span> <span m=''260210''>you</span>
  <span m=''260290''>have</span> <span m=''260500''>some</span> <span m=''260670''>communication</span>
  <span m=''261270''>going</span> <span m=''261530''>too.</span> <span m=''262280''>So</span>
  <span m=''262830''>you</span> <span m=''262940''>had to</span> <span m=''263060''>move</span>
  <span m=''263360''>data.</span> <span m=''263670''>So it''s</span> <span m=''263800''>not</span>
  <span m=''264230''>completely</span> <span m=''264750''>running</span> <span m=''265210''>parallel,</span>
  <span m=''265660''>there''s</span> <span m=''265880''>some</span> <span m=''266590''>synchronization</span>
  <span m=''267060''>going</span> <span m=''267310''>on.</span> <span m=''267720''>But</span>
  <span m=''268040''>you</span> <span m=''268120''>can</span> <span m=''268300''>get</span>
  <span m=''268440''>large</span> <span m=''268520''>chunk</span> <span m=''268780''>running
  parallels.</span> </p><p><span m=''272200''>So</span> <span m=''272540''>we</span>
  <span m=''272770''>kind</span> <span m=''272940''>of</span> <span m=''273030''>focus</span>
  <span m=''273440''>on</span> <span m=''273770''>dual</span> <span m=''274050''>loops</span>
  <span m=''274350''>today,</span> <span m=''275320''>and</span> <span m=''276280''>let''s</span>
  <span m=''276560''>look</span> <span m=''276710''>at</span> <span m=''276840''>this</span>
  <span m=''277060''>example.</span> <span m=''278720''>We</span> <span m=''278920''>see</span>
  <span m=''279200''>it''s a</span> <span m=''279270''>for far</span> <span m=''280060''>so</span>
  <span m=''280350''>it''s</span> <span m=''280510''>a parallel</span> <span m=''280940''>loop</span>
  <span m=''283620''>or</span> <span m=''283820''>for all</span> <span m=''284230''>loop.</span>
  <span m=''286110''>When</span> <span m=''286240''>you</span> <span m=''286370''>know</span>
  <span m=''286520''>it''s</span> <span m=''286730''>parallel,</span> <span m=''287150''>in</span>
  <span m=''287650''>here,</span> <span m=''287820''>of</span> <span m=''287930''>course,</span>
  <span m=''288430''>the</span> <span m=''289740''>user</span> <span m=''290350''>said</span>
  <span m=''290570''>that.</span> <span m=''291030''>What</span> <span m=''291260''>we</span>
  <span m=''291380''>can</span> <span m=''291570''>do</span> <span m=''291640''>is</span>
  <span m=''291770''>we</span> <span m=''291860''>can</span> <span m=''291990''>distribute</span>
  <span m=''292370''>the</span> <span m=''292490''>iteration</span> <span m=''293640''>by</span>
  <span m=''293930''>chunking</span> <span m=''294380''>up</span> <span m=''294550''>the</span>
  <span m=''295420''>iteration</span> <span m=''295920''>space</span> <span m=''296440''>into</span>
  <span m=''296690''>number of</span> <span m=''297050''>process</span> <span m=''297520''>chunks,</span>
  <span m=''299030''>and</span> <span m=''299300''>basically</span> <span m=''300370''>run</span>
  <span m=''300540''>that.</span> <span m=''302170''>If</span> <span m=''302520''>PMD</span>
  <span m=''302850''>mode,</span> <span m=''303470''>you can</span> <span m=''303730''>at</span>
  <span m=''303830''>the</span> <span m=''303910''>beginning</span> <span m=''304650''>the</span>
  <span m=''304950''>first processor</span> <span m=''305480''>can</span> <span m=''305680''>calculate</span>
  <span m=''305940''>the</span> <span m=''306890''>number</span> <span m=''308560''>of</span>
  <span m=''309010''>iterations</span> <span m=''309460''>you</span> <span m=''309570''>can</span>
  <span m=''309710''>run on each</span> <span m=''310120''>process</span> <span m=''311700''>in</span>
  <span m=''311900''>here,</span> <span m=''312280''>and</span> <span m=''312580''>then</span>
  <span m=''312650''>you</span> <span m=''312890''>synchronize,</span> <span m=''313740''>you
  put a</span> <span m=''314010''>barrier</span> <span m=''314250''>there,</span>
  <span m=''314370''>so</span> <span m=''314810''>everybody</span> <span m=''315160''>kind
  of</span> <span m=''315420''>sync</span> <span m=''315700''>up</span> <span m=''315830''>at</span>
  <span m=''315930''>that</span> <span m=''316140''>point.</span> <span m=''317170''>Or</span>
  <span m=''317550''>other</span> <span m=''318290''>process</span> <span m=''318570''>of</span>
  <span m=''318800''>waiting,</span> <span m=''319130''>and at</span> <span m=''319240''>that</span>
  <span m=''319540''>point,</span> <span m=''320070''>everybody</span> <span m=''320590''>starts,</span>
  <span m=''321300''>when</span> <span m=''321480''>you</span> <span m=''321640''>reach</span>
  <span m=''321940''>this</span> <span m=''322150''>point it''s</span> <span m=''322590''>running,</span>
  <span m=''322970''>it''s part of</span> <span m=''323190''>iterations,</span> <span
  m=''324410''>and</span> <span m=''324580''>then you''re</span> <span m=''324820''>going
  to</span> <span m=''324900''>put a</span> <span m=''325220''>barrier</span> <span
  m=''325420''>synchronization</span> <span m=''325500''>in place.</span> <span m=''328230''>Kind</span>
  <span m=''328450''>of</span> <span m=''328670''>obvious,</span> <span m=''329780''>parallel</span>
  <span m=''330100''>code</span> <span m=''330480''>basically</span> <span m=''330920''>in</span>
  <span m=''331090''>here,</span> <span m=''331160''>running</span> <span m=''331480''>on</span>
  <span m=''332150''>shared</span> <span m=''332500''>memory</span> <span m=''332600''>machine</span>
  <span m=''333360''>at this point.</span> </p><p><span m=''334780''>So</span> <span
  m=''334910''>this</span> <span m=''335090''>is</span> <span m=''335300''>what</span>
  <span m=''335910''>we</span> <span m=''335990''>can</span> <span m=''336160''>do.</span>
  <span m=''336310''>I</span> <span m=''336360''>mean</span> <span m=''336490''>this
  is</span> <span m=''336740''>what</span> <span m=''336910''>we</span> <span m=''337110''>saw</span>
  <span m=''337460''>before.</span> <span m=''339000''>Of</span> <span m=''339140''>course,</span>
  <span m=''339620''>instead</span> <span m=''339940''>of</span> <span m=''340040''>doing</span>
  <span m=''340240''>that,</span> <span m=''340380''>you</span> <span m=''340470''>can</span>
  <span m=''340650''>also</span> <span m=''341220''>do</span> <span m=''341460''>fork
  join</span> <span m=''342130''>types</span> <span m=''342440''>or</span> <span m=''342840''>once</span>
  <span m=''343340''>you</span> <span m=''343410''>want to</span> <span m=''343580''>run</span>
  <span m=''343740''>something</span> <span m=''343990''>parallel,</span> <span m=''344600''>you</span>
  <span m=''344890''>can</span> <span m=''345380''>fork</span> <span m=''345830''>a</span>
  <span m=''346300''>thread</span> <span m=''346460''>and</span> <span m=''346640''>each
  thread</span> <span m=''346820''>gets</span> <span m=''347800''>some</span> <span
  m=''348850''>amount</span> <span m=''349140''>of</span> <span m=''349220''>iterations</span>
  <span m=''349600''>you</span> <span m=''349730''>run,</span> <span m=''350100''>and</span>
  <span m=''350450''>after</span> <span m=''350650''>that</span> <span m=''350820''>you</span>
  <span m=''351110''>merge together.</span> <span m=''351480''>So</span> <span m=''351960''>you</span>
  <span m=''352080''>can</span> <span m=''352220''>do</span> <span m=''352330''>both.</span>
  <span m=''354180''>So</span> <span m=''354390''>that''s</span> <span m=''354660''>my</span>
  <span m=''354780''>hand.</span> <span m=''355290''>How</span> <span m=''355560''>do
  you</span> <span m=''355810''>do</span> <span m=''356190''>something</span> <span
  m=''356560''>like</span> <span m=''356870''>that</span> <span m=''357160''>by</span>
  <span m=''357340''>the</span> <span m=''357460''>compiler?</span> <span m=''359330''>That</span>
  <span m=''359470''>sounds</span> <span m=''360070''>simple</span> <span m=''360240''>enough,</span>
  <span m=''360490''>trivial enough.</span> <span m=''361540''>But</span> <span m=''361680''>you</span>
  <span m=''361880''>don''t</span> <span m=''362020''>automate</span> <span m=''362110''>the
  entire process.</span> <span m=''363010''>How to</span> <span m=''363230''>go about
  doing</span> <span m=''363620''>that.</span> <span m=''366480''>So,</span> <span
  m=''367640''>here are some normal</span> <span m=''368300''>loops,</span> <span
  m=''368613''>for</span> <span m=''368926''>loops.</span> <span m=''369240''>So</span>
  <span m=''369350''>the</span> <span m=''369470''>for</span> <span m=''369730''>all</span>
  <span m=''370500''>does this</span> <span m=''370610''>thing</span> <span m=''371220''>that</span>
  <span m=''372040''>was</span> <span m=''372290''>so</span> <span m=''372420''>simple,</span>
  <span m=''372770''>which</span> <span m=''372970''>is</span> <span m=''373110''>the</span>
  <span m=''373220''>for all</span> <span m=''373460''>construct</span> <span m=''374120''>that</span>
  <span m=''374290''>means</span> <span m=''374440''>somebody</span> <span m=''374820''>could</span>
  <span m=''374930''>look</span> <span m=''375110''>at</span> <span m=''375270''>that</span>
  <span m=''375750''>and</span> <span m=''376410''>said</span> <span m=''376580''>this</span>
  <span m=''376680''>loop</span> <span m=''377110''>is parallel.</span> <span m=''378310''>But</span>
  <span m=''378840''>you</span> <span m=''379070''>look at</span> <span m=''379290''>these</span>
  <span m=''379630''>FOR</span> <span m=''380470''>loops,</span> <span m=''380910''>how
  many of</span> <span m=''381030''>these</span> <span m=''381270''>loops</span> <span
  m=''381470''>are</span> <span m=''381580''>parallel?</span> <span m=''383780''>Is</span>
  <span m=''383890''>the first</span> <span m=''384240''>loop</span> <span m=''384430''>parallel?</span>
  <span m=''386940''>Why?</span> <span m=''387160''>Why</span> <span m=''387560''>not?</span>
  </p><p><span m=''387810''>AUDIENCE:</span> <span m=''388784''>[OBSCURED.]</span>
  </p><p><span m=''391220''>PROFESSOR: It''s</span> <span m=''391380''>a</span> <span
  m=''391660''>loop</span> <span m=''392290''>because</span> <span m=''394290''>the</span>
  <span m=''394430''>iteration,</span> <span m=''395170''>one of</span> <span m=''395640''>that</span>
  <span m=''396060''>is</span> <span m=''396480''>using</span> <span m=''397050''>what</span>
  <span m=''397620''>you</span> <span m=''397790''>wrote</span> <span m=''398100''>in</span>
  <span m=''398256''>iteration</span> <span m=''398413''>zero.</span> <span m=''398860''>So</span>
  <span m=''399850''>iteration</span> <span m=''400360''>one</span> <span m=''400630''>has</span>
  <span m=''400800''>to</span> <span m=''400880''>wait</span> <span m=''401350''>until
  iteration</span> <span m=''401550''>zero</span> <span m=''401680''>is</span> <span
  m=''401910''>done,</span> <span m=''402870''>so and so.</span> <span m=''403310''>How</span>
  <span m=''403670''>about this</span> <span m=''403840''>one?</span> <span m=''410110''>Why?</span>
  </p><p><span m=''410460''>AUDIENCE:</span> <span m=''411936''>[NOISE.]</span> </p><p><span
  m=''417350''>PROFESSOR:</span> <span m=''419750''>Not</span> <span m=''420230''>really.</span>
  <span m=''421380''>So it''s writing</span> <span m=''422550''>element 0 to</span>
  <span m=''423000''>5,</span> <span m=''423700''>it''s</span> <span m=''424290''>reading</span>
  <span m=''424500''>elements</span> <span m=''425130''>6</span> <span m=''425590''>to</span>
  <span m=''426190''>11.</span> <span m=''428040''>So</span> <span m=''428770''>they</span>
  <span m=''428920''>don''t</span> <span m=''429080''>overlap.</span> <span m=''430440''>So</span>
  <span m=''430730''>what you</span> <span m=''431040''>read and</span> <span m=''431180''>what</span>
  <span m=''431330''>you</span> <span m=''431440''>write</span> <span m=''431890''>never
  overlap,</span> <span m=''432270''>so</span> <span m=''432670''>you</span> <span
  m=''432740''>can</span> <span m=''432930''>keep</span> <span m=''433390''>doing</span>
  <span m=''433770''>it in any order,</span> <span m=''434380''>because</span> <span
  m=''435590''>the</span> <span m=''435690''>dependence</span> <span m=''436240''>means</span>
  <span m=''436520''>something</span> <span m=''436870''>you</span> <span m=''437200''>wrote,</span>
  <span m=''438260''>later</span> <span m=''438410''>you</span> <span m=''438470''>will</span>
  <span m=''438730''>read.</span> <span m=''438990''>This</span> <span m=''439570''>doesn''t
  happen in here.</span> <span m=''439920''>How about</span> <span m=''440790''>this
  one?</span> </p><p><span m=''453600''>AUDIENCE:</span> <span m=''454070''>There''s
  no dependence in there.</span> </p><p><span m=''455010''>PROFESSOR: Why?</span>
  </p><p><span m=''455250''>AUDIENCE:</span> <span m=''455778''>[OBSCURED.]</span>
  </p><p><span m=''458420''>PROFESSOR: So</span> <span m=''458600''>you''re</span>
  <span m=''458830''>writing</span> <span m=''459110''>even,</span> <span m=''459330''>you''re</span>
  <span m=''459790''>reading</span> <span m=''460090''>odd.</span> <span m=''461420''>So</span>
  <span m=''461550''>there''s</span> <span m=''461610''>no</span> <span m=''461990''>overlapping</span>
  <span m=''462150''>or</span> <span m=''462330''>anything</span> <span m=''462410''>like
  that.</span> <span m=''463900''>Question?</span> <span m=''464350''>OK.</span> <span
  m=''467020''>So,</span> <span m=''467610''>the way to look</span> <span m=''468290''>at</span>
  <span m=''468460''>that --</span> <span m=''468620''>I''m</span> <span m=''468780''>going
  to</span> <span m=''468950''>go</span> <span m=''469050''>a</span> <span m=''469370''>little</span>
  <span m=''469450''>bit of</span> <span m=''470110''>formalism.</span> <span m=''470260''>You</span>
  <span m=''470350''>can</span> <span m=''470560''>think</span> <span m=''470830''>about</span>
  <span m=''470930''>this</span> <span m=''471380''>as a</span> <span m=''471460''>iteration</span>
  <span m=''471900''>space.</span> <span m=''473100''>So iteration is</span> <span
  m=''474290''>if you look at</span> <span m=''474870''>each</span> <span m=''474960''>iteration</span>
  <span m=''475650''>separately,</span> <span m=''477080''>there</span> <span m=''477290''>could</span>
  <span m=''477530''>be thousands</span> <span m=''478090''>and</span> <span m=''478460''>millions</span>
  <span m=''478630''>of</span> <span m=''478810''>iterations</span> <span m=''479220''>and</span>
  <span m=''479820''>your</span> <span m=''479930''>compiler</span> <span m=''480130''>never</span>
  <span m=''480970''>[COUGHING]</span> <span m=''481160''>doing</span> <span m=''481360''>any</span>
  <span m=''481480''>work,</span> <span m=''482030''>and</span> <span m=''482190''>also</span>
  <span m=''482450''>some</span> <span m=''482690''>iteration</span> <span m=''483180''>space</span>
  <span m=''483610''>is</span> <span m=''483730''>defined</span> <span m=''484030''>by</span>
  <span m=''484740''>a</span> <span m=''484870''>range</span> <span m=''485250''>like</span>
  <span m=''485450''>1</span> <span m=''485710''>to</span> <span m=''485810''>n,</span>
  <span m=''486150''>so</span> <span m=''486230''>you</span> <span m=''486310''>don''t</span>
  <span m=''486480''>even</span> <span m=''486680''>know</span> <span m=''487510''>exactly</span>
  <span m=''487930''>how</span> <span m=''488070''>many</span> <span m=''488260''>iterations</span>
  <span m=''488580''>are</span> <span m=''488670''>going</span> <span m=''488830''>to</span>
  <span m=''488910''>be</span> <span m=''489550''>there. So</span> <span m=''490260''>you
  can represent</span> <span m=''490680''>this</span> <span m=''491490''>as</span>
  <span m=''491710''>abstract</span> <span m=''491930''>space.</span> <span m=''493310''>Normally,</span>
  <span m=''494570''>most</span> <span m=''494880''>of</span> <span m=''494970''>this</span>
  <span m=''495080''>loops</span> <span m=''495390''>you</span> <span m=''495670''>look</span>
  <span m=''495840''>at</span> <span m=''496040''>you</span> <span m=''496470''>normalize</span>
  <span m=''496790''>to</span> <span m=''496840''>step</span> <span m=''497310''>one.</span>
  <span m=''497470''>So</span> <span m=''498080''>what</span> <span m=''498240''>that</span>
  <span m=''498430''>means</span> <span m=''498650''>is</span> <span m=''498870''>all</span>
  <span m=''499090''>the</span> <span m=''499260''>integer</span> <span m=''499380''>points</span>
  <span m=''499540''>in</span> <span m=''499880''>that</span> <span m=''500020''>space.</span>
  <span m=''502320''>So</span> <span m=''502420''>if</span> <span m=''502590''>you</span>
  <span m=''502680''>have</span> <span m=''503090''>a</span> <span m=''503120''>loop</span>
  <span m=''503360''>like</span> <span m=''503580''>this,</span> <span m=''504450''>y</span>
  <span m=''504840''>equals</span> <span m=''505030''>0</span> <span m=''505190''>to</span>
  <span m=''505350''>6,</span> <span m=''505590''>J</span> <span m=''505880''>equals</span>
  <span m=''506050''>1i</span> <span m=''506350''>to</span> <span m=''506550''>7.</span>
  <span m=''507600''>That''s</span> <span m=''507860''>the</span> <span m=''507950''>iteration</span>
  <span m=''508410''>space,</span> <span m=''508730''>there are</span> <span m=''508930''>two</span>
  <span m=''509040''>dimensions</span> <span m=''509180''>in</span> <span m=''509310''>there.</span>
  <span m=''511080''>The</span> <span m=''511260''>points</span> <span m=''511800''>that</span>
  <span m=''511990''>start</span> <span m=''512450''>iteration</span> <span m=''512830''>off</span>
  <span m=''513090''>because</span> <span m=''513780''>it''s</span> <span m=''514070''>not</span>
  <span m=''514150''>a</span> <span m=''514450''>rectangular</span> <span m=''514610''>space,</span>
  <span m=''515620''>it</span> <span m=''516080''>can</span> <span m=''516250''>have</span>
  <span m=''516630''>this</span> <span m=''516720''>structure</span> <span m=''517260''>because</span>
  <span m=''518980''>j''s</span> <span m=''519480''>go in</span> <span m=''519710''>triangular</span>
  <span m=''519970''>in</span> <span m=''520060''>here.</span> </p><p><span m=''522090''>So</span>
  <span m=''522360''>the</span> <span m=''522490''>way</span> <span m=''522820''>you</span>
  <span m=''523030''>can</span> <span m=''523120''>represent</span> <span m=''523460''>that</span>
  <span m=''523750''>is</span> <span m=''523920''>so</span> <span m=''524010''>you</span>
  <span m=''524130''>can</span> <span m=''524300''>represent</span> <span m=''524340''>iteration</span>
  <span m=''525000''>space</span> <span m=''525430''>by a</span> <span m=''525660''>vector</span>
  <span m=''526020''>i,</span> <span m=''526790''>and</span> <span m=''527550''>you</span>
  <span m=''527690''>can</span> <span m=''527920''>have</span> <span m=''528690''>each</span>
  <span m=''528990''>dimension</span> <span m=''529490''>or</span> <span m=''529600''>use</span>
  <span m=''529820''>two</span> <span m=''529950''>dimension.</span> <span m=''530340''>This</span>
  <span m=''530450''>was</span> <span m=''530580''>some</span> <span m=''530740''>i1,</span>
  <span m=''531130''>i2</span> <span m=''531410''>space in here.</span> <span m=''532370''>So
  you</span> <span m=''532460''>can</span> <span m=''532680''>represent</span> <span
  m=''532830''>it</span> <span m=''532980''>like</span> <span m=''533150''>that.</span>
  <span m=''534900''>It''s</span> <span m=''535200''>the</span> <span m=''535330''>notion</span>
  <span m=''535530''>of</span> <span m=''535690''>lexicographic</span> <span m=''536970''>ordering.</span>
  <span m=''537840''>That</span> <span m=''538090''>means</span> <span m=''538370''>if</span>
  <span m=''538570''>you</span> <span m=''538670''>execute</span> <span m=''539230''>the</span>
  <span m=''539330''>loop,</span> <span m=''539660''>what''s</span> <span m=''539910''>the</span>
  <span m=''540020''>order</span> <span m=''540410''>you''re</span> <span m=''540540''>going</span>
  <span m=''540710''>to</span> <span m=''540800''>receive</span> <span m=''540910''>this</span>
  <span m=''541040''>thing.</span> <span m=''541990''>If you</span> <span m=''542390''>execute</span>
  <span m=''542880''>this loop,</span> <span m=''543200''>what</span> <span m=''543340''>you
  are</span> <span m=''543500''>going</span> <span m=''543730''>to</span> <span m=''543840''>do
  is</span> <span m=''544060''>you</span> <span m=''544180''>go</span> <span m=''544370''>from</span>
  <span m=''544990''>--</span> <span m=''546010''>you</span> <span m=''546160''>go</span>
  <span m=''546330''>like</span> <span m=''546560''>this.</span> <span m=''547590''>This</span>
  <span m=''547830''>is</span> <span m=''548090''>lexicographical</span> <span m=''548700''>ordering</span>
  <span m=''549230''>of</span> <span m=''549810''>everything in the</span> <span m=''549890''>loops.</span>
  <span m=''552070''>That''s</span> <span m=''552520''>the</span> <span m=''552610''>normal</span>
  <span m=''552950''>execution</span> <span m=''553210''>order.</span> <span m=''553440''>That''s</span>
  <span m=''553990''>a</span> <span m=''554060''>sequential</span> <span m=''554540''>order.</span>
  <span m=''555440''>At</span> <span m=''555530''>some</span> <span m=''555750''>point</span>
  <span m=''555960''>you</span> <span m=''556020''>want to</span> <span m=''556180''>make</span>
  <span m=''556400''>sure</span> <span m=''556580''>that</span> <span m=''556720''>anything</span>
  <span m=''557060''>we</span> <span m=''557230''>do</span> <span m=''557740''>kind</span>
  <span m=''557940''>of</span> <span m=''558680''>has</span> <span m=''558870''>a</span>
  <span m=''558930''>look</span> <span m=''559160''>and</span> <span m=''559310''>feel</span>
  <span m=''559660''>of</span> <span m=''559750''>the</span> <span m=''560060''>sequential</span>
  <span m=''560210''>lexicographical</span> <span m=''560790''>order.</span> </p><p><span
  m=''563430''>So,</span> <span m=''564350''>one</span> <span m=''564660''>thing</span>
  <span m=''564830''>you</span> <span m=''564920''>can</span> <span m=''565120''>say</span>
  <span m=''565410''>is</span> <span m=''566190''>if</span> <span m=''566410''>you</span>
  <span m=''566480''>have</span> <span m=''566750''>multiple</span> <span m=''567440''>dimensions,</span>
  <span m=''568270''>if</span> <span m=''570110''>there</span> <span m=''570270''>are
  two</span> <span m=''570570''>iterations,</span> <span m=''571330''>one</span> <span
  m=''571520''>iteration</span> <span m=''573610''>lexicographical</span> <span m=''574200''>and</span>
  <span m=''574570''>another</span> <span m=''574810''>iterations</span> <span m=''575260''>says</span>
  <span m=''575910''>if</span> <span m=''576410''>all</span> <span m=''576790''>outer</span>
  <span m=''577180''>dimensions</span> <span m=''577740''>are</span> <span m=''577880''>the</span>
  <span m=''577970''>same,</span> <span m=''578330''>you</span> <span m=''578490''>go</span>
  <span m=''578740''>to</span> <span m=''578840''>the</span> <span m=''578990''>first</span>
  <span m=''579890''>dimension</span> <span m=''580490''>where</span> <span m=''581450''>the</span>
  <span m=''581590''>numbers,</span> <span m=''582320''>they</span> <span m=''582400''>are
  in</span> <span m=''582700''>two</span> <span m=''582840''>different</span> <span
  m=''583320''>iterations.</span> <span m=''584650''>Then</span> <span m=''585210''>that</span>
  <span m=''585450''>dictates</span> <span m=''586490''>if</span> <span m=''586610''>it''s</span>
  <span m=''586960''>lexicographical</span> <span m=''587160''>than</span> <span m=''587330''>the
  other.</span> <span m=''588790''>So</span> <span m=''588930''>if the outer</span>
  <span m=''589790''>dimensions</span> <span m=''590310''>are</span> <span m=''590470''>the</span>
  <span m=''590610''>same,</span> <span m=''591200''>that</span> <span m=''591370''>means</span>
  <span m=''591570''>the</span> <span m=''591650''>next</span> <span m=''591840''>one</span>
  <span m=''591960''>decides, the</span> <span m=''592290''>next</span> <span m=''592480''>one</span>
  <span m=''592580''>decides,</span> <span m=''592840''>next</span> <span m=''593010''>one</span>
  <span m=''593120''>decides</span> <span m=''593470''>going down.</span> <span m=''594610''>First</span>
  <span m=''594870''>one</span> <span m=''595010''>that''s</span> <span m=''595150''>actually</span>
  <span m=''595420''>different</span> <span m=''595840''>decides</span> <span m=''596340''>who''s</span>
  <span m=''596620''>before</span> <span m=''597000''>the</span> <span m=''597100''>other</span>
  <span m=''597310''>one.</span> </p><p><span m=''600630''>So</span> <span m=''600840''>another</span>
  <span m=''601170''>concept</span> <span m=''601660''>is</span> <span m=''602230''>called</span>
  <span m=''602500''>affine</span> <span m=''603020''>loop nest.</span> <span m=''603840''>Affine</span>
  <span m=''604300''>loop nest</span> <span m=''604730''>says</span> <span m=''605420''>loop</span>
  <span m=''606050''>bounds are</span> <span m=''606460''>integer</span> <span m=''606940''>linear</span>
  <span m=''607080''>functions</span> <span m=''607820''>of</span> <span m=''608770''>constants,</span>
  <span m=''610830''>loop</span> <span m=''611150''>constant</span> <span m=''611590''>variable</span>
  <span m=''611840''>and</span> <span m=''612090''>outer</span> <span m=''612220''>loop</span>
  <span m=''612750''>indices.</span> <span m=''614200''>So</span> <span m=''614350''>that</span>
  <span m=''614620''>means</span> <span m=''615120''>if</span> <span m=''615310''>you</span>
  <span m=''615760''>want</span> <span m=''615940''>to</span> <span m=''616000''>get</span>
  <span m=''616130''>affine</span> <span m=''616500''>function</span> <span m=''616810''>within</span>
  <span m=''617100''>a loop,</span> <span m=''617950''>that</span> <span m=''618300''>has</span>
  <span m=''618500''>to</span> <span m=''618620''>be</span> <span m=''618850''>a</span>
  <span m=''618900''>linear</span> <span m=''619230''>function</span> <span m=''620090''>or</span>
  <span m=''620360''>integer</span> <span m=''620600''>function</span> <span m=''621370''>where</span>
  <span m=''621780''>all</span> <span m=''622070''>the</span> <span m=''622340''>things</span>
  <span m=''622590''>either</span> <span m=''622780''>has</span> <span m=''622990''>to</span>
  <span m=''623120''>be</span> <span m=''624060''>constant</span> <span m=''625720''>or</span>
  <span m=''626250''>loop</span> <span m=''626500''>constants --</span> <span m=''626950''>that</span>
  <span m=''627130''>means</span> <span m=''627260''>that</span> <span m=''627460''>that</span>
  <span m=''627640''>variable</span> <span m=''627980''>doesn''t</span> <span m=''628190''>change
  in</span> <span m=''628530''>the</span> <span m=''628640''>loop</span> <span m=''629160''>or</span>
  <span m=''629760''>outer</span> <span m=''629860''>loop</span> <span m=''630190''>indices.</span>
  <span m=''630940''>That</span> <span m=''631630''>makes</span> <span m=''631860''>it</span>
  <span m=''631970''>much</span> <span m=''632200''>easier</span> <span m=''632480''>to</span>
  <span m=''632750''>analyze.</span> <span m=''635550''>Also,</span> <span m=''635820''>array</span>
  <span m=''636160''>axises,</span> <span m=''636970''>each</span> <span m=''638300''>dimension,</span>
  <span m=''639000''>axis</span> <span m=''639310''>function</span> <span m=''639690''>has</span>
  <span m=''639890''>the</span> <span m=''639970''>same</span> <span m=''640260''>property.</span>
  </p><p><span m=''641430''>So of</span> <span m=''641580''>course,</span> <span m=''642350''>there</span>
  <span m=''642660''>are</span> <span m=''642730''>many</span> <span m=''643610''>programs</span>
  <span m=''644040''>that</span> <span m=''644170''>doesn''t</span> <span m=''644430''>satisfy</span>
  <span m=''644670''>this,</span> <span m=''645020''>for</span> <span m=''645130''>example,</span>
  <span m=''645490''>if</span> <span m=''645570''>we</span> <span m=''645670''>do</span>
  <span m=''645880''>FFD.</span> <span m=''646730''>That</span> <span m=''646870''>doesn''t</span>
  <span m=''647100''>satisfy</span> <span m=''647430''>that</span> <span m=''647640''>because</span>
  <span m=''647940''>you</span> <span m=''648070''>have</span> <span m=''648450''>exponentials</span>
  <span m=''648790''>in</span> <span m=''648880''>there.</span> <span m=''650390''>But</span>
  <span m=''650700''>what</span> <span m=''650860''>that</span> <span m=''651060''>means</span>
  <span m=''651350''>is</span> <span m=''651460''>at</span> <span m=''651600''>50,</span>
  <span m=''652310''>there''s</span> <span m=''652560''>probably</span> <span m=''652820''>no</span>
  <span m=''653470''>way</span> <span m=''653750''>that the</span> <span m=''654050''>compiler''s</span>
  <span m=''654470''>going to</span> <span m=''654780''>analyze that.</span> <span
  m=''655620''>But</span> <span m=''656030''>most</span> <span m=''656920''>kind</span>
  <span m=''657180''>of</span> <span m=''657290''>loops</span> <span m=''657640''>fit</span>
  <span m=''658040''>this</span> <span m=''658520''>kind</span> <span m=''658720''>of</span>
  <span m=''658800''>model</span> <span m=''659480''>and</span> <span m=''660510''>then</span>
  <span m=''661060''>you</span> <span m=''661170''>can</span> <span m=''661330''>put</span>
  <span m=''661550''>into</span> <span m=''661880''>nice</span> <span m=''662120''>mathematical</span>
  <span m=''662620''>framework</span> <span m=''662970''>and</span> <span m=''663120''>analyze</span>
  <span m=''663480''>that</span> <span m=''663740''>what</span> <span m=''663910''>I''m</span>
  <span m=''664030''>going to</span> <span m=''664200''>go</span> <span m=''664350''>through</span>
  <span m=''664540''>is</span> <span m=''665140''>kind</span> <span m=''665400''>of</span>
  <span m=''665480''>follow</span> <span m=''665840''>through</span> <span m=''666050''>some</span>
  <span m=''666260''>of</span> <span m=''666340''>the</span> <span m=''666470''>mathematical</span>
  <span m=''666930''>framework</span> <span m=''667210''>with</span> <span m=''667320''>you
  guys.</span> </p><p><span m=''670280''>So,</span> <span m=''670910''>what</span>
  <span m=''671110''>you</span> <span m=''671210''>can</span> <span m=''671440''>do</span>
  <span m=''671630''>here</span> <span m=''672470''>is if</span> <span m=''672550''>you</span>
  <span m=''672650''>look</span> <span m=''672780''>at</span> <span m=''672930''>this</span>
  <span m=''673200''>one,</span> <span m=''673780''>instead</span> <span m=''674100''>of</span>
  <span m=''675540''>representing</span> <span m=''676500''>this</span> <span m=''676760''>iteration</span>
  <span m=''677650''>space</span> <span m=''677920''>by</span> <span m=''678020''>each</span>
  <span m=''678300''>iteration,</span> <span m=''679610''>which</span> <span m=''680280''>can</span>
  <span m=''680560''>be</span> <span m=''680680''>huge</span> <span m=''681280''>or</span>
  <span m=''681620''>which is</span> <span m=''681970''>not</span> <span m=''682240''>even</span>
  <span m=''682560''>known</span> <span m=''682790''>at</span> <span m=''682880''>compile</span>
  <span m=''683020''>time,</span> <span m=''683650''>what</span> <span m=''683960''>you</span>
  <span m=''684040''>can</span> <span m=''684250''>do</span> <span m=''684330''>is</span>
  <span m=''684500''>you can</span> <span m=''685050''>represent</span> <span m=''685570''>this</span>
  <span m=''685810''>by</span> <span m=''687430''>kind</span> <span m=''687770''>of</span>
  <span m=''687830''>a</span> <span m=''687890''>bounding</span> <span m=''688620''>space</span>
  <span m=''689470''>of iterations,</span> <span m=''690130''>basically.</span> <span
  m=''691800''>So</span> <span m=''691990''>what</span> <span m=''692150''>this</span>
  <span m=''692490''>is,</span> <span m=''692610''>we</span> <span m=''692840''>don''t</span>
  <span m=''693420''>mark</span> <span m=''693680''>every</span> <span m=''694240''>box
  there,</span> <span m=''694830''>but we say</span> <span m=''695270''>OK,</span>
  <span m=''695500''>look,</span> <span m=''695990''>if you</span> <span m=''696150''>put</span>
  <span m=''696440''>these</span> <span m=''696710''>planes --</span> <span m=''697160''>I</span>
  <span m=''697240''>put</span> <span m=''697660''>four</span> <span m=''698010''>planes</span>
  <span m=''698200''>in</span> <span m=''698920''>here, and</span> <span m=''699110''>everything</span>
  <span m=''699600''>inside</span> <span m=''700010''>these</span> <span m=''700130''>planes</span>
  <span m=''700650''>represent</span> <span m=''700790''>this</span> <span m=''701100''>iteration</span>
  <span m=''701240''>space.</span> <span m=''703120''>That''s</span> <span m=''703310''>nice</span>
  <span m=''703580''>because</span> <span m=''704360''>instead</span> <span m=''704610''>of</span>
  <span m=''704840''>going</span> <span m=''705370''>0</span> <span m=''705540''>to</span>
  <span m=''705660''>6,</span> <span m=''706030''>if</span> <span m=''706270''>you</span>
  <span m=''706350''>go</span> <span m=''706480''>0</span> <span m=''706610''>to</span>
  <span m=''706850''>60,000,</span> <span m=''708420''>still</span> <span m=''709370''>I</span>
  <span m=''709540''>have</span> <span m=''709760''>the</span> <span m=''709900''>same</span>
  <span m=''710080''>equation,</span> <span m=''710400''>I</span> <span m=''710520''>don''t</span>
  <span m=''710640''>suddenly</span> <span m=''711010''>have</span> <span m=''712080''>6</span>
  <span m=''712340''>million</span> <span m=''713210''>data</span> <span m=''713510''>points</span>
  <span m=''713780''>in here</span> <span m=''714210''>I need to represent.</span>
  <span m=''715370''>So,</span> <span m=''715940''>my</span> <span m=''716280''>representation</span>
  <span m=''717490''>doesn''t</span> <span m=''717820''>grow</span> <span m=''718560''>with</span>
  <span m=''718730''>the</span> <span m=''718830''>size</span> <span m=''719180''>of</span>
  <span m=''719940''>my</span> <span m=''720230''>iteration</span> <span m=''720660''>space.
  It</span> <span m=''721650''>grows</span> <span m=''722090''>with</span> <span m=''722250''>the</span>
  <span m=''722360''>shape</span> <span m=''722720''>of</span> <span m=''722820''>this
  iteration space.</span> <span m=''723500''>If</span> <span m=''723790''>you</span>
  <span m=''723940''>have</span> <span m=''724030''>complicated</span> <span m=''724280''>one,</span>
  <span m=''724700''>it</span> <span m=''724880''>can</span> <span m=''725050''>be</span>
  <span m=''725140''>difficult.</span> </p><p><span m=''726590''>So</span> <span m=''726750''>what</span>
  <span m=''726920''>you</span> <span m=''726990''>can</span> <span m=''727180''>do</span>
  <span m=''727280''>is</span> <span m=''727470''>you</span> <span m=''727550''>can</span>
  <span m=''727710''>iteration</span> <span m=''728130''>space,</span> <span m=''728480''>it''s</span>
  <span m=''728630''>all</span> <span m=''728890''>iterations</span> <span m=''730060''>zero</span>
  <span m=''730270''>to</span> <span m=''730390''>six,</span> <span m=''731000''>j''s</span>
  <span m=''731620''>I27.</span> <span m=''733140''>This is</span> <span m=''733290''>all
  linear</span> <span m=''733540''>functionns.</span> <span m=''736240''>That</span>
  <span m=''736380''>makes</span> <span m=''736510''>our</span> <span m=''736630''>analysis</span>
  <span m=''736940''>easier.</span> <span m=''738530''>So</span> <span m=''738740''>the</span>
  <span m=''739390''>flip</span> <span m=''739750''>side</span> <span m=''739860''>of</span>
  <span m=''740060''>that</span> <span m=''740170''>is the</span> <span m=''740220''>data</span>
  <span m=''740360''>space.</span> <span m=''741570''>So,</span> <span m=''741950''>if</span>
  <span m=''742230''>m</span> <span m=''742330''>dimension</span> <span m=''742990''>array</span>
  <span m=''743330''>has</span> <span m=''743700''>m</span> <span m=''743830''>dimensional</span>
  <span m=''744200''>discrete</span> <span m=''744500''>cartesian</span> <span m=''744800''>space.</span>
  <span m=''747290''>Basically,</span> <span m=''748160''>in the</span> <span m=''748260''>data
  space</span> <span m=''748890''>you</span> <span m=''749000''>don''t</span> <span
  m=''749220''>have</span> <span m=''749690''>arrays</span> <span m=''750100''>that</span>
  <span m=''750280''>are</span> <span m=''750520''>odd shaped.</span> <span m=''751240''>It''s</span>
  <span m=''751440''>almost</span> <span m=''751610''>a</span> <span m=''751900''>hypercube</span>
  <span m=''752820''>always.</span> <span m=''754420''>So</span> <span m=''755800''>something</span>
  <span m=''756090''>like</span> <span m=''756280''>that</span> <span m=''756580''>is</span>
  <span m=''756670''>a</span> <span m=''756760''>one</span> <span m=''756920''>dimensional</span>
  <span m=''757350''>space</span> <span m=''758240''>and</span> <span m=''758790''>something</span>
  <span m=''759080''>can</span> <span m=''759240''>be</span> <span m=''759330''>represented</span>
  <span m=''759720''>as a</span> <span m=''760020''>two</span> <span m=''760130''>dimensional</span>
  <span m=''761010''>space in here.</span> <span m=''762470''>So</span> <span m=''763510''>data</span>
  <span m=''764050''>space</span> <span m=''764220''>has this</span> <span m=''764630''>nice</span>
  <span m=''764860''>property,</span> <span m=''765210''>in that</span> <span m=''765460''>sense</span>
  <span m=''765670''>it''s</span> <span m=''765840''>a</span> <span m=''765990''>t</span>
  <span m=''766610''>multi-dimensional</span> <span m=''767230''>hypercube.</span>
  <span m=''768140''>And</span> <span m=''768480''>what</span> <span m=''768580''>that</span>
  <span m=''768830''>gives you</span> <span m=''769110''>is</span> <span m=''769270''>kind</span>
  <span m=''769510''>of</span> <span m=''769610''>a</span> <span m=''769890''>bunch</span>
  <span m=''770530''>of</span> <span m=''771290''>mathematical</span> <span m=''772080''>techniques</span>
  <span m=''773190''>to</span> <span m=''773300''>kind</span> <span m=''773660''>of</span>
  <span m=''773780''>do</span> <span m=''773920''>and</span> <span m=''774140''>at</span>
  <span m=''774310''>least</span> <span m=''774390''>see some</span> <span m=''774660''>transformations</span>
  <span m=''775600''>we</span> <span m=''775720''>need</span> <span m=''776000''>to</span>
  <span m=''776070''>do</span> <span m=''776150''>in compiling.</span> </p><p><span
  m=''779570''>As</span> <span m=''779850''>humans,</span> <span m=''779980''>I</span>
  <span m=''780130''>think</span> <span m=''780420''>we can</span> <span m=''780790''>look</span>
  <span m=''780970''>at</span> <span m=''781160''>a lot  more</span> <span m=''781280''>complicated</span>
  <span m=''781470''>loops</span> <span m=''781970''>by</span> <span m=''782080''>hand,</span>
  <span m=''783470''>and</span> <span m=''784670''>get</span> <span m=''784790''>a</span>
  <span m=''784850''>better</span> <span m=''785080''>idea</span> <span m=''785350''>what''s</span>
  <span m=''785520''>going</span> <span m=''785780''>on.</span> <span m=''786320''>But
  in</span> <span m=''786510''>a</span> <span m=''786580''>compiler</span> <span m=''787020''>you</span>
  <span m=''787110''>need</span> <span m=''787300''>to</span> <span m=''787380''>have</span>
  <span m=''787610''>a</span> <span m=''787670''>very</span> <span m=''787920''>simple</span>
  <span m=''788200''>way</span> <span m=''788460''>of</span> <span m=''788850''>describing</span>
  <span m=''789330''>what</span> <span m=''789960''>to</span> <span m=''790080''>analyze,</span>
  <span m=''790340''>what to</span> <span m=''790570''>formulate,</span> <span m=''791280''>and</span>
  <span m=''791550''>having</span> <span m=''791910''>this</span> <span m=''792110''>model</span>
  <span m=''792810''>helps</span> <span m=''793210''>you</span> <span m=''793540''>put</span>
  <span m=''793750''>it</span> <span m=''793850''>into</span> <span m=''794020''>a</span>
  <span m=''794050''>nice</span> <span m=''794250''>mathematical</span> <span m=''794690''>frame</span>
  <span m=''794900''>you</span> <span m=''795080''>can do.</span> </p><p><span m=''797250''>So</span>
  <span m=''797400''>the</span> <span m=''797480''>next</span> <span m=''797690''>thing
  is</span> <span m=''797820''>dependence. We</span> <span m=''798500''>have</span>
  <span m=''798690''>done</span> <span m=''798880''>that</span> <span m=''799040''>so</span>
  <span m=''799140''>I</span> <span m=''799250''>will</span> <span m=''799360''>go</span>
  <span m=''799580''>through</span> <span m=''799760''>this</span> <span m=''799860''>fast.</span>
  <span m=''800520''>So</span> <span m=''800670''>the</span> <span m=''800770''>first</span>
  <span m=''801010''>is a true</span> <span m=''801430''>dependence.</span> <span
  m=''802330''>What</span> <span m=''802470''>that</span> <span m=''802710''>means</span>
  <span m=''803230''>is</span> <span m=''803620''>I</span> <span m=''803720''>wrote</span>
  <span m=''803940''>something,</span> <span m=''804300''>I write</span> <span m=''804430''>it</span>
  <span m=''804490''>here.</span> <span m=''805890''>So I</span> <span m=''806040''>really</span>
  <span m=''806880''>meant</span> <span m=''807320''>that</span> <span m=''807460''>I</span>
  <span m=''807600''>actually</span> <span m=''807750''>really</span> <span m=''807920''>use</span>
  <span m=''808180''>that</span> <span m=''808270''>value.</span> <span m=''809860''>There</span>
  <span m=''810120''>are two</span> <span m=''810260''>dependences</span> <span m=''811410''>mainly</span>
  <span m=''812020''>because</span> <span m=''812420''>we are</span> <span m=''813720''>finding</span>
  <span m=''814020''>dependence</span> <span m=''814590''>on</span> <span m=''814790''>some</span>
  <span m=''814880''>location,</span> <span m=''815700''>is</span> <span m=''816070''>an</span>
  <span m=''816130''>anti-dependence.</span> <span m=''817050''>That</span> <span
  m=''817250''>means</span> <span m=''817390''>I can''t</span> <span m=''817910''>write</span>
  <span m=''818160''>it</span> <span m=''818350''>until</span> <span m=''818610''>this</span>
  <span m=''818970''>read is</span> <span m=''819490''>done</span> <span m=''819870''>because</span>
  <span m=''820110''>I</span> <span m=''820520''>can''t</span> <span m=''820740''>destroy</span>
  <span m=''820990''>the value.</span> <span m=''821460''>Output</span> <span m=''821890''>dependence</span>
  <span m=''822400''>is there,</span> <span m=''822520''>so</span> <span m=''822730''>ordering</span>
  <span m=''823240''>of</span> <span m=''823470''>writing</span> <span m=''824160''>that</span>
  <span m=''824390''>you</span> <span m=''824480''>need to</span> <span m=''824680''>maintain.</span>
  </p><p><span m=''828010''>So</span> <span m=''829770''>in</span> <span m=''830120''>a</span>
  <span m=''830210''>dynamic</span> <span m=''830710''>instance,</span> <span m=''831010''>data</span>
  <span m=''831350''>dependence</span> <span m=''831770''>exist</span> <span m=''833380''>between</span>
  <span m=''833840''>i and j</span> <span m=''833960''>if</span> <span m=''835300''>Either</span>
  <span m=''836140''>i and j</span> <span m=''836760''>is</span> <span m=''836860''>a</span>
  <span m=''837100''>write</span> <span m=''837240''>operation,</span> <span m=''838250''>and</span>
  <span m=''838650''>i and j</span> <span m=''838810''>refers</span> <span m=''839130''>to</span>
  <span m=''839240''>the</span> <span m=''839550''>same</span> <span m=''839840''>variable,</span>
  <span m=''840180''>and</span> <span m=''840410''>i</span> <span m=''840930''>executes</span>
  <span m=''841180''>before</span> <span m=''841470''>j.</span> <span m=''841780''>So</span>
  <span m=''842090''>it''s</span> <span m=''842370''>the</span> <span m=''842810''>same</span>
  <span m=''843120''>thing,</span> <span m=''843940''>one</span> <span m=''844170''>execute</span>
  <span m=''844560''>before</span> <span m=''844840''>the other.</span> <span m=''845590''>So</span>
  <span m=''846070''>it''s</span> <span m=''846230''>not that</span> <span m=''846460''>you</span>
  <span m=''846550''>don''t</span> <span m=''846740''>have</span> <span m=''846900''>a</span>
  <span m=''846970''>dependence</span> <span m=''847470''>when they get</span> <span
  m=''847650''>there</span> <span m=''847730''>in</span> <span m=''848120''>time,</span>
  <span m=''848650''>then</span> <span m=''849030''>it</span> <span m=''849110''>become</span>
  <span m=''849400''>either</span> <span m=''849570''>true</span> <span m=''849900''>or</span>
  <span m=''850130''>anti.</span> <span m=''850680''>So</span> <span m=''851260''>it''s</span>
  <span m=''851400''>always</span> <span m=''851760''>going to</span> <span m=''852100''>be
  positive</span> <span m=''852230''>over</span> <span m=''852360''>time.</span> </p><p><span
  m=''857150''>So</span> <span m=''857330''>how</span> <span m=''857460''>about other</span>
  <span m=''857610''>accesses?</span> <span m=''859050''>So one</span> <span m=''859420''>element,</span>
  <span m=''860290''>you</span> <span m=''860440''>can</span> <span m=''860600''>figure</span>
  <span m=''860830''>out</span> <span m=''860930''>what</span> <span m=''861110''>happened.</span>
  <span m=''861930''>So how</span> <span m=''862310''>do you</span> <span m=''862400''>do</span>
  <span m=''862600''>dependence</span> <span m=''862830''>and</span> <span m=''862950''>other</span>
  <span m=''863120''>accesses?</span> <span m=''863890''>Now things</span> <span m=''864400''>get
  a</span> <span m=''864590''>little</span> <span m=''864710''>bit</span> <span m=''864800''>complicated,</span>
  <span m=''865230''>because</span> <span m=''865560''>arrays</span> <span m=''865840''>is</span>
  <span m=''866040''>not</span> <span m=''866210''>one</span> <span m=''866400''>element.</span>
  <span m=''868210''>So</span> <span m=''868410''>that''s</span> <span m=''868650''>when</span>
  <span m=''868810''>you</span> <span m=''868930''>go</span> <span m=''869030''>to</span>
  <span m=''869130''>dependence</span> <span m=''869640''>analysis.</span> <span m=''872660''>So</span>
  <span m=''873140''>I</span> <span m=''873230''>will</span> <span m=''873770''>describe</span>
  <span m=''874310''>this</span> <span m=''874510''>using</span> <span m=''874810''>bunch</span>
  <span m=''875080''>of</span> <span m=''875140''>examples.</span> <span m=''876620''>So</span>
  <span m=''876780''>in</span> <span m=''876920''>order</span> <span m=''877090''>to</span>
  <span m=''877150''>look</span> <span m=''877380''>at</span> <span m=''877590''>arrays,</span>
  <span m=''878600''>there</span> <span m=''878750''>are</span> <span m=''878800''>two</span>
  <span m=''879140''>spaces</span> <span m=''879460''>I</span> <span m=''879520''>need
  to</span> <span m=''879710''>worry</span> <span m=''879920''>about.</span> <span
  m=''880960''>One</span> <span m=''881180''>is</span> <span m=''881300''>the</span>
  <span m=''881380''>iteration</span> <span m=''881860''>space,</span> <span m=''882600''>one</span>
  <span m=''882810''>is</span> <span m=''882890''>the</span> <span m=''882980''>data</span>
  <span m=''883120''>space.</span> <span m=''884930''>What</span> <span m=''885170''>we</span>
  <span m=''885340''>want</span> <span m=''885590''>to</span> <span m=''885680''>do</span>
  <span m=''885850''>is</span> <span m=''886400''>figure</span> <span m=''886880''>out</span>
  <span m=''887160''>what</span> <span m=''887450''>happens</span> <span m=''887980''>at</span>
  <span m=''888810''>every</span> <span m=''889410''>iteration</span> <span m=''890420''>for</span>
  <span m=''890550''>data</span> <span m=''891010''>and</span> <span m=''891210''>what
  other</span> <span m=''891460''>dependences</span> <span m=''892470''>kind</span>
  <span m=''892620''>of</span> <span m=''892700''>summarize</span> <span m=''893090''>this</span>
  <span m=''893200''>down.</span> <span m=''895020''>We</span> <span m=''895240''>don''t</span>
  <span m=''895430''>want</span> <span m=''895560''>to</span> <span m=''895670''>look</span>
  <span m=''895800''>at,</span> <span m=''895920''>say</span> <span m=''896080''>OK,</span>
  <span m=''896890''>one</span> <span m=''897720''>iteration</span> <span m=''898040''>depend</span>
  <span m=''898190''>on</span> <span m=''898320''>second,</span> <span m=''898700''>two</span>
  <span m=''898850''>depend</span> <span m=''899070''>on</span> <span m=''899170''>third
  --</span> <span m=''899540''>you</span> <span m=''899620''>don''t</span> <span m=''899780''>want</span>
  <span m=''899920''>to</span> <span m=''900140''>list</span> <span m=''900470''>everything.</span>
  <span m=''901090''>We</span> <span m=''901190''>need</span> <span m=''901330''>to</span>
  <span m=''901390''>come</span> <span m=''901510''>up</span> <span m=''901610''>with</span>
  <span m=''901680''>a</span> <span m=''901760''>summary --</span> <span m=''902390''>that''s</span>
  <span m=''902610''>what</span> <span m=''902970''>basically</span> <span m=''903300''>dependence</span>
  <span m=''903690''>analysis will</span> <span m=''904170''>do.</span> </p><p><span
  m=''905300''>So</span> <span m=''905470''>if</span> <span m=''905670''>you</span>
  <span m=''905790''>have this</span> <span m=''906030''>access,</span> <span m=''906800''>this</span>
  <span m=''906960''>is</span> <span m=''907430''>this loop.</span> <span m=''908110''>What</span>
  <span m=''908370''>happens</span> <span m=''908740''>is</span> <span m=''909400''>as
  we</span> <span m=''909850''>run</span> <span m=''910290''>down,</span> <span m=''911110''>so</span>
  <span m=''911300''>iterations</span> <span m=''911730''>we</span> <span m=''911800''>are</span>
  <span m=''912000''>running</span> <span m=''912250''>down</span> <span m=''912490''>here.</span>
  <span m=''912970''>So</span> <span m=''913150''>we</span> <span m=''913250''>have</span>
  <span m=''913400''>iteration</span> <span m=''913820''>zero,</span> <span m=''914220''>1,</span>
  <span m=''914660''>2,</span> <span m=''914900''>3,</span> <span m=''915140''>4,</span>
  <span m=''915400''>5.</span> <span m=''915760''>First</span> <span m=''915990''>do</span>
  <span m=''916210''>the</span> <span m=''916350''>read,</span> <span m=''916690''>write,</span>
  <span m=''917000''>read,</span> <span m=''917270''>write.</span> <span m=''918040''>So</span>
  <span m=''918120''>this is</span> <span m=''918250''>kind</span> <span m=''918480''>of</span>
  <span m=''918580''>time</span> <span m=''919110''>going</span> <span m=''919360''>down
  there.</span> <span m=''920440''>What</span> <span m=''920730''>you do</span> <span
  m=''921100''>is</span> <span m=''921320''>this</span> <span m=''921620''>one</span>
  <span m=''923530''>you are</span> <span m=''923860''>reading</span> <span m=''924300''>and</span>
  <span m=''924470''>you</span> <span m=''924660''>are</span> <span m=''924800''>writing.</span>
  <span m=''925730''>You''re</span> <span m=''926000''>reading</span> <span m=''926370''>and</span>
  <span m=''926520''>writing,</span> <span m=''927200''>so</span> <span m=''927300''>you</span>
  <span m=''927430''>have</span> <span m=''927680''>a</span> <span m=''927760''>dependence</span>
  <span m=''928200''>like</span> <span m=''928390''>that.</span> <span m=''929690''>You</span>
  <span m=''929760''>see</span> <span m=''929870''>the</span> <span m=''929980''>two</span>
  <span m=''930210''>anti-dependence.</span> <span m=''934410''>Read --</span> <span
  m=''935280''>anti-dependence,</span> <span m=''935920''>I</span> <span m=''935990''>have</span>
  <span m=''936270''>anti-dependence</span> <span m=''936760''>going on here.</span>
  <span m=''938090''>If you look</span> <span m=''938480''>at it,</span> <span m=''938800''>here''s
  a</span> <span m=''939000''>dependence</span> <span m=''939500''>vector.</span>
  <span m=''939690''>What</span> <span m=''939850''>that</span> <span m=''939990''>means</span>
  <span m=''940200''>is</span> <span m=''940620''>there''s</span> <span m=''940770''>a</span>
  <span m=''940860''>dependence</span> <span m=''941250''>at</span> <span m=''941320''>each</span>
  <span m=''941880''>of</span> <span m=''942060''>those</span> <span m=''942270''>things</span>
  <span m=''942790''>in</span> <span m=''943160''>there --</span> <span m=''943280''>that''s</span>
  <span m=''943470''>anti-dependence</span> <span m=''943800''>going on.</span> </p><p><span
  m=''945870''>One</span> <span m=''946130''>way to</span> <span m=''946370''>look</span>
  <span m=''946450''>at</span> <span m=''946640''>summarizes</span> <span m=''947090''>of</span>
  <span m=''947360''>this,</span> <span m=''947630''>what</span> <span m=''947910''>is</span>
  <span m=''948140''>my</span> <span m=''948460''>iteration.</span> <span m=''949020''>My</span>
  <span m=''949220''>iteration</span> <span m=''950330''>goes</span> <span m=''950720''>like
  --</span> <span m=''950930''>what''s</span> <span m=''951090''>my</span> <span m=''951400''>dependence.</span>
  <span m=''952210''>I</span> <span m=''952410''>have</span> <span m=''952580''>anti-dependence</span>
  <span m=''953130''>with</span> <span m=''953440''>the</span> <span m=''953550''>same</span>
  <span m=''953790''>iteration,</span> <span m=''955830''>because</span> <span m=''956280''>my</span>
  <span m=''956530''>read</span> <span m=''956670''>and</span> <span m=''956910''>write</span>
  <span m=''957540''>has</span> <span m=''957740''>to</span> <span m=''957830''>be</span>
  <span m=''957970''>dependence</span> <span m=''958100''>in the</span> <span m=''958520''>same</span>
  <span m=''958710''>iteration.</span> <span m=''959990''>So</span> <span m=''960110''>this
  is</span> <span m=''960180''>a way to</span> <span m=''960540''>kind</span> <span
  m=''960750''>of</span> <span m=''960820''>describe that.</span> </p><p><span m=''961990''>So</span>
  <span m=''962330''>a</span> <span m=''962480''>different one.</span> <span m=''965890''>This</span>
  <span m=''966180''>one.</span> <span m=''967060''>I</span> <span m=''967260''>did</span>
  <span m=''967510''>Ai</span> <span m=''968080''>plus</span> <span m=''968400''>1</span>
  <span m=''969630''>equals</span> <span m=''970140''>Ai</span> <span m=''971000''>So</span>
  <span m=''971120''>what</span> <span m=''971290''>you</span> <span m=''971410''>realize</span>
  <span m=''971830''>is</span> <span m=''972420''>iteration</span> <span m=''973350''>zero,</span>
  <span m=''973780''>you</span> <span m=''974070''>wrote</span> <span m=''975020''>iteration</span>
  <span m=''975440''>zero,</span> <span m=''975540''>you</span> <span m=''975850''>wrote</span>
  <span m=''976520''>a</span> <span m=''976750''>zero,</span> <span m=''978570''>you</span>
  <span m=''978880''>read</span> <span m=''979060''>these</span> <span m=''979520''>and</span>
  <span m=''979690''>you</span> <span m=''979750''>wrote</span> <span m=''980130''>A1,</span>
  <span m=''980910''>and</span> <span m=''981540''>iteration</span> <span m=''982130''>1,</span>
  <span m=''982600''>you</span> <span m=''982880''>read</span> <span m=''983360''>A1</span>
  <span m=''984270''>and</span> <span m=''984550''>wrote</span> <span m=''984890''>A2,</span>
  <span m=''987100''>basically.</span> <span m=''988820''>Now</span> <span m=''989040''>what</span>
  <span m=''989220''>you</span> <span m=''989320''>have</span> <span m=''989650''>is</span>
  <span m=''989840''>your</span> <span m=''990270''>dependence</span> <span m=''990870''>is</span>
  <span m=''991000''>like</span> <span m=''991210''>that,</span> <span m=''992100''>going
  like</span> <span m=''992300''>that.</span> <span m=''994600''>So</span> <span m=''994730''>if
  you</span> <span m=''995000''>look</span> <span m=''995180''>at</span> <span m=''995370''>what''s</span>
  <span m=''995740''>happening</span> <span m=''996220''>in here,</span> <span m=''996890''>if
  you</span> <span m=''997090''>summarize</span> <span m=''997590''>in here,</span>
  <span m=''998190''>what</span> <span m=''998620''>you</span> <span m=''998720''>have</span>
  <span m=''998830''>is a</span> <span m=''999040''>dependence</span> <span m=''999640''>going</span>
  <span m=''999890''>like</span> <span m=''1000090''>that</span> <span m=''1000670''>in
  iteration</span> <span m=''1001190''>space.</span> <span m=''1002960''>So</span>
  <span m=''1003120''>in</span> <span m=''1003260''>iteration</span> <span m=''1003560''>that</span>
  <span m=''1003910''>means</span> <span m=''1004340''>iteration</span> <span m=''1004650''>1</span>
  <span m=''1005240''>is</span> <span m=''1005610''>actually</span> <span m=''1005960''>these</span>
  <span m=''1006300''>two</span> <span m=''1006550''>dependence,</span> <span m=''1007320''>that</span>
  <span m=''1007960''>uses</span> <span m=''1008240''>something</span> <span m=''1008540''>that</span>
  <span m=''1008650''>wrote</span> <span m=''1008970''>iteration</span> <span m=''1009130''>zero,</span>
  <span m=''1010230''>iteration</span> <span m=''1010400''>2 you have</span> <span
  m=''1010630''>something</span> <span m=''1011050''>iteration</span> <span m=''1011480''>1,</span>
  <span m=''1012040''>and you</span> <span m=''1012660''>have</span> <span m=''1013410''>iteration</span>
  <span m=''1014030''>going like that.</span> <span m=''1015530''>Sometimes</span>
  <span m=''1015990''>this</span> <span m=''1016100''>can</span> <span m=''1016290''>be</span>
  <span m=''1016360''>summarized</span> <span m=''1016910''>as</span> <span m=''1017180''>the</span>
  <span m=''1018920''>dependence</span> <span m=''1019240''>vector</span> <span m=''1019600''>of</span>
  <span m=''1019750''>1.</span> <span m=''1025750''>Because</span> <span m=''1027340''>the</span>
  <span m=''1027520''>previous</span> <span m=''1027890''>one</span> <span m=''1028060''>was</span>
  <span m=''1028120''>zero</span> <span m=''1029200''>because</span> <span m=''1029390''>there''s</span>
  <span m=''1029730''>no</span> <span m=''1030500''>loop</span> <span m=''1030700''>carry</span>
  <span m=''1031050''>dependency.</span> <span m=''1031480''>In</span> <span m=''1031670''>the</span>
  <span m=''1031820''>outer</span> <span m=''1032260''>loop there''s</span> <span
  m=''1032580''>a</span> <span m=''1032670''>dependence</span> <span m=''1033130''>on</span>
  <span m=''1033530''>1.</span> <span m=''1033650''>So</span> <span m=''1036670''>if</span>
  <span m=''1036850''>you</span> <span m=''1036920''>have</span> <span m=''1037120''>this</span>
  <span m=''1037400''>one,</span> <span m=''1037730''>I</span> <span m=''1037880''>plus</span>
  <span m=''1038260''>2,</span> <span m=''1039760''>of</span> <span m=''1039870''>course,</span>
  <span m=''1040130''>it</span> <span m=''1040500''>gets</span> <span m=''1041850''>carried</span>
  <span m=''1042210''>1</span> <span m=''1043090''>across in here</span> <span m=''1044150''>and</span>
  <span m=''1044420''>then</span> <span m=''1044550''>you</span> <span m=''1044670''>have</span>
  <span m=''1044910''>a</span> <span m=''1044960''>1</span> <span m=''1045300''>skipped</span>
  <span m=''1046510''>representation</span> <span m=''1047600''>in here.</span> <span
  m=''1050080''>If</span> <span m=''1050230''>you</span> <span m=''1050300''>have</span>
  <span m=''1050510''>2I2</span> <span m=''1050930''>by</span> <span m=''1051050''>plus</span>
  <span m=''1051500''>1,</span> <span m=''1051620''>what</span> <span m=''1051820''>you</span>
  <span m=''1051920''>realize</span> <span m=''1052320''>is</span> <span m=''1052990''>there''s</span>
  <span m=''1053210''>no</span> <span m=''1053360''>overlap.</span> <span m=''1054370''>So</span>
  <span m=''1054520''>there''s</span> <span m=''1054710''>no</span> <span m=''1054840''>basically</span>
  <span m=''1055530''>dependency.</span> <span m=''1058840''>You</span> <span m=''1058960''>kind</span>
  <span m=''1059150''>of</span> <span m=''1059230''>get</span> <span m=''1060250''>how</span>
  <span m=''1060400''>that</span> <span m=''1060540''>analytic</span> <span m=''1060720''>goes.</span>
  </p><p><span m=''1062040''>So,</span> <span m=''1063340''>to</span> <span m=''1063430''>find</span>
  <span m=''1064000''>data</span> <span m=''1064370''>dependence</span> <span m=''1064570''>in</span>
  <span m=''1064850''>a</span> <span m=''1064970''>loop,</span> <span m=''1066220''>so</span>
  <span m=''1066430''>there''s</span> <span m=''1066710''>a little bit of</span> <span
  m=''1066910''>legalese.</span> <span m=''1067530''>So</span> <span m=''1067750''>let</span>
  <span m=''1067880''>me</span> <span m=''1067980''>try to do that.</span> <span m=''1068520''>So</span>
  <span m=''1068700''>for</span> <span m=''1068810''>every</span> <span m=''1069100''>pair</span>
  <span m=''1069290''>of</span> <span m=''1069730''>array</span> <span m=''1069910''>accesses,</span>
  <span m=''1073610''>what</span> <span m=''1073870''>you</span> <span m=''1073960''>want
  to</span> <span m=''1074220''>find</span> <span m=''1074530''>is</span> <span m=''1075850''>is
  there</span> <span m=''1076080''>a</span> <span m=''1076470''>dynamic</span> <span
  m=''1076990''>instant</span> <span m=''1077520''>that</span> <span m=''1077670''>happened?</span>
  <span m=''1079940''>An</span> <span m=''1080900''>iteration</span> <span m=''1080990''>that</span>
  <span m=''1081200''>wrote</span> <span m=''1081530''>a</span> <span m=''1082790''>value,</span>
  <span m=''1083370''>and</span> <span m=''1084060''>another</span> <span m=''1084370''>dynamic</span>
  <span m=''1084640''>instance</span> <span m=''1085320''>happened</span> <span m=''1085590''>that</span>
  <span m=''1085720''>later</span> <span m=''1086110''>that</span> <span m=''1086260''>actually</span>
  <span m=''1086610''>used</span> <span m=''1086840''>that</span> <span m=''1086960''>value.</span>
  <span m=''1088240''>So</span> <span m=''1088400''>the</span> <span m=''1088520''>first</span>
  <span m=''1088820''>access,</span> <span m=''1090570''>so</span> <span m=''1090670''>there''s
  a</span> <span m=''1090840''>dynamic</span> <span m=''1091300''>instance</span>
  <span m=''1091690''>that''s</span> <span m=''1092120''>wrote,</span> <span m=''1093120''>or</span>
  <span m=''1093280''>that</span> <span m=''1093830''>access,</span> <span m=''1094750''>and</span>
  <span m=''1094940''>another</span> <span m=''1096160''>iteration</span> <span m=''1097050''>instance</span>
  <span m=''1097820''>that</span> <span m=''1098060''>also</span> <span m=''1098460''>accessed</span>
  <span m=''1098770''>the</span> <span m=''1098840''>same</span> <span m=''1099130''>location</span>
  <span m=''1099620''>later.</span> <span m=''1100250''>And</span> <span m=''1100350''>one</span>
  <span m=''1100530''>of</span> <span m=''1100630''>them</span> <span m=''1100780''>has</span>
  <span m=''1100910''>to</span> <span m=''1100980''>be</span> <span m=''1101090''>right,</span>
  <span m=''1101600''>otherwise</span> <span m=''1101980''>there</span> <span m=''1102090''>are</span>
  <span m=''1102200''>two</span> <span m=''1102310''>in anti.</span> <span m=''1103930''>That''s</span>
  <span m=''1104130''>the</span> <span m=''1104170''>notion</span> <span m=''1104520''>about</span>
  <span m=''1104930''>the</span> <span m=''1105090''>second</span> <span m=''1105330''>one</span>
  <span m=''1105450''>came</span> <span m=''1105860''>after</span> <span m=''1106000''>the</span>
  <span m=''1106320''>first</span> <span m=''1106410''>one.</span> <span m=''1108350''>You</span>
  <span m=''1108430''>can</span> <span m=''1108590''>also</span> <span m=''1108950''>look</span>
  <span m=''1109210''>at the</span> <span m=''1109300''>same</span> <span m=''1109630''>arrays.</span>
  <span m=''1110000''>It</span> <span m=''1110130''>doesn''t</span> <span m=''1110360''>have</span>
  <span m=''1110480''>the</span> <span m=''1110720''>be</span> <span m=''1111120''>the
  same</span> <span m=''1111390''>as</span> <span m=''1111470''>different</span> <span
  m=''1111620''>access,</span> <span m=''1112140''>the</span> <span m=''1112270''>same</span>
  <span m=''1112530''>array</span> <span m=''1112650''>access</span> <span m=''1113030''>if
  you are</span> <span m=''1113160''>writing.</span> <span m=''1113510''>If</span>
  <span m=''1114180''>you</span> <span m=''1114290''>look</span> <span m=''1114460''>at</span>
  <span m=''1114630''>same array</span> <span m=''1114870''>access</span> <span m=''1115150''>writing</span>
  <span m=''1115490''>you</span> <span m=''1115640''>can</span> <span m=''1115800''>have</span>
  <span m=''1116150''>output</span> <span m=''1116250''>dependences</span> <span m=''1116500''>also.</span>
  <span m=''1117370''>So</span> <span m=''1117720''>it''s</span> <span m=''1118010''>basically</span>
  <span m=''1118610''>between</span> <span m=''1119430''>a</span> <span m=''1119490''>read</span>
  <span m=''1119730''>and</span> <span m=''1119830''>a</span> <span m=''1119930''>write,</span>
  <span m=''1121190''>and</span> <span m=''1121320''>a</span> <span m=''1121470''>write</span>
  <span m=''1121580''>and</span> <span m=''1121850''>a</span> <span m=''1122420''>write.</span>
  <span m=''1122590''>Two</span> <span m=''1122680''>different</span> <span m=''1122880''>writes,</span>
  <span m=''1123210''>it can</span> <span m=''1123370''>be</span> <span m=''1123430''>the</span>
  <span m=''1123510''>same</span> <span m=''1123820''>write too.</span> </p><p><span
  m=''1125600''>Key</span> <span m=''1126160''>thing</span> <span m=''1126340''>is</span>
  <span m=''1126410''>we are</span> <span m=''1126610''>looking</span> <span m=''1126700''>at</span>
  <span m=''1126880''>location.</span> <span m=''1127590''>We''re</span> <span m=''1127770''>not</span>
  <span m=''1127980''>looking</span> <span m=''1128190''>at value</span> <span m=''1128410''>path
  and</span> <span m=''1128770''>say</span> <span m=''1128880''>who''s</span> <span
  m=''1129120''>actually</span> <span m=''1129310''>in the</span> <span m=''1129500''>same</span>
  <span m=''1129690''>location.</span> <span m=''1132560''>Loop</span> <span m=''1132970''>carry</span>
  <span m=''1133180''>dependence</span> <span m=''1133820''>means</span> <span m=''1134160''>the</span>
  <span m=''1134290''>dependence</span> <span m=''1135360''>cross</span> <span m=''1135800''>a</span>
  <span m=''1135930''>loop</span> <span m=''1136080''>boundary.</span> <span m=''1137790''>That</span>
  <span m=''1138050''>means</span> <span m=''1138520''>the</span> <span m=''1138640''>person</span>
  <span m=''1138960''>who</span> <span m=''1139090''>read</span> <span m=''1141130''>and
  person</span> <span m=''1141560''>who</span> <span m=''1141700''>wrote</span> <span
  m=''1142480''>are</span> <span m=''1142710''>in</span> <span m=''1143100''>different</span>
  <span m=''1144070''>loop</span> <span m=''1144370''>iteration.</span> <span m=''1146040''>If
  it''s</span> <span m=''1146200''>in the</span> <span m=''1146410''>same</span> <span
  m=''1146550''>iteration,</span> <span m=''1147160''>then</span> <span m=''1147290''>it''s</span>
  <span m=''1147390''>all</span> <span m=''1147500''>local,</span> <span m=''1147970''>because</span>
  <span m=''1148290''>in</span> <span m=''1148390''>my</span> <span m=''1148540''>iteration</span>
  <span m=''1148880''>I</span> <span m=''1148960''>deal</span> <span m=''1149080''>with</span>
  <span m=''1149200''>that,</span> <span m=''1149720''>I</span> <span m=''1149880''>moved</span>
  <span m=''1150160''>data</span> <span m=''1150390''>around.</span> <span m=''1150570''>But</span>
  <span m=''1151090''>what</span> <span m=''1151320''>I''m</span> <span m=''1151480''>writing</span>
  <span m=''1151800''>is</span> <span m=''1151890''>used</span> <span m=''1151980''>by</span>
  <span m=''1152260''>somebody</span> <span m=''1152610''>else</span> <span m=''1152820''>in</span>
  <span m=''1152920''>different</span> <span m=''1153300''>iteration,</span> <span
  m=''1153570''>I</span> <span m=''1153610''>have</span> <span m=''1153810''>loop</span>
  <span m=''1154040''>carry</span> <span m=''1154270''>dependence</span> <span m=''1154640''>going
  on.</span> <span m=''1158220''>Basic</span> <span m=''1158570''>thing</span> <span
  m=''1158850''>is</span> <span m=''1159100''>there''s</span> <span m=''1159260''>a</span>
  <span m=''1159350''>loop</span> <span m=''1159650''>carry</span> <span m=''1159790''>dependence,</span>
  <span m=''1160430''>that</span> <span m=''1160580''>loop</span> <span m=''1160700''>is</span>
  <span m=''1160880''>not</span> <span m=''1161020''>parallelized</span> <span m=''1161180''>in
  that.</span> <span m=''1163650''>What</span> <span m=''1163810''>that</span> <span
  m=''1164060''>means</span> <span m=''1164600''>is</span> <span m=''1165200''>I</span>
  <span m=''1165350''>am</span> <span m=''1165580''>writing</span> <span m=''1166080''>in
  one</span> <span m=''1166250''>iteration</span> <span m=''1166750''>of the</span>
  <span m=''1166850''>loop</span> <span m=''1167120''>and</span> <span m=''1167220''>somebody</span>
  <span m=''1167530''>is</span> <span m=''1167680''>reading</span> <span m=''1167980''>in</span>
  <span m=''1168120''>different</span> <span m=''1168550''>iteration</span> <span
  m=''1168830''>of</span> <span m=''1168910''>the</span> <span m=''1169000''>loop.</span>
  <span m=''1169630''>That</span> <span m=''1169840''>means</span> <span m=''1170080''>I
  actually</span> <span m=''1170330''>had to</span> <span m=''1170500''>move</span>
  <span m=''1170720''>the</span> <span m=''1170790''>data</span> <span m=''1171080''>across,</span>
  <span m=''1171420''>they</span> <span m=''1171780''>can</span> <span m=''1171960''>happen</span>
  <span m=''1172160''>in</span> <span m=''1172310''>parallel.</span> <span m=''1173340''>That''s</span>
  <span m=''1173500''>a</span> <span m=''1173600''>very</span> <span m=''1173760''>simple
  way of</span> <span m=''1174080''>looking at that.</span> </p><p><span m=''1177930''>So,</span>
  <span m=''1180260''>what</span> <span m=''1180500''>we</span> <span m=''1180590''>have</span>
  <span m=''1180810''>done</span> <span m=''1181070''>is --</span> <span m=''1181510''>OK,</span>
  <span m=''1181890''>the</span> <span m=''1182600''>basic</span> <span m=''1183030''>idea
  is</span> <span m=''1183390''>how</span> <span m=''1183610''>to</span> <span m=''1183740''>actually</span>
  <span m=''1184030''>go</span> <span m=''1184340''>and</span> <span m=''1184550''>automate</span>
  <span m=''1184720''>this</span> <span m=''1184760''>process.</span> <span m=''1186740''>The</span>
  <span m=''1186810''>simple</span> <span m=''1187020''>notion</span> <span m=''1187540''>is</span>
  <span m=''1187640''>called</span> <span m=''1187860''>a</span> <span m=''1188030''>data</span>
  <span m=''1188090''>dependence</span> <span m=''1188490''>analysis,</span> <span
  m=''1188940''>and</span> <span m=''1189050''>I</span> <span m=''1189110''>will</span>
  <span m=''1189530''>give</span> <span m=''1189780''>you</span> <span m=''1189880''>a</span>
  <span m=''1189940''>formulation</span> <span m=''1190440''>of</span> <span m=''1190550''>that.</span>
  <span m=''1191850''>So</span> <span m=''1191980''>what</span> <span m=''1192200''>you</span>
  <span m=''1192310''>can</span> <span m=''1192510''>formally</span> <span m=''1193140''>do</span>
  <span m=''1193450''>is</span> <span m=''1194250''>using</span> <span m=''1195160''>a
  set</span> <span m=''1195570''>of</span> <span m=''1195670''>equations.</span> <span
  m=''1197700''>So</span> <span m=''1197860''>what</span> <span m=''1198070''>you</span>
  <span m=''1198190''>want</span> <span m=''1198410''>to</span> <span m=''1198520''>say</span>
  <span m=''1199720''>is</span> <span m=''1199840''>instead</span> <span m=''1200140''>of</span>
  <span m=''1200300''>two</span> <span m=''1200540''>distinct</span> <span m=''1201140''>iterations,</span>
  <span m=''1201730''>one is the</span> <span m=''1202010''>write</span> <span m=''1202220''>iteration,</span>
  <span m=''1203110''>one</span> <span m=''1203240''>is</span> <span m=''1203320''>the</span>
  <span m=''1203420''>read</span> <span m=''1203560''>iteration.</span> <span m=''1206150''>One</span>
  <span m=''1206440''>iteration</span> <span m=''1206920''>writes</span> <span m=''1207280''>the</span>
  <span m=''1207370''>value,</span> <span m=''1207560''>one iteration</span> <span
  m=''1207950''>reads</span> <span m=''1208100''>the value.</span> <span m=''1209200''>So</span>
  <span m=''1209430''>write</span> <span m=''1209750''>iteration</span> <span m=''1210380''>basically,</span>
  <span m=''1211390''>writes</span> <span m=''1211930''>a</span> <span m=''1212600''>item</span>
  <span m=''1212760''>loop</span> <span m=''1213120''>plus</span> <span m=''1213390''>1,</span>
  <span m=''1214090''>the</span> <span m=''1214200''>read iteration</span> <span m=''1214830''>reads</span>
  <span m=''1215040''>AI.</span> <span m=''1216620''>So</span> <span m=''1216780''>we</span>
  <span m=''1217150''>know</span> <span m=''1217810''>both</span> <span m=''1218350''>read</span>
  <span m=''1218770''>and</span> <span m=''1219000''>write</span> <span m=''1219260''>have</span>
  <span m=''1219460''>to</span> <span m=''1219550''>be</span> <span m=''1219640''>within</span>
  <span m=''1220940''>loop bound iteration,</span> <span m=''1221490''>because</span>
  <span m=''1221830''>we</span> <span m=''1221970''>know</span> <span m=''1222080''>that</span>
  <span m=''1222750''>because</span> <span m=''1222920''>we</span> <span m=''1223000''>can''t</span>
  <span m=''1223240''>be</span> <span m=''1223360''>outside</span> <span m=''1223460''>loop
  bounds.</span> </p><p><span m=''1224920''>Then</span> <span m=''1225070''>we</span>
  <span m=''1225200''>also</span> <span m=''1226360''>want</span> <span m=''1226590''>to</span>
  <span m=''1226650''>make</span> <span m=''1226850''>sure</span> <span m=''1227080''>that</span>
  <span m=''1227640''>the</span> <span m=''1227930''>loop</span> <span m=''1228110''>carried</span>
  <span m=''1228410''>dependence,</span> <span m=''1228820''>that</span> <span m=''1229040''>means</span>
  <span m=''1229450''>read</span> <span m=''1229530''>and</span> <span m=''1229700''>write</span>
  <span m=''1229870''>can''t</span> <span m=''1230330''>be in</span> <span m=''1230430''>the</span>
  <span m=''1230510''>same</span> <span m=''1230740''>iteration.</span> <span m=''1231560''>If
  it''s in the</span> <span m=''1231910''>same</span> <span m=''1232190''>iteration,</span>
  <span m=''1232580''>I</span> <span m=''1232670''>don''t</span> <span m=''1232840''>have</span>
  <span m=''1233000''>loop</span> <span m=''1233220''>carry</span> <span m=''1233330''>dependence.</span>
  <span m=''1234120''>I am</span> <span m=''1234430''>looking</span> <span m=''1234700''>for</span>
  <span m=''1234830''>loop carry</span> <span m=''1234980''>dependence</span> <span
  m=''1235020''>at this point.</span> <span m=''1237070''>Then</span> <span m=''1237850''>what</span>
  <span m=''1238230''>makes</span> <span m=''1239400''>both</span> <span m=''1239720''>of</span>
  <span m=''1239820''>the</span> <span m=''1240420''>read and write</span> <span m=''1241250''>write</span>
  <span m=''1241380''>the same</span> <span m=''1241620''>location.</span> <span m=''1242790''>That</span>
  <span m=''1242960''>means</span> <span m=''1243120''>access</span> <span m=''1243450''>1</span>
  <span m=''1243540''>has to be</span> <span m=''1243870''>the</span> <span m=''1243960''>same.</span>
  <span m=''1244580''>So</span> <span m=''1244840''>the</span> <span m=''1244980''>right</span>
  <span m=''1245120''>access</span> <span m=''1245480''>point</span> <span m=''1245720''>is</span>
  <span m=''1246600''>iw</span> <span m=''1247040''>plus</span> <span m=''1247380''>1,</span>
  <span m=''1247910''>and</span> <span m=''1248030''>read</span> <span m=''1248270''>access</span>
  <span m=''1248550''>function</span> <span m=''1248940''>is</span> <span m=''1249610''>[?
  IEI. ?]</span> <span m=''1251330''>So</span> <span m=''1251870''>the</span> <span
  m=''1252080''>key</span> <span m=''1252310''>thing</span> <span m=''1252550''>is</span>
  <span m=''1252760''>now</span> <span m=''1252940''>we</span> <span m=''1253050''>have</span>
  <span m=''1253200''>set</span> <span m=''1253370''>up</span> <span m=''1253480''>equation.</span>
  <span m=''1255380''>Are there</span> <span m=''1255710''>any</span> <span m=''1256000''>values</span>
  <span m=''1256770''>for</span> <span m=''1256960''>ie</span> <span m=''1257190''>and</span>
  <span m=''1257490''>j,</span> <span m=''1258110''>integer</span> <span m=''1258330''>values,</span>
  <span m=''1259330''>I''m sorry,</span> <span m=''1259980''>iw</span> <span m=''1260100''>and</span>
  <span m=''1260420''>ir</span> <span m=''1261240''>that</span> <span m=''1261400''>these</span>
  <span m=''1261800''>equations</span> <span m=''1262100''>are</span> <span m=''1262340''>true.</span>
  <span m=''1263470''>If that is the case,</span> <span m=''1263640''>we</span> <span
  m=''1264100''>can</span> <span m=''1264400''>say ah-ha,</span> <span m=''1264610''>that
  is</span> <span m=''1264740''>the</span> <span m=''1264820''>case,</span> <span
  m=''1266140''>there''s</span> <span m=''1266490''>an</span> <span m=''1266900''>iteration</span>
  <span m=''1267530''>that</span> <span m=''1268760''>the</span> <span m=''1268860''>write</span>
  <span m=''1269200''>and</span> <span m=''1269380''>read</span> <span m=''1269880''>are</span>
  <span m=''1270250''>writing</span> <span m=''1270630''>into</span> <span m=''1271280''>two</span>
  <span m=''1271430''>different</span> <span m=''1271710''>iterations --</span> <span
  m=''1272220''>one</span> <span m=''1272460''>write</span> <span m=''1272680''>iteration,</span>
  <span m=''1273060''>one</span> <span m=''1273210''>read</span> <span m=''1273300''>iteration,</span>
  <span m=''1274200''>writing</span> <span m=''1274800''>to</span> <span m=''1275080''>the</span>
  <span m=''1275280''>same</span> <span m=''1275510''>value.</span> <span m=''1276970''>Therefore</span>
  <span m=''1277260''>that''s</span> <span m=''1277420''>a</span> <span m=''1277490''>different</span>
  <span m=''1278220''>[OBSCURED].</span> <span m=''1278460''>Is this</span> <span
  m=''1278640''>true?</span> <span m=''1278840''>Is there a</span> <span m=''1279060''>set
  of</span> <span m=''1279140''>values</span> <span m=''1279400''>that</span> <span
  m=''1279650''>makes</span> <span m=''1279860''>this</span> <span m=''1280030''>true?</span>
  </p><p><span m=''1288710''>Yeah,</span> <span m=''1288900''>I</span> <span m=''1288930''>mean</span>
  <span m=''1289050''>you</span> <span m=''1289140''>can</span> <span m=''1289380''>do</span>
  <span m=''1290770''>ir</span> <span m=''1291150''>equals</span> <span m=''1291530''>1,</span>
  <span m=''1292330''>iw</span> <span m=''1292840''>equals</span> <span m=''1293210''>1,</span>
  <span m=''1293480''>and</span> <span m=''1293670''>ir</span> <span m=''1293790''>equals</span>
  <span m=''1294350''>2.</span> <span m=''1296120''>So</span> <span m=''1296230''>there''s</span>
  <span m=''1296440''>a</span> <span m=''1296750''>value</span> <span m=''1296910''>in
  there</span> <span m=''1297200''>so</span> <span m=''1297330''>these equations</span>
  <span m=''1297820''>will</span> <span m=''1298350''>come</span> <span m=''1298530''>up</span>
  <span m=''1298670''>with</span> <span m=''1298770''>a</span> <span m=''1298820''>solution,</span>
  <span m=''1299240''>and</span> <span m=''1299470''>at</span> <span m=''1299930''>that</span>
  <span m=''1300040''>point</span> <span m=''1300250''>you</span> <span m=''1300330''>have
  a</span> <span m=''1300850''>dependency.</span> </p><p><span m=''1303560''>AUDIENCE:</span>
  <span m=''1303925''>[NOISE]</span> </p><p><span m=''1311670''>PROFESSOR: So</span>
  <span m=''1311930''>that''s</span> <span m=''1312760''>very</span> <span m=''1313210''>easy</span>
  <span m=''1313620''>to</span> <span m=''1313720''>make</span> <span m=''1314020''>this</span>
  <span m=''1314110''>formulation.</span> <span m=''1316260''>So if the</span> <span
  m=''1318040''>indices</span> <span m=''1318790''>is</span> <span m=''1319230''>calculated
  with some thing or</span> <span m=''1319620''>loop</span> <span m=''1320130''>value,</span>
  <span m=''1320250''>I can''t write the</span> <span m=''1320530''>formulation.</span>
  <span m=''1322670''>So</span> <span m=''1323280''>the data that</span> <span m=''1323680''>I</span>
  <span m=''1324010''>can</span> <span m=''1324220''>do</span> <span m=''1324290''>this</span>
  <span m=''1324450''>analysis</span> <span m=''1324730''>is</span> <span m=''1325840''>this</span>
  <span m=''1326210''>indices</span> <span m=''1327020''>has</span> <span m=''1327250''>to</span>
  <span m=''1327360''>be</span> <span m=''1327600''>the</span> <span m=''1327680''>constant</span>
  <span m=''1328340''>or</span> <span m=''1328520''>indefinite.</span> <span m=''1329110''>This</span>
  <span m=''1329270''>is</span> <span m=''1329530''>A</span> <span m=''1329840''>of</span>
  <span m=''1330100''>b</span> <span m=''1330320''>of</span> <span m=''1330480''>I.</span>
  <span m=''1331880''>So</span> <span m=''1332000''>if</span> <span m=''1332600''>my</span>
  <span m=''1333310''>array</span> <span m=''1333450''>is</span> <span m=''1333870''>A
  of b</span> <span m=''1334000''>of</span> <span m=''1334100''>i,</span> <span m=''1335910''>I</span>
  <span m=''1336320''>don''t</span> <span m=''1336540''>know</span> <span m=''1337360''>how
  the numbers</span> <span m=''1338120''>work</span> <span m=''1338360''>if you have</span>
  <span m=''1338650''>A of</span> <span m=''1338790''>b</span> <span m=''1338950''>i.</span>
  <span m=''1341790''>I</span> <span m=''1342110''>have</span> <span m=''1342310''>no</span>
  <span m=''1342490''>idea about</span> <span m=''1342630''>Ai</span> <span m=''1342850''>is</span>
  <span m=''1343950''>without</span> <span m=''1344520''>knowing</span> <span m=''1344810''>values</span>
  <span m=''1344960''>of</span> <span m=''1345140''>B of i.</span> <span m=''1345770''>And</span>
  <span m=''1345970''>B</span> <span m=''1346110''>of</span> <span m=''1346300''>i,</span>
  <span m=''1346660''>I can''t</span> <span m=''1347350''>summarize</span> <span m=''1347660''>it.</span>
  <span m=''1347780''>Each</span> <span m=''1348130''>B</span> <span m=''1348700''>of</span>
  <span m=''1349150''>i</span> <span m=''1349370''>might</span> <span m=''1349520''>be</span>
  <span m=''1349600''>different</span> <span m=''1350410''>and</span> <span m=''1350550''>I</span>
  <span m=''1350610''>can''t</span> <span m=''1350850''>come up with this</span> <span
  m=''1351330''>nice</span> <span m=''1351690''>single</span> <span m=''1351910''>formulation</span>
  <span m=''1352370''>that</span> <span m=''1352610''>can</span> <span m=''1352890''>check</span>
  <span m=''1353030''>out</span> <span m=''1353660''>every</span> <span m=''1354630''>B
  of i.</span> <span m=''1354750''>And I''m in</span> <span m=''1354880''>big trouble.</span>
  <span m=''1356330''>This</span> <span m=''1356450''>is</span> <span m=''1356640''>doable,</span>
  <span m=''1357060''>but</span> <span m=''1357280''>this</span> <span m=''1357430''>is</span>
  <span m=''1357550''>not</span> <span m=''1357760''>easy to do</span> <span m=''1358360''>like
  this.</span> <span m=''1370070''>Question?</span> </p><p><span m=''1370780''>AUDIENCE:</span>
  <span m=''1371345''>[NOISE]</span> </p><p><span m=''1373150''>PROFESSOR: Yeah,</span>
  <span m=''1373520''>that''s right.</span> <span m=''1374000''>So</span> <span m=''1374280''>that</span>
  <span m=''1375730''>the interesting</span> <span m=''1376170''>thing</span> <span
  m=''1376670''>that you''re</span> <span m=''1377180''>not looking at.</span> <span
  m=''1377800''>Because when we</span> <span m=''1378090''>summarized</span> <span
  m=''1378290''>it,</span> <span m=''1379740''>because</span> <span m=''1379890''>what
  you are</span> <span m=''1380040''>going</span> <span m=''1380260''>to</span> <span
  m=''1380400''>do</span> <span m=''1380500''>is</span> <span m=''1380690''>we</span>
  <span m=''1380870''>are</span> <span m=''1380990''>trying to</span> <span m=''1381080''>summarize</span>
  <span m=''1381520''>for</span> <span m=''1381820''>everything,</span> <span m=''1382400''>every</span>
  <span m=''1382710''>iteration,</span> <span m=''1383560''>and</span> <span m=''1384560''>we
  are not</span> <span m=''1384710''>trying to divide</span> <span m=''1385350''>it</span>
  <span m=''1385420''>into</span> <span m=''1385730''>saying</span> <span m=''1386170''>OK,</span>
  <span m=''1386570''>can</span> <span m=''1386790''>I</span> <span m=''1386860''>find</span>
  <span m=''1387120''>the</span> <span m=''1387250''>parallel</span> <span m=''1387600''>groups.</span>
  <span m=''1387860''>Yes.</span> <span m=''1388480''>You</span> <span m=''1388610''>can</span>
  <span m=''1388820''>do</span> <span m=''1388940''>some more</span> <span m=''1389450''>complicated</span>
  <span m=''1389820''>analysis</span> <span m=''1389880''>and</span> <span m=''1390220''>do</span>
  <span m=''1390340''>something</span> <span m=''1390640''>like</span> <span m=''1390780''>that.</span>
  <span m=''1391410''>Yes.</span> </p><p><span m=''1393060''>So</span> <span m=''1393600''>other</span>
  <span m=''1393820''>interesting</span> <span m=''1394190''>thing</span> <span m=''1394330''>is</span>
  <span m=''1394420''>OK,</span> <span m=''1394590''>the</span> <span m=''1394760''>next</span>
  <span m=''1395010''>thing</span> <span m=''1395180''>you</span> <span m=''1395290''>want
  to</span> <span m=''1395850''>see</span> <span m=''1396120''>whether</span> <span
  m=''1396640''>can</span> <span m=''1396810''>find</span> <span m=''1398180''>output</span>
  <span m=''1398360''>dependence.</span> <span m=''1400020''>OK,</span> <span m=''1400520''>are</span>
  <span m=''1400780''>there</span> <span m=''1400920''>two</span> <span m=''1401110''>different</span>
  <span m=''1401470''>iterations</span> <span m=''1401970''>that</span> <span m=''1402160''>they''re
  fighting</span> <span m=''1402570''>the</span> <span m=''1402660''>same</span> <span
  m=''1402960''>thing.</span> <span m=''1405360''>What</span> <span m=''1405530''>that</span>
  <span m=''1405710''>means</span> <span m=''1406000''>is</span> <span m=''1406220''>the</span>
  <span m=''1406430''>iterations</span> <span m=''1406690''>are</span> <span m=''1407600''>I1,</span>
  <span m=''1407980''>I2,</span> <span m=''1408840''>and</span> <span m=''1409160''>I1</span>
  <span m=''1409350''>not</span> <span m=''1409590''>equals</span> <span m=''1409900''>I2,</span>
  <span m=''1410860''>and</span> <span m=''1411190''>I1</span> <span m=''1411530''>plus</span>
  <span m=''1411720''>1 equals</span> <span m=''1412000''>I2</span> <span m=''1412120''>plus
  one.</span> <span m=''1413190''>There''s</span> <span m=''1413800''>no</span> <span
  m=''1414090''>solution</span> <span m=''1414260''>to this</span> <span m=''1414500''>one</span>
  <span m=''1415630''>because</span> <span m=''1416110''>the</span> <span m=''1416290''>I1</span>
  <span m=''1416730''>has</span> <span m=''1416900''>to</span> <span m=''1417020''>be</span>
  <span m=''1417120''>equal</span> <span m=''1417580''>to</span> <span m=''1417700''>I2</span>
  <span m=''1417940''>according</span> <span m=''1418000''>to this,</span> <span m=''1418490''>and</span>
  <span m=''1418640''>I1</span> <span m=''1418710''>cannot</span> <span m=''1418790''>be</span>
  <span m=''1418910''>equal</span> <span m=''1419150''>to</span> <span m=''1419340''>I2</span>
  <span m=''1419820''>during</span> <span m=''1420090''>this</span> <span m=''1420290''>one.</span>
  <span m=''1420400''>That</span> <span m=''1420600''>says</span> <span m=''1420740''>OK,</span>
  <span m=''1420940''>look,</span> <span m=''1421980''>I</span> <span m=''1422080''>don''t</span>
  <span m=''1422260''>have</span> <span m=''1422540''>output</span> <span m=''1422630''>dependence</span>
  <span m=''1423510''>because</span> <span m=''1424020''>it can be</span> <span m=''1424130''>satisfied.</span>
  <span m=''1425880''>OK,</span> <span m=''1426000''>so</span> <span m=''1426160''>here</span>
  <span m=''1426390''>I</span> <span m=''1426500''>know</span> <span m=''1426740''>I</span>
  <span m=''1426870''>have</span> <span m=''1427710''>a</span> <span m=''1428110''>loop</span>
  <span m=''1428350''>carried --</span> <span m=''1429880''>I</span> <span m=''1429980''>haven''t</span>
  <span m=''1430170''>said</span> <span m=''1430250''>the two</span> <span m=''1430620''>anti</span>
  <span m=''1431290''>depends</span> <span m=''1431650''>on</span> <span m=''1432060''>which</span>
  <span m=''1432220''>directions</span> <span m=''1432330''>this</span> <span m=''1432540''>is.</span>
  <span m=''1434370''>Two</span> <span m=''1434460''>anti-dependents,</span> <span
  m=''1435680''>but</span> <span m=''1435840''>I</span> <span m=''1435920''>don''t</span>
  <span m=''1436070''>have</span> <span m=''1436190''>a</span> <span m=''1436380''>loop</span>
  <span m=''1436620''>carried</span> <span m=''1436860''>out</span> <span m=''1437386''>to</span>
  <span m=''1437912''>[OBSCURED].</span> </p><p><span m=''1441070''>So</span> <span
  m=''1441260''>how</span> <span m=''1441510''>do</span> <span m=''1441730''>we</span>
  <span m=''1441950''>generalize</span> <span m=''1442290''>this?</span> <span m=''1442870''>So</span>
  <span m=''1443050''>what</span> <span m=''1443240''>you</span> <span m=''1443320''>can</span>
  <span m=''1443560''>do</span> <span m=''1443670''>is</span> <span m=''1443890''>as</span>
  <span m=''1443980''>integer</span> <span m=''1444210''>vector</span> <span m=''1444630''>I,</span>
  <span m=''1445390''>so</span> <span m=''1445700''>in</span> <span m=''1446260''>order</span>
  <span m=''1446410''>to</span> <span m=''1446730''>generalize</span> <span m=''1447120''>this,</span>
  <span m=''1447360''>you</span> <span m=''1447640''>can</span> <span m=''1447830''>use</span>
  <span m=''1447960''>integer</span> <span m=''1448290''>programming.</span> <span
  m=''1448940''>How</span> <span m=''1449050''>many</span> <span m=''1449210''>of</span>
  <span m=''1449360''>you</span> <span m=''1449750''>know integer programming</span>
  <span m=''1449820''>or</span> <span m=''1450630''>linear programming?</span> <span
  m=''1452260''>OK.</span> <span m=''1454390''>We</span> <span m=''1454620''>are</span>
  <span m=''1454870''>not going to</span> <span m=''1455130''>go</span> <span m=''1455280''>into</span>
  <span m=''1455510''>detail,</span> <span m=''1455880''>but</span> <span m=''1456930''>I''ll</span>
  <span m=''1457480''>tell</span> <span m=''1457950''>you</span> <span m=''1458190''>what</span>
  <span m=''1458350''>actually</span> <span m=''1458510''>happen.</span> <span m=''1459280''>So</span>
  <span m=''1459500''>integer</span> <span m=''1459940''>programming</span> <span
  m=''1460480''>says</span> <span m=''1461250''>there''s</span> <span m=''1461440''>a</span>
  <span m=''1461930''>vector</span> <span m=''1462320''>of</span> <span m=''1463350''>variable</span>
  <span m=''1464050''>I,</span> <span m=''1464740''>and</span> <span m=''1465220''>if</span>
  <span m=''1465410''>you</span> <span m=''1465500''>have</span> <span m=''1466180''>a</span>
  <span m=''1466580''>formulation</span> <span m=''1467230''>like</span> <span m=''1467490''>that,</span>
  <span m=''1468420''>is</span> <span m=''1468570''>array,</span> <span m=''1469030''>AI</span>
  <span m=''1469300''>is</span> <span m=''1469670''>less than or</span> <span m=''1469960''>equal</span>
  <span m=''1470150''>to</span> <span m=''1470490''>B,</span> <span m=''1471270''>A
  and</span> <span m=''1471740''>B</span> <span m=''1471920''>are</span> <span m=''1472110''>all</span>
  <span m=''1472360''>constant</span> <span m=''1472990''>integers,</span> <span m=''1473900''>and</span>
  <span m=''1476550''>you</span> <span m=''1476910''>can</span> <span m=''1477330''>use</span>
  <span m=''1477560''>the</span> <span m=''1477870''>integer</span> <span m=''1477990''>programming,</span>
  <span m=''1478230''>you</span> <span m=''1478480''>can</span> <span m=''1478810''>see</span>
  <span m=''1478950''>that there''s</span> <span m=''1479090''>a</span> <span m=''1479150''>solution</span>
  <span m=''1479660''>for</span> <span m=''1479990''>IE or</span> <span m=''1480130''>not.</span>
  <span m=''1482290''>This</span> <span m=''1482500''>is</span> <span m=''1483050''>if</span>
  <span m=''1483260''>you</span> <span m=''1483350''>do</span> <span m=''1483510''>things</span>
  <span m=''1483660''>like</span> <span m=''1483750''>operations</span> <span m=''1484190''>research,</span>
  <span m=''1484920''>there''s</span> <span m=''1485090''>a</span> <span m=''1485120''>lot</span>
  <span m=''1485380''>of</span> <span m=''1485500''>work</span> <span m=''1485710''>around</span>
  <span m=''1486020''>it.</span> <span m=''1486890''>People</span> <span m=''1487180''>actually</span>
  <span m=''1487590''>want</span> <span m=''1487800''>to</span> <span m=''1487880''>know</span>
  <span m=''1488000''>what</span> <span m=''1488210''>value</span> <span m=''1488400''>is</span>
  <span m=''1488540''>Y.</span> <span m=''1488810''>We</span> <span m=''1488940''>don''t</span>
  <span m=''1489160''>care</span> <span m=''1489350''>that</span> <span m=''1489540''>much</span>
  <span m=''1489710''>what</span> <span m=''1489900''>values,</span> <span m=''1490530''>we</span>
  <span m=''1490870''>just</span> <span m=''1491060''>want</span> <span m=''1491230''>to</span>
  <span m=''1491360''>know the</span> <span m=''1491530''>solution</span> <span m=''1492150''>or
  not.</span> <span m=''1493520''>If</span> <span m=''1493590''>there''s</span> <span
  m=''1493870''>a</span> <span m=''1494240''>solution,</span> <span m=''1494530''>we</span>
  <span m=''1494700''>know</span> <span m=''1495010''>that</span> <span m=''1495140''>there''s
  a dependent.</span> <span m=''1495600''>If</span> <span m=''1495690''>there''s</span>
  <span m=''1495860''>no</span> <span m=''1496040''>solution</span> <span m=''1496350''>we</span>
  <span m=''1496440''>know</span> <span m=''1496530''>there''s</span> <span m=''1496700''>no</span>
  <span m=''1496820''>dependent.</span> </p><p><span m=''1497520''>So</span> <span
  m=''1497680''>we need to</span> <span m=''1497810''>do</span> <span m=''1497930''>is</span>
  <span m=''1498470''>we</span> <span m=''1498560''>need to</span> <span m=''1498760''>get</span>
  <span m=''1498950''>this set</span> <span m=''1499130''>of equations and</span>
  <span m=''1499810''>put</span> <span m=''1499950''>it on</span> <span m=''1500260''>that</span>
  <span m=''1500430''>form.</span> <span m=''1502420''>That''s</span> <span m=''1502760''>simple.</span>
  <span m=''1503140''>For</span> <span m=''1503380''>example,</span> <span m=''1505480''>what</span>
  <span m=''1505900''>you</span> <span m=''1506020''>want</span> <span m=''1506840''>is</span>
  <span m=''1507110''>AI</span> <span m=''1507620''>less than</span> <span m=''1507860''>B
  --</span> <span m=''1508350''>that</span> <span m=''1508600''>means</span> <span
  m=''1508870''>you</span> <span m=''1508990''>have</span> <span m=''1510080''>constnat</span>
  <span m=''1510560''>A1</span> <span m=''1511100''>I1,</span> <span m=''1511770''>plus</span>
  <span m=''1512440''>A2</span> <span m=''1513300''>i2,</span> <span m=''1514230''>which
  is</span> <span m=''1514680''>less</span> <span m=''1514800''>than</span> <span
  m=''1514980''>or</span> <span m=''1515300''>equal</span> <span m=''1515430''>to</span>
  <span m=''1515860''>B.</span> <span m=''1519270''>So you</span> <span m=''1519440''>won''t</span>
  <span m=''1519670''>have</span> <span m=''1519870''>this</span> <span m=''1520040''>kind</span>
  <span m=''1520250''>of</span> <span m=''1520320''>a</span> <span m=''1521710''>system.</span>
  <span m=''1522500''>Not</span> <span m=''1522780''>equals</span> <span m=''1523050''>doesn''t</span>
  <span m=''1523500''>really</span> <span m=''1524310''>belong there.</span> <span
  m=''1527050''>So</span> <span m=''1527200''>the</span> <span m=''1527310''>way you
  deal</span> <span m=''1527940''>with</span> <span m=''1528050''>not</span> <span
  m=''1528280''>equals</span> <span m=''1528700''>if</span> <span m=''1528800''>you
  do</span> <span m=''1528920''>it</span> <span m=''1529010''>in</span> <span m=''1529260''>two</span>
  <span m=''1529390''>different</span> <span m=''1529750''>problems.</span> <span
  m=''1530770''>You</span> <span m=''1532060''>can say</span> <span m=''1532700''>IW</span>
  <span m=''1533200''>less</span> <span m=''1533470''>than</span> <span m=''1533630''>IER</span>
  <span m=''1534210''>is</span> <span m=''1534450''>one</span> <span m=''1534710''>problem,</span>
  <span m=''1535660''>and</span> <span m=''1537000''>W</span> <span m=''1537360''>is
  greater</span> <span m=''1537680''>then</span> <span m=''1537860''>IER</span> <span
  m=''1538190''>is</span> <span m=''1538340''>other</span> <span m=''1538610''>problem,</span>
  <span m=''1539340''>and</span> <span m=''1539460''>if</span> <span m=''1539590''>either</span>
  <span m=''1540040''>problem</span> <span m=''1540380''>has</span> <span m=''1540630''>a</span>
  <span m=''1540920''>solution,</span> <span m=''1541380''>you</span> <span m=''1541490''>have</span>
  <span m=''1541590''>a</span> <span m=''1541620''>dependence.</span> <span m=''1542070''>So</span>
  <span m=''1542300''>that</span> <span m=''1542620''>means</span> <span m=''1542820''>one
  is true and</span> <span m=''1543250''>one</span> <span m=''1543500''>is</span>
  <span m=''1543650''>anti.</span> <span m=''1544710''>You can</span> <span m=''1545070''>see</span>
  <span m=''1545170''>the</span> <span m=''1545340''>true dependence</span> <span
  m=''1545580''>or</span> <span m=''1545850''>anti-dependence,</span> <span m=''1546970''>you</span>
  <span m=''1547110''>can</span> <span m=''1547360''>look at that.</span> </p><p><span
  m=''1550580''>This</span> <span m=''1550890''>one</span> <span m=''1551030''>is
  a</span> <span m=''1551430''>little bit</span> <span m=''1551570''>easier.</span>
  <span m=''1552610''>This</span> <span m=''1552750''>is</span> <span m=''1552960''>less</span>
  <span m=''1553210''>than,</span> <span m=''1553770''>not</span> <span m=''1554180''>actually</span>
  <span m=''1554360''>less</span> <span m=''1554500''>than</span> <span m=''1554660''>--</span>
  <span m=''1556890''>less than</span> <span m=''1557390''>equal.</span> <span m=''1561900''>How</span>
  <span m=''1562100''>do you</span> <span m=''1562220''>deal with</span> <span m=''1562550''>equal?</span>
  <span m=''1564520''>So</span> <span m=''1564670''>the way</span> <span m=''1565320''>you</span>
  <span m=''1565520''>deal with equal</span> <span m=''1565680''>is</span> <span m=''1565800''>you</span>
  <span m=''1565900''>write</span> <span m=''1566140''>in</span> <span m=''1566270''>both</span>
  <span m=''1566400''>directions.</span> <span m=''1567330''>So</span> <span m=''1568190''>if</span>
  <span m=''1568760''>A</span> <span m=''1568910''>is</span> <span m=''1569080''>less
  than B,</span> <span m=''1570110''>A</span> <span m=''1570190''>less than or equal</span>
  <span m=''1570630''>to</span> <span m=''1570690''>B,</span> <span m=''1571000''>B
  is</span> <span m=''1571320''>less</span> <span m=''1571450''>than or</span> <span
  m=''1571630''>equal</span> <span m=''1571730''>to</span> <span m=''1571940''>A</span>
  <span m=''1572410''>means</span> <span m=''1572670''>actually</span> <span m=''1573120''>is
  equal</span> <span m=''1573340''>to</span> <span m=''1574110''>B.</span> <span m=''1574250''>So
  you can actually</span> <span m=''1574680''>try</span> <span m=''1574890''>two</span>
  <span m=''1575020''>different</span> <span m=''1575410''>inequalities</span> <span
  m=''1576490''>and</span> <span m=''1576700''>get</span> <span m=''1576810''>equal</span>
  <span m=''1577200''>to down there.</span> <span m=''1577840''>So</span> <span m=''1578210''>you</span>
  <span m=''1578340''>have</span> <span m=''1578450''>to</span> <span m=''1578520''>kind</span>
  <span m=''1578700''>of</span> <span m=''1578790''>massage</span> <span m=''1579300''>things</span>
  <span m=''1579570''>a little</span> <span m=''1579830''>bit</span> <span m=''1579940''>in</span>
  <span m=''1580630''>here.</span> <span m=''1580850''>So here</span> <span m=''1581110''>are</span>
  <span m=''1581310''>our</span> <span m=''1583300''>original</span> <span m=''1585470''>iteration</span>
  <span m=''1585940''>bounds,</span> <span m=''1586610''>and</span> <span m=''1586870''>here''s</span>
  <span m=''1587620''>our</span> <span m=''1588180''>one</span> <span m=''1588470''>problem</span>
  <span m=''1588900''>because</span> <span m=''1589340''>we are</span> <span m=''1589660''>saying</span>
  <span m=''1591440''>write</span> <span m=''1591840''>happens</span> <span m=''1592340''>before</span>
  <span m=''1592800''>read,</span> <span m=''1592990''>so</span> <span m=''1593090''>these
  are</span> <span m=''1593360''>two</span> <span m=''1593520''>dependents</span>
  <span m=''1593830''>that</span> <span m=''1593950''>we are</span> <span m=''1594090''>looking</span>
  <span m=''1594370''>at.</span> <span m=''1597050''>This</span> <span m=''1597190''>is</span>
  <span m=''1597370''>saying</span> <span m=''1597890''>that</span> <span m=''1601260''>write</span>
  <span m=''1602320''>location</span> <span m=''1602870''>is</span> <span m=''1602940''>the</span>
  <span m=''1603030''>same</span> <span m=''1603290''>as</span> <span m=''1603480''>the
  read</span> <span m=''1603620''>location</span> <span m=''1604290''>and</span> <span
  m=''1604470''>this is</span> <span m=''1604550''>equal,</span> <span m=''1605010''>so</span>
  <span m=''1605190''>I have two</span> <span m=''1605260''>different</span> <span
  m=''1605560''>equations</span> <span m=''1605950''>in here.</span> <span m=''1606930''>So</span>
  <span m=''1607110''>kind</span> <span m=''1607230''>of</span> <span m=''1607440''>massage</span>
  <span m=''1607850''>this</span> <span m=''1607980''>a</span> <span m=''1608040''>little</span>
  <span m=''1608310''>bit</span> <span m=''1608780''>to put it  in</span> <span m=''1609290''>i</span>
  <span m=''1609520''>form,</span> <span m=''1610030''>and</span> <span m=''1610150''>we</span>
  <span m=''1610230''>can</span> <span m=''1610370''>come</span> <span m=''1610510''>up</span>
  <span m=''1610620''>with</span> <span m=''1610730''>A''s and</span> <span m=''1611180''>B''s.</span>
  <span m=''1612840''>These</span> <span m=''1613420''>are just</span> <span m=''1613880''>manual</span>
  <span m=''1614870''>steps,</span> <span m=''1615100''>A''s</span> <span m=''1615630''>and</span>
  <span m=''1615850''>B''s, and</span> <span m=''1616370''>now</span> <span m=''1616490''>we
  are</span> <span m=''1616690''>going to</span> <span m=''1616900''>throw</span>
  <span m=''1617290''>it into</span> <span m=''1618450''>some</span> <span m=''1618880''>super</span>
  <span m=''1619170''>duper</span> <span m=''1620540''>integer</span> <span m=''1621850''>linear</span>
  <span m=''1622050''>program</span> <span m=''1623640''>package</span> <span m=''1624230''>and</span>
  <span m=''1624350''>it will</span> <span m=''1624430''>say</span> <span m=''1624800''>yes</span>
  <span m=''1625040''>or no</span> <span m=''1625250''>and your set.</span> </p><p><span
  m=''1628540''>And of</span> <span m=''1628730''>course,</span> <span m=''1628910''>you</span>
  <span m=''1628980''>had</span> <span m=''1629140''>to do</span> <span m=''1629290''>another</span>
  <span m=''1629440''>problem</span> <span m=''1629820''>for the</span> <span m=''1629950''>other</span>
  <span m=''1630130''>side.</span> <span m=''1632370''>You</span> <span m=''1632430''>can</span>
  <span m=''1632640''>generalize</span> <span m=''1632830''>it</span> <span m=''1633240''>for</span>
  <span m=''1633870''>much</span> <span m=''1634120''>more</span> <span m=''1635340''>complete</span>
  <span m=''1635720''>loop nest.</span> <span m=''1636560''>So if you</span> <span
  m=''1636890''>have this</span> <span m=''1637020''>complicated</span> <span m=''1637540''>loop
  nest</span> <span m=''1637820''>in</span> <span m=''1638270''>here,</span> <span
  m=''1638330''>you</span> <span m=''1638450''>had</span> <span m=''1638600''>to solve</span>
  <span m=''1639310''>you''ve got</span> <span m=''1639460''>n</span> <span m=''1639770''>deepness,</span>
  <span m=''1640080''>you have to</span> <span m=''1640360''>solve</span> <span m=''1640630''>two</span>
  <span m=''1640840''>end</span> <span m=''1641120''>problems</span> <span m=''1641950''>with</span>
  <span m=''1642140''>all</span> <span m=''1642310''>these</span> <span m=''1642560''>different</span>
  <span m=''1642840''>constraints.</span> <span m=''1643720''>I''m</span> <span m=''1643970''>not
  going to go</span> <span m=''1644060''>over</span> <span m=''1644180''>this.</span>
  <span m=''1644590''>I</span> <span m=''1645000''>have</span> <span m=''1645510''>the</span>
  <span m=''1645670''>slides</span> <span m=''1645880''>in here.</span> <span m=''1648090''>So</span>
  <span m=''1648230''>that''s</span> <span m=''1649820''>the</span> <span m=''1650380''>single</span>
  <span m=''1650770''>dimension.</span> </p><p><span m=''1651820''>So how about</span>
  <span m=''1652390''>multi-dimension</span> <span m=''1653100''>dependences?</span>
  <span m=''1655770''>So I</span> <span m=''1655840''>have</span> <span m=''1655970''>two</span>
  <span m=''1656790''>dimensional</span> <span m=''1657910''>iteration</span> <span
  m=''1658070''>space</span> <span m=''1658280''>here,</span> <span m=''1659050''>and</span>
  <span m=''1659540''>I</span> <span m=''1659580''>have</span> <span m=''1660150''>I,J</span>
  <span m=''1660920''>equals</span> <span m=''1661140''>AI,</span> <span m=''1662190''>J</span>
  <span m=''1662370''>minus</span> <span m=''1662740''>1.</span> <span m=''1663350''>That''s</span>
  <span m=''1663530''>my</span> <span m=''1664110''>iteration</span> <span m=''1664520''>space.</span>
  <span m=''1665140''>What</span> <span m=''1665350''>does</span> <span m=''1665530''>my</span>
  <span m=''1665640''>dependence</span> <span m=''1665980''>look</span> <span m=''1666320''>like?</span>
  <span m=''1667240''>We have</span> <span m=''1667420''>arrows</span> <span m=''1667660''>too.</span>
  <span m=''1678480''>Which</span> <span m=''1678710''>direction</span> <span m=''1678830''>are</span>
  <span m=''1678920''>the</span> <span m=''1679150''>arrows going?</span> </p><p><span
  m=''1679730''>AUDIENCE:</span> <span m=''1680270''>[OBSCURED]</span> </p><p><span
  m=''1682970''>PROFESSOR: We</span> <span m=''1683170''>have</span> <span m=''1683290''>something</span>
  <span m=''1683600''>like</span> <span m=''1683720''>this.</span> <span m=''1684840''>Yup.</span>
  <span m=''1686680''>We have</span> <span m=''1687170''>something</span> <span m=''1687480''>like</span>
  <span m=''1687630''>this</span> <span m=''1688040''>because</span> <span m=''1688710''>that''s</span>
  <span m=''1689480''>J</span> <span m=''1689800''>minus</span> <span m=''1690130''>1,</span>
  <span m=''1690640''>the</span> <span m=''1690990''>I''s are</span> <span m=''1691100''>the</span>
  <span m=''1691200''>same.</span> <span m=''1692470''>Of course,</span> <span m=''1693000''>if</span>
  <span m=''1693120''>you</span> <span m=''1693210''>have the</span> <span m=''1693390''>other</span>
  <span m=''1693620''>way</span> <span m=''1693780''>around,</span> <span m=''1696310''>go</span>
  <span m=''1696630''>other</span> <span m=''1696750''>direction,</span> <span m=''1697450''>one</span>
  <span m=''1697900''>is</span> <span m=''1698000''>anti</span> <span m=''1698380''>and</span>
  <span m=''1698570''>one</span> <span m=''1698710''>is</span> <span m=''1698810''>it</span>
  <span m=''1698930''>two</span> <span m=''1699050''>dependence,</span> <span m=''1699530''>so</span>
  <span m=''1699940''>you</span> <span m=''1700030''>can</span> <span m=''1700190''>figure</span>
  <span m=''1700360''>that</span> <span m=''1700540''>one</span> <span m=''1700660''>out.</span>
  <span m=''1702410''>And do</span> <span m=''1702540''>something</span> <span m=''1703050''>complicated.</span>
  <span m=''1703730''>First</span> <span m=''1703950''>one.</span> <span m=''1705670''>So</span>
  <span m=''1706030''>IJ,</span> <span m=''1707030''>I</span> <span m=''1707200''>minus</span>
  <span m=''1707460''>1,</span> <span m=''1707650''>J</span> <span m=''1707950''>plus</span>
  <span m=''1708560''>1.</span> <span m=''1710750''>Which</span> <span m=''1711760''>has</span>
  <span m=''1711990''>to</span> <span m=''1712070''>be</span> <span m=''1712140''>diagonal.</span>
  <span m=''1712580''>Which</span> <span m=''1712780''>diagonal</span> <span m=''1713210''>does
  it</span> <span m=''1713500''>go?</span> <span m=''1717910''>This</span> <span m=''1718290''>way</span>
  <span m=''1718640''>or this</span> <span m=''1718920''>way?</span> <span m=''1722900''>Who</span>
  <span m=''1723270''>says</span> <span m=''1723470''>this</span> <span m=''1723710''>way?</span>
  <span m=''1726910''>Who</span> <span m=''1727120''>says</span> <span m=''1727310''>this</span>
  <span m=''1727440''>way?</span> <span m=''1731820''>So,</span> <span m=''1732790''>this
  is</span> <span m=''1733090''>actually</span> <span m=''1733440''>going</span> <span
  m=''1733730''>in</span> <span m=''1736680''>this direction.</span> <span m=''1740630''>This
  is</span> <span m=''1741020''>where</span> <span m=''1741550''>you</span> <span
  m=''1741750''>have</span> <span m=''1741850''>to</span> <span m=''1742190''>actually</span>
  <span m=''1742330''>think which</span> <span m=''1742460''>iteration</span> <span
  m=''1742680''>is</span> <span m=''1742900''>actually</span> <span m=''1743220''>write</span>
  <span m=''1743630''>and</span> <span m=''1743930''>read</span> <span m=''1744340''>in</span>
  <span m=''1744490''>here.</span> <span m=''1744750''>So</span> <span m=''1745320''>things</span>
  <span m=''1745490''>get</span> <span m=''1745650''>complicated.</span> </p><p><span
  m=''1746200''>This</span> <span m=''1746380''>one</span> <span m=''1746500''>is</span>
  <span m=''1746800''>even</span> <span m=''1747090''>more</span> <span m=''1747220''>interesting.</span>
  <span m=''1748060''>This</span> <span m=''1748280''>one.</span> <span m=''1748770''>There''s</span>
  <span m=''1748910''>only</span> <span m=''1749040''>one</span> <span m=''1749260''>dimensional</span>
  <span m=''1749900''>array</span> <span m=''1750710''>or</span> <span m=''1751110''>two</span>
  <span m=''1751220''>dimensional</span> <span m=''1751460''>loop nest.</span> <span
  m=''1754790''>So</span> <span m=''1754910''>what</span> <span m=''1755060''>that</span>
  <span m=''1755270''>means</span> <span m=''1755620''>is</span> <span m=''1756990''>who''s</span>
  <span m=''1757250''>writing</span> <span m=''1757810''>and</span> <span m=''1757920''>who''s</span>
  <span m=''1758160''>reading?</span> <span m=''1763550''>If</span> <span m=''1763740''>you</span>
  <span m=''1763850''>look</span> <span m=''1764010''>at</span> <span m=''1764150''>it</span>
  <span m=''1764340''>basically --</span> <span m=''1766580''>actually</span> <span
  m=''1766940''>this actually</span> <span m=''1767410''>is</span> <span m=''1767570''>a
  little</span> <span m=''1767730''>bit</span> <span m=''1767840''>wrong,</span> <span
  m=''1768300''>because</span> <span m=''1768710''>the</span> <span m=''1768790''>dependence</span>
  <span m=''1769380''>analysis</span> <span m=''1769630''>says</span> <span m=''1772270''>--</span>
  <span m=''1776450''>actually,</span> <span m=''1776860''>all</span> <span m=''1777120''>these</span>
  <span m=''1777390''>things,</span> <span m=''1777680''>all</span> <span m=''1778020''>this</span>
  <span m=''1778660''>read</span> <span m=''1778870''>has to go</span> <span m=''1779360''>into</span>
  <span m=''1779490''>all the</span> <span m=''1779770''>write,</span> <span m=''1780670''>because</span>
  <span m=''1781580''>they are</span> <span m=''1781660''>writing</span> <span m=''1782400''>any</span>
  <span m=''1782660''>J,</span> <span m=''1783360''>just</span> <span m=''1783560''>writing</span>
  <span m=''1783790''>the</span> <span m=''1783880''>same</span> <span m=''1784120''>thing.</span>
  <span m=''1784980''>So</span> <span m=''1785370''>this</span> <span m=''1785580''>is</span>
  <span m=''1785720''>a</span> <span m=''1785840''>little bit</span> <span m=''1786360''>wrong.
  This is actually</span> <span m=''1786760''>more</span> <span m=''1787130''>data</span>
  <span m=''1787520''>flow</span> <span m=''1787690''>analysis.</span> <span m=''1788620''>This
  is a</span> <span m=''1789310''>different --</span> <span m=''1789920''>their</span>
  <span m=''1790200''>dependence</span> <span m=''1790640''>means</span> <span m=''1791590''>I</span>
  <span m=''1791700''>don''t</span> <span m=''1791890''>care</span> <span m=''1792070''>who</span>
  <span m=''1792240''>the</span> <span m=''1792350''>guy</span> <span m=''1792690''>wrote,</span>
  <span m=''1793200''>because</span> <span m=''1793320''>he''s</span> <span m=''1793500''>the</span>
  <span m=''1793580''>last</span> <span m=''1793840''>guy who</span> <span m=''1794010''>wrote,</span>
  <span m=''1794900''>but</span> <span m=''1795020''>everybody''s</span> <span m=''1795520''>reading,</span>
  <span m=''1795800''>everybody</span> <span m=''1796230''>else</span> <span m=''1796540''>is</span>
  <span m=''1796700''>writing</span> <span m=''1796780''>the</span> <span m=''1797000''>same</span>
  <span m=''1797170''>location.</span> </p><p><span m=''1801880''>AUDIENCE: [OBSCURED].</span>
  </p><p><span m=''1802010''>PROFESSOR: Keep</span> <span m=''1802140''>rewriting
  the</span> <span m=''1802570''>same thing</span> <span m=''1803150''>again</span>
  <span m=''1803370''>and</span> <span m=''1803490''>again</span> <span m=''1803760''>and
  again.</span> <span m=''1805060''>You start</span> <span m=''1805330''>depending</span>
  <span m=''1805750''>on --</span> <span m=''1806570''>It''s not</span> <span m=''1807370''>dependant</span>
  <span m=''1807660''>on</span> <span m=''1807860''>J''s</span> <span m=''1808030''>it''s
  dependant</span> <span m=''1808110''>on</span> <span m=''1808220''>I.</span> <span
  m=''1811460''>But</span> <span m=''1811850''>location</span> <span m=''1812140''>says</span>
  <span m=''1813230''>you</span> <span m=''1813530''>used</span> <span m=''1813690''>to</span>
  <span m=''1813860''>have</span> <span m=''1814010''>iterations</span> <span m=''1814240''>right</span>
  <span m=''1814430''>in</span> <span m=''1814510''>the</span> <span m=''1814630''>same</span>
  <span m=''1814840''>location,</span> <span m=''1816540''>different</span> <span
  m=''1816950''>J.</span> <span m=''1819740''>So</span> <span m=''1820860''>not matter</span>
  <span m=''1820960''>what</span> <span m=''1821220''>J,</span> <span m=''1821570''>it''s</span>
  <span m=''1821760''>writing</span> <span m=''1821920''>in</span> <span m=''1822030''>the</span>
  <span m=''1822140''>same</span> <span m=''1822370''>location.</span> <span m=''1825800''>You
  know what I''m saying?</span> <span m=''1827010''>Because</span> <span m=''1827530''>J</span>
  <span m=''1829160''>thinks J.</span> </p><p><span m=''1830180''>AUDIENCE:</span>
  <span m=''1831268''>[NOISE].</span> </p><p><span m=''1834640''>PROFESSOR: This</span>
  <span m=''1835140''>is</span> <span m=''1835290''>iteration</span> <span m=''1835820''>space.</span>
  <span m=''1836770''>I am</span> <span m=''1837160''>looking</span> <span m=''1837490''>at</span>
  <span m=''1837630''>iteration.</span> <span m=''1837830''>I am looking at I and
  J.s</span> </p><p><span m=''1838030''>AUDIENCE:</span> <span m=''1838470''>[OBSCURED].</span>
  </p><p><span m=''1839790''>PROFESSOR:</span> <span m=''1839893''>B</span> <span
  m=''1839996''>is</span> <span m=''1840100''>a</span> <span m=''1840203''>one</span>
  <span m=''1840306''>dimensional</span> <span m=''1840410''>array.</span> <span m=''1842640''>So</span>
  <span m=''1842928''>B is a</span> <span m=''1843505''>one</span> <span m=''1843793''>dimensional</span>
  <span m=''1844081''>array.</span> <span m=''1844370''>So what</span> <span m=''1844580''>that</span>
  <span m=''1844760''>means</span> <span m=''1845170''>is --</span> <span m=''1845430''>The</span>
  <span m=''1845570''>reason</span> <span m=''1845820''>I''m</span> <span m=''1846020''>saying</span>
  <span m=''1846400''>it''s</span> <span m=''1846570''>the</span> <span m=''1847100''>iteration</span>
  <span m=''1847340''>space</span> <span m=''1847640''>and array</span> <span m=''1847840''>space</span>
  <span m=''1852810''>is a</span> <span m=''1853010''>match.</span> <span m=''1853300''>I''ll
  correct this and</span> <span m=''1853450''>put</span> <span m=''1853680''>it</span>
  <span m=''1853850''>in</span> <span m=''1854120''>there</span> <span m=''1854430''>because</span>
  <span m=''1854700''>this is</span> <span m=''1854730''>a</span> <span m=''1854760''>data</span>
  <span m=''1855250''>flow</span> <span m=''1855440''>diagram.</span> <span m=''1855740''>It''s</span>
  <span m=''1855920''>row</span> <span m=''1856060''>independant.</span> <span m=''1858800''>This</span>
  <span m=''1859080''>one</span> <span m=''1859260''>writing</span> <span m=''1859420''>to</span>
  <span m=''1859590''>what?</span> </p><p><span m=''1861230''>AUDIENCE:</span> <span
  m=''1862194''>[OBSCURED].</span> </p><p><span m=''1864590''>PROFESSOR: Iteration</span>
  <span m=''1865330''>space is</span> <span m=''1865590''>I</span> <span m=''1866280''>and
  J.</span> <span m=''1867000''>So,</span> <span m=''1868050''>this is</span> <span
  m=''1868730''>writing</span> <span m=''1869130''>to what?</span> <span m=''1869470''>I</span>
  <span m=''1870300''>zero</span> <span m=''1871150''>is</span> <span m=''1871790''>--</span>
  <span m=''1872240''>This</span> <span m=''1872990''>is</span> <span m=''1873170''>writing
  to what?</span> <span m=''1875120''>B1.</span> <span m=''1878720''>All</span> <span
  m=''1879070''>those</span> <span m=''1879250''>things are</span> <span m=''1879900''>writng
  to</span> <span m=''1880210''>B1.</span> <span m=''1883070''>This is</span> <span
  m=''1883350''>really</span> <span m=''1883520''>--</span> <span m=''1889920''>So
  this</span> <span m=''1890190''>is</span> <span m=''1890660''>writing</span> <span
  m=''1890740''>to</span> <span m=''1890930''>B1,</span> <span m=''1891520''>this</span>
  <span m=''1891980''>is</span> <span m=''1892340''>reading</span> <span m=''1892470''>B
  zero.</span> <span m=''1893860''>So</span> <span m=''1893990''>this</span> <span
  m=''1894280''>iteration</span> <span m=''1894390''>is</span> <span m=''1895040''>reading</span>
  <span m=''1895330''>B1</span> <span m=''1895550''>again.</span> <span m=''1896210''>So
  this</span> <span m=''1896530''>was</span> <span m=''1896680''>B1,</span> <span
  m=''1897010''>this is</span> <span m=''1897280''>iteration</span> <span m=''1897510''>B1.</span>
  <span m=''1897990''>So</span> <span m=''1898880''>each</span> <span m=''1899200''>of
  these</span> <span m=''1899380''>is writing</span> <span m=''1899840''>to</span>
  <span m=''1899900''>B1,</span> <span m=''1900370''>each of</span> <span m=''1900550''>these</span>
  <span m=''1900780''>are</span> <span m=''1901180''>reading</span> <span m=''1901570''>from</span>
  <span m=''1901780''>B1,</span> <span m=''1902390''>so</span> <span m=''1902570''>each</span>
  <span m=''1902680''>has to</span> <span m=''1902990''>be</span> <span m=''1903070''>dependent</span>
  <span m=''1903460''>from</span> <span m=''1903730''>each other.</span> </p><p><span
  m=''1907000''>AUDIENCE:</span> <span m=''1907423''>So I guess one thing that''s
  confusing here is</span> <span m=''1908270''>why</span> <span m=''1908550''>isn''t</span>
  <span m=''1908670''>it</span> <span m=''1908970''>just --</span> <span m=''1909510''>why</span>
  <span m=''1909880''>don''t we just</span> <span m=''1910690''>have</span> <span
  m=''1910840''>arrows going down the column? Why do we have all these--?</span> </p><p><span
  m=''1913550''>PROFESSOR: Arrows</span> <span m=''1913700''>going</span> <span m=''1913760''>down
  the</span> <span m=''1914050''>column</span> <span m=''1914480''>means</span> <span
  m=''1915860''>each</span> <span m=''1916170''>is</span> <span m=''1916420''>trying</span>
  <span m=''1916820''>to do</span> <span m=''1916900''>different</span> <span m=''1917230''>location.</span>
  <span m=''1918860''>So</span> <span m=''1919000''>what</span> <span m=''1919230''>happens</span>
  <span m=''1919700''>is</span> <span m=''1920760''>that</span> <span m=''1921200''>this</span>
  <span m=''1921450''>one,</span> <span m=''1921690''>arrays</span> <span m=''1922030''>going</span>
  <span m=''1922280''>down</span> <span m=''1922660''>this</span> <span m=''1922860''>way.</span>
  <span m=''1923280''>Is this</span> <span m=''1923600''>one --</span> <span m=''1924000''>what''s</span>
  <span m=''1924270''>wrote</span> <span m=''1924630''>here</span> <span m=''1924750''>is</span>
  <span m=''1925020''>only</span> <span m=''1925510''>that</span> <span m=''1926140''>location,</span>
  <span m=''1927350''>only</span> <span m=''1927700''>this</span> <span m=''1927910''>side</span>
  <span m=''1928070''>I accidentally </span> <span m=''1928820''>located.</span> <span
  m=''1929830''>These</span> <span m=''1930200''>are</span> <span m=''1930360''>all</span>
  <span m=''1930630''>writing</span> <span m=''1930870''>to</span> <span m=''1931090''>the</span>
  <span m=''1931160''>same</span> <span m=''1931490''>location</span> <span m=''1931910''>and
  reading</span> <span m=''1932240''>from</span> <span m=''1932390''>the</span> <span
  m=''1932460''>same</span> <span m=''1932670''>location.</span> </p><p><span m=''1933210''>AUDIENCE:</span>
  <span m=''1933670''>Why isn''t B</span> <span m=''1934130''>iterated?</span> </p><p><span
  m=''1936180''>PROFESSOR: This</span> <span m=''1936370''>is</span> <span m=''1936480''>iteration</span>
  <span m=''1936890''>space.</span> <span m=''1937390''>I</span> <span m=''1937550''>have</span>
  <span m=''1937760''>two</span> <span m=''1937920''>different loops here.</span>
  </p><p><span m=''1938620''>AUDIENCE:</span> <span m=''1939120''>But I don''t understand
  why B [NOISE.]</span> </p><p><span m=''1942120''>PROFESSOR: This</span> <span m=''1942340''>is</span>
  <span m=''1942520''>my</span> <span m=''1942710''>program.</span> <span m=''1944110''>I</span>
  <span m=''1944250''>can</span> <span m=''1944450''>write</span> <span m=''1944830''>this</span>
  <span m=''1944930''>program.</span> <span m=''1945250''>This is a</span> <span m=''1945370''>little
  bit of a</span> <span m=''1945810''>stupid</span> <span m=''1946070''>program</span>
  <span m=''1946900''>because I</span> <span m=''1947430''>am kind of</span> <span
  m=''1947860''>trying to do the</span> <span m=''1947970''>same</span> <span m=''1948100''>thing</span>
  <span m=''1948160''>again and</span> <span m=''1948290''>again.</span> <span m=''1950090''>But</span>
  <span m=''1950400''>hey,</span> <span m=''1951040''>my</span> <span m=''1951240''>program</span>
  <span m=''1951440''>doesn''t</span> <span m=''1951820''>say</span> <span m=''1953340''>array</span>
  <span m=''1953920''>dimensions</span> <span m=''1954810''>has</span> <span m=''1955590''>to
  match</span> <span m=''1956010''>your loop dimension.</span> <span m=''1956790''>It</span>
  <span m=''1957010''>doesn''t say</span> <span m=''1957540''>that so you</span> <span
  m=''1957720''>can</span> <span m=''1958710''>have</span> <span m=''1958900''>programs
  like that.</span> <span m=''1959050''>You can have other</span> <span m=''1959140''>way</span>
  <span m=''1959280''>too.</span> <span m=''1962440''>So</span> <span m=''1963550''>the</span>
  <span m=''1963720''>key thing is to make --</span> <span m=''1964380''>don''t</span>
  <span m=''1964920''>confuse</span> <span m=''1966530''>iteration</span> <span m=''1966830''>space</span>
  <span m=''1967800''>versus</span> <span m=''1967980''>array</span> <span m=''1968580''>space.</span>
  <span m=''1968750''>They are two</span> <span m=''1968880''>different</span> <span
  m=''1969200''>spaces,</span> <span m=''1969510''>two different</span> <span m=''1970050''>number
  of</span> <span m=''1970280''>dimensions.</span> <span m=''1970980''>That''s</span>
  <span m=''1971180''>all</span> <span m=''1971340''>the</span> <span m=''1971480''>point
  that</span> <span m=''1971670''>I''m going to make here.</span> </p><p><span m=''1975360''>So</span>
  <span m=''1975490''>by</span> <span m=''1975720''>doing</span> <span m=''1976050''>dependence</span>
  <span m=''1976410''>analysis,</span> <span m=''1977470''>you</span> <span m=''1977770''>can</span>
  <span m=''1977960''>figure</span> <span m=''1978320''>out --</span> <span m=''1978970''>now
  you can</span> <span m=''1979230''>formulate</span> <span m=''1979730''>this</span>
  <span m=''1980020''>nicely --</span> <span m=''1980410''>figure</span> <span m=''1980740''>out</span>
  <span m=''1980910''>where the</span> <span m=''1980940''>loops</span> <span m=''1981240''>are
  parallel.</span> <span m=''1983550''>So</span> <span m=''1983710''>that''s</span>
  <span m=''1984390''>really</span> <span m=''1984640''>neat.</span> <span m=''1986480''>The</span>
  <span m=''1986540''>next</span> <span m=''1986780''>thing</span> <span m=''1986930''>I''m</span>
  <span m=''1987090''>going to</span> <span m=''1987310''>go</span> <span m=''1987520''>is</span>
  <span m=''1988460''>trying</span> <span m=''1988700''>to</span> <span m=''1988780''>figure</span>
  <span m=''1989070''>out</span> <span m=''1989260''>how</span> <span m=''1989620''>you</span>
  <span m=''1989730''>can</span> <span m=''1990150''>increase</span> <span m=''1990430''>the</span>
  <span m=''1990650''>parallelism</span> <span m=''1991080''>opportunities.</span>
  <span m=''1991970''>Because</span> <span m=''1992400''>there</span> <span m=''1992550''>might</span>
  <span m=''1992680''>be</span> <span m=''1992800''>cases</span> <span m=''1993030''>where</span>
  <span m=''1993790''>the</span> <span m=''1993960''>original</span> <span m=''1994070''>code</span>
  <span m=''1994410''>you wrote,</span> <span m=''1995700''>there</span> <span m=''1995890''>might</span>
  <span m=''1996050''>be</span> <span m=''1996160''>some</span> <span m=''1996560''>loops</span>
  <span m=''1996710''>that</span> <span m=''1996870''>are not</span> <span m=''1997350''>parallelizable,</span>
  <span m=''1998010''>assays,</span> <span m=''1998710''>and</span> <span m=''1998830''>can</span>
  <span m=''1998990''>you</span> <span m=''1999090''>go and</span> <span m=''1999410''>increase</span>
  <span m=''1999520''>that.</span> <span m=''2000580''>So</span> <span m=''2000700''>I''m</span>
  <span m=''2000810''>going to</span> <span m=''2000960''>talk</span> <span m=''2001180''>about</span>
  <span m=''2001440''>few</span> <span m=''2001660''>different</span> <span m=''2002350''>possibilities</span>
  <span m=''2002700''>of</span> <span m=''2002750''>doing</span> <span m=''2003040''>that.</span>
  </p><p><span m=''2005880''>Scalar</span> <span m=''2006150''>privatization,</span>
  <span m=''2006800''>I</span> <span m=''2006900''>will</span> <span m=''2007080''>just</span>
  <span m=''2007310''>go</span> <span m=''2007450''>in</span> <span m=''2007690''>each</span>
  <span m=''2007800''>of</span> <span m=''2008080''>these</span> <span m=''2008270''>separating.</span>
  <span m=''2010550''>So</span> <span m=''2010700''>here is</span> <span m=''2010980''>interesting</span>
  <span m=''2011400''>program.</span> <span m=''2013040''>To</span> <span m=''2015290''>get</span>
  <span m=''2015430''>parallel</span> <span m=''2015600''>to the</span> <span m=''2015880''>temporary</span>
  <span m=''2016840''>and</span> <span m=''2017200''>use</span> <span m=''2017300''>the</span>
  <span m=''2017490''>temporary</span> <span m=''2017620''>in</span> <span m=''2017820''>here.</span>
  <span m=''2019080''>You</span> <span m=''2019250''>might</span> <span m=''2019450''>not</span>
  <span m=''2019590''>know you had</span> <span m=''2019830''>written</span> <span
  m=''2020220''>that</span> <span m=''2020460''>but the</span> <span m=''2020630''>compiler</span>
  <span m=''2021080''>normally</span> <span m=''2021310''>generates</span> <span m=''2021620''>something</span>
  <span m=''2021970''>like</span> <span m=''2022130''>that</span> <span m=''2022270''>because</span>
  <span m=''2022530''>you</span> <span m=''2022780''>always</span> <span m=''2022950''>had</span>
  <span m=''2023150''>temporaries</span> <span m=''2023450''>in</span> <span m=''2023700''>here,</span>
  <span m=''2024090''>so</span> <span m=''2024230''>this</span> <span m=''2024480''>might</span>
  <span m=''2024650''>be</span> <span m=''2024790''>what</span> <span m=''2025020''>compiler</span>
  <span m=''2026300''>generate.</span> <span m=''2026460''>Is</span> <span m=''2026610''>this
  loop</span> <span m=''2026700''>parallel?</span> </p><p><span m=''2027240''>AUDIENCE:</span>
  <span m=''2035044''>Yup.</span> </p><p><span m=''2036020''>PROFESSOR: Why?</span>
  </p><p><span m=''2036290''>AUDIENCE:</span> <span m=''2036805''>[OBSCURED].</span>
  </p><p><span m=''2040000''>PROFESSOR: Is</span> <span m=''2040280''>the</span> <span
  m=''2040360''>loop</span> <span m=''2040590''>carry</span> <span m=''2040900''>dependence</span>
  <span m=''2041000''>true or</span> <span m=''2041380''>anti --</span> <span m=''2042150''>What''s</span>
  <span m=''2042540''>the true</span> <span m=''2043050''>dependence</span> <span
  m=''2043930''>which to which?</span> <span m=''2045820''>We</span> <span m=''2045920''>didn''t</span>
  <span m=''2046090''>loop</span> <span m=''2046280''>true</span> <span m=''2046530''>dependence.</span>
  <span m=''2048260''>What</span> <span m=''2048570''>is</span> <span m=''2048680''>the</span>
  <span m=''2048780''>loop</span> <span m=''2049030''>carry</span> <span m=''2049320''>dependence?</span>
  <span m=''2052810''>Anti-dependence.</span> <span m=''2054070''>Because</span> <span
  m=''2054780''>I</span> <span m=''2054970''>cannot --</span> <span m=''2055560''>you</span>
  <span m=''2055940''>see</span> <span m=''2056160''>I</span> <span m=''2056570''>equal</span>
  <span m=''2057120''>1,</span> <span m=''2058120''>basically</span> <span m=''2060240''>wrote</span>
  <span m=''2060530''>here</span> <span m=''2060710''>in</span> <span m=''2060950''>this</span>
  <span m=''2061440''>reading.</span> <span m=''2061820''>I can''t</span> <span m=''2062450''>write</span>
  <span m=''2062810''>I</span> <span m=''2063130''>equals</span> <span m=''2063410''>2x</span>
  <span m=''2064360''>until</span> <span m=''2064630''>I equals</span> <span m=''2065300''>1</span>
  <span m=''2065560''>is</span> <span m=''2065690''>done</span> <span m=''2065970''>and</span>
  <span m=''2066170''>done</span> <span m=''2066400''>reading</span> <span m=''2066720''>that.</span>
  <span m=''2066870''>I</span> <span m=''2066910''>have</span> <span m=''2067110''>one</span>
  <span m=''2067360''>location</span> <span m=''2067920''>and</span> <span m=''2068050''>everybody''s</span>
  <span m=''2068560''>trying</span> <span m=''2068770''>to</span> <span m=''2068880''>read</span>
  <span m=''2069110''>or</span> <span m=''2069210''>write</span> <span m=''2069490''>that,</span>
  <span m=''2070080''>even</span> <span m=''2070400''>though</span> <span m=''2070500''>I</span>
  <span m=''2070590''>don''t really</span> <span m=''2070810''>use</span> <span m=''2071220''>data.</span>
  <span m=''2071450''>This</span> <span m=''2071620''>is</span> <span m=''2071760''>the</span>
  <span m=''2071840''>sad</span> <span m=''2072090''>thing</span> <span m=''2072250''>about</span>
  <span m=''2072500''>this.</span> <span m=''2072860''>That</span> <span m=''2073040''>I''m</span>
  <span m=''2073070''>really</span> <span m=''2073240''>using</span> <span m=''2073500''>this</span>
  <span m=''2073650''>guy''s</span> <span m=''2073860''>data,</span> <span m=''2074510''>but</span>
  <span m=''2074610''>I''m</span> <span m=''2074750''>just</span> <span m=''2074900''>waiting</span>
  <span m=''2075000''>for</span> <span m=''2075290''>the</span> <span m=''2075360''>same</span>
  <span m=''2075630''>space</span> <span m=''2076310''>to</span> <span m=''2076410''>occupy.</span>
  <span m=''2079510''>So,</span> <span m=''2079900''>there''s</span> <span m=''2080120''>a</span>
  <span m=''2080370''>loop carry</span> <span m=''2080610''>dependence</span> <span
  m=''2081070''>in</span> <span m=''2081210''>here,</span> <span m=''2082510''>and</span>
  <span m=''2083320''>it''s</span> <span m=''2083410''>anti-dependent.</span> <span
  m=''2085330''>So</span> <span m=''2085430''>what</span> <span m=''2085630''>you</span>
  <span m=''2085750''>can</span> <span m=''2086020''>do</span> <span m=''2086150''>is</span>
  <span m=''2087120''>if you</span> <span m=''2087250''>find</span> <span m=''2087560''>any</span>
  <span m=''2087740''>anti</span> <span m=''2087980''>or</span> <span m=''2088180''>output</span>
  <span m=''2088780''>loop</span> <span m=''2089040''>carry</span> <span m=''2089190''>dependence,
  you can get rid of them.</span> <span m=''2090880''>I''m</span> <span m=''2091070''>not
  really</span> <span m=''2091350''>using</span> <span m=''2091670''>that</span> <span
  m=''2092370''>value, I''m just</span> <span m=''2092860''>keeping</span> <span m=''2093140''>a</span>
  <span m=''2093220''>location</span> <span m=''2093850''>in here.</span> <span m=''2094430''>So</span>
  <span m=''2095100''>how can</span> <span m=''2095310''>we</span> <span m=''2095400''>get</span>
  <span m=''2095560''>rid</span> <span m=''2095650''>of that?</span> </p><p><span
  m=''2095820''>AUDIENCE:</span> <span m=''2098745''>[OBSCURED].</span> </p><p><span
  m=''2101670''>PROFESSOR: Yeah.</span> <span m=''2102040''>That''s</span> <span m=''2102220''>one
  thing.</span> <span m=''2103100''>There''s two</span> <span m=''2103410''>ways of
  doing it.</span> <span m=''2103970''>One</span> <span m=''2104190''>is</span> <span
  m=''2104400''>I</span> <span m=''2105050''>assign something</span> <span m=''2105300''>local.</span>
  <span m=''2107210''>So each</span> <span m=''2108150''>processor</span> <span m=''2108490''>will</span>
  <span m=''2108650''>have</span> <span m=''2109240''>its</span> <span m=''2109380''>own</span>
  <span m=''2109930''>copy,</span> <span m=''2111060''>so</span> <span m=''2111180''>I</span>
  <span m=''2111260''>don''t</span> <span m=''2111950''>do that.</span> <span m=''2112760''>So</span>
  <span m=''2112930''>it''s</span> <span m=''2113030''>something</span> <span m=''2113420''>like
  this,</span> <span m=''2114510''>so</span> <span m=''2115050''>that''s</span> <span
  m=''2115710''>[OBSCURED].</span> <span m=''2117670''>Or</span> <span m=''2118590''>I</span>
  <span m=''2119690''>can</span> <span m=''2119840''>look at the array.</span> <span
  m=''2121300''>In the array</span> <span m=''2121500''>you can</span> <span m=''2121540''>have</span>
  <span m=''2122300''>either</span> <span m=''2122470''>number</span> <span m=''2122650''>of</span>
  <span m=''2123060''>process or</span> <span m=''2123480''>iterations for</span>
  <span m=''2123740''>each iteration.</span> <span m=''2124860''>But</span> <span
  m=''2125730''>uses</span> <span m=''2125890''>a</span> <span m=''2126090''>different</span>
  <span m=''2126590''>location.</span> <span m=''2127590''>This</span> <span m=''2128000''>is</span>
  <span m=''2128280''>more</span> <span m=''2128450''>efficient</span> <span m=''2129080''>than</span>
  <span m=''2129190''>this</span> <span m=''2129260''>one</span> <span m=''2129740''>because</span>
  <span m=''2130280''>we are</span> <span m=''2130510''>touching</span> <span m=''2130830''>lot</span>
  <span m=''2131020''>more</span> <span m=''2131260''>locations</span> <span m=''2131650''>in
  here.</span> <span m=''2134330''>I</span> <span m=''2134470''>haven''t</span> <span
  m=''2134760''>done</span> <span m=''2134940''>one</span> <span m=''2135290''>thing
  here.</span> <span m=''2136330''>I''m</span> <span m=''2136470''>not complete.</span>
  <span m=''2137210''>What</span> <span m=''2137500''>have</span> <span m=''2137680''>I</span>
  <span m=''2137750''>forgotten</span> <span m=''2138100''>to</span> <span m=''2138190''>do</span>
  <span m=''2139080''>in both of these?</span> </p><p><span m=''2139640''>AUDIENCE:</span>
  <span m=''2140620''>[OBSCURED].</span> </p><p><span m=''2143070''>PROFESSOR: Yeah,</span>
  <span m=''2143800''>because</span> <span m=''2144440''>it was</span> <span m=''2144700''>beforehand</span>
  <span m=''2145460''>somebody</span> <span m=''2145760''>might</span> <span m=''2145980''>use</span>
  <span m=''2146200''>final assignment</span> <span m=''2146810''>of the</span> <span
  m=''2147160''>loop nest,</span> <span m=''2147350''>so</span> <span m=''2147450''>what</span>
  <span m=''2147620''>you</span> <span m=''2147680''>had to</span> <span m=''2147880''>do</span>
  <span m=''2148020''>is</span> <span m=''2148450''>you</span> <span m=''2148710''>had</span>
  <span m=''2148780''>to</span> <span m=''2148880''>kind</span> <span m=''2149150''>of</span>
  <span m=''2149240''>finalize</span> <span m=''2149520''>x.</span> <span m=''2150690''>Because</span>
  <span m=''2150890''>I</span> <span m=''2151100''>had</span> <span m=''2151260''>a</span>
  <span m=''2151420''>temporary</span> <span m=''2151620''>variable,</span> <span
  m=''2151970''>so</span> <span m=''2152510''>with</span> <span m=''2153200''>n,</span>
  <span m=''2153350''>the last</span> <span m=''2153730''>value</span> <span m=''2153960''>has</span>
  <span m=''2154060''>to</span> <span m=''2154290''>go into</span> <span m=''2154530''>x.</span>
  <span m=''2156940''>You</span> <span m=''2157070''>can''t</span> <span m=''2157400''>keep</span>
  <span m=''2157950''>just</span> <span m=''2158280''>not</span> <span m=''2158570''>calculating</span>
  <span m=''2158770''>value</span> <span m=''2158950''>in</span> <span m=''2159570''>something.</span>
  <span m=''2160740''>So in here,</span> <span m=''2161010''>also,</span> <span m=''2161330''>you</span>
  <span m=''2161420''>just</span> <span m=''2161590''>say last</span> <span m=''2161820''>value
  is x.</span> <span m=''2163270''>But</span> <span m=''2163470''>after</span> <span
  m=''2163750''>you</span> <span m=''2163870''>do</span> <span m=''2164030''>that,</span>
  <span m=''2164830''>basically</span> <span m=''2165390''>now</span> <span m=''2165980''>each</span>
  <span m=''2166200''>of</span> <span m=''2166310''>this</span> <span m=''2166390''>loop</span>
  <span m=''2166700''>is faster.</span> <span m=''2170100''>Everybody</span> <span
  m=''2170460''>go</span> <span m=''2170560''>that?</span> </p><p><span m=''2173420''>OK,</span>
  <span m=''2173700''>here''s</span> <span m=''2174020''>another</span> <span m=''2174210''>example.</span>
  <span m=''2176090''>x</span> <span m=''2176510''>equals</span> <span m=''2176920''>x
  plus</span> <span m=''2177440''>AI.</span> <span m=''2179110''>Do</span> <span m=''2179430''>I
  have loop</span> <span m=''2179600''>carry</span> <span m=''2179800''>dependent?</span>
  <span m=''2190780''>What</span> <span m=''2190990''>did</span> <span m=''2191100''>the</span>
  <span m=''2191320''>loop-carried</span> <span m=''2191500''>dependence?</span> <span
  m=''2192780''>True</span> <span m=''2193260''>or anti?</span> <span m=''2199120''>True</span>
  <span m=''2199260''>dependence.</span> <span m=''2199400''>So</span> <span m=''2199570''>this</span>
  <span m=''2199690''>guy is</span> <span m=''2199990''>actually</span> <span m=''2200880''>creating</span>
  <span m=''2201190''>previous</span> <span m=''2201760''>value</span> <span m=''2202470''>and</span>
  <span m=''2203600''>adding</span> <span m=''2203880''>something</span> <span m=''2204190''>in</span>
  <span m=''2204310''>the event.</span> <span m=''2205800''>So</span> <span m=''2205970''>of
  course</span> <span m=''2206240''>in true</span> <span m=''2206340''>dependence</span>
  <span m=''2206930''>I</span> <span m=''2207010''>cannot</span> <span m=''2207330''>seem</span>
  <span m=''2207770''>to</span> <span m=''2208020''>parallelize.</span> <span m=''2208940''>But</span>
  <span m=''2209710''>there</span> <span m=''2209820''>are some</span> <span m=''2210220''>interesting</span>
  <span m=''2210760''>things</span> <span m=''2211010''>we can do.</span> <span m=''2211760''>That</span>
  <span m=''2212290''>was an</span> <span m=''2212460''>associative</span> <span m=''2213020''>operation.</span>
  <span m=''2215740''>I</span> <span m=''2215880''>didn''t</span> <span m=''2216130''>care</span>
  <span m=''2216490''>which</span> <span m=''2216820''>order</span> <span m=''2216930''>this</span>
  <span m=''2217180''>initial</span> <span m=''2217540''>happened,</span> <span m=''2217810''>so</span>
  <span m=''2217940''>I''m</span> <span m=''2218170''>just</span> <span m=''2218300''>keeping</span>
  <span m=''2218560''>a  lean</span> <span m=''2218790''>bunch</span> <span m=''2219070''>of
  values in here.</span> <span m=''2220330''>And</span> <span m=''2220810''>the</span>
  <span m=''2221050''>results</span> <span m=''2221270''>were</span> <span m=''2221370''>never</span>
  <span m=''2222100''>used</span> <span m=''2222580''>in the  other</span> <span m=''2222820''>loop.</span>
  <span m=''2223710''>So</span> <span m=''2223790''>we</span> <span m=''2223870''>just</span>
  <span m=''2223950''>keep</span> <span m=''2224030''>adding</span> <span m=''2224540''>things</span>
  <span m=''2224710''>and</span> <span m=''2224930''>at</span> <span m=''2225050''>the</span>
  <span m=''2225180''>end</span> <span m=''2225420''>of the loop</span> <span m=''2225590''>you</span>
  <span m=''2225700''>get the</span> <span m=''2225900''>sum</span> <span m=''2226340''>total</span>
  <span m=''2226740''>in here.</span> <span m=''2228600''>I</span> <span m=''2228660''>never</span>
  <span m=''2228940''>used</span> <span m=''2229180''>any</span> <span m=''2229340''>kind</span>
  <span m=''2229490''>of</span> <span m=''2229570''>partial</span> <span m=''2230210''>values</span>
  <span m=''2230330''>anywhere.</span> <span m=''2230580''>So</span> <span m=''2230680''>that</span>
  <span m=''2231050''>gives the</span> <span m=''2231270''>idea.</span> <span m=''2232130''>So</span>
  <span m=''2232290''>what</span> <span m=''2232480''>you</span> <span m=''2232560''>can</span>
  <span m=''2232810''>do</span> <span m=''2233060''>is</span> <span m=''2234420''>we
  can</span> <span m=''2235750''>translate</span> <span m=''2236420''>this</span>
  <span m=''2236720''>into</span> <span m=''2237300''>each</span> <span m=''2237740''>of
  the</span> <span m=''2238000''>guys</span> <span m=''2238640''>doing</span> <span
  m=''2239170''>a</span> <span m=''2239540''>temporary</span> <span m=''2241080''>addition</span>
  <span m=''2241580''>into</span> <span m=''2241960''>its</span> <span m=''2242170''>own</span>
  <span m=''2242260''>variable.</span> </p><p><span m=''2242460''>So</span> <span
  m=''2242830''>each</span> <span m=''2244050''>processor,</span> <span m=''2244280''>just</span>
  <span m=''2244500''>do</span> <span m=''2244960''>a</span> <span m=''2245240''>partial
  sum.</span> <span m=''2247650''>At</span> <span m=''2247810''>the</span> <span m=''2248490''>end,
  once</span> <span m=''2248730''>they''re done,</span> <span m=''2249270''>you</span>
  <span m=''2249390''>basically</span> <span m=''2249920''>do</span> <span m=''2250440''>the
  full sum.</span> <span m=''2251390''>Of course,</span> <span m=''2251660''>you can
  do a</span> <span m=''2251830''>tree</span> <span m=''2252370''>or</span> <span
  m=''2252540''>whatever</span> <span m=''2252940''>much</span> <span m=''2253180''>more</span>
  <span m=''2253290''>complicated</span> <span m=''2253460''>thing</span> <span m=''2253720''>then</span>
  <span m=''2254010''>that --</span> <span m=''2254230''>you</span> <span m=''2254670''>can</span>
  <span m=''2254830''>also</span> <span m=''2255060''>parallelize</span> <span m=''2255590''>this</span>
  <span m=''2255700''>part</span> <span m=''2256040''>at</span> <span m=''2256250''>the</span>
  <span m=''2256500''>tree</span> <span m=''2256930''>addition.</span> <span m=''2258050''>But</span>
  <span m=''2258440''>you</span> <span m=''2258580''>can</span> <span m=''2258690''>do
  that.</span> <span m=''2259130''>I</span> <span m=''2259190''>mean</span> <span
  m=''2259860''>Roderick</span> <span m=''2260200''>talked</span> <span m=''2260520''>about</span>
  <span m=''2260760''>this</span> <span m=''2261270''>in</span> <span m=''2261820''>hand</span>
  <span m=''2262160''>parallelization.</span> <span m=''2263170''>But</span> <span
  m=''2263320''>we</span> <span m=''2263420''>are</span> <span m=''2263560''>doing</span>
  <span m=''2263940''>something very</span> <span m=''2264280''>simple</span> <span
  m=''2264550''>in here.</span> <span m=''2266040''>So</span> <span m=''2266120''>these</span>
  <span m=''2266390''>compilers</span> <span m=''2266620''>can</span> <span m=''2266770''>figure</span>
  <span m=''2267370''>out</span> <span m=''2269670''>associative</span> <span m=''2270150''>operations</span>
  <span m=''2270930''>and</span> <span m=''2271330''>do</span> <span m=''2271460''>that.</span>
  <span m=''2271950''>So</span> <span m=''2272650''>this is</span> <span m=''2273090''>where</span>
  <span m=''2273840''>all</span> <span m=''2274080''>the</span> <span m=''2274170''>people</span>
  <span m=''2274400''>who</span> <span m=''2274480''>are</span> <span m=''2274610''>in</span>
  <span m=''2275020''>parallelizing,</span> <span m=''2275880''>and</span> <span m=''2276050''>all</span>
  <span m=''2276180''>the</span> <span m=''2276750''>people</span> <span m=''2277020''>who</span>
  <span m=''2277300''>are</span> <span m=''2277460''>writing</span> <span m=''2277640''>this</span>
  <span m=''2277720''>scientific</span> <span m=''2278100''>code</span> <span m=''2278560''>kind</span>
  <span m=''2278910''>of start</span> <span m=''2279080''>having</span> <span m=''2279370''>arguments.</span>
  <span m=''2280100''>Because they say</span> <span m=''2280500''>oh</span> <span
  m=''2280620''>my</span> <span m=''2280770''>God,</span> <span m=''2281050''>you''re</span>
  <span m=''2281560''>doing</span> <span m=''2281760''>operations</span> <span m=''2282360''>and</span>
  <span m=''2282770''>it''s</span> <span m=''2283520''>going to have</span> <span
  m=''2284190''>numerical</span> <span m=''2285100''>stability</span> <span m=''2285450''>issues.</span>
  <span m=''2285700''>Yes all</span> <span m=''2286050''>true.</span> <span m=''2286720''>In</span>
  <span m=''2287010''>compilers</span> <span m=''2287130''>you</span> <span m=''2287320''>have</span>
  <span m=''2287570''>these</span> <span m=''2287900''>flags</span> <span m=''2288250''>that</span>
  <span m=''2288430''>say</span> <span m=''2288620''>OK,</span> <span m=''2288720''>just</span>
  <span m=''2288930''>forget</span> <span m=''2289260''>about</span> <span m=''2289680''>all</span>
  <span m=''2289900''>these</span> <span m=''2290150''>very</span> <span m=''2291070''>issues,</span>
  <span m=''2291270''>and</span> <span m=''2291660''>most</span> <span m=''2292080''>probably</span>
  <span m=''2292560''>it will be right,</span> <span m=''2292880''>and</span> <span
  m=''2293130''>in most</span> <span m=''2293390''>code</span> <span m=''2293565''>it
  will work.</span> <span m=''2295320''>You</span> <span m=''2295450''>might</span>
  <span m=''2295640''>find</span> <span m=''2295950''>that</span> <span m=''2296080''>problem,
  too --</span> <span m=''2296750''>you</span> <span m=''2297750''>change</span> <span
  m=''2298070''>operation</span> <span m=''2298610''>order</span> <span m=''2298970''>to
  get</span> <span m=''2299130''>some</span> <span m=''2299280''>parallelism</span>
  <span m=''2299850''>and</span> <span m=''2300430''>suddenly</span> <span m=''2300990''>you</span>
  <span m=''2301150''>are</span> <span m=''2301280''>running unstability.</span> <span
  m=''2302960''>There are some</span> <span m=''2303470''>algorithms</span> <span
  m=''2303570''>that you</span> <span m=''2303760''>can''t</span> <span m=''2304780''>do
  that, but</span> <span m=''2304910''>most</span> <span m=''2305190''>algorithms</span>
  <span m=''2305550''>you can.</span> </p><p><span m=''2308710''>So</span> <span m=''2308900''>here''s</span>
  <span m=''2309390''>another</span> <span m=''2309590''>interesting</span> <span
  m=''2309780''>thing.</span> <span m=''2310090''>So,</span> <span m=''2311680''>I</span>
  <span m=''2311810''>have a</span> <span m=''2312180''>program</span> <span m=''2312560''>like</span>
  <span m=''2312740''>that,</span> <span m=''2313510''>2</span> <span m=''2313840''>to
  the power</span> <span m=''2314030''>I,</span> <span m=''2314910''>and</span> <span
  m=''2315140''>of</span> <span m=''2315430''>course,</span> <span m=''2315550''>most
  of the</span> <span m=''2315900''>time</span> <span m=''2317310''>exponentiation</span>
  <span m=''2318150''>is</span> <span m=''2318300''>very</span> <span m=''2318490''>expensive.</span>
  <span m=''2320080''>If you</span> <span m=''2320360''>have</span> <span m=''2320780''>a</span>
  <span m=''2320920''>smart</span> <span m=''2321080''>compiler --</span> <span m=''2321450''>I</span>
  <span m=''2321540''>don''t have</span> <span m=''2321830''>to</span> <span m=''2322330''>exponentiate.</span>
  <span m=''2322840''>This</span> <span m=''2323000''>thing</span> <span m=''2323320''>called</span>
  <span m=''2323580''>strength</span> <span m=''2323930''>reduction.</span> <span
  m=''2324390''>They</span> <span m=''2324720''>say</span> <span m=''2324760''>wait
  a minute --</span> <span m=''2324970''>I</span> <span m=''2325070''>will</span>
  <span m=''2325640''>keep</span> <span m=''2325910''>variable</span> <span m=''2326010''>t.</span>
  <span m=''2326160''>This</span> <span m=''2326780''>2</span> <span m=''2327200''>to
  the</span> <span m=''2327320''>power i</span> <span m=''2328000''>means</span> <span
  m=''2328370''>basically</span> <span m=''2328820''>every</span> <span m=''2328990''>time</span>
  <span m=''2329220''>I</span> <span m=''2329270''>multiply</span> <span m=''2329560''>it</span>
  <span m=''2329770''>by</span> <span m=''2330620''>2</span> <span m=''2330800''>and</span>
  <span m=''2330870''>I</span> <span m=''2331060''>can''t keep</span> <span m=''2331190''>repeating
  that.</span> <span m=''2332150''>Do you see</span> <span m=''2332590''>why these</span>
  <span m=''2332740''>two</span> <span m=''2333580''>are equal there?</span> <span
  m=''2337210''>This</span> <span m=''2337453''>is</span> <span m=''2337696''>good.</span>
  <span m=''2337940''>A lot of</span> <span m=''2338130''>good</span> <span m=''2338280''>compilers</span>
  <span m=''2338650''>do</span> <span m=''2338870''>that.</span> <span m=''2339550''>But</span>
  <span m=''2339720''>now</span> <span m=''2339810''>what</span> <span m=''2340020''>did</span>
  <span m=''2340100''>I</span> <span m=''2340510''>suddenly</span> <span m=''2340860''>do?</span>
  </p><p><span m=''2341040''>AUDIENCE:</span> <span m=''2342120''>[OBSCURED.]</span>
  </p><p><span m=''2343740''>PROFESSOR: Yeah,</span> <span m=''2343980''>I</span>
  <span m=''2344290''>reduced</span> <span m=''2344480''>the</span> <span m=''2344700''>amount</span>
  <span m=''2344950''>of</span> <span m=''2345040''>computation,</span> <span m=''2345680''>obviously,</span>
  <span m=''2346470''>but</span> <span m=''2347440''>I</span> <span m=''2347610''>just</span>
  <span m=''2347800''>introduce a</span> <span m=''2348450''>loop-carried</span> <span
  m=''2348920''>true</span> <span m=''2349100''>dependence</span> <span m=''2349640''>here.</span>
  <span m=''2352760''>Because</span> <span m=''2353070''>now</span> <span m=''2353370''>I</span>
  <span m=''2353440''>have</span> <span m=''2353700''>t</span> <span m=''2354140''>dependent</span>
  <span m=''2354450''>on</span> <span m=''2354520''>the</span> <span m=''2354590''>previous</span>
  <span m=''2354950''>t</span> <span m=''2355060''>to</span> <span m=''2355340''>calculate</span>
  <span m=''2355560''>the</span> <span m=''2355670''>next</span> <span m=''2355880''>value,</span>
  <span m=''2357470''>and</span> <span m=''2358260''>while</span> <span m=''2359270''>order-wise
  or</span> <span m=''2359530''>sequential-wise</span> <span m=''2360630''>this</span>
  <span m=''2360860''>is a win,</span> <span m=''2361870''>now</span> <span m=''2362200''>suddenly</span>
  <span m=''2362500''>I</span> <span m=''2362660''>can''t</span> <span m=''2362950''>parallelize.</span>
  <span m=''2364350''>Of</span> <span m=''2364500''>course,</span> <span m=''2364760''>a</span>
  <span m=''2364790''>lot</span> <span m=''2364940''>of</span> <span m=''2365030''>times</span>
  <span m=''2365210''>what</span> <span m=''2365370''>you</span> <span m=''2365440''>had</span>
  <span m=''2365530''>to</span> <span m=''2365600''>do</span> <span m=''2365840''>is</span>
  <span m=''2366420''>you</span> <span m=''2366600''>have a</span> <span m=''2366840''>very</span>
  <span m=''2367040''>smart</span> <span m=''2367390''>programmer.</span> <span m=''2367750''>They</span>
  <span m=''2367850''>say</span> <span m=''2367990''>aha,</span> <span m=''2368540''>I</span>
  <span m=''2368780''>know</span> <span m=''2369040''>this</span> <span m=''2369220''>operation</span>
  <span m=''2369810''>is</span> <span m=''2369890''>expensive so</span> <span m=''2370350''>I
  am</span> <span m=''2370610''>going</span> <span m=''2370790''>to</span> <span m=''2370870''>do</span>
  <span m=''2371080''>this</span> <span m=''2371290''>myself</span> <span m=''2372260''>and</span>
  <span m=''2372510''>create</span> <span m=''2372880''>you a</span> <span m=''2373020''>much</span>
  <span m=''2373260''>simpler</span> <span m=''2373580''>program in</span> <span m=''2374280''>sequentially.</span>
  <span m=''2375670''>Then</span> <span m=''2375770''>you try</span> <span m=''2375940''>to</span>
  <span m=''2376330''>parallelizes this and</span> <span m=''2376550''>you</span>
  <span m=''2376630''>can''t.</span> <span m=''2377380''>So</span> <span m=''2377480''>what</span>
  <span m=''2377670''>you</span> <span m=''2377760''>might</span> <span m=''2377990''>try</span>
  <span m=''2378110''>to</span> <span m=''2378220''>do</span> <span m=''2378400''>is</span>
  <span m=''2378710''>kind</span> <span m=''2378950''>of</span> <span m=''2379090''>do</span>
  <span m=''2379980''>this</span> <span m=''2380450''>direction</span> <span m=''2381100''>transformation</span>
  <span m=''2381600''>many</span> <span m=''2381800''>times</span> <span m=''2382400''>to
  make</span> <span m=''2382690''>the</span> <span m=''2382770''>program</span> <span
  m=''2383180''>run</span> <span m=''2383430''>a</span> <span m=''2383580''>little
  bit</span> <span m=''2383740''>slower</span> <span m=''2384270''>sequentially</span>
  <span m=''2385900''>just</span> <span m=''2386240''>so</span> <span m=''2386370''>you</span>
  <span m=''2386510''>can</span> <span m=''2386670''>actually</span> <span m=''2386910''>go</span>
  <span m=''2387190''>and</span> <span m=''2387260''>parallelize</span> <span m=''2387380''>it.</span>
  <span m=''2389340''>So this</span> <span m=''2389560''>get''s</span> <span m=''2389730''>a
  little</span> <span m=''2389820''>bit</span> <span m=''2389940''>counterintuitive.</span>
  <span m=''2390770''>You</span> <span m=''2390880''>just</span> <span m=''2391410''>look
  at</span> <span m=''2391560''>a</span> <span m=''2391610''>program</span> <span
  m=''2391960''>and say</span> <span m=''2392060''>yeah</span> <span m=''2392520''>there</span>
  <span m=''2393320''>is a</span> <span m=''2393730''>loop</span> <span m=''2393900''>carried</span>
  <span m=''2394130''>dependence,</span> <span m=''2394490''>I</span> <span m=''2394570''>can</span>
  <span m=''2394790''>do</span> <span m=''2394880''>it</span> <span m=''2395030''>a</span>
  <span m=''2395130''>little bit</span> <span m=''2395270''>more</span> <span m=''2395410''>expensive</span>
  <span m=''2395850''>without</span> <span m=''2395960''>the</span> <span m=''2396050''>loop</span>
  <span m=''2396130''>carried</span> <span m=''2396810''>dependence,</span> <span
  m=''2397500''>and</span> <span m=''2397780''>then</span> <span m=''2397920''>suddenly</span>
  <span m=''2398540''>my loop is</span> <span m=''2398760''>parallelized.</span> <span
  m=''2399320''>So</span> <span m=''2399420''>there</span> <span m=''2399630''>might</span>
  <span m=''2399830''>be cases</span> <span m=''2400310''>where</span> <span m=''2400460''>you</span>
  <span m=''2400560''>might</span> <span m=''2400730''>have</span> <span m=''2400880''>to
  do it</span> <span m=''2401070''>by hand,</span> <span m=''2401850''>and</span>
  <span m=''2402110''>a lot of</span> <span m=''2402300''>compilers</span> <span m=''2403250''>automatic</span>
  <span m=''2403800''>parallelizing</span> <span m=''2404020''>compilers,</span> <span
  m=''2404070''>try</span> <span m=''2404280''>to</span> <span m=''2404740''>do</span>
  <span m=''2404960''>this</span> <span m=''2405190''>also.</span> <span m=''2405990''>Kind</span>
  <span m=''2406190''>of</span> <span m=''2406360''>look</span> <span m=''2406540''>at
  these</span> <span m=''2406720''>kind</span> <span m=''2406930''>of</span> <span
  m=''2407010''>things</span> <span m=''2407220''>and</span> <span m=''2407370''>try</span>
  <span m=''2408050''>to</span> <span m=''2408230''>move in that</span> <span m=''2408380''>direction.</span>
  <span m=''2409450''>Whereas,</span> <span m=''2410030''>most</span> <span m=''2410260''>of</span>
  <span m=''2410320''>the</span> <span m=''2410380''>sequential</span> <span m=''2410700''>compiler</span>
  <span m=''2410870''>is</span> <span m=''2411150''>trying</span> <span m=''2411290''>to</span>
  <span m=''2411390''>find</span> <span m=''2411670''>this</span> <span m=''2411970''>and</span>
  <span m=''2412160''>move</span> <span m=''2412260''>this</span> <span m=''2412420''>direction.</span>
  </p><p><span m=''2416320''>So,</span> <span m=''2417410''>OK I said that.</span>
  <span m=''2419840''>So,</span> <span m=''2420190''>another</span> <span m=''2420540''>thing</span>
  <span m=''2420850''>called</span> <span m=''2420990''>array</span> <span m=''2421190''>privatization.</span>
  <span m=''2421790''>So</span> <span m=''2421990''>scalars,</span> <span m=''2422770''>I</span>
  <span m=''2423250''>show</span> <span m=''2423500''>you</span> <span m=''2424660''>where</span>
  <span m=''2424990''>when</span> <span m=''2425040''>you</span> <span m=''2425250''>have</span>
  <span m=''2425390''>anti</span> <span m=''2425570''>and</span> <span m=''2425820''>output</span>
  <span m=''2426130''>dependence</span> <span m=''2426540''>on</span> <span m=''2426630''>a</span>
  <span m=''2426670''>variable,</span> <span m=''2427140''>you</span> <span m=''2427200''>need</span>
  <span m=''2427370''>to</span> <span m=''2427440''>privatize.</span> <span m=''2428260''>And</span>
  <span m=''2428530''>in</span> <span m=''2428650''>arrays,</span> <span m=''2429410''>you</span>
  <span m=''2429800''>have</span> <span m=''2430090''>a</span> <span m=''2430550''>lot</span>
  <span m=''2430750''>more</span> <span m=''2430900''>complexity.</span> <span m=''2431360''>I''m</span>
  <span m=''2431500''>not</span> <span m=''2431620''>going</span> <span m=''2431810''>to
  go into</span> <span m=''2432110''>that,</span> <span m=''2432290''>you</span> <span
  m=''2432380''>can</span> <span m=''2432530''>actually</span> <span m=''2432800''>do</span>
  <span m=''2432890''>private</span> <span m=''2433250''>copies</span> <span m=''2433510''>also</span>
  <span m=''2433720''>in there.</span> <span m=''2435440''>You</span> <span m=''2435660''>can</span>
  <span m=''2435800''>do</span> <span m=''2435880''>bunch of</span> <span m=''2436300''>transformation.</span>
  </p><p><span m=''2437830''>Another</span> <span m=''2438170''>thing</span> <span
  m=''2438710''>people do</span> <span m=''2439060''>is</span> <span m=''2439090''>called</span>
  <span m=''2439230''>interprocedural</span> <span m=''2439840''>parallelization.</span>
  <span m=''2441740''>So</span> <span m=''2441840''>the</span> <span m=''2441930''>thing</span>
  <span m=''2442210''>is</span> <span m=''2442340''>you</span> <span m=''2442410''>have
  a</span> <span m=''2442490''>nice</span> <span m=''2442750''>loop</span> <span m=''2442980''>and</span>
  <span m=''2444030''>you</span> <span m=''2444270''>start</span> <span m=''2444470''>analyzing</span>
  <span m=''2444980''>loop</span> <span m=''2445240''>and in</span> <span m=''2445330''>the</span>
  <span m=''2445390''>middle</span> <span m=''2445870''>of a loop you have a</span>
  <span m=''2446070''>function</span> <span m=''2446420''>call.</span> <span m=''2448250''>Suddenly</span>
  <span m=''2448510''>what</span> <span m=''2448630''>are</span> <span m=''2448700''>you
  going to</span> <span m=''2448810''>do</span> <span m=''2449030''>with</span> <span
  m=''2449780''>it?</span> <span m=''2450120''>You</span> <span m=''2450310''>have</span>
  <span m=''2450390''>no</span> <span m=''2450510''>idea</span> <span m=''2450580''>what
  the function does,</span> <span m=''2451470''>and</span> <span m=''2451880''>most</span>
  <span m=''2452200''>of</span> <span m=''2452300''>the</span> <span m=''2452400''>simple</span>
  <span m=''2452570''>analysis</span> <span m=''2453160''>says</span> <span m=''2453280''>OK,</span>
  <span m=''2453510''>I can''t</span> <span m=''2453910''>parallelize</span> <span
  m=''2454280''>anything</span> <span m=''2454530''>that</span> <span m=''2454670''>has</span>
  <span m=''2454820''>a</span> <span m=''2454870''>function</span> <span m=''2455200''>call.</span>
  <span m=''2455750''>That''s</span> <span m=''2455910''>not</span> <span m=''2456040''>a</span>
  <span m=''2456090''>good</span> <span m=''2456330''>parallelizing</span> <span m=''2456620''>compiler</span>
  <span m=''2456950''>because</span> <span m=''2457430''>a</span> <span m=''2457460''>lot</span>
  <span m=''2457600''>of</span> <span m=''2457700''>loops</span> <span m=''2458000''>have</span>
  <span m=''2458200''>function</span> <span m=''2458370''>calls</span> <span m=''2458890''>and</span>
  <span m=''2459240''>you</span> <span m=''2459420''>might</span> <span m=''2459640''>call
  it</span> <span m=''2459780''>something</span> <span m=''2460320''>simple</span>
  <span m=''2460530''>as</span> <span m=''2461720''>sine</span> <span m=''2462010''>function</span>
  <span m=''2463390''>or</span> <span m=''2463570''>some simple</span> <span m=''2464090''>exponentiation
  function</span> <span m=''2464670''>and then</span> <span m=''2465550''>suddenly</span>
  <span m=''2465910''>it''s not</span> <span m=''2466030''>parallelizable.</span>
  <span m=''2468750''>This</span> <span m=''2468890''>is</span> <span m=''2469000''>a</span>
  <span m=''2469050''>big</span> <span m=''2469250''>problem.</span> <span m=''2470470''>There</span>
  <span m=''2470560''>are</span> <span m=''2470670''>two</span> <span m=''2470910''>things</span>
  <span m=''2471040''>you</span> <span m=''2471150''>can</span> <span m=''2471380''>do.</span>
  <span m=''2471460''>One</span> <span m=''2471760''>is</span> <span m=''2471920''>interprocedural</span>
  <span m=''2472460''>analysis</span> <span m=''2472790''>and</span> <span m=''2473040''>another</span>
  <span m=''2473410''>inlining.</span> <span m=''2475080''>So</span> <span m=''2475240''>the</span>
  <span m=''2475380''>interprocedural</span> <span m=''2475500''>analysis</span> <span
  m=''2476600''>says</span> <span m=''2478970''>I''m</span> <span m=''2479270''>going</span>
  <span m=''2479510''>to</span> <span m=''2479600''>analyze</span> <span m=''2480270''>the
  entire</span> <span m=''2481400''>program</span> <span m=''2481990''>and</span>
  <span m=''2482130''>I</span> <span m=''2482770''>have</span> <span m=''2483040''>function,</span>
  <span m=''2483470''>I''m</span> <span m=''2484180''>going to</span> <span m=''2484370''>go</span>
  <span m=''2484470''>and</span> <span m=''2484610''>try</span> <span m=''2484860''>to</span>
  <span m=''2484970''>analyze</span> <span m=''2485250''>the</span> <span m=''2485450''>function</span>
  <span m=''2485910''>itself also.</span> <span m=''2488830''>What</span> <span m=''2489100''>happens</span>
  <span m=''2489550''>is</span> <span m=''2489930''>--</span> <span m=''2491270''>so</span>
  <span m=''2491530''>assume</span> <span m=''2492110''>if the</span> <span m=''2492320''>functions</span>
  <span m=''2492750''>are</span> <span m=''2492960''>used</span> <span m=''2493220''>many,</span>
  <span m=''2493400''>many</span> <span m=''2493570''>times,</span> <span m=''2493880''>so</span>
  <span m=''2493980''>fine</span> <span m=''2494300''>function</span> <span m=''2495240''>might</span>
  <span m=''2495420''>be</span> <span m=''2495530''>used</span> <span m=''2496060''>hundreds</span>
  <span m=''2496530''>of</span> <span m=''2496803''>time.</span> </p><p><span m=''2497076''>So</span>
  <span m=''2497350''>every</span> <span m=''2497660''>time</span> <span m=''2497890''>you</span>
  <span m=''2497980''>have</span> <span m=''2498250''>a call of a sine</span> <span
  m=''2498880''>function,</span> <span m=''2499150''>if</span> <span m=''2499280''>you</span>
  <span m=''2499380''>keep</span> <span m=''2499640''>analyzing,</span> <span m=''2500200''>reanalyzing</span>
  <span m=''2500870''>what''s</span> <span m=''2501090''>happening</span> <span m=''2501390''>inside</span>
  <span m=''2501480''>of the</span> <span m=''2501650''>sine</span> <span m=''2501900''>function,</span>
  <span m=''2502480''>you</span> <span m=''2502710''>kind</span> <span m=''2502940''>of
  have</span> <span m=''2503010''>exponential</span> <span m=''2503260''>blow</span>
  <span m=''2503600''>up.</span> <span m=''2504450''>So if you</span> <span m=''2504640''>code</span>
  <span m=''2505310''>size</span> <span m=''2505530''>n,</span> <span m=''2506150''>you</span>
  <span m=''2506350''>might</span> <span m=''2506610''>have</span> <span m=''2507610''>an</span>
  <span m=''2507800''>exponential</span> <span m=''2508490''>time</span> <span m=''2508800''>of</span>
  <span m=''2509620''>a</span> <span m=''2509880''>number</span> <span m=''2510310''>of</span>
  <span m=''2510410''>lines that</span> <span m=''2510550''>need</span> <span m=''2510740''>to</span>
  <span m=''2510810''>be</span> <span m=''2510910''>analyzed</span> <span m=''2511220''>because</span>
  <span m=''2511420''>every</span> <span m=''2511640''>call</span> <span m=''2512070''>need
  to go</span> <span m=''2512320''>there,</span> <span m=''2512920''>call</span> <span
  m=''2513090''>some</span> <span m=''2513260''>other</span> <span m=''2513420''>functions,</span>
  <span m=''2513840''>you</span> <span m=''2513930''>can</span> <span m=''2514080''>see</span>
  <span m=''2514190''>the</span> <span m=''2514310''>blow up.</span> <span m=''2515490''>And</span>
  <span m=''2516440''>so</span> <span m=''2516540''>analysis</span> <span m=''2516700''>might</span>
  <span m=''2516850''>be</span> <span m=''2516960''>expensive.</span> <span m=''2517530''>Other</span>
  <span m=''2517880''>option</span> <span m=''2518180''>is</span> <span m=''2518740''>you</span>
  <span m=''2518970''>analyze each</span> <span m=''2519270''>function</span> <span
  m=''2520420''>once.</span> <span m=''2520620''>Yeah,</span> <span m=''2520870''>OK.</span>
  <span m=''2521910''>I</span> <span m=''2521970''>analyze</span> <span m=''2522210''>this</span>
  <span m=''2522360''>function</span> <span m=''2522480''>once</span> <span m=''2522770''>and</span>
  <span m=''2523000''>every</span> <span m=''2523200''>time</span> <span m=''2523400''>I</span>
  <span m=''2523460''>use</span> <span m=''2523950''>that</span> <span m=''2524160''>function</span>
  <span m=''2524500''>I</span> <span m=''2524570''>just</span> <span m=''2524820''>use</span>
  <span m=''2525020''>that analysis</span> <span m=''2525430''>information.</span>
  <span m=''2527990''>What</span> <span m=''2528200''>that</span> <span m=''2528430''>means</span>
  <span m=''2528830''>is you</span> <span m=''2528930''>have a</span> <span m=''2529130''>kind</span>
  <span m=''2529340''>of</span> <span m=''2529460''>summary</span> <span m=''2530930''>of</span>
  <span m=''2531140''>what</span> <span m=''2531310''>that</span> <span m=''2531450''>function</span>
  <span m=''2531870''>does</span> <span m=''2532090''>for</span> <span m=''2532220''>every</span>
  <span m=''2533110''>call.</span> <span m=''2533390''>This is</span> <span m=''2533560''>not</span>
  <span m=''2533740''>that</span> <span m=''2533930''>easy</span> <span m=''2534160''>and</span>
  <span m=''2534350''>this</span> <span m=''2534460''>runs</span> <span m=''2534930''>into
  a</span> <span m=''2535080''>thing</span> <span m=''2535400''>called</span> <span
  m=''2535580''>unrealizable</span> <span m=''2535900''>part</span> <span m=''2536530''>problem,</span>
  <span m=''2536910''>because</span> <span m=''2537560''>you</span> <span m=''2537920''>go</span>
  <span m=''2538170''>into</span> <span m=''2538400''>function in</span> <span m=''2538920''>one</span>
  <span m=''2539700''>part --</span> <span m=''2542210''>assume</span> <span m=''2542580''>you</span>
  <span m=''2542700''>call</span> <span m=''2542960''>foo</span> <span m=''2544430''>from</span>
  <span m=''2544650''>here</span> <span m=''2545380''>and return here.</span> <span
  m=''2546460''>You</span> <span m=''2547000''>call it here</span> <span m=''2548170''>and
  return and here.</span> <span m=''2548470''>So when you analyze,</span> <span m=''2549330''>normally</span>
  <span m=''2549760''>you</span> <span m=''2549890''>can</span> <span m=''2550170''>go</span>
  <span m=''2550340''>from</span> <span m=''2550510''>here</span> <span m=''2550870''>to</span>
  <span m=''2551110''>here,</span> <span m=''2551270''>here to here,</span> <span
  m=''2551970''>but</span> <span m=''2552240''>if</span> <span m=''2552370''>you</span>
  <span m=''2552490''>treat</span> <span m=''2552940''>foo as</span> <span m=''2553430''>only</span>
  <span m=''2553720''>one</span> <span m=''2554020''>thing you</span> <span m=''2554530''>might</span>
  <span m=''2554810''>be</span> <span m=''2554900''>able</span> <span m=''2555040''>to</span>
  <span m=''2555100''>even</span> <span m=''2555330''>think</span> <span m=''2555560''>that</span>
  <span m=''2555690''>you</span> <span m=''2555860''>can</span> <span m=''2556080''>go</span>
  <span m=''2556240''>here</span> <span m=''2556380''>to here and</span> <span m=''2556510''>here
  to</span> <span m=''2556600''>here.</span> <span m=''2558220''>So this</span> <span
  m=''2558830''>looks</span> <span m=''2559010''>like</span> <span m=''2559160''>one</span>
  <span m=''2559430''>thing in here.</span> <span m=''2560790''>You see that</span>
  <span m=''2561040''>control</span> <span m=''2562030''>here</span> <span m=''2562960''>goes
  here,</span> <span m=''2563740''>comes</span> <span m=''2564230''>here do a function
  call</span> <span m=''2564520''>goes</span> <span m=''2564790''>here,</span> <span
  m=''2565290''>because</span> <span m=''2565590''>we</span> <span m=''2565800''>are</span>
  <span m=''2565940''>not</span> <span m=''2566080''>treating</span> <span m=''2566550''>this</span>
  <span m=''2566730''>as</span> <span m=''2567530''>separate</span> <span m=''2567930''>instance.</span>
  </p><p><span m=''2568610''>So</span> <span m=''2568780''>why</span> <span m=''2568930''>did</span>
  <span m=''2569050''>are we</span> <span m=''2569140''>analyzing</span> <span m=''2569300''>it</span>
  <span m=''2569730''>once?</span> <span m=''2570480''>This</span> <span m=''2570690''>cleared</span>
  <span m=''2571130''>all</span> <span m=''2571300''>this</span> <span m=''2571410''>additional</span>
  <span m=''2571910''>mess</span> <span m=''2572170''>and</span> <span m=''2572350''>then</span>
  <span m=''2572460''>can</span> <span m=''2572650''>have</span> <span m=''2572810''>problems
  in here.</span> <span m=''2573770''>So</span> <span m=''2574500''>these</span> <span
  m=''2574830''>are</span> <span m=''2575010''>the</span> <span m=''2575260''>kind</span>
  <span m=''2575450''>of</span> <span m=''2575570''>researchy</span> <span m=''2575960''>things</span>
  <span m=''2576170''>people</span> <span m=''2576410''>are</span> <span m=''2576480''>working</span>
  <span m=''2576820''>on.</span> <span m=''2577210''>There''s</span> <span m=''2577400''>no</span>
  <span m=''2577540''>perfect</span> <span m=''2578010''>answer,</span> <span m=''2578260''>these
  are</span> <span m=''2579080''>complicated</span> <span m=''2579480''>problems,</span>
  <span m=''2579880''>so</span> <span m=''2579990''>you</span> <span m=''2580090''>had</span>
  <span m=''2580210''>to</span> <span m=''2580300''>do</span> <span m=''2580390''>some</span>
  <span m=''2580650''>interesting</span> <span m=''2581060''>balance</span> <span
  m=''2581760''>in here.</span> <span m=''2585770''>Because</span> <span m=''2586330''>other</span>
  <span m=''2586620''>thing</span> <span m=''2586920''>is</span> <span m=''2587190''>every</span>
  <span m=''2587370''>analyst</span> <span m=''2587660''>has</span> <span m=''2587780''>to</span>
  <span m=''2587870''>deal with</span> <span m=''2588130''>that,</span> <span m=''2588360''>so</span>
  <span m=''2588510''>you</span> <span m=''2588640''>had</span> <span m=''2588730''>to</span>
  <span m=''2588800''>kind</span> <span m=''2589000''>of</span> <span m=''2589090''>an</span>
  <span m=''2589260''>anti-compiler,</span> <span m=''2590030''>which</span> <span
  m=''2590220''>is</span> <span m=''2590300''>not</span> <span m=''2590430''>simple.</span>
  </p><p><span m=''2592940''>Inlining</span> <span m=''2593640''>is</span> <span m=''2593760''>much</span>
  <span m=''2593990''>more</span> <span m=''2594160''>easy.</span> <span m=''2594550''>It''s
  a</span> <span m=''2594730''>poor</span> <span m=''2594830''>man solution,</span>
  <span m=''2595700''>so</span> <span m=''2595940''>every</span> <span m=''2596120''>time</span>
  <span m=''2596290''>you</span> <span m=''2596360''>have</span> <span m=''2596500''>function</span>
  <span m=''2596700''>call,</span> <span m=''2596990''>you just</span> <span m=''2597840''>bring</span>
  <span m=''2598040''>the</span> <span m=''2598130''>function</span> <span m=''2598370''>and</span>
  <span m=''2598570''>just</span> <span m=''2598690''>copy it</span> <span m=''2599010''>in</span>
  <span m=''2599750''>there. And</span> <span m=''2599960''>every</span> <span m=''2600090''>time</span>
  <span m=''2600150''>you</span> <span m=''2600330''>have</span> <span m=''2600440''>function
  call you</span> <span m=''2600570''>bring</span> <span m=''2600710''>the</span>
  <span m=''2600810''>function</span> <span m=''2601230''>and</span> <span m=''2601510''>you</span>
  <span m=''2601570''>can</span> <span m=''2601710''>run it</span> <span m=''2601930''>through</span>
  <span m=''2602000''>the</span> <span m=''2602070''>same</span> <span m=''2602310''>compiler,</span>
  <span m=''2603170''>but</span> <span m=''2603410''>of</span> <span m=''2603510''>course,</span>
  <span m=''2603800''>you</span> <span m=''2603880''>can</span> <span m=''2604010''>have</span>
  <span m=''2604150''>huge</span> <span m=''2604450''>code blow up.</span> <span m=''2605510''>It''s
  not</span> <span m=''2605780''>only</span> <span m=''2606040''>analysis</span> <span
  m=''2606570''>expense,</span> <span m=''2606980''>you</span> <span m=''2607090''>might</span>
  <span m=''2607300''>have</span> <span m=''2607460''>a</span> <span m=''2608060''>function</span>
  <span m=''2608490''>that</span> <span m=''2608720''>before</span> <span m=''2609040''>had</span>
  <span m=''2609250''>only</span> <span m=''2609410''>100</span> <span m=''2609980''>lines,</span>
  <span m=''2610300''>now</span> <span m=''2610410''>we</span> <span m=''2610520''>have</span>
  <span m=''2610730''>millions</span> <span m=''2610820''>of</span> <span m=''2611160''>lines</span>
  <span m=''2611390''>in</span> <span m=''2611550''>there</span> <span m=''2611900''>and</span>
  <span m=''2612030''>then</span> <span m=''2612140''>try</span> <span m=''2612330''>and
  do</span> <span m=''2612520''>cache</span> <span m=''2612760''>problems,</span>
  <span m=''2613160''>all</span> <span m=''2613280''>those</span> <span m=''2613470''>other</span>
  <span m=''2613560''>issues.</span> <span m=''2614660''>So</span> <span m=''2615200''>can</span>
  <span m=''2615410''>be</span> <span m=''2615500''>very</span> <span m=''2615660''>expensive
  too.</span> <span m=''2616310''>So</span> <span m=''2616620''>what</span> <span
  m=''2616900''>people</span> <span m=''2617180''>do is</span> <span m=''2617340''>things</span>
  <span m=''2617570''>like</span> <span m=''2617990''>selective</span> <span m=''2618240''>inlining</span>
  <span m=''2618870''>and</span> <span m=''2619160''>a lot</span> <span m=''2619370''>of</span>
  <span m=''2619620''>kind</span> <span m=''2619800''>of</span> <span m=''2619880''>interesting</span>
  <span m=''2620210''>combinations</span> <span m=''2620720''>of these.</span> </p><p><span
  m=''2625970''>Finally,</span> <span m=''2626780''>loop</span> <span m=''2626980''>transformations.</span>
  <span m=''2628010''>So i</span> <span m=''2628160''>have</span> <span m=''2628330''>this</span>
  <span m=''2628490''>loop,</span> <span m=''2629850''>so</span> <span m=''2630120''>I</span>
  <span m=''2630210''>have</span> <span m=''2631050''>Aij</span> <span m=''2631820''>equals</span>
  <span m=''2632200''>Aij</span> <span m=''2632580''>minus</span> <span m=''2632920''>1,</span>
  <span m=''2633120''>A</span> <span m=''2633440''>i</span> <span m=''2633560''>minus</span>
  <span m=''2633780''>1 j</span> <span m=''2634710''>So look</span> <span m=''2634950''>at</span>
  <span m=''2635060''>my</span> <span m=''2635160''>--</span> <span m=''2635580''>my</span>
  <span m=''2635640''>arrowheads</span> <span m=''2635810''>look</span> <span m=''2636460''>too</span>
  <span m=''2636550''>big</span> <span m=''2636790''>there,</span> <span m=''2637000''>but</span>
  <span m=''2637600''>look at</span> <span m=''2637860''>my</span> <span m=''2637960''>dependences.</span>
  <span m=''2640280''>Is</span> <span m=''2640520''>any of this</span> <span m=''2641530''>parallel?</span>
  </p><p><span m=''2642020''>AUDIENCE:</span> <span m=''2647481''>[OBSCURED.]</span>
  </p><p><span m=''2650460''>PROFESSOR: Yeah.</span> <span m=''2653840''>So,</span>
  <span m=''2654410''>assays</span> <span m=''2655470''>neither --</span> <span m=''2656280''>you</span>
  <span m=''2656420''>can''t</span> <span m=''2656630''>parallelize</span> <span m=''2657000''>I</span>
  <span m=''2657730''>because</span> <span m=''2658060''>there''s</span> <span m=''2658240''>a
  loop</span> <span m=''2658500''>carry</span> <span m=''2658650''>dependence</span>
  <span m=''2659970''>in</span> <span m=''2660290''>I</span> <span m=''2660440''>dimension.</span>
  <span m=''2661260''>You</span> <span m=''2661610''>can''t</span> <span m=''2661770''>parallelize</span>
  <span m=''2662130''>J</span> <span m=''2662940''>because</span> <span m=''2663200''>there''s</span>
  <span m=''2663390''>loop</span> <span m=''2663510''>carry</span> <span m=''2663800''>dependence</span>
  <span m=''2664240''>in J diimension.</span> <span m=''2664900''>She</span> <span
  m=''2665080''>has</span> <span m=''2665280''>idea</span> <span m=''2665630''>because</span>
  <span m=''2666050''>you</span> <span m=''2666140''>can actually</span> <span m=''2666560''>pipeline.</span>
  <span m=''2667900''>So</span> <span m=''2668550''>pipelining,</span> <span m=''2669620''>we</span>
  <span m=''2669740''>haven''t</span> <span m=''2670090''>figured</span> <span m=''2670180''>out</span>
  <span m=''2670270''>how</span> <span m=''2670480''>to</span> <span m=''2670570''>parallelize</span>
  <span m=''2671040''>pipeline.</span> <span m=''2672070''>So</span> <span m=''2672370''>the</span>
  <span m=''2672540''>way</span> <span m=''2672810''>you</span> <span m=''2672970''>can</span>
  <span m=''2673180''>do</span> <span m=''2673300''>this</span> <span m=''2673520''>simply</span>
  <span m=''2673670''>is</span> <span m=''2674090''>a</span> <span m=''2674250''>thing</span>
  <span m=''2674490''>called</span> <span m=''2676200''>loop</span> <span m=''2676490''>skewing.</span>
  <span m=''2677410''>You</span> <span m=''2677600''>can</span> <span m=''2677780''>kind</span>
  <span m=''2678050''>of --</span> <span m=''2679040''>because</span> <span m=''2679270''>iteration</span>
  <span m=''2679480''>space</span> <span m=''2679860''>has</span> <span m=''2680820''>changed</span>
  <span m=''2681280''>from</span> <span m=''2681450''>a</span> <span m=''2681500''>data
  space.</span> <span m=''2682080''>You</span> <span m=''2682150''>can</span> <span
  m=''2682300''>come</span> <span m=''2682470''>up</span> <span m=''2682680''>with
  a</span> <span m=''2682750''>new</span> <span m=''2683060''>iteration</span> <span
  m=''2684460''>space that</span> <span m=''2684640''>kind</span> <span m=''2684900''>of</span>
  <span m=''2685090''>skew</span> <span m=''2685340''>the</span> <span m=''2685930''>loop</span>
  <span m=''2686080''>in there.</span> <span m=''2687790''>So</span> <span m=''2688180''>what</span>
  <span m=''2688380''>it</span> <span m=''2688460''>does</span> <span m=''2688830''>is</span>
  <span m=''2689050''>normally</span> <span m=''2689490''>iteration</span> <span m=''2689850''>space,</span>
  <span m=''2690180''>what</span> <span m=''2690450''>this J</span> <span m=''2691120''>outside,</span>
  <span m=''2691690''>so</span> <span m=''2691850''>you</span> <span m=''2691960''>go</span>
  <span m=''2692170''>execute</span> <span m=''2692680''>like</span> <span m=''2692890''>this.</span>
  <span m=''2694480''>The skill</span> <span m=''2695150''>that</span> <span m=''2695300''>--</span>
  <span m=''2695580''>loop</span> <span m=''2695760''>basically</span> <span m=''2696310''>say</span>
  <span m=''2697050''>I am</span> <span m=''2697300''>executing</span> <span m=''2697640''>this</span>
  <span m=''2697750''>way,</span> <span m=''2697850''>so</span> <span m=''2698270''>I''m</span>
  <span m=''2698440''>executing</span> <span m=''2698880''>the</span> <span m=''2698970''>pipeline,</span>
  <span m=''2699650''>basically</span> <span m=''2700080''>pipeline here.</span> <span
  m=''2700890''>So I''m</span> <span m=''2701110''>kind</span> <span m=''2701290''>of</span>
  <span m=''2701360''>going</span> <span m=''2701570''>like</span> <span m=''2701810''>this</span>
  <span m=''2702470''>way,</span> <span m=''2702860''>executing</span> <span m=''2703580''>that
  way.</span> <span m=''2704060''>If</span> <span m=''2704470''>I</span> <span m=''2704690''>could</span>
  <span m=''2705100''>run</span> <span m=''2705230''>that</span> <span m=''2705390''>loop</span>
  <span m=''2705760''>in</span> <span m=''2706450''>that</span> <span m=''2706670''>fashion,</span>
  <span m=''2707770''>what</span> <span m=''2707950''>I</span> <span m=''2708060''>can</span>
  <span m=''2708280''>do</span> <span m=''2708430''>is</span> <span m=''2709470''>I</span>
  <span m=''2709600''>can</span> <span m=''2709850''>run</span> <span m=''2710020''>this
  --</span> <span m=''2710660''>after</span> <span m=''2711010''>this</span> <span
  m=''2711170''>iteration,</span> <span m=''2711830''>when</span> <span m=''2712130''>you</span>
  <span m=''2712310''>go</span> <span m=''2712530''>run the</span> <span m=''2712600''>next</span>
  <span m=''2712920''>iteration,</span> <span m=''2713410''>there''s</span> <span
  m=''2714180''>no</span> <span m=''2714340''>dependence</span> <span m=''2714450''>across</span>
  <span m=''2714750''>here.</span> <span m=''2716340''>If</span> <span m=''2716470''>I</span>
  <span m=''2716590''>run</span> <span m=''2716720''>here, I</span> <span m=''2716830''>don''t</span>
  <span m=''2716980''>have</span> <span m=''2717090''>dependence,</span> <span m=''2717630''>so</span>
  <span m=''2717820''>I</span> <span m=''2717960''>can run</span> <span m=''2718110''>each</span>
  <span m=''2718340''>of</span> <span m=''2718490''>these</span> <span m=''2719080''>and</span>
  <span m=''2719270''>I</span> <span m=''2719460''>have</span> <span m=''2719680''>a
  parallel</span> <span m=''2719860''>set of</span> <span m=''2720340''>iterations</span>
  <span m=''2720560''>to</span> <span m=''2720940''>run.</span> <span m=''2722510''>So</span>
  <span m=''2722670''>in here,</span> <span m=''2723310''>what</span> <span m=''2723500''>happens</span>
  <span m=''2723810''>is</span> <span m=''2724240''>this</span> <span m=''2724760''>inner</span>
  <span m=''2724950''>loop</span> <span m=''2725070''>it</span> <span m=''2725350''>can</span>
  <span m=''2725570''>be</span> <span m=''2725670''>parallel,</span> <span m=''2727700''>basically</span>
  <span m=''2727950''>like</span> <span m=''2728040''>your</span> <span m=''2728310''>pipeline,</span>
  <span m=''2729260''>but</span> <span m=''2729590''>it''s</span> <span m=''2729910''>written</span>
  <span m=''2730070''>in</span> <span m=''2730200''>a</span> <span m=''2730340''>way</span>
  <span m=''2730740''>that</span> <span m=''2730890''>I</span> <span m=''2730970''>still</span>
  <span m=''2731210''>have</span> <span m=''2731400''>my</span> <span m=''2731580''>two</span>
  <span m=''2731820''>loops</span> <span m=''2732710''>in here,</span> <span m=''2732990''>but</span>
  <span m=''2733120''>I have</span> <span m=''2733290''>done</span> <span m=''2734010''>this
  weird</span> <span m=''2734220''>transformation.</span> </p><p><span m=''2736700''>Another</span>
  <span m=''2736820''>interesting</span> <span m=''2737380''>is</span> <span m=''2737500''>granularity</span>
  <span m=''2737720''>of</span> <span m=''2738250''>parallelism.</span> <span m=''2738430''>Assume</span>
  <span m=''2738570''>I</span> <span m=''2738680''>have</span> <span m=''2738870''>a</span>
  <span m=''2738970''>loop</span> <span m=''2739360''>like</span> <span m=''2739560''>that,</span>
  <span m=''2740200''>i and j.</span> <span m=''2740950''>Which</span> <span m=''2741160''>loop
  is that</span> <span m=''2741290''>in here?</span> <span m=''2744150''>i or j?</span>
  <span m=''2746050''>j</span> <span m=''2746390''>is parallel.</span> <span m=''2747740''>OK,
  I</span> <span m=''2747860''>do</span> <span m=''2748050''>something</span> <span
  m=''2748360''>like</span> <span m=''2748520''>that.</span> <span m=''2748700''>I</span>
  <span m=''2748790''>say</span> <span m=''2749040''>I</span> <span m=''2749190''>run</span>
  <span m=''2749380''>i,</span> <span m=''2750080''>every iteration</span> <span m=''2750760''>I</span>
  <span m=''2750970''>do a</span> <span m=''2751040''>barrier,</span> <span m=''2751320''>I</span>
  <span m=''2751920''>run</span> <span m=''2752300''>j</span> <span m=''2752580''>parallel</span>
  <span m=''2753260''>and</span> <span m=''2753430''>I</span> <span m=''2753540''>end</span>
  <span m=''2753720''>up</span> <span m=''2754010''>doing</span> <span m=''2754310''>a</span>
  <span m=''2754540''>barrier</span> <span m=''2754590''>again.</span> <span m=''2756770''>What</span>
  <span m=''2757010''>might</span> <span m=''2757210''>be</span> <span m=''2757270''>a</span>
  <span m=''2757310''>problem</span> <span m=''2757660''>in</span> <span m=''2757810''>something</span>
  <span m=''2758110''>like</span> <span m=''2758270''>this?</span> </p><p><span m=''2765510''>I</span>
  <span m=''2765600''>mean</span> <span m=''2767260''>inner</span> <span m=''2767550''>parallelism</span>
  <span m=''2768030''>can</span> <span m=''2768270''>be</span> <span m=''2768340''>expensive,</span>
  <span m=''2768850''>because</span> <span m=''2769130''>every</span> <span m=''2769440''>time</span>
  <span m=''2769710''>I</span> <span m=''2770160''>had</span> <span m=''2770340''>to</span>
  <span m=''2770410''>do</span> <span m=''2770770''>this</span> <span m=''2771040''>probably</span>
  <span m=''2771570''>expensive</span> <span m=''2771690''>barrier,</span> <span m=''2772440''>run</span>
  <span m=''2772950''>a few</span> <span m=''2773120''>iterations,</span> <span m=''2773500''>a
  few</span> <span m=''2773840''>in</span> <span m=''2774200''>this</span> <span m=''2774390''>one,</span>
  <span m=''2774640''>probably</span> <span m=''2774870''>only</span> <span m=''2774960''>like</span>
  <span m=''2775200''>a few cycles.</span> <span m=''2776850''>And write</span> <span
  m=''2776950''>this</span> <span m=''2777030''>very expensive</span> <span m=''2777400''>barrier</span>
  <span m=''2777880''>again,</span> <span m=''2778360''>and</span> <span m=''2778600''>everybody</span>
  <span m=''2778980''>communicates --</span> <span m=''2780440''>all of</span> <span
  m=''2780700''>those</span> <span m=''2780940''>things.</span> <span m=''2783050''>Most</span>
  <span m=''2783370''>of the time</span> <span m=''2783640''>when you do</span> <span
  m=''2784050''>inner loop</span> <span m=''2784600''>parallelism</span> <span m=''2784950''>it
  actually</span> <span m=''2785390''>slows</span> <span m=''2785610''>down</span>
  <span m=''2785780''>the program.</span> <span m=''2787510''>You will</span> <span
  m=''2787760''>probably</span> <span m=''2788020''>find</span> <span m=''2788300''>it</span>
  <span m=''2788410''>too</span> <span m=''2788600''>sometimes,</span> <span m=''2788910''>if</span>
  <span m=''2789020''>you</span> <span m=''2789090''>define</span> <span m=''2789420''>the</span>
  <span m=''2789640''>parallelism</span> <span m=''2789730''>inner</span> <span m=''2789840''>array</span>
  <span m=''2790250''>to</span> <span m=''2790360''>be</span> <span m=''2790450''>too</span>
  <span m=''2790640''>small,</span> <span m=''2791390''>it</span> <span m=''2791690''>actually</span>
  <span m=''2791830''>has</span> <span m=''2791980''>a</span> <span m=''2792060''>negative</span>
  <span m=''2792410''>impact,</span> <span m=''2793060''>because</span> <span m=''2793320''>all</span>
  <span m=''2793520''>the</span> <span m=''2793640''>communication</span> <span m=''2794310''>you
  need</span> <span m=''2794520''>to do,</span> <span m=''2794780''>synchronization</span>
  <span m=''2795160''>you</span> <span m=''2795270''>need</span> <span m=''2795540''>to</span>
  <span m=''2795670''>do</span> <span m=''2795800''>all of them</span> <span m=''2797040''>out</span>
  <span m=''2797290''>of</span> <span m=''2797490''>the</span> <span m=''2797560''>program.</span>
  </p><p><span m=''2799740''>So</span> <span m=''2799980''>inner</span> <span m=''2800050''>loop</span>
  <span m=''2800340''>is</span> <span m=''2800470''>expensive.</span> <span m=''2800920''>What</span>
  <span m=''2801040''>are</span> <span m=''2801240''>your choices?</span> <span m=''2802650''>Don''t</span>
  <span m=''2802950''>parallelize.</span> <span m=''2804140''>Pretty</span> <span
  m=''2804390''>good</span> <span m=''2804520''>choice</span> <span m=''2804810''>for</span>
  <span m=''2805490''>a lot of</span> <span m=''2805820''>cases.</span> <span m=''2805980''>You
  look at this and</span> <span m=''2806140''>this</span> <span m=''2806240''>is</span>
  <span m=''2806360''>actually</span> <span m=''2806520''>going to</span> <span m=''2806730''>win
  you</span> <span m=''2807510''>basically</span> <span m=''2807850''>by</span> <span
  m=''2808640''>doing that.</span> <span m=''2809530''>Or can you</span> <span m=''2809640''>transform</span>
  <span m=''2810270''>it to</span> <span m=''2810560''>outer loop parallelism.</span>
  <span m=''2811960''>Take</span> <span m=''2812210''>inner</span> <span m=''2812280''>loop</span>
  <span m=''2812400''>parallelism</span> <span m=''2812520''>and you</span> <span
  m=''2813350''>change</span> <span m=''2814130''>it to</span> <span m=''2814240''>get</span>
  <span m=''2814370''>outer</span> <span m=''2814540''>loop</span> <span m=''2814670''>parallelism.</span>
  <span m=''2815120''>This</span> <span m=''2815290''>program</span> <span m=''2815750''>is
  actually</span> <span m=''2816100''>nice,</span> <span m=''2816430''>there are</span>
  <span m=''2816740''>some complex</span> <span m=''2817070''>analysis</span> <span
  m=''2817270''>you need to</span> <span m=''2817500''>do</span> <span m=''2817630''>to</span>
  <span m=''2818250''>make</span> <span m=''2818490''>sure</span> <span m=''2818610''>that''s</span>
  <span m=''2818810''>legal.</span> <span m=''2819710''>So you</span> <span m=''2819870''>can</span>
  <span m=''2820090''>basically</span> <span m=''2820560''>take</span> <span m=''2820860''>this</span>
  <span m=''2821040''>one</span> <span m=''2822490''>and</span> <span m=''2823390''>transform</span>
  <span m=''2823720''>in</span> <span m=''2823940''>other</span> <span m=''2824290''>direction.</span>
  <span m=''2826170''>What</span> <span m=''2826300''>that</span> <span m=''2826490''>means</span>
  <span m=''2826690''>is</span> <span m=''2826850''>kind</span> <span m=''2827110''>of</span>
  <span m=''2828000''>do</span> <span m=''2829130''>a</span> <span m=''2829770''>loop</span>
  <span m=''2830480''>interchange.</span> <span m=''2830780''>So</span> <span m=''2830990''>now</span>
  <span m=''2831640''>instead of i,</span> <span m=''2832150''>you</span> <span m=''2832330''>have</span>
  <span m=''2832610''>a</span> <span m=''2832690''>a j</span> <span m=''2832870''>outer
  dimension,</span> <span m=''2833160''>i</span> <span m=''2833380''>inner</span>
  <span m=''2833500''>dimension,</span> <span m=''2834550''>inner loop.</span> <span
  m=''2836050''>When</span> <span m=''2836210''>you</span> <span m=''2836330''>do</span>
  <span m=''2836550''>that</span> <span m=''2836900''>what</span> <span m=''2837200''>you</span>
  <span m=''2837260''>have</span> <span m=''2837470''>is</span> <span m=''2837560''>your</span>
  <span m=''2837870''>barrier,</span> <span m=''2839290''>and</span> <span m=''2839560''>then</span>
  <span m=''2839660''>you can</span> <span m=''2839770''>run</span> <span m=''2840360''>this
  is</span> <span m=''2840520''>parallel</span> <span m=''2841210''>and</span> <span
  m=''2841410''>this</span> <span m=''2842040''>like</span> <span m=''2842250''>this.</span>
  <span m=''2843750''>Suddenly,</span> <span m=''2844640''>instead</span> <span m=''2845050''>of</span>
  <span m=''2845190''>having</span> <span m=''2846690''>n</span> <span m=''2846970''>barriers</span>
  <span m=''2848920''>for</span> <span m=''2849090''>that</span> <span m=''2849260''>loop,</span>
  <span m=''2849940''>you have</span> <span m=''2850030''>only</span> <span m=''2850300''>one</span>
  <span m=''2850530''>barrier.</span> <span m=''2851740''>Suddenly</span> <span m=''2852170''>you
  have</span> <span m=''2852330''>a much</span> <span m=''2852650''>larger</span>
  <span m=''2852880''>chunk</span> <span m=''2853020''>you''re</span> <span m=''2853210''>running,</span>
  <span m=''2854940''>and</span> <span m=''2855140''>this</span> <span m=''2855260''>can</span>
  <span m=''2855430''>be</span> <span m=''2855570''>run.</span> </p><p><span m=''2861070''>OK,</span>
  <span m=''2861970''>so</span> <span m=''2862120''>this</span> <span m=''2862270''>is</span>
  <span m=''2862400''>great.</span> <span m=''2862670''>So</span> <span m=''2862800''>I</span>
  <span m=''2862880''>talked</span> <span m=''2863210''>to</span> <span m=''2863310''>all</span>
  <span m=''2863440''>about</span> <span m=''2863600''>all</span> <span m=''2863800''>this</span>
  <span m=''2864010''>nice</span> <span m=''2864290''>transformation,</span> <span
  m=''2864960''>stuff</span> <span m=''2865240''>like</span> <span m=''2865450''>that.</span>
  <span m=''2865690''>So</span> <span m=''2866090''>at</span> <span m=''2866180''>some</span>
  <span m=''2866430''>point</span> <span m=''2866780''>when</span> <span m=''2866900''>you</span>
  <span m=''2866990''>know</span> <span m=''2867120''>something</span> <span m=''2867400''>is</span>
  <span m=''2867500''>parallel</span> <span m=''2867740''>you</span> <span m=''2867790''>might</span>
  <span m=''2868030''>want to</span> <span m=''2868190''>go</span> <span m=''2868330''>and</span>
  <span m=''2868600''>generate</span> <span m=''2868770''>parallel</span> <span m=''2868860''>form.</span>
  <span m=''2871330''>So</span> <span m=''2871480''>the</span> <span m=''2871570''>problem</span>
  <span m=''2872040''>is,</span> <span m=''2873310''>depending</span> <span m=''2873890''>on</span>
  <span m=''2874810''>how</span> <span m=''2875100''>you</span> <span m=''2875180''>partition,</span>
  <span m=''2875840''>the</span> <span m=''2875930''>loop</span> <span m=''2876150''>bound</span>
  <span m=''2876780''>has to</span> <span m=''2877070''>be changed,</span> <span m=''2877510''>and</span>
  <span m=''2877650''>I''m</span> <span m=''2877730''>going to</span> <span m=''2877940''>talk
  to you</span> <span m=''2878270''>about</span> <span m=''2878460''>how to</span>
  <span m=''2878750''>get</span> <span m=''2878820''>loop bound.</span> <span m=''2880030''>So</span>
  <span m=''2880240''>let''s</span> <span m=''2880470''>look</span> <span m=''2880590''>at</span>
  <span m=''2880730''>this</span> <span m=''2880930''>program.</span> <span m=''2882440''>So</span>
  <span m=''2882610''>I</span> <span m=''2882670''>have</span> <span m=''2882920''>something</span>
  <span m=''2883830''>in</span> <span m=''2884030''>here</span> <span m=''2884560''>and</span>
  <span m=''2887940''>there''s</span> <span m=''2888130''>an</span> <span m=''2888220''>inner</span>
  <span m=''2888390''>loop</span> <span m=''2888610''>that</span> <span m=''2888790''>actually
  reads,</span> <span m=''2889340''>outer</span> <span m=''2889560''>loop</span> <span
  m=''2889710''>writes.</span> <span m=''2889980''>Inner</span> <span m=''2890140''>loop</span>
  <span m=''2890290''>reads.</span> <span m=''2890660''>And</span> <span m=''2891060''>it''s</span>
  <span m=''2891120''>a</span> <span m=''2891260''>triangular</span> <span m=''2892240''>thing.</span>
  <span m=''2893050''>It''s a big mess.</span> <span m=''2894300''>Now</span> <span
  m=''2894480''>I</span> <span m=''2894550''>assume</span> <span m=''2894680''>I</span>
  <span m=''2894950''>want</span> <span m=''2895090''>to</span> <span m=''2895150''>run</span>
  <span m=''2897160''>the</span> <span m=''2897540''>i</span> <span m=''2897740''>loop</span>
  <span m=''2897900''>parallel.</span> <span m=''2899110''>So</span> <span m=''2899240''>what</span>
  <span m=''2899450''>that</span> <span m=''2899700''>means</span> <span m=''2900140''>is
  I</span> <span m=''2900940''>want to run</span> <span m=''2901520''>the</span> <span
  m=''2901810''>first</span> <span m=''2902090''>process --</span> <span m=''2902860''>there
  is no for</span> <span m=''2903110''>this</span> <span m=''2903320''>one,</span>
  <span m=''2903790''>this one on</span> <span m=''2904190''>one iteration,</span>
  <span m=''2904610''>two</span> <span m=''2904900''>iteration,</span> <span m=''2905200''>three,</span>
  <span m=''2905680''>four,</span> <span m=''2906410''>whatever,</span> <span m=''2906670''>each
  one''s in here.</span> <span m=''2908450''>How</span> <span m=''2908570''>do</span>
  <span m=''2908870''>I</span> <span m=''2909050''>actually</span> <span m=''2909520''>go</span>
  <span m=''2909850''>about</span> <span m=''2910860''>generating</span> <span m=''2911390''>code</span>
  <span m=''2912000''>that</span> <span m=''2912170''>actually</span> <span m=''2912220''>does</span>
  <span m=''2912480''>that?</span> <span m=''2913750''>Each</span> <span m=''2914070''>processor</span>
  <span m=''2914440''>runs</span> <span m=''2914510''>its</span> <span m=''2914640''>right</span>
  <span m=''2915190''>number</span> <span m=''2915440''>of iteration.</span> <span
  m=''2916740''>This</span> <span m=''2916880''>is a</span> <span m=''2917230''>non-trivial</span>
  <span m=''2917760''>thing</span> <span m=''2917980''>because</span> <span m=''2918540''>triangularly</span>
  <span m=''2918820''>you</span> <span m=''2919230''>get</span> <span m=''2919410''>something</span>
  <span m=''2919730''>different</span> <span m=''2920520''>and</span> <span m=''2920700''>you</span>
  <span m=''2920770''>can</span> <span m=''2920960''>assume</span> <span m=''2922100''>all</span>
  <span m=''2922340''>this</span> <span m=''2922430''>complexity.</span> <span m=''2924090''>One</span>
  <span m=''2924330''>thing</span> <span m=''2924490''>I</span> <span m=''2924560''>did</span>
  <span m=''2924860''>is</span> <span m=''2926070''>my</span> <span m=''2926840''>iteration</span>
  <span m=''2927330''>space</span> <span m=''2927660''>between</span> <span m=''2927850''>i
  and</span> <span m=''2928250''>j,</span> <span m=''2928900''>this is</span> <span
  m=''2929170''>my</span> <span m=''2931790''>iteration space.</span> <span m=''2934050''>So</span>
  <span m=''2934150''>I</span> <span m=''2934270''>assume,</span> <span m=''2934770''>assume</span>
  <span m=''2935220''>I am</span> <span m=''2935370''>running</span> <span m=''2935620''>a</span>
  <span m=''2935680''>processor.</span> <span m=''2936150''>Each</span> <span m=''2936460''>I</span>
  <span m=''2936740''>iteration</span> <span m=''2937380''>run by</span> <span m=''2937760''>your</span>
  <span m=''2937820''>processor,</span> <span m=''2938260''>you can</span> <span m=''2938650''>say</span>
  <span m=''2939160''>you</span> <span m=''2939320''>have</span> <span m=''2939410''>then</span>
  <span m=''2939570''>another</span> <span m=''2940010''>dimension</span> <span m=''2940500''>P,</span>
  <span m=''2941220''>and say</span> <span m=''2941390''>i</span> <span m=''2941740''>equals</span>
  <span m=''2941970''>P.</span> <span m=''2944160''>So</span> <span m=''2944300''>I</span>
  <span m=''2944380''>can</span> <span m=''2944580''>look</span> <span m=''2944710''>at</span>
  <span m=''2944860''>now</span> <span m=''2945020''>instead</span> <span m=''2945240''>of</span>
  <span m=''2945380''>a</span> <span m=''2945740''>two dimensional</span> <span m=''2946070''>space</span>
  <span m=''2946430''>in</span> <span m=''2946520''>a</span> <span m=''2946610''>three</span>
  <span m=''2946770''>dimensional</span> <span m=''2947290''>space.</span> <span m=''2948300''>So</span>
  <span m=''2948480''>in</span> <span m=''2948640''>this</span> <span m=''2948880''>analysis,</span>
  <span m=''2949400''>if</span> <span m=''2949530''>you</span> <span m=''2949600''>can</span>
  <span m=''2949750''>think</span> <span m=''2950090''>multi-dimensionally</span>
  <span m=''2950340''>it''s</span> <span m=''2950800''>actually</span> <span m=''2950940''>very</span>
  <span m=''2951200''>helpful</span> <span m=''2951630''>because</span> <span m=''2952060''>we</span>
  <span m=''2952150''>can</span> <span m=''2952300''>kind</span> <span m=''2952500''>of</span>
  <span m=''2952570''>keep</span> <span m=''2952800''>adding</span> <span m=''2953010''>dimensions</span>
  <span m=''2953480''>in here.</span> </p><p><span m=''2955970''>So</span> <span m=''2956690''>what</span>
  <span m=''2956850''>are</span> <span m=''2956900''>the</span> <span m=''2957070''>loop</span>
  <span m=''2957150''>bounds</span> <span m=''2957500''>in</span> <span m=''2957590''>here?</span>
  <span m=''2959380''>What</span> <span m=''2959590''>we</span> <span m=''2959720''>can</span>
  <span m=''2959980''>do</span> <span m=''2960230''>is</span> <span m=''2960850''>use</span>
  <span m=''2961340''>another</span> <span m=''2961620''>technique</span> <span m=''2962120''>called</span>
  <span m=''2962600''>Fourier-Motzkin</span> <span m=''2963100''>Elimination</span>
  <span m=''2964510''>to</span> <span m=''2964630''>calculate</span> <span m=''2965070''>loop</span>
  <span m=''2965250''>bounds</span> <span m=''2965890''>by</span> <span m=''2966100''>using</span>
  <span m=''2966530''>projections</span> <span m=''2966760''>of</span> <span m=''2966960''>the</span>
  <span m=''2967150''>iteration</span> <span m=''2967480''>space.</span> <span m=''2968040''>I</span>
  <span m=''2968110''>will</span> <span m=''2968300''>go</span> <span m=''2968720''>through
  later a bit</span> <span m=''2968890''>to</span> <span m=''2969040''>give</span>
  <span m=''2969210''>you</span> <span m=''2969290''>a</span> <span m=''2969330''>flavor
  for</span> <span m=''2969700''>what</span> <span m=''2969840''>it</span> <span m=''2970470''>is.
  It''s</span> <span m=''2970700''>also,</span> <span m=''2971310''>if you</span>
  <span m=''2971530''>are in</span> <span m=''2971770''>to</span> <span m=''2972480''>linear</span>
  <span m=''2972790''>programming,</span> <span m=''2973640''>this is</span> <span
  m=''2973910''>kind</span> <span m=''2974130''>of</span> <span m=''2974190''>extension</span>
  <span m=''2974630''>techniques</span> <span m=''2974990''>on</span> <span m=''2975170''>that.</span>
  <span m=''2977850''>So</span> <span m=''2978680''>the</span> <span m=''2978800''>way
  we look at</span> <span m=''2979160''>that</span> <span m=''2979560''>is --</span>
  <span m=''3006390''>A</span> <span m=''3006750''>little</span> <span m=''3007670''>bit</span>
  <span m=''3008010''>too</span> <span m=''3009970''>far.</span> <span m=''3010960''>I</span>
  <span m=''3011050''>didn''t</span> <span m=''3011430''>realize</span> <span m=''3013360''>MAC</span>
  <span m=''3013760''>can</span> <span m=''3016950''>be</span> <span m=''3017180''>this</span>
  <span m=''3017740''>slow.</span> </p><p><span m=''3018600''>[ASIDE CONVERSATION]</span>
  <span m=''3026480''>See</span> <span m=''3027160''>this is</span> <span m=''3027280''>why</span>
  <span m=''3027390''>we</span> <span m=''3027910''>need</span> <span m=''3028340''>parallelism</span>
  <span m=''3028600''>if</span> <span m=''3028780''>you think</span> <span m=''3028920''>this
  running fast.</span> <span m=''3029270''>So</span> <span m=''3029790''>what</span>
  <span m=''3030060''>you</span> <span m=''3030090''>can</span> <span m=''3030360''>do</span>
  <span m=''3030590''>is</span> <span m=''3030770''>you can</span> <span m=''3030810''>think</span>
  <span m=''3031320''>about</span> <span m=''3031970''>this</span> <span m=''3033000''>as
  this  three dimensional</span> <span m=''3033730''>space.</span> <span m=''3034960''>i,</span>
  <span m=''3035160''>j</span> <span m=''3035670''>and</span> <span m=''3035860''>p.</span>
  <span m=''3036400''>And</span> <span m=''3036610''>because</span> <span m=''3037010''>i</span>
  <span m=''3037290''>is equal</span> <span m=''3037580''>to</span> <span m=''3037880''>p,</span>
  <span m=''3038540''>if</span> <span m=''3038690''>you</span> <span m=''3038790''>get</span>
  <span m=''3038960''>i</span> <span m=''3039380''>and</span> <span m=''3039550''>p,</span>
  <span m=''3039660''>get</span> <span m=''3039810''>a</span> <span m=''3039850''>line
  in</span> <span m=''3040290''>that</span> <span m=''3040510''>dimension</span> <span
  m=''3040910''>and</span> <span m=''3041050''>then</span> <span m=''3041230''>j</span>
  <span m=''3041520''>goes</span> <span m=''3041690''>there.</span> <span m=''3041960''>So
  this is the</span> <span m=''3042390''>kind</span> <span m=''3042600''>of</span>
  <span m=''3042700''>iteration</span> <span m=''3043070''>space in here,</span> <span
  m=''3043900''>and</span> <span m=''3044050''>that</span> <span m=''3044250''>represents</span>
  <span m=''3045120''>inequalities here.</span> </p><p><span m=''3047930''>So</span>
  <span m=''3048120''>what</span> <span m=''3048360''>I</span> <span m=''3048890''>want</span>
  <span m=''3049210''>is</span> <span m=''3049290''>a</span> <span m=''3049470''>loop</span>
  <span m=''3050260''>where</span> <span m=''3050420''>outer</span> <span m=''3050980''>dimension</span>
  <span m=''3051320''>is</span> <span m=''3051450''>p,</span> <span m=''3052310''>then</span>
  <span m=''3052540''>the</span> <span m=''3052630''>next</span> <span m=''3052870''>dimension</span>
  <span m=''3053220''>is</span> <span m=''3053360''>i</span> <span m=''3053610''>and</span>
  <span m=''3053860''>j.</span> <span m=''3054800''>We</span> <span m=''3055210''>can</span>
  <span m=''3055350''>think</span> <span m=''3055540''>about</span> <span m=''3055750''>it
  like</span> <span m=''3055940''>that.</span> <span m=''3056420''>So</span> <span
  m=''3056570''>what</span> <span m=''3056720''>that</span> <span m=''3056920''>means</span>
  <span m=''3057220''>is I</span> <span m=''3057330''>need</span> <span m=''3057500''>to</span>
  <span m=''3057580''>get</span> <span m=''3058130''>my</span> <span m=''3058420''>iteration</span>
  <span m=''3059010''>ordering --</span> <span m=''3060040''>when</span> <span m=''3060230''>it
  happens,</span> <span m=''3060940''>you just go</span> <span m=''3061780''>like</span>
  <span m=''3062210''>that.</span> <span m=''3064140''>All right,</span> <span m=''3064580''>about</span>
  <span m=''3064760''>doing</span> <span m=''3064990''>that.</span> <span m=''3065190''>So</span>
  <span m=''3065330''>this</span> <span m=''3065510''>is</span> <span m=''3065630''>the</span>
  <span m=''3065730''>kind</span> <span m=''3066250''>of</span> <span m=''3066380''>loop</span>
  <span m=''3066550''>I want to</span> <span m=''3066710''>generate -- let</span>
  <span m=''3067350''>me</span> <span m=''3067460''>go and</span> <span m=''3067680''>show
  you</span> <span m=''3067920''>how</span> <span m=''3068080''>we</span> <span m=''3068180''>generate</span>
  <span m=''3068380''>that.</span> <span m=''3085530''>So</span> <span m=''3085760''>here''s</span>
  <span m=''3086060''>my</span> <span m=''3086260''>space</span> <span m=''3087030''>in
  here,</span> <span m=''3087180''>so</span> <span m=''3087250''>first</span> <span
  m=''3087570''>one</span> <span m=''3087750''>I</span> <span m=''3087870''>want</span>
  <span m=''3088100''>to</span> <span m=''3088190''>do</span> <span m=''3088400''>is</span>
  <span m=''3089440''>my</span> <span m=''3089750''>inner</span> <span m=''3089950''>most</span>
  <span m=''3090200''>dimension</span> <span m=''3090500''>is</span> <span m=''3091030''>j.</span>
  <span m=''3092100''>And</span> <span m=''3092420''>what</span> <span m=''3092580''>I</span>
  <span m=''3092660''>can</span> <span m=''3092900''>do</span> <span m=''3092970''>is</span>
  <span m=''3093110''>I</span> <span m=''3093190''>can</span> <span m=''3093370''>look</span>
  <span m=''3093460''>at</span> <span m=''3093690''>this</span> <span m=''3093860''>thing</span>
  <span m=''3094140''>and</span> <span m=''3094300''>say</span> <span m=''3094360''>what</span>
  <span m=''3094690''>are</span> <span m=''3094830''>the</span> <span m=''3095000''>bounds
  of</span> <span m=''3095310''>j.</span> <span m=''3096540''>So,</span> <span m=''3097310''>for
  each</span> <span m=''3097670''>of</span> <span m=''3097890''>the</span> <span m=''3098020''>bounds
  of</span> <span m=''3098520''>j</span> <span m=''3098720''>can</span> <span m=''3098900''>be</span>
  <span m=''3099010''>described</span> <span m=''3099510''>by</span> <span m=''3099810''>--</span>
  <span m=''3100370''>with</span> <span m=''3100790''>p and</span> <span m=''3101000''>i.</span>
  <span m=''3101520''>I''ll</span> <span m=''3101640''>actually</span> <span m=''3101990''>show</span>
  <span m=''3102160''>you</span> <span m=''3102580''>how to do</span> <span m=''3102790''>that
  in</span> <span m=''3103190''>little</span> <span m=''3103640''>while.</span> <span
  m=''3104470''>Then</span> <span m=''3104860''>I</span> <span m=''3104980''>will</span>
  <span m=''3105230''>get</span> <span m=''3106300''>j</span> <span m=''3106750''>goes</span>
  <span m=''3107020''>from</span> <span m=''3109450''>1</span> <span m=''3109860''>to
  i</span> <span m=''3110080''>minus</span> <span m=''3110430''>1.</span> <span m=''3111180''>Then</span>
  <span m=''3111270''>after</span> <span m=''3111610''>that</span> <span m=''3111730''>I</span>
  <span m=''3111840''>can</span> <span m=''3112060''>basically</span> <span m=''3112490''>project</span>
  <span m=''3113140''>it</span> <span m=''3113330''>into</span> <span m=''3113520''>to</span>
  <span m=''3113740''>eliminate</span> <span m=''3113980''>j</span> <span m=''3114180''>dimension.</span>
  </p><p><span m=''3114580''>So</span> <span m=''3115240''>what</span> <span m=''3115420''>I''m</span>
  <span m=''3115580''>doing</span> <span m=''3115800''>is I''m</span> <span m=''3116080''>going
  to have a three dimension</span> <span m=''3116830''>and I</span> <span m=''3116890''>project</span>
  <span m=''3117100''>into</span> <span m=''3117440''>two</span> <span m=''3117590''>dimensions</span>
  <span m=''3118520''>without</span> <span m=''3118860''>j</span> <span m=''3119120''>anymore,</span>
  <span m=''3119480''>because</span> <span m=''3119670''>now</span> <span m=''3119780''>all</span>
  <span m=''3119940''>I</span> <span m=''3119970''>have</span> <span m=''3120440''>left
  is</span> <span m=''3120710''>i</span> <span m=''3120910''>p</span> <span m=''3121330''>and</span>
  <span m=''3121500''>I</span> <span m=''3121530''>get</span> <span m=''3121690''>a</span>
  <span m=''3121730''>line in</span> <span m=''3122070''>that</span> <span m=''3122240''>dimension.</span>
  <span m=''3124110''>Then</span> <span m=''3124540''>what</span> <span m=''3124760''>I</span>
  <span m=''3124850''>have to  do</span> <span m=''3125270''>is now</span> <span m=''3125440''>I</span>
  <span m=''3125480''>had to find</span> <span m=''3125740''>i.</span> <span m=''3126250''>What</span>
  <span m=''3126530''>are</span> <span m=''3126730''>my</span> <span m=''3126780''>bounds</span>
  <span m=''3127150''>of</span> <span m=''3127310''>i?</span> <span m=''3130110''>And</span>
  <span m=''3131270''>bounds of</span> <span m=''3131710''>i</span> <span m=''3131990''>is
  actually</span> <span m=''3132200''>i is</span> <span m=''3132290''>equal</span>
  <span m=''3132440''>to</span> <span m=''3132900''>p.</span> <span m=''3133340''>You</span>
  <span m=''3133450''>can</span> <span m=''3133710''>figure</span> <span m=''3134010''>that</span>
  <span m=''3134260''>one</span> <span m=''3134380''>out</span> <span m=''3134520''>because</span>
  <span m=''3134690''>there''s a</span> <span m=''3134860''>line</span> <span m=''3135130''>in</span>
  <span m=''3135330''>there.</span> <span m=''3136190''>Then</span> <span m=''3136510''>you</span>
  <span m=''3136630''>eliminate</span> <span m=''3137050''>i</span> <span m=''3137520''>and
  now</span> <span m=''3137650''>you</span> <span m=''3137820''>get</span> <span m=''3138020''>this</span>
  <span m=''3138260''>one.</span> <span m=''3141330''>Then</span> <span m=''3142500''>what</span>
  <span m=''3142720''>are</span> <span m=''3142860''>bounds</span> <span m=''3143200''>of</span>
  <span m=''3143470''>p?</span> <span m=''3143550''>p goes</span> <span m=''3143970''>from</span>
  <span m=''3145070''>basically</span> <span m=''3145890''>2 to n.</span> <span m=''3147070''>You</span>
  <span m=''3147190''>just</span> <span m=''3147380''>basically</span> <span m=''3147560''>get
  that.</span> <span m=''3148110''>So you</span> <span m=''3148260''>can</span> <span
  m=''3148450''>do</span> <span m=''3148580''>this</span> <span m=''3148770''>projection</span>
  <span m=''3148910''>in</span> <span m=''3149320''>here --</span> <span m=''3149480''>let</span>
  <span m=''3149630''>me</span> <span m=''3149740''>go</span> <span m=''3149880''>in</span>
  <span m=''3150130''>there,</span> <span m=''3151160''>and</span> <span m=''3151500''>now</span>
  <span m=''3151650''>what you</span> <span m=''3151930''>end</span> <span m=''3152050''>up</span>
  <span m=''3152230''>doing</span> <span m=''3152560''>is</span> <span m=''3154210''>you</span>
  <span m=''3154420''>can</span> <span m=''3154640''>get</span> <span m=''3154790''>this,</span>
  <span m=''3155380''>and</span> <span m=''3155590''>of</span> <span m=''3155710''>course,</span>
  <span m=''3155990''>outer</span> <span m=''3156200''>loop</span> <span m=''3156300''>p</span>
  <span m=''3156840''>is</span> <span m=''3157070''>not</span> <span m=''3157630''>a</span>
  <span m=''3157890''>true --</span> <span m=''3158230''>like</span> <span m=''3158460''>a</span>
  <span m=''3158580''>loop.</span> <span m=''3159240''>You</span> <span m=''3159360''>can</span>
  <span m=''3159560''>say</span> <span m=''3159850''>you</span> <span m=''3159980''>get</span>
  <span m=''3160210''>p,</span> <span m=''3160490''>my_pid.</span> <span m=''3161050''>p
  is with</span> <span m=''3161440''>this</span> <span m=''3161800''>range.</span>
  <span m=''3162690''>i equals</span> <span m=''3162830''>p.</span> <span m=''3163330''>Do
  this</span> <span m=''3163640''>one.</span> <span m=''3164190''>So</span> <span
  m=''3164420''>this one, --</span> <span m=''3164650''>generated</span> <span m=''3164940''>that</span>
  <span m=''3165140''>piece of</span> <span m=''3165390''>code.</span> <span m=''3166570''>So
  I</span> <span m=''3166800''>will</span> <span m=''3167240''>go</span> <span m=''3167420''>a
  little</span> <span m=''3167700''>bit</span> <span m=''3167780''>detail</span> <span
  m=''3168060''>and</span> <span m=''3168210''>show how</span> <span m=''3168560''>this</span>
  <span m=''3169280''>happens,</span> <span m=''3169720''>pretty</span> <span m=''3170000''>much
  can</span> <span m=''3170380''>happen.</span> <span m=''3171080''>So</span> <span
  m=''3171230''>I</span> <span m=''3171680''>have</span> <span m=''3171910''>my</span>
  <span m=''3172410''>little bit</span> <span m=''3172680''>of</span> <span m=''3172890''>different</span>
  <span m=''3173330''>space.</span> <span m=''3174640''>I''m doing a different</span>
  <span m=''3175270''>projection.</span> <span m=''3175400''>I''m doing</span> <span
  m=''3175960''>i, j, p.</span> <span m=''3177050''>I</span> <span m=''3177153''>want</span>
  <span m=''3177256''>to</span> <span m=''3177360''>predict</span> <span m=''3177510''>first</span>
  <span m=''3178020''>i</span> <span m=''3178280''>of</span> <span m=''3178630''>a,</span>
  <span m=''3178830''>j of</span> <span m=''3178940''>a,</span> <span m=''3179230''>and
  p</span> <span m=''3179860''>of</span> <span m=''3180060''>a</span> <span m=''3180250''>instead
  of</span> <span m=''3180430''>j, i, p</span> <span m=''3180630''>before</span> <span
  m=''3180910''>I do anything.</span> </p><p><span m=''3181830''>So</span> <span m=''3182070''>here''s</span>
  <span m=''3182230''>my iteration</span> <span m=''3182600''>space,</span> <span
  m=''3182720''>what</span> <span m=''3182880''>do I</span> <span m=''3183020''>do?</span>
  <span m=''3184250''>The</span> <span m=''3184540''>first</span> <span m=''3184570''>thing</span>
  <span m=''3184750''>I</span> <span m=''3184870''>do</span> <span m=''3185100''>is</span>
  <span m=''3185830''>I</span> <span m=''3186040''>find the</span> <span m=''3186340''>bounds</span>
  <span m=''3186740''>of</span> <span m=''3186910''>i,</span> <span m=''3187500''>So
  I</span> <span m=''3187660''>have</span> <span m=''3187860''>this</span> <span m=''3187990''>thing.</span>
  <span m=''3188410''>I just</span> <span m=''3188490''>basically</span> <span m=''3188950''>expanded</span>
  <span m=''3189750''>this,</span> <span m=''3190230''>and</span> <span m=''3190500''>eliminated</span>
  <span m=''3190890''>the</span> <span m=''3191650''>j</span> <span m=''3194230''>this
  one</span> <span m=''3194290''>doesn''t</span> <span m=''3194790''>contribute</span>
  <span m=''3195340''>to the bounds</span> <span m=''3195730''>of</span> <span m=''3195870''>i,</span>
  <span m=''3196040''>but</span> <span m=''3196170''>everybody</span> <span m=''3196610''>else.</span>
  <span m=''3197220''>So</span> <span m=''3197360''>there are</span> <span m=''3197510''>a</span>
  <span m=''3197650''>bunch</span> <span m=''3197860''>of</span> <span m=''3198040''>things</span>
  <span m=''3198410''>that</span> <span m=''3198670''>i</span> <span m=''3198850''>has
  to be</span> <span m=''3199070''>less</span> <span m=''3199380''>than</span> <span
  m=''3199630''>that</span> <span m=''3199820''>and</span> <span m=''3199950''>i have</span>
  <span m=''3200250''>to be</span> <span m=''3200350''>greater</span> <span m=''3200500''>than
  these</span> <span m=''3201000''>two.</span> <span m=''3202530''>Then</span> <span
  m=''3202740''>what</span> <span m=''3202840''>I</span> <span m=''3202990''>have</span>
  <span m=''3203320''>is</span> <span m=''3203630''>bound of</span> <span m=''3204080''>i</span>
  <span m=''3204420''>is,</span> <span m=''3205430''>it has to</span> <span m=''3205800''>be</span>
  <span m=''3205950''>maximum</span> <span m=''3206550''>of this</span> <span m=''3207130''>because</span>
  <span m=''3207360''>it</span> <span m=''3207390''>has to be greater</span> <span
  m=''3207650''>than</span> <span m=''3207810''>all</span> <span m=''3208130''>three.</span>
  <span m=''3208540''>So it</span> <span m=''3208650''>has to be</span> <span m=''3208960''>max
  of</span> <span m=''3209320''>this,</span> <span m=''3209810''>this, and this.</span>
  <span m=''3210380''>It has to be</span> <span m=''3210600''>less than</span> <span
  m=''3211140''>these</span> <span m=''3211450''>two,</span> <span m=''3211570''>it
  has</span> <span m=''3211670''>to</span> <span m=''3211990''>be</span> <span m=''3212190''>mean</span>
  <span m=''3212340''>of</span> <span m=''3212590''>this one.</span> <span m=''3213480''>Question?</span>
  </p><p><span m=''3213800''>AUDIENCE:</span> <span m=''3214260''>Well why did</span>
  <span m=''3214720''>you have to</span> <span m=''3215180''>go</span> <span m=''3215360''>through</span>
  <span m=''3215620''>all</span> <span m=''3215720''>this. At</span> <span m=''3215880''>least
  in</span> <span m=''3216270''>this</span> <span m=''3216630''>case,</span> <span
  m=''3217150''>the outer</span> <span m=''3217530''>loop was</span> <span m=''3217850''>very</span>
  <span m=''3218160''>simple,</span> <span m=''3218520''>you could have just</span>
  <span m=''3218990''>directly mapped that.</span> </p><p><span m=''3219970''>PROFESSOR:</span>
  <span m=''3220240''>I agree</span> <span m=''3220610''>with</span> <span m=''3220740''>you,</span>
  <span m=''3220840''>it''s</span> <span m=''3221120''>very</span> <span m=''3221440''>simple</span>
  <span m=''3221630''>thing,</span> <span m=''3222410''>but</span> <span m=''3222590''>the</span>
  <span m=''3222690''>problem</span> <span m=''3223170''>is</span> <span m=''3223660''>that''s</span>
  <span m=''3223930''>because</span> <span m=''3224150''>you are</span> <span m=''3224250''>smart</span>
  <span m=''3224990''>and</span> <span m=''3225170''>you can</span> <span m=''3225260''>think
  a</span> <span m=''3225450''>little bit</span> <span m=''3225920''>ahead</span>
  <span m=''3226800''>in there,</span> <span m=''3227100''>and</span> <span m=''3227430''>if</span>
  <span m=''3227560''>I''m</span> <span m=''3227790''>programming</span> <span m=''3228270''>a</span>
  <span m=''3228410''>computer,</span> <span m=''3228550''>I</span> <span m=''3228670''>can''t</span>
  <span m=''3229290''>say</span> <span m=''3230330''>find</span> <span m=''3230700''>these</span>
  <span m=''3230950''>special</span> <span m=''3231200''>cases.</span> <span m=''3232290''>So</span>
  <span m=''3232390''>I</span> <span m=''3232450''>want to</span> <span m=''3232740''>come</span>
  <span m=''3232880''>up</span> <span m=''3233020''>with</span> <span m=''3233110''>a</span>
  <span m=''3233190''>mathematical</span> <span m=''3233990''>way</span> <span m=''3234210''>that</span>
  <span m=''3234350''>is a</span> <span m=''3234850''>bullet proof way that</span>
  <span m=''3235480''>will</span> <span m=''3235790''>work from</span> <span m=''3236000''>the</span>
  <span m=''3236090''>simplest</span> <span m=''3236330''>one</span> <span m=''3236670''>to</span>
  <span m=''3237340''>very</span> <span m=''3237920''>complicated,</span> <span m=''3238460''>like</span>
  <span m=''3238660''>for</span> <span m=''3238730''>example,</span> <span m=''3239270''>finding
  the</span> <span m=''3239700''>loop</span> <span m=''3239970''>bounds</span> <span
  m=''3240440''>for</span> <span m=''3240550''>that</span> <span m=''3241090''>loop</span>
  <span m=''3241290''>transpose</span> <span m=''3243140''>that</span> <span m=''3243290''>I</span>
  <span m=''3243360''>showed you</span> <span m=''3243700''>before --</span> <span
  m=''3244850''>no,</span> <span m=''3245050''>the</span> <span m=''3245560''>skew</span>
  <span m=''3246140''>that</span> <span m=''3247770''>what we called before.</span>
  </p><p><span m=''3249160''>AUDIENCE: So</span> <span m=''3249670''>it''s not</span>
  <span m=''3250190''>so much</span> <span m=''3250740''>just</span> <span m=''3251170''>defining</span>
  <span m=''3252020''>an</span> <span m=''3252790''>index</span> <span m=''3253190''>to
  iterate on,</span> <span m=''3253420''>it''s to</span> <span m=''3253830''>find
  the best index</span> <span m=''3254360''>to map,</span> <span m=''3255450''>to</span>
  <span m=''3256110''>parellize.</span> </p><p><span m=''3256910''>PROFESSOR: Any</span>
  <span m=''3257520''>could be</span> <span m=''3257890''>issue,</span> <span m=''3258130''>because</span>
  <span m=''3258620''>you</span> <span m=''3258740''>have --</span> <span m=''3260010''>for</span>
  <span m=''3260150''>example,</span> <span m=''3260560''>if</span> <span m=''3260950''>the</span>
  <span m=''3261630''>inner</span> <span m=''3262070''>dimension</span> <span m=''3262580''>depends</span>
  <span m=''3262780''>on</span> <span m=''3262920''>i,</span> <span m=''3264020''>and</span>
  <span m=''3264380''>i</span> <span m=''3264640''>goes</span> <span m=''3264940''>outside,</span>
  <span m=''3265770''>then I can''t</span> <span m=''3266370''>make</span> <span m=''3266590''>it</span>
  <span m=''3266650''>depend</span> <span m=''3266970''>on</span> <span m=''3267090''>i.</span>
  <span m=''3267270''>So</span> <span m=''3267440''>if</span> <span m=''3267600''>I</span>
  <span m=''3267670''>have</span> <span m=''3268020''>something</span> <span m=''3268360''>like</span>
  <span m=''3271500''>for</span> <span m=''3271700''>i</span> <span m=''3271940''>equals</span>
  <span m=''3273110''>something,</span> <span m=''3273400''>for j</span> <span m=''3273850''>equals</span>
  <span m=''3275680''>i</span> <span m=''3276040''>to</span> <span m=''3276150''>something.</span>
  <span m=''3277910''>Now</span> <span m=''3278020''>if</span> <span m=''3278130''>I</span>
  <span m=''3278320''>switch</span> <span m=''3278610''>these</span> <span m=''3279080''>two</span>
  <span m=''3279260''>I</span> <span m=''3279300''>have</span> <span m=''3279560''>4j.</span>
  <span m=''3281350''>I can''t</span> <span m=''3281800''>say</span> <span m=''3282050''>it''s
  i to</span> <span m=''3282370''>something. I</span> <span m=''3283170''>have</span>
  <span m=''3283550''>to  get</span> <span m=''3283750''>rid of</span> <span m=''3284310''>i</span>
  <span m=''3284480''>and I have to</span> <span m=''3284700''>figure</span> <span
  m=''3284790''>out</span> <span m=''3285210''>in</span> <span m=''3285540''>the</span>
  <span m=''3285720''>for</span> <span m=''3285830''>i,</span> <span m=''3287430''>this
  has to</span> <span m=''3287830''>be</span> <span m=''3287900''>something</span>
  <span m=''3288260''>with</span> <span m=''3288350''>j, with</span> <span m=''3288760''>some</span>
  <span m=''3289000''>function with</span> <span m=''3289460''>j</span> <span m=''3290160''>in
  here.</span> <span m=''3292160''>So</span> <span m=''3293030''>what</span> <span
  m=''3293520''>is</span> <span m=''3293630''>this</span> <span m=''3293770''>function,</span>
  <span m=''3294150''>how</span> <span m=''3294300''>do you</span> <span m=''3294470''>get</span>
  <span m=''3294710''>that?</span> <span m=''3296690''>You</span> <span m=''3296810''>need</span>
  <span m=''3297050''>this</span> <span m=''3297220''>kind</span> <span m=''3297380''>of</span>
  <span m=''3297460''>transformations</span> <span m=''3298120''>do</span> <span m=''3298290''>that.</span>
  <span m=''3299070''>Next</span> <span m=''3299380''>time I''ll</span> <span m=''3299520''>talk
  to</span> <span m=''3299800''>you</span> <span m=''3299900''>about</span> <span
  m=''3300520''>can</span> <span m=''3300810''>you do</span> <span m=''3300900''>it</span>
  <span m=''3300990''>a</span> <span m=''3301150''>little</span> <span m=''3301260''>bit</span>
  <span m=''3301470''>even</span> <span m=''3301650''>better.</span> </p><p><span
  m=''3302480''>So</span> <span m=''3302590''>I</span> <span m=''3302650''>get</span>
  <span m=''3302860''>this</span> <span m=''3302970''>bound in</span> <span m=''3303350''>here.</span>
  <span m=''3306600''>Then</span> <span m=''3306980''>actually</span> <span m=''3307360''>you
  found</span> <span m=''3308540''>this is</span> <span m=''3309020''>going</span>
  <span m=''3309230''>from</span> <span m=''3309450''>p</span> <span m=''3309680''>to</span>
  <span m=''3309760''>p.</span> <span m=''3311390''>So I can actually</span> <span
  m=''3311810''>set</span> <span m=''3311990''>p</span> <span m=''3312960''>because,</span>
  <span m=''3313850''>mean</span> <span m=''3314620''>and max</span> <span m=''3314750''>in
  here.</span> <span m=''3316400''>Then</span> <span m=''3316580''>after</span> <span
  m=''3316910''>you do</span> <span m=''3317220''>that,</span> <span m=''3317440''>what
  you</span> <span m=''3317580''>have to do</span> <span m=''3317760''>is</span> <span
  m=''3317850''>eliminate</span> <span m=''3318630''>I.</span> <span m=''3319370''>The</span>
  <span m=''3319500''>way you</span> <span m=''3319810''>eliminate</span> <span m=''3320280''>I</span>
  <span m=''3321660''>is</span> <span m=''3322610''>you</span> <span m=''3322790''>take</span>
  <span m=''3324060''>this</span> <span m=''3325190''>has to</span> <span m=''3325460''>be</span>
  <span m=''3325570''>always</span> <span m=''3325980''>less</span> <span m=''3326710''>than</span>
  <span m=''3326960''>n</span> <span m=''3327290''>and</span> <span m=''3327700''>less</span>
  <span m=''3327830''>than</span> <span m=''3328120''>p.</span> <span m=''3329160''>So</span>
  <span m=''3329290''>you</span> <span m=''3329440''>take</span> <span m=''3330230''>this</span>
  <span m=''3330810''>n</span> <span m=''3331060''>constraints</span> <span m=''3332170''>here</span>
  <span m=''3333050''>and</span> <span m=''3333220''>you</span> <span m=''3333310''>get</span>
  <span m=''3333610''>a</span> <span m=''3333680''>n</span> <span m=''3333930''>times</span>
  <span m=''3334180''>m</span> <span m=''3334630''>constraints</span> <span m=''3334950''>tier
  in here.</span> <span m=''3335660''>So</span> <span m=''3335820''>the</span> <span
  m=''3335930''>first</span> <span m=''3336270''>three</span> <span m=''3336800''>has
  to be</span> <span m=''3336990''>less than</span> <span m=''3337360''>n,</span>
  <span m=''3337580''>again,</span> <span m=''3338870''>we</span> <span m=''3339010''>repeat</span>
  <span m=''3339100''>it</span> <span m=''3339380''>again,</span> <span m=''3339910''>has</span>
  <span m=''3339990''>to be</span> <span m=''3340120''>less than</span> <span m=''3340460''>p.</span>
  <span m=''3342260''>Then,</span> <span m=''3342360''>of</span> <span m=''3342600''>course,</span>
  <span m=''3342830''>the</span> <span m=''3343000''>missing</span> <span m=''3343250''>constraint</span>
  <span m=''3343430''>that</span> <span m=''3345380''>1</span> <span m=''3345710''>is</span>
  <span m=''3346630''>less than j.</span> <span m=''3347660''>You</span> <span m=''3347870''>put</span>
  <span m=''3348000''>all</span> <span m=''3348310''>those</span> <span m=''3348460''>constraints</span>
  <span m=''3348700''>together.</span> <span m=''3349430''>Now,</span> <span m=''3349830''>nice</span>
  <span m=''3350080''>think</span> <span m=''3350330''>is in</span> <span m=''3350660''>that</span>
  <span m=''3350910''>one,</span> <span m=''3351090''>it''s</span> <span m=''3351290''>still</span>
  <span m=''3351510''>legal,</span> <span m=''3351610''>it</span> <span m=''3351730''>still</span>
  <span m=''3351860''>represents</span> <span m=''3352350''>that</span> <span m=''3352770''>space,</span>
  <span m=''3353550''>but</span> <span m=''3353770''>you</span> <span m=''3353870''>don''t</span>
  <span m=''3354050''>have</span> <span m=''3354240''>i</span> <span m=''3354450''>there</span>
  <span m=''3355170''>anymore.</span> <span m=''3355580''>You can</span> <span m=''3355640''>completely</span>
  <span m=''3355910''>get rid of</span> <span m=''3356230''>i.</span> </p><p><span
  m=''3358470''>So,</span> <span m=''3359210''>by</span> <span m=''3359400''>doing</span>
  <span m=''3359670''>that --</span> <span m=''3360080''>and then</span> <span m=''3360240''>of
  course,</span> <span m=''3360520''>there''s a lot of</span> <span m=''3361160''>redundancy</span>
  <span m=''3361460''>in</span> <span m=''3361600''>here,</span> <span m=''3362220''>and</span>
  <span m=''3362390''>then</span> <span m=''3362510''>you</span> <span m=''3362580''>can</span>
  <span m=''3362790''>do</span> <span m=''3362980''>some</span> <span m=''3363200''>analysis</span>
  <span m=''3363550''>and</span> <span m=''3363940''>eliminate</span> <span m=''3364370''>redundancy</span>
  <span m=''3364660''>and</span> <span m=''3364780''>you end</span> <span m=''3364960''>up</span>
  <span m=''3365120''>in</span> <span m=''3365230''>this set</span> <span m=''3365320''>of
  constraints.</span> <span m=''3366760''>That''s</span> <span m=''3367000''>where</span>
  <span m=''3367370''>when you</span> <span m=''3367550''>say</span> <span m=''3367790''>what''s</span>
  <span m=''3367970''>the</span> <span m=''3368120''>best,</span> <span m=''3369310''>you</span>
  <span m=''3369490''>can</span> <span m=''3369690''>be</span> <span m=''3369800''>best</span>
  <span m=''3370250''>--</span> <span m=''3370740''>it</span> <span m=''3371160''>has
  to</span> <span m=''3371460''>be</span> <span m=''3371530''>correct</span> <span
  m=''3372330''>or</span> <span m=''3372470''>that</span> <span m=''3372630''>means</span>
  <span m=''3372860''>you</span> <span m=''3372990''>can''t</span> <span m=''3373240''>have</span>
  <span m=''3373590''>additional</span> <span m=''3373990''>iterations</span> <span
  m=''3374120''>or less</span> <span m=''3374790''>iterations.</span> <span m=''3375220''>But</span>
  <span m=''3375930''>best</span> <span m=''3376660''>depends</span> <span m=''3377130''>on</span>
  <span m=''3377480''>how</span> <span m=''3377800''>complicated</span> <span m=''3378370''>is</span>
  <span m=''3378450''>the</span> <span m=''3378790''>loop</span> <span m=''3379020''>bound</span>
  <span m=''3379400''>calculation.</span> <span m=''3381610''>You</span> <span m=''3381800''>can</span>
  <span m=''3382030''>come</span> <span m=''3382200''>up</span> <span m=''3382330''>with
  a</span> <span m=''3382410''>correct</span> <span m=''3382770''>solution,</span>
  <span m=''3383180''>and</span> <span m=''3383300''>the</span> <span m=''3383400''>best</span>
  <span m=''3383740''>is</span> <span m=''3384080''>depending</span> <span m=''3384570''>on</span>
  <span m=''3384760''>which</span> <span m=''3384900''>order</span> <span m=''3385260''>you</span>
  <span m=''3385420''>do</span> <span m=''3385540''>that.</span> <span m=''3386060''>When</span>
  <span m=''3386190''>you have</span> <span m=''3386330''>two</span> <span m=''3386680''>redundant</span>
  <span m=''3386850''>thing,</span> <span m=''3387130''>which</span> <span m=''3387310''>one</span>
  <span m=''3387450''>you</span> <span m=''3387530''>eliminate,</span> <span m=''3387720''>so</span>
  <span m=''3388010''>you</span> <span m=''3388120''>can</span> <span m=''3388300''>have
  a</span> <span m=''3388390''>lot</span> <span m=''3388580''>of</span> <span m=''3388670''>heuristics</span>
  <span m=''3388900''>saying</span> <span m=''3389400''>OK,</span> <span m=''3389600''>look</span>
  <span m=''3389730''>if this</span> <span m=''3390060''>one looks</span> <span m=''3390660''>harder</span>
  <span m=''3390990''>to calculate,</span> <span m=''3391330''>eliminate</span> <span
  m=''3392260''>that</span> <span m=''3392520''>one</span> <span m=''3392910''>with
  the</span> <span m=''3393250''>other</span> <span m=''3393340''>one.</span> <span
  m=''3394080''>So</span> <span m=''3394420''>you</span> <span m=''3394540''>get</span>
  <span m=''3394720''>this</span> <span m=''3394850''>set</span> <span m=''3395100''>of</span>
  <span m=''3395230''>constraints.</span> </p><p><span m=''3396800''>Then</span> <span
  m=''3396920''>you have to</span> <span m=''3397240''>do</span> <span m=''3397840''>is
  now</span> <span m=''3398160''>find</span> <span m=''3398410''>the</span> <span
  m=''3398500''>bounds</span> <span m=''3398690''>of</span> <span m=''3398870''>j.</span>
  <span m=''3399950''>So</span> <span m=''3400500''>you</span> <span m=''3400640''>have</span>
  <span m=''3400900''>this</span> <span m=''3401000''>set</span> <span m=''3401920''>again.
  To</span> <span m=''3402470''>find</span> <span m=''3402790''>a bound</span> <span
  m=''3403040''>of</span> <span m=''3403180''>j</span> <span m=''3404170''>only</span>
  <span m=''3404390''>two</span> <span m=''3404670''>constraints</span> <span m=''3405280''>are</span>
  <span m=''3405430''>there,</span> <span m=''3406120''>and</span> <span m=''3406350''>you</span>
  <span m=''3406450''>know</span> <span m=''3406630''>j</span> <span m=''3406750''>goes</span>
  <span m=''3406870''>to</span> <span m=''3407170''>1</span> <span m=''3407510''>to</span>
  <span m=''3407590''>p</span> <span m=''3407740''>minus</span> <span m=''3408080''>1,</span>
  <span m=''3408710''>and</span> <span m=''3409520''>you find the</span> <span m=''3409760''>bound</span>
  <span m=''3409960''>of</span> <span m=''3410020''>j.</span> <span m=''3411210''>Getting</span>
  <span m=''3411440''>rid</span> <span m=''3411600''>of</span> <span m=''3411750''>j</span>
  <span m=''3412280''>means</span> <span m=''3414170''>there''s</span> <span m=''3414700''>only</span>
  <span m=''3415760''>two.</span> <span m=''3415860''>One</span> <span m=''3416160''>get
  rid of</span> <span m=''3416580''>p</span> <span m=''3416690''>minus</span> <span
  m=''3416860''>1.</span> <span m=''3417550''>There are</span> <span m=''3417740''>two</span>
  <span m=''3418180''>left for</span> <span m=''3418540''>p.</span> <span m=''3418980''>You
  put it</span> <span m=''3419080''>there,</span> <span m=''3420420''>and</span> <span
  m=''3420970''>then</span> <span m=''3421080''>you</span> <span m=''3421170''>can</span>
  <span m=''3421320''>eliminate</span> <span m=''3421840''>the</span> <span m=''3421910''>redundance</span>
  <span m=''3422200''>in</span> <span m=''3422370''>here,</span> <span m=''3423370''>and</span>
  <span m=''3424270''>now</span> <span m=''3424610''>you</span> <span m=''3424720''>can</span>
  <span m=''3425320''>find the</span> <span m=''3425670''>bounds</span> <span m=''3426180''>of</span>
  <span m=''3426390''>p</span> <span m=''3427000''>which</span> <span m=''3427400''>goes
  from</span> <span m=''3427500''>2</span> <span m=''3427910''>to</span> <span m=''3428030''>n.</span>
  <span m=''3429530''>And</span> <span m=''3429750''>suddenly</span> <span m=''3430150''>you</span>
  <span m=''3430260''>have the loop nest.</span> <span m=''3432490''>So</span> <span
  m=''3432640''>now</span> <span m=''3432830''>I</span> <span m=''3433610''>actually</span>
  <span m=''3434460''>di</span> <span m=''3434720''>parallelization</span> <span m=''3435330''>and</span>
  <span m=''3435760''>a</span> <span m=''3435870''>loop</span> <span m=''3436040''>transpose</span>
  <span m=''3436610''>in</span> <span m=''3436850''>here.</span> <span m=''3440200''>I</span>
  <span m=''3440280''>could</span> <span m=''3440500''>combine</span> <span m=''3440910''>those</span>
  <span m=''3441200''>two,</span> <span m=''3441690''>use</span> <span m=''3441960''>this</span>
  <span m=''3442210''>simple</span> <span m=''3442530''>mathematical</span> <span
  m=''3443230''>way</span> <span m=''3443480''>and</span> <span m=''3443560''>find</span>
  <span m=''3443750''>loop</span> <span m=''3444270''>bounds</span> <span m=''3444420''>in
  here.</span> </p><p><span m=''3447050''>So,</span> <span m=''3447550''>I''m</span>
  <span m=''3447740''>going to</span> <span m=''3447930''>give</span> <span m=''3448110''>you</span>
  <span m=''3448430''>something</span> <span m=''3448830''>even</span> <span m=''3448930''>a</span>
  <span m=''3449090''>little</span> <span m=''3449200''>bit</span> <span m=''3450650''>interesting</span>
  <span m=''3451130''>beyond</span> <span m=''3451400''>that,</span> <span m=''3452090''>which</span>
  <span m=''3452220''>is</span> <span m=''3452420''>communication</span> <span m=''3452660''>code</span>
  <span m=''3452830''>generation.</span> <span m=''3457470''>So if</span> <span m=''3457740''>you</span>
  <span m=''3458040''>are</span> <span m=''3458170''>dealing</span> <span m=''3458240''>with
  a</span> <span m=''3458340''>cache</span> <span m=''3458740''>coherent</span> <span
  m=''3458860''>shared</span> <span m=''3458940''>memory</span> <span m=''3459240''>machine,</span>
  <span m=''3459570''>you are</span> <span m=''3459860''>done.</span> <span m=''3460940''>You</span>
  <span m=''3461230''>generate</span> <span m=''3461660''>code</span> <span m=''3461830''>for</span>
  <span m=''3461910''>parallel</span> <span m=''3462150''>loop nest,</span> <span
  m=''3463140''>you</span> <span m=''3463230''>can</span> <span m=''3463390''>go</span>
  <span m=''3463550''>home</span> <span m=''3463890''>because</span> <span m=''3464260''>everything</span>
  <span m=''3464620''>else will be done</span> <span m=''3464790''>automatically.</span>
  <span m=''3465900''>But</span> <span m=''3466420''>as</span> <span m=''3466710''>we</span>
  <span m=''3466860''>all</span> <span m=''3467060''>know in</span> <span m=''3467460''>something</span>
  <span m=''3467710''>like</span> <span m=''3467920''>Cell,</span> <span m=''3468570''>if</span>
  <span m=''3468860''>you</span> <span m=''3468920''>have</span> <span m=''3469150''>a
  no</span> <span m=''3469370''>cache</span> <span m=''3469680''>coherent</span> <span
  m=''3470240''>shared</span> <span m=''3470330''>memory</span> <span m=''3470660''>or</span>
  <span m=''3470880''>distributed</span> <span m=''3471100''>memory,</span> <span
  m=''3471330''>you</span> <span m=''3471700''>have to do</span> <span m=''3472070''>this</span>
  <span m=''3472480''>one</span> <span m=''3472970''>first.</span> <span m=''3473480''>Then</span>
  <span m=''3473780''>you</span> <span m=''3473850''>write</span> <span m=''3474050''>identify</span>
  <span m=''3474200''>communication</span> <span m=''3475330''>and</span> <span m=''3475750''>then
  you generate</span> <span m=''3476640''>communication code.</span> <span m=''3479590''>This</span>
  <span m=''3480500''>have additional</span> <span m=''3480970''>burden in</span>
  <span m=''3481280''>here.</span> </p><p><span m=''3484670''>So</span> <span m=''3485170''>until</span>
  <span m=''3485540''>now</span> <span m=''3485820''>in data dependence</span> <span
  m=''3486390''>analysis,</span> <span m=''3487180''>what</span> <span m=''3487450''>we</span>
  <span m=''3487630''>looked</span> <span m=''3487960''>at was</span> <span m=''3488410''>location-centric</span>
  <span m=''3489750''>dependences.</span> <span m=''3491040''>Which</span> <span m=''3491340''>location</span>
  <span m=''3491890''>is</span> <span m=''3492200''>written</span> <span m=''3492460''>by</span>
  <span m=''3492550''>processor</span> <span m=''3492930''>one is</span> <span m=''3493220''>used</span>
  <span m=''3493540''>by</span> <span m=''3493950''>processor two.</span> <span m=''3495650''>That''s</span>
  <span m=''3495820''>kind</span> <span m=''3496000''>of</span> <span m=''3496100''>a</span>
  <span m=''3496210''>location-centric</span> <span m=''3496710''>kind</span> <span
  m=''3496850''>of</span> <span m=''3496940''>view.</span> <span m=''3499600''>How</span>
  <span m=''3499890''>about</span> <span m=''3500120''>if</span> <span m=''3500320''>multiple</span>
  <span m=''3500470''>writes</span> <span m=''3500830''>the</span> <span m=''3500960''>same</span>
  <span m=''3501180''>location?</span> <span m=''3503470''>We</span> <span m=''3503550''>show</span>
  <span m=''3503740''>that</span> <span m=''3503970''>in example,</span> <span m=''3504220''>if</span>
  <span m=''3504290''>multiple</span> <span m=''3504510''>people</span> <span m=''3504810''>write</span>
  <span m=''3505030''>the</span> <span m=''3505170''>same</span> <span m=''3505220''>location,</span>
  <span m=''3505600''>which</span> <span m=''3506550''>one</span> <span m=''3506800''>should</span>
  <span m=''3507010''>I</span> <span m=''3507080''>use?</span> <span m=''3509450''>That''s
  not clear.</span> <span m=''3510850''>What you are using in</span> <span m=''3511020''>the
  last</span> <span m=''3511440''>last guy</span> <span m=''3511980''>who wrote</span>
  <span m=''3512140''>that</span> <span m=''3512730''>location</span> <span m=''3513100''>before</span>
  <span m=''3513300''>I read that thing,</span> <span m=''3513930''>and</span> <span
  m=''3514110''>that''s</span> <span m=''3514330''>not</span> <span m=''3514800''>in</span>
  <span m=''3515010''>these</span> <span m=''3515290''>data</span> <span m=''3515810''>flow</span>
  <span m=''3516150''>analysis.</span> <span m=''3516690''>No</span> <span m=''3517170''>data</span>
  <span m=''3517430''>dependence</span> <span m=''3517590''>analysis</span> <span
  m=''3518060''>doesn''t</span> <span m=''3518320''>get</span> <span m=''3518600''>it.</span>
  <span m=''3520110''>What</span> <span m=''3520490''>you</span> <span m=''3520560''>want</span>
  <span m=''3520840''>is</span> <span m=''3520910''>something</span> <span m=''3521250''>of</span>
  <span m=''3521320''>a</span> <span m=''3521400''>value-centric.</span> <span m=''3523490''>Who</span>
  <span m=''3523910''>was the</span> <span m=''3523970''>last</span> <span m=''3524430''>write</span>
  <span m=''3525060''>before</span> <span m=''3525460''>my</span> <span m=''3525890''>iteration,</span>
  <span m=''3527330''>who</span> <span m=''3527670''>wrote that</span> <span m=''3527850''>location?</span>
  <span m=''3529540''>If</span> <span m=''3529740''>I</span> <span m=''3529790''>know</span>
  <span m=''3529910''>the</span> <span m=''3530060''>last</span> <span m=''3530240''>write,</span>
  <span m=''3530930''>he''s</span> <span m=''3531130''>the</span> <span m=''3531230''>one</span>
  <span m=''3531620''>I</span> <span m=''3532000''>should</span> <span m=''3532170''>be</span>
  <span m=''3532270''>getting</span> <span m=''3532490''>the value</span> <span m=''3532740''>from.</span>
  <span m=''3533570''>If the</span> <span m=''3533910''>last</span> <span m=''3534190''>write</span>
  <span m=''3534270''>happened</span> <span m=''3534730''>in</span> <span m=''3534810''>the
  same</span> <span m=''3535100''>processor,</span> <span m=''3536880''>I</span> <span
  m=''3537360''>am set</span> <span m=''3537720''>because</span> <span m=''3537850''>I
  wrote</span> <span m=''3538290''>the</span> <span m=''3538810''>local</span> <span
  m=''3539130''>copy</span> <span m=''3539480''>and</span> <span m=''3539710''>I</span>
  <span m=''3539960''>don''t</span> <span m=''3540150''>need</span> <span m=''3540270''>to</span>
  <span m=''3540350''>deal</span> <span m=''3540600''>with anything.</span> <span
  m=''3542010''>If the last</span> <span m=''3542180''>write</span> <span m=''3542670''>happened</span>
  <span m=''3542930''>in a</span> <span m=''3543060''>different</span> <span m=''3543410''>processor,</span>
  <span m=''3544840''>you</span> <span m=''3545040''>need</span> <span m=''3545150''>to</span>
  <span m=''3545220''>get</span> <span m=''3545370''>that</span> <span m=''3545550''>value</span>
  <span m=''3546020''>from</span> <span m=''3546190''>the guys who</span> <span m=''3546800''>wrote
  it</span> <span m=''3546910''>and</span> <span m=''3547080''>say, OK,</span> <span
  m=''3547190''>you</span> <span m=''3547470''>wrote that value,</span> <span m=''3547630''>give</span>
  <span m=''3547790''>it</span> <span m=''3548070''>to</span> <span m=''3548130''>me.</span>
  <span m=''3549470''>If</span> <span m=''3549990''>nobody</span> <span m=''3550120''>wrote</span>
  <span m=''3550550''>it and</span> <span m=''3550670''>I''m</span> <span m=''3550820''>reading</span>
  <span m=''3551750''>it, that</span> <span m=''3551960''>means</span> <span m=''3552170''>the</span>
  <span m=''3552340''>value</span> <span m=''3552410''>came</span> <span m=''3552740''>from</span>
  <span m=''3552930''>the</span> <span m=''3553270''>original</span> <span m=''3553330''>array</span>
  <span m=''3554700''>because</span> <span m=''3555020''>nobody</span> <span m=''3556230''>had</span>
  <span m=''3556340''>written</span> <span m=''3556720''>it</span> <span m=''3557200''>in
  my iteration.</span> <span m=''3557600''>Then</span> <span m=''3557720''>I''m</span>
  <span m=''3557900''>reading</span> <span m=''3558210''>something</span> <span m=''3558460''>that</span>
  <span m=''3558680''>has</span> <span m=''3558970''>come</span> <span m=''3559200''>from</span>
  <span m=''3559340''>the</span> <span m=''3559410''>previous</span> <span m=''3560420''>iteration.</span>
  <span m=''3561370''>So</span> <span m=''3561630''>I</span> <span m=''3561710''>have
  to</span> <span m=''3561900''>get</span> <span m=''3562020''>it</span> <span m=''3562110''>from</span>
  <span m=''3562310''>the</span> <span m=''3562490''>original</span> <span m=''3563250''>array.</span>
  <span m=''3563630''>But I have</span> <span m=''3563830''>these</span> <span m=''3563930''>three</span>
  <span m=''3564120''>different</span> <span m=''3564430''>conditions.</span> </p><p><span
  m=''3566800''>So</span> <span m=''3567400''>you</span> <span m=''3567490''>know</span>
  <span m=''3567740''>to</span> <span m=''3567880''>represent</span> <span m=''3568240''>that.</span>
  <span m=''3569260''>I''m</span> <span m=''3569430''>not</span> <span m=''3569660''>going
  to</span> <span m=''3569740''>go</span> <span m=''3569970''>into</span> <span m=''3570130''>detail</span>
  <span m=''3570230''>on</span> <span m=''3570370''>into detail on this representation
  called</span> <span m=''3572430''>Last Write Trees.</span> <span m=''3574160''>So</span>
  <span m=''3574300''>what</span> <span m=''3574480''>it</span> <span m=''3574580''>says</span>
  <span m=''3575050''>is in</span> <span m=''3575330''>this</span> <span m=''3576620''>kind</span>
  <span m=''3576780''>of</span> <span m=''3576930''>a</span> <span m=''3576990''>loop
  nest</span> <span m=''3579520''>in here,</span> <span m=''3581160''>you</span> <span
  m=''3581310''>have</span> <span m=''3581500''>some read</span> <span m=''3581890''>access</span>
  <span m=''3582310''>and write</span> <span m=''3582690''>accesses</span> <span m=''3583130''>in</span>
  <span m=''3583270''>here,</span> <span m=''3583850''>and</span> <span m=''3584030''>if</span>
  <span m=''3584160''>you</span> <span m=''3584260''>look</span> <span m=''3584470''>at</span>
  <span m=''3584640''>it</span> <span m=''3585170''>location-centrically</span> <span
  m=''3586210''>you</span> <span m=''3586310''>get</span> <span m=''3586480''>this</span>
  <span m=''3586700''>entire</span> <span m=''3587140''>complex</span> <span m=''3587260''>graph,</span>
  <span m=''3587990''>because</span> <span m=''3588430''>this</span> <span m=''3588640''>is</span>
  <span m=''3588730''>the</span> <span m=''3588820''>graph</span> <span m=''3589160''>that</span>
  <span m=''3589860''>should</span> <span m=''3590100''>have</span> <span m=''3590200''>been</span>
  <span m=''3590330''>in</span> <span m=''3590620''>that</span> <span m=''3590930''>example</span>
  <span m=''3591390''>we gave.</span> <span m=''3593080''>So these arrays</span> <span
  m=''3593210''>going</span> <span m=''3594170''>in here.</span> <span m=''3595760''>I''m</span>
  <span m=''3596770''>switching</span> <span m=''3597180''>notation.</span> <span
  m=''3597500''>before</span> <span m=''3597820''>i was going</span> <span m=''3598040''>the</span>
  <span m=''3598210''>other</span> <span m=''3598360''>way</span> <span m=''3598520''>around.</span>
  <span m=''3598650''>j</span> <span m=''3599350''>was in</span> <span m=''3599500''>here.</span>
  <span m=''3602960''>But</span> <span m=''3603960''>if</span> <span m=''3604190''>you</span>
  <span m=''3604330''>go</span> <span m=''3604490''>look</span> <span m=''3604730''>at</span>
  <span m=''3604950''>value-centric,</span> <span m=''3606590''>this</span> <span
  m=''3606740''>is</span> <span m=''3606910''>what</span> <span m=''3607080''>happens.</span>
  <span m=''3607440''>So you</span> <span m=''3607570''>say</span> <span m=''3607780''>all</span>
  <span m=''3608320''>these</span> <span m=''3608660''>guys</span> <span m=''3610420''>basically</span>
  <span m=''3610720''>got</span> <span m=''3611150''>the</span> <span m=''3611280''>value</span>
  <span m=''3612040''>from</span> <span m=''3612290''>outside.</span> <span m=''3612910''>Nobody
  wrote</span> <span m=''3613850''>it.</span> <span m=''3614070''>This got</span>
  <span m=''3614280''>from --</span> <span m=''3614510''>this</span> <span m=''3614690''>is</span>
  <span m=''3614780''>the</span> <span m=''3614870''>write,</span> <span m=''3615220''>this</span>
  <span m=''3615440''>is</span> <span m=''3615510''>the</span> <span m=''3615590''>last</span>
  <span m=''3615870''>write,</span> <span m=''3615920''>this</span> <span m=''3616120''>is</span>
  <span m=''3616240''>the</span> <span m=''3616310''>last</span> <span m=''3616540''>write
  --</span> <span m=''3616730''>I</span> <span m=''3617030''>actually</span> <span
  m=''3617340''>have</span> <span m=''3617470''>my</span> <span m=''3617720''>last</span>
  <span m=''3617940''>write</span> <span m=''3618270''>information.</span> <span m=''3619380''>So</span>
  <span m=''3619990''>where</span> <span m=''3620460''>to look</span> <span m=''3620680''>at</span>
  <span m=''3620890''>that</span> <span m=''3621120''>is</span> <span m=''3621270''>there</span>
  <span m=''3621320''>are some</span> <span m=''3621650''>part</span> <span m=''3621870''>of</span>
  <span m=''3621970''>iteration</span> <span m=''3622120''>got</span> <span m=''3622480''>value</span>
  <span m=''3622570''>from</span> <span m=''3622970''>somewhere,</span> <span m=''3623220''>other</span>
  <span m=''3623420''>part</span> <span m=''3623530''>go</span> <span m=''3623640''>somewhere</span>
  <span m=''3623980''>else.</span> <span m=''3624740''>You</span> <span m=''3624950''>can''t</span>
  <span m=''3625170''>kind</span> <span m=''3625340''>of</span> <span m=''3625430''>do
  a</span> <span m=''3625650''>big</span> <span m=''3625980''>summary,</span> <span
  m=''3626520''>as</span> <span m=''3626760''>you</span> <span m=''3626820''>point</span>
  <span m=''3627070''>out</span> <span m=''3627180''>that</span> <span m=''3627380''>kind</span>
  <span m=''3627540''>of</span> <span m=''3627600''>dependence</span> <span m=''3628150''>depend</span>
  <span m=''3628600''>on</span> <span m=''3628770''>where the</span> <span m=''3629030''>iterations</span>
  <span m=''3629530''>are.</span> <span m=''3630080''>So</span> <span m=''3630250''>you</span>
  <span m=''3630340''>can</span> <span m=''3630810''>represent</span> <span m=''3631610''>it</span>
  <span m=''3631880''>using</span> <span m=''3632240''>a</span> <span m=''3632320''>tree</span>
  <span m=''3632850''>when</span> <span m=''3633460''>it</span> <span m=''3633530''>shows</span>
  <span m=''3633820''>up.</span> <span m=''3634320''>So you can</span> <span m=''3634770''>say</span>
  <span m=''3635910''>if</span> <span m=''3637070''>j</span> <span m=''3637630''>greater</span>
  <span m=''3637880''>than</span> <span m=''3638140''>1,</span> <span m=''3638650''>here''s</span>
  <span m=''3639060''>the</span> <span m=''3639170''>relationship</span> <span m=''3639710''>between</span>
  <span m=''3640020''>reads</span> <span m=''3640220''>and</span> <span m=''3640440''>writes.</span>
  <span m=''3641430''>Otherwise</span> <span m=''3642010''>relationship</span> <span
  m=''3642530''>means</span> <span m=''3642920''>it</span> <span m=''3643120''>came</span>
  <span m=''3643360''>from</span> <span m=''3643460''>outside.</span> <span m=''3644230''>So</span>
  <span m=''3644340''>I</span> <span m=''3644420''>can</span> <span m=''3644620''>say</span>
  <span m=''3644770''>for</span> <span m=''3644900''>each</span> <span m=''3645680''>different</span>
  <span m=''3646120''>places.</span> <span m=''3646550''>So</span> <span m=''3646980''>you</span>
  <span m=''3647070''>can</span> <span m=''3647250''>think</span> <span m=''3647500''>about</span>
  <span m=''3648480''>this</span> <span m=''3648740''>tree</span> <span m=''3648920''>can</span>
  <span m=''3649090''>be</span> <span m=''3649190''>a lot more</span> <span m=''3649410''>complicated</span>
  <span m=''3649700''>tree.</span> <span m=''3650200''>So</span> <span m=''3650310''>each</span>
  <span m=''3650510''>part</span> <span m=''3650860''>of</span> <span m=''3650940''>the</span>
  <span m=''3651040''>iteration</span> <span m=''3651500''>space,</span> <span m=''3651990''>I</span>
  <span m=''3652180''>got</span> <span m=''3652400''>data</span> <span m=''3652610''>from</span>
  <span m=''3652740''>somewhere</span> <span m=''3652980''>else.</span> </p><p><span
  m=''3657060''>So,</span> <span m=''3658340''>you</span> <span m=''3658490''>get</span>
  <span m=''3658660''>this</span> <span m=''3659020''>function</span> <span m=''3659580''>here.</span>
  <span m=''3659730''>I</span> <span m=''3659770''>think</span> <span m=''3660100''>I''ll</span>
  <span m=''3660240''>go</span> <span m=''3660390''>to</span> <span m=''3660450''>the</span>
  <span m=''3660540''>next</span> <span m=''3661140''>slide.</span> <span m=''3682490''>So</span>
  <span m=''3682690''>what</span> <span m=''3683040''>you</span> <span m=''3683070''>can</span>
  <span m=''3683300''>do</span> <span m=''3683360''>is now</span> <span m=''3683600''>I</span>
  <span m=''3683830''>have</span> <span m=''3685760''>processor</span> <span m=''3686080''>who</span>
  <span m=''3686340''>read,</span> <span m=''3687240''>processor</span> <span m=''3687600''>who</span>
  <span m=''3687910''>write,</span> <span m=''3689200''>and</span> <span m=''3689480''>iterations</span>
  <span m=''3690110''>that</span> <span m=''3690290''>I</span> <span m=''3690340''>can</span>
  <span m=''3690570''>reading</span> <span m=''3690880''>and</span> <span m=''3691050''>writing.</span>
  <span m=''3693190''>One</span> <span m=''3693780''>thing</span> <span m=''3693950''>I</span>
  <span m=''3694040''>can</span> <span m=''3694340''>do</span> <span m=''3694570''>is</span>
  <span m=''3695670''>I</span> <span m=''3695810''>can</span> <span m=''3696050''>represent</span>
  <span m=''3696300''>i</span> <span m=''3696760''>using</span> <span m=''3697110''>a</span>
  <span m=''3697660''>huge</span> <span m=''3698090''>multi-dimensional</span> <span
  m=''3698940''>space.</span> <span m=''3700660''>So</span> <span m=''3701010''>what</span>
  <span m=''3701230''>happens</span> <span m=''3701580''>in</span> <span m=''3701760''>here</span>
  <span m=''3702040''>is</span> <span m=''3702930''>the</span> <span m=''3703690''>receive</span>
  <span m=''3704030''>iterations,</span> <span m=''3705410''>those</span> <span m=''3706010''>are</span>
  <span m=''3706300''>the</span> <span m=''3706420''>iterations</span> <span m=''3706810''>that</span>
  <span m=''3707080''>actually</span> <span m=''3707570''>data has to</span> <span
  m=''3707650''>be</span> <span m=''3707730''>received in</span> <span m=''3708260''>communication.</span>
  <span m=''3709440''>Assume</span> <span m=''3709780''>that</span> <span m=''3709860''>the</span>
  <span m=''3710280''>part</span> <span m=''3710510''>I''m</span> <span m=''3710660''>actually</span>
  <span m=''3710730''>communicating</span> <span m=''3711080''>is</span> <span m=''3711220''>also</span>
  <span m=''3711790''>within</span> <span m=''3712020''>the</span> <span m=''3712490''>loop</span>
  <span m=''3712690''>bound,</span> <span m=''3712880''>so</span> <span m=''3712990''>I</span>
  <span m=''3713430''>can</span> <span m=''3713650''>write</span> <span m=''3713840''>that.</span>
  <span m=''3715570''>And</span> <span m=''3715880''>the</span> <span m=''3715960''>last</span>
  <span m=''3716320''>write</span> <span m=''3717960''>relation</span> <span m=''3718080''>is</span>
  <span m=''3718560''>that</span> <span m=''3720100''>i</span> <span m=''3720280''>send</span>
  <span m=''3720530''>has</span> <span m=''3720680''>to</span> <span m=''3720770''>be</span>
  <span m=''3720860''>i</span> <span m=''3721000''>receive.</span> <span m=''3722890''>We</span>
  <span m=''3722980''>know</span> <span m=''3723110''>that.</span> <span m=''3726040''>What</span>
  <span m=''3726380''>you</span> <span m=''3726440''>have</span> <span m=''3726850''>is</span>
  <span m=''3728910''>the</span> <span m=''3729470''>parallel</span> <span m=''3729920''>with</span>
  <span m=''3730030''>the processors --</span> <span m=''3730420''>this</span> <span
  m=''3730620''>is</span> <span m=''3731250''>i</span> <span m=''3731700''>iterations</span>
  <span m=''3731870''>are</span> <span m=''3732460''>parallel,</span> <span m=''3732900''>so</span>
  <span m=''3733010''>processor,</span> <span m=''3733410''>receive</span> <span m=''3733840''>processor,</span>
  <span m=''3734660''>is</span> <span m=''3734840''>running</span> <span m=''3736200''>iteration</span>
  <span m=''3736610''>i,</span> <span m=''3738030''>process i.</span> <span m=''3738500''>Send</span>
  <span m=''3738810''>iterations</span> <span m=''3739130''>are</span> <span m=''3739350''>the</span>
  <span m=''3739430''>same</span> <span m=''3739690''>because</span> <span m=''3739930''>you</span>
  <span m=''3740050''>want</span> <span m=''3740250''>to</span> <span m=''3740410''>parallelize</span>
  <span m=''3740650''>that</span> <span m=''3741790''>loop</span> <span m=''3741960''>basically.</span>
  <span m=''3742990''>In</span> <span m=''3743280''>each</span> <span m=''3743650''>iteration</span>
  <span m=''3744500''>get</span> <span m=''3744850''>assigned</span> <span m=''3745160''>to</span>
  <span m=''3745220''>each</span> <span m=''3745350''>process.</span> <span m=''3746900''>Of</span>
  <span m=''3747000''>course,</span> <span m=''3747210''>you</span> <span m=''3747310''>want
  to</span> <span m=''3747510''>make</span> <span m=''3747670''>sure</span> <span
  m=''3747780''>the</span> <span m=''3748640''>process</span> <span m=''3748730''>communication</span>
  <span m=''3749370''>is</span> <span m=''3749520''>non-local.</span> <span m=''3749960''>If
  it''s local</span> <span m=''3750480''>I</span> <span m=''3750530''>don''t</span>
  <span m=''3750690''>have</span> <span m=''3750860''>loop</span> <span m=''3750930''>communication.</span>
  <span m=''3751900''>I</span> <span m=''3751940''>can</span> <span m=''3752160''>represent</span>
  <span m=''3752610''>this</span> <span m=''3752830''>as</span> <span m=''3753030''>this</span>
  <span m=''3753550''>gigantic</span> <span m=''3754260''>system</span> <span m=''3754580''>of</span>
  <span m=''3754640''>equalities.</span> <span m=''3755310''>It</span> <span m=''3755730''>has</span>
  <span m=''3756310''>one,</span> <span m=''3756620''>two,</span> <span m=''3756780''>three,</span>
  <span m=''3757030''>four,</span> <span m=''3757270''>five,</span> <span m=''3757650''>and</span>
  <span m=''3757810''>there''s</span> <span m=''3757940''>a</span> <span m=''3758010''>j</span>
  <span m=''3758270''>receiver</span> <span m=''3758590''>also</span> <span m=''3758740''>in</span>
  <span m=''3758870''>here,</span> <span m=''3759190''>because</span> <span m=''3759450''>you''ve</span>
  <span m=''3759670''>got</span> <span m=''3760150''>to</span> <span m=''3760310''>remember</span>
  <span m=''3761520''>I</span> <span m=''3761600''>think</span> <span m=''3761990''>the</span>
  <span m=''3762130''>program</span> <span m=''3762510''>I</span> <span m=''3762590''>wrote,</span>
  <span m=''3763260''>the</span> <span m=''3763430''>original</span> <span m=''3763640''>program</span>
  <span m=''3764060''>basically,</span> <span m=''3764870''>write</span> <span m=''3765480''>happen</span>
  <span m=''3765920''>in</span> <span m=''3766210''>outer</span> <span m=''3766520''>loop</span>
  <span m=''3767160''>and</span> <span m=''3767330''>the</span> <span m=''3767410''>read</span>
  <span m=''3767570''>happen inner</span> <span m=''3767740''>loop.</span> <span m=''3768230''>So</span>
  <span m=''3768400''>there''s</span> <span m=''3768590''>only</span> <span m=''3768940''>j</span>
  <span m=''3769180''>receive,</span> <span m=''3769850''>the</span> <span m=''3769920''>i</span>
  <span m=''3770440''>send in here.</span> <span m=''3771690''>I''ll</span> <span
  m=''3773370''>show that later.</span> </p><p><span m=''3774220''>So</span> <span
  m=''3774840''>I</span> <span m=''3774920''>have</span> <span m=''3775680''>five</span>
  <span m=''3775990''>dimensions.</span> <span m=''3776570''>So</span> <span m=''3777120''>I</span>
  <span m=''3777250''>can''t really</span> <span m=''3777950''>draw</span> <span m=''3778310''>five</span>
  <span m=''3778510''>dimensions,</span> <span m=''3778940''>but</span> <span m=''3780340''>can</span>
  <span m=''3780490''>I</span> <span m=''3780560''>wait</span> <span m=''3780990''>until</span>
  <span m=''3781290''>it</span> <span m=''3781410''>comes</span> <span m=''3781680''>back?</span>
  <span m=''3804640''>So</span> <span m=''3805390''>what</span> <span m=''3805610''>I</span>
  <span m=''3805700''>have</span> <span m=''3806220''>here</span> <span m=''3806470''>is</span>
  <span m=''3806870''>I</span> <span m=''3806970''>have</span> <span m=''3807190''>this</span>
  <span m=''3807290''>set</span> <span m=''3807550''>of</span> <span m=''3807700''>complete</span>
  <span m=''3808460''>system</span> <span m=''3808960''>of</span> <span m=''3809050''>inequalities</span>
  <span m=''3810100''>for</span> <span m=''3810550''>receive</span> <span m=''3810890''>and</span>
  <span m=''3811050''>in</span> <span m=''3811430''>communication.</span> <span m=''3812620''>Of</span>
  <span m=''3812800''>course,</span> <span m=''3813070''>since</span> <span m=''3813210''>I</span>
  <span m=''3813440''>can''t</span> <span m=''3813930''>draw</span> <span m=''3814140''>five</span>
  <span m=''3814610''>dimensions,</span> <span m=''3815290''>and</span> <span m=''3816450''>these</span>
  <span m=''3816650''>dimensions</span> <span m=''3817050''>are</span> <span m=''3817160''>the</span>
  <span m=''3817250''>same,</span> <span m=''3817840''>I</span> <span m=''3817950''>just</span>
  <span m=''3818140''>wrote</span> <span m=''3818330''>it</span> <span m=''3818450''>in</span>
  <span m=''3818560''>the</span> <span m=''3818700''>same.</span> <span m=''3819100''>So</span>
  <span m=''3819210''>you</span> <span m=''3819290''>can</span> <span m=''3819470''>actually</span>
  <span m=''3819620''>assume</span> <span m=''3819890''>that there''s</span> <span
  m=''3820040''>another</span> <span m=''3820320''>two</span> <span m=''3820430''>dimensions</span>
  <span m=''3821180''>for</span> <span m=''3821320''>this</span> <span m=''3821540''>one,</span>
  <span m=''3822000''>and</span> <span m=''3822210''>that''s</span> <span m=''3822340''>a</span>
  <span m=''3822410''>line</span> <span m=''3823040''>in</span> <span m=''3823380''>that</span>
  <span m=''3823730''>dimension.</span> <span m=''3827320''>Actually,</span> <span
  m=''3828800''>this</span> <span m=''3829070''>is</span> <span m=''3830000''>wrong.
  Sorry.</span> <span m=''3830200''>This</span> <span m=''3830500''>should</span>
  <span m=''3830820''>be</span> <span m=''3831030''>xi</span> <span m=''3832330''>here</span>
  <span m=''3832950''>written.</span> <span m=''3836330''>My</span> <span m=''3836450''>program</span>
  <span m=''3836790''>is</span> <span m=''3837120''>wrong, sorry.</span> <span m=''3844290''>Now
  what</span> <span m=''3845070''>do I do?</span> <span m=''3845690''>One</span> <span
  m=''3845760''>more</span> <span m=''3846050''>time</span> <span m=''3846340''>it</span>
  <span m=''3850070''>has</span> <span m=''3850350''>to go.</span> <span m=''3850460''>It</span>
  <span m=''3851060''>makes</span> <span m=''3851670''>me</span> <span m=''3851850''>slow</span>
  <span m=''3852170''>down my</span> <span m=''3853720''>lectures which</span> <span
  m=''3853910''>is</span> <span m=''3856080''>probably</span> <span m=''3856390''>a</span>
  <span m=''3857300''>good</span> <span m=''3857510''>thing.</span> <span m=''3858350''>There</span>
  <span m=''3858610''>we go.</span> </p><p><span m=''3859490''>So</span> <span m=''3859700''>what</span>
  <span m=''3859950''>you</span> <span m=''3860040''>can</span> <span m=''3860320''>do</span>
  <span m=''3860530''>is</span> <span m=''3861160''>you</span> <span m=''3861420''>can</span>
  <span m=''3861630''>just</span> <span m=''3861880''>scan</span> <span m=''3862390''>these</span>
  <span m=''3862590''>by</span> <span m=''3862830''>predicting</span> <span m=''3863500''>different</span>
  <span m=''3864000''>ways</span> <span m=''3864280''>to</span> <span m=''3864460''>calculate</span>
  <span m=''3864910''>the</span> <span m=''3864990''>send</span> <span m=''3865330''>loop
  nest</span> <span m=''3865590''>and</span> <span m=''3866280''>receive</span> <span
  m=''3866720''>loop nest.</span> <span m=''3867200''>So if you</span> <span m=''3867660''>scan
  in</span> <span m=''3868140''>that</span> <span m=''3868340''>direction,</span>
  <span m=''3869260''>what</span> <span m=''3869590''>you</span> <span m=''3869700''>end</span>
  <span m=''3870060''>up</span> <span m=''3870280''>is</span> <span m=''3870420''>something</span>
  <span m=''3870840''>saying</span> <span m=''3872030''>for</span> <span m=''3872480''>this</span>
  <span m=''3872900''>processor</span> <span m=''3873770''>you</span> <span m=''3874060''>need</span>
  <span m=''3874200''>to</span> <span m=''3874280''>send,</span> <span m=''3875110''>for</span>
  <span m=''3875250''>this</span> <span m=''3875500''>iteration,</span> <span m=''3877850''>this</span>
  <span m=''3877960''>processor.</span> <span m=''3879090''>For</span> <span m=''3879570''>what</span>
  <span m=''3879900''>you</span> <span m=''3880010''>need</span> <span m=''3880230''>to</span>
  <span m=''3880330''>send</span> <span m=''3880750''>will</span> <span m=''3880880''>be</span>
  <span m=''3881160''>received</span> <span m=''3881540''>by</span> <span m=''3881710''>these</span>
  <span m=''3882080''>processors</span> <span m=''3883250''>and</span> <span m=''3883510''>this</span>
  <span m=''3883600''>iteration</span> <span m=''3884320''>and</span> <span m=''3885430''>this,</span>
  <span m=''3885840''>and</span> <span m=''3886070''>this</span> <span m=''3886210''>you</span>
  <span m=''3886320''>can</span> <span m=''3886650''>send</span> <span m=''3886950''>xi</span>
  <span m=''3888390''>to</span> <span m=''3888550''>this</span> <span m=''3889700''>iteration</span>
  <span m=''3890740''>at</span> <span m=''3890910''>this</span> <span m=''3891090''>processor.</span>
  <span m=''3891760''>Because</span> <span m=''3892550''>you</span> <span m=''3892710''>had</span>
  <span m=''3893510''>that</span> <span m=''3894280''>relationship,</span> <span m=''3895040''>you</span>
  <span m=''3895230''>can</span> <span m=''3895410''>get</span> <span m=''3895560''>the</span>
  <span m=''3895600''>loop nest</span> <span m=''3896080''>that</span> <span m=''3896210''>actually</span>
  <span m=''3896520''>will</span> <span m=''3896680''>do</span> <span m=''3897300''>the</span>
  <span m=''3898820''>send.</span> <span m=''3900720''>The</span> <span m=''3900850''>send</span>
  <span m=''3901300''>there</span> <span m=''3901480''>you</span> <span m=''3901620''>can</span>
  <span m=''3901790''>actually</span> <span m=''3902110''>get</span> <span m=''3902720''>a</span>
  <span m=''3902970''>loop nest</span> <span m=''3903470''>do</span> <span m=''3903590''>receive</span>
  <span m=''3904050''>and it</span> <span m=''3904220''>shows</span> <span m=''3904470''>up.</span>
  </p><p><span m=''3906640''>So</span> <span m=''3906740''>what</span> <span m=''3906880''>that</span>
  <span m=''3907500''>means</span> <span m=''3907740''>is,</span> <span m=''3908000''>so</span>
  <span m=''3908390''>all</span> <span m=''3908600''>these</span> <span m=''3908800''>guys</span>
  <span m=''3908970''>have to send</span> <span m=''3911100''>all</span> <span m=''3911340''>these</span>
  <span m=''3911470''>iterations</span> <span m=''3912300''>have</span> <span m=''3912480''>to
  do the</span> <span m=''3912750''>receive.</span> <span m=''3930900''>So,</span>
  <span m=''3931000''>if you</span> <span m=''3931460''>predicted</span> <span m=''3932020''>a</span>
  <span m=''3932100''>different</span> <span m=''3933220''>ordering,</span> <span
  m=''3935010''>what</span> <span m=''3935220''>you</span> <span m=''3935330''>end</span>
  <span m=''3935520''>up</span> <span m=''3935740''>is</span> <span m=''3936210''>you
  can</span> <span m=''3936510''>say</span> <span m=''3936780''>now</span> <span m=''3937390''>for</span>
  <span m=''3937580''>this</span> <span m=''3938110''>processor</span> <span m=''3938710''>has</span>
  <span m=''3938900''>to</span> <span m=''3939010''>receive.</span> <span m=''3939550''>All</span>
  <span m=''3939830''>these</span> <span m=''3940020''>processors</span> <span m=''3940870''>had
  to</span> <span m=''3941070''>receive</span> <span m=''3941420''>something</span>
  <span m=''3941730''>send</span> <span m=''3942040''>by</span> <span m=''3942140''>these</span>
  <span m=''3942420''>guys.</span> <span m=''3944500''>So</span> <span m=''3944640''>now</span>
  <span m=''3944810''>you</span> <span m=''3944970''>can</span> <span m=''3945170''>get</span>
  <span m=''3945310''>that</span> <span m=''3945750''>entire</span> <span m=''3946130''>loop
  nest</span> <span m=''3947050''>for</span> <span m=''3947760''>receiving</span>
  <span m=''3948130''>and</span> <span m=''3948550''>entire</span> <span m=''3948870''>loop
  nest</span> <span m=''3949440''>for sending, and you have</span> <span m=''3949810''>computation</span>
  <span m=''3950480''>loop nest also.</span> <span m=''3951570''>The</span> <span
  m=''3951670''>problem</span> <span m=''3952000''>is</span> <span m=''3952070''>you</span>
  <span m=''3952170''>can''t</span> <span m=''3952450''>run</span> <span m=''3952630''>them</span>
  <span m=''3952960''>sequentially</span> <span m=''3953570''>because</span> <span
  m=''3953790''>you''re</span> <span m=''3953950''>run</span> <span m=''3954270''>in
  some</span> <span m=''3954440''>into the</span> <span m=''3954550''>order.</span>
  <span m=''3955440''>So</span> <span m=''3955630''>what</span> <span m=''3955920''>you</span>
  <span m=''3955980''>have</span> <span m=''3956360''>is</span> <span m=''3956850''>something</span>
  <span m=''3957310''>that</span> <span m=''3957670''>next</span> <span m=''3958180''>slide
  will</span> <span m=''3958350''>show.</span> <span m=''3960350''>So</span> <span
  m=''3960490''>you</span> <span m=''3960700''>have</span> <span m=''3960750''>this</span>
  <span m=''3961130''>iteration,</span> <span m=''3961710''>there''s</span> <span
  m=''3961850''>some</span> <span m=''3962170''>computation</span> <span m=''3962580''>happen</span>
  <span m=''3962820''>from</span> <span m=''3963510''>all</span> <span m=''3963750''>the</span>
  <span m=''3963880''>one,</span> <span m=''3964300''>and</span> <span m=''3964540''>I</span>
  <span m=''3964600''>will</span> <span m=''3964730''>get</span> <span m=''3964840''>a</span>
  <span m=''3964870''>loop nest</span> <span m=''3965380''>do</span> <span m=''3965580''>some</span>
  <span m=''3965760''>send,</span> <span m=''3966130''>I</span> <span m=''3966190''>need</span>
  <span m=''3966390''>loop nest</span> <span m=''3967030''>do</span> <span m=''3967160''>some</span>
  <span m=''3967470''>receive,</span> <span m=''3967960''>in a</span> <span m=''3968030''>one</span>
  <span m=''3968210''>dimensional,</span> <span m=''3968700''>these</span> <span m=''3968980''>kind</span>
  <span m=''3969200''>of,</span> <span m=''3969730''>you</span> <span m=''3970020''>get</span>
  <span m=''3970160''>three</span> <span m=''3970700''>seperate things.</span> <span
  m=''3971440''>But</span> <span m=''3971610''>of</span> <span m=''3971740''>course,</span>
  <span m=''3971980''>what</span> <span m=''3972120''>you had</span> <span m=''3972300''>to</span>
  <span m=''3972360''>do</span> <span m=''3972610''>is</span> <span m=''3973310''>you</span>
  <span m=''3973540''>had</span> <span m=''3973840''>to</span> <span m=''3973960''>generate</span>
  <span m=''3974760''>code.</span> <span m=''3974940''>So the</span> <span m=''3975060''>way</span>
  <span m=''3975270''>to</span> <span m=''3975350''>do</span> <span m=''3975530''>that</span>
  <span m=''3976020''>is --.</span> <span m=''3981850''>So</span> <span m=''3982000''>what</span>
  <span m=''3982140''>you</span> <span m=''3982330''>have to do</span> <span m=''3982530''>is</span>
  <span m=''3982680''>kind</span> <span m=''3982870''>of</span> <span m=''3982990''>break
  this</span> <span m=''3983300''>apart</span> <span m=''3983610''>into</span> <span
  m=''3984240''>pieces</span> <span m=''3984740''>where</span> <span m=''3985000''>things</span>
  <span m=''3985250''>happen,</span> <span m=''3985550''>so</span> <span m=''3985640''>this</span>
  <span m=''3985850''>one</span> <span m=''3986080''>you</span> <span m=''3986180''>do</span>
  <span m=''3986280''>computation,</span> <span m=''3987290''>this</span> <span m=''3987460''>one</span>
  <span m=''3987630''>you</span> <span m=''3987930''>do</span> <span m=''3988090''>computation</span>
  <span m=''3988870''>and</span> <span m=''3988990''>receive,</span> <span m=''3989720''>and</span>
  <span m=''3990430''>computation</span> <span m=''3991330''>send</span> <span m=''3991740''>receive
  and</span> <span m=''3991950''>whatever.</span> <span m=''3994840''>Should</span>
  <span m=''3995130''>be</span> <span m=''3995240''>probably</span> <span m=''3995530''>send</span>
  <span m=''3996680''>here</span> <span m=''3997080''>and</span> <span m=''3997240''>receive</span>
  <span m=''3997480''>but --</span> </p><p><span m=''4000350''>For</span> <span m=''4000440''>that</span>
  <span m=''4000750''>one,</span> <span m=''4001460''>if</span> <span m=''4001600''>you</span>
  <span m=''4001700''>combine</span> <span m=''4002100''>this</span> <span m=''4002230''>you</span>
  <span m=''4002350''>get</span> <span m=''4002540''>a</span> <span m=''4002890''>complicated</span>
  <span m=''4003360''>mess</span> <span m=''4003560''>like</span> <span m=''4003790''>this.</span>
  <span m=''4003960''>But</span> <span m=''4004110''>this all</span> <span m=''4004770''>can</span>
  <span m=''4004950''>be</span> <span m=''4005070''>done</span> <span m=''4005380''>very</span>
  <span m=''4006160''>in</span> <span m=''4006370''>an</span> <span m=''4006870''>automated</span>
  <span m=''4007450''>fashion</span> <span m=''4008060''>by</span> <span m=''4008200''>using</span>
  <span m=''4009300''>this</span> <span m=''4009460''>Fourier-Motzkin</span> <span
  m=''4009960''>Elimination</span> <span m=''4010650''>and</span> <span m=''4011070''>this</span>
  <span m=''4011240''>linear</span> <span m=''4011850''>representation.</span> <span
  m=''4015830''>Of</span> <span m=''4015940''>course,</span> <span m=''4016210''>you</span>
  <span m=''4016290''>can</span> <span m=''4016470''>do</span> <span m=''4016530''>a</span>
  <span m=''4016560''>lot</span> <span m=''4016720''>of</span> <span m=''4016870''>interesting</span>
  <span m=''4017240''>things</span> <span m=''4017420''>on</span> <span m=''4017560''>top</span>
  <span m=''4017720''>of</span> <span m=''4017780''>that.</span> <span m=''4017880''>You</span>
  <span m=''4017970''>can</span> <span m=''4018100''>eliminate</span> <span m=''4018510''>redundant</span>
  <span m=''4018790''>communication,</span> <span m=''4019360''>if</span> <span m=''4019470''>you''re</span>
  <span m=''4019600''>keeping</span> <span m=''4019940''>sending</span> <span m=''4020230''>the</span>
  <span m=''4020330''>same</span> <span m=''4020590''>thing</span> <span m=''4020760''>again</span>
  <span m=''4021170''>that</span> <span m=''4021340''>have</span> <span m=''4021450''>a</span>
  <span m=''4021520''>send unit,</span> <span m=''4021950''>eliminate</span> <span
  m=''4022330''>that,</span> <span m=''4022830''>you</span> <span m=''4023010''>can</span>
  <span m=''4023340''>aggregate</span> <span m=''4023620''>communication.</span> <span
  m=''4024780''>You</span> <span m=''4024860''>want</span> <span m=''4024920''>to</span>
  <span m=''4025170''>send a word at</span> <span m=''4025270''>a</span> <span m=''4025330''>time,</span>
  <span m=''4025630''>you</span> <span m=''4025710''>can</span> <span m=''4025930''>send</span>
  <span m=''4026300''>bunch</span> <span m=''4026540''>of</span> <span m=''4026650''>things</span>
  <span m=''4026870''>into</span> <span m=''4027030''>one</span> <span m=''4027220''>packet.</span>
  <span m=''4028940''>You</span> <span m=''4029150''>can</span> <span m=''4029310''>do</span>
  <span m=''4029610''>multitask.</span> <span m=''4029810''>So</span> <span m=''4030420''>same</span>
  <span m=''4030770''>thing,</span> <span m=''4031020''>send</span> <span m=''4031100''>to
  multiple</span> <span m=''4031690''>people.</span> <span m=''4032160''>Doesn''t</span>
  <span m=''4032460''>have</span> <span m=''4032620''>that</span> <span m=''4032820''>much</span>
  <span m=''4033030''>in</span> <span m=''4033350''>Cell,</span> <span m=''4034050''>but</span>
  <span m=''4034820''>assume</span> <span m=''4034930''>some</span> <span m=''4035110''>machines
  have multitask support,</span> <span m=''4036390''>you</span> <span m=''4036480''>can</span>
  <span m=''4036690''>do</span> <span m=''4036830''>that,</span> <span m=''4037310''>and</span>
  <span m=''4037590''>also</span> <span m=''4037790''>you</span> <span m=''4037890''>can</span>
  <span m=''4038050''>do</span> <span m=''4038200''>some</span> <span m=''4038470''>local</span>
  <span m=''4038600''>memory</span> <span m=''4038760''>management</span> <span m=''4039510''>because</span>
  <span m=''4040020''>if</span> <span m=''4040220''>you</span> <span m=''4040290''>have</span>
  <span m=''4040670''>distributed</span> <span m=''4040980''>memory,</span> <span
  m=''4042080''>you don''t have</span> <span m=''4042150''>to allocate</span> <span
  m=''4042690''>everybody''s</span> <span m=''4043270''>memory</span> <span m=''4043490''>and</span>
  <span m=''4043580''>only</span> <span m=''4043810''>use</span> <span m=''4044020''>a</span>
  <span m=''4044090''>part.</span> <span m=''4044520''>You can say</span> <span m=''4044680''>OK,</span>
  <span m=''4044790''>look</span> <span m=''4045320''>everybody</span> <span m=''4045950''>only</span>
  <span m=''4046160''>had</span> <span m=''4046260''>to</span> <span m=''4046370''>allocate</span>
  <span m=''4046590''>that</span> <span m=''4046790''>part.</span> </p><p><span m=''4049270''>OK.</span>
  <span m=''4050680''>In</span> <span m=''4051230''>summary,</span> <span m=''4052920''>I</span>
  <span m=''4053110''>think</span> <span m=''4053750''>automatic</span> <span m=''4054290''>parallelism</span>
  <span m=''4054990''>of</span> <span m=''4055680''>loops</span> <span m=''4056030''>and</span>
  <span m=''4056180''>arrays --</span> <span m=''4057180''>we</span> <span m=''4057330''>talked</span>
  <span m=''4057540''>about</span> <span m=''4057690''>data</span> <span m=''4057830''>dependence</span>
  <span m=''4058260''>analysis,</span> <span m=''4058960''>and</span> <span m=''4059250''>we</span>
  <span m=''4059350''>talked</span> <span m=''4059690''>about</span> <span m=''4059980''>iteration</span>
  <span m=''4060480''>and</span> <span m=''4060770''>data</span> <span m=''4061010''>spaces,</span>
  <span m=''4061130''>a</span> <span m=''4061190''>how to</span> <span m=''4061470''>do</span>
  <span m=''4061640''>that,</span> <span m=''4062210''>and</span> <span m=''4062840''>how</span>
  <span m=''4063000''>the</span> <span m=''4063120''>formulate</span> <span m=''4063330''>assay</span>
  <span m=''4063820''>integer</span> <span m=''4064270''>programming</span> <span
  m=''4064680''>problem.</span> <span m=''4066890''>We</span> <span m=''4067110''>can</span>
  <span m=''4067420''>look at</span> <span m=''4067680''>lot</span> <span m=''4067880''>of</span>
  <span m=''4068150''>optimization</span> <span m=''4068370''>that</span> <span m=''4068880''>can</span>
  <span m=''4069180''>increase</span> <span m=''4069380''>parallelism</span> <span
  m=''4070080''>and</span> <span m=''4070200''>then</span> <span m=''4070350''>do</span>
  <span m=''4070500''>that.</span> <span m=''4071740''>Also,</span> <span m=''4072030''>we</span>
  <span m=''4072190''>can deal</span> <span m=''4072570''>with</span> <span m=''4072720''>tings</span>
  <span m=''4073070''>like</span> <span m=''4074520''>communication</span> <span m=''4075040''>code</span>
  <span m=''4075760''>generation</span> <span m=''4075970''>and</span> <span m=''4076210''>generating</span>
  <span m=''4076330''>loop nest</span> <span m=''4077390''>by</span> <span m=''4077630''>doing</span>
  <span m=''4077990''>this</span> <span m=''4078150''>Fourier-Motzkin</span> <span
  m=''4078740''>Elimination.</span> </p><p><span m=''4079570''>So</span> <span m=''4079830''>what</span>
  <span m=''4080100''>I</span> <span m=''4080220''>want</span> <span m=''4080400''>to</span>
  <span m=''4080490''>show</span> <span m=''4080740''>out</span> <span m=''4080930''>of</span>
  <span m=''4081040''>this</span> <span m=''4081760''>talk</span> <span m=''4082090''>is</span>
  <span m=''4082280''>that,</span> <span m=''4082470''>in</span> <span m=''4082620''>fact,</span>
  <span m=''4083260''>this</span> <span m=''4083410''>parallelization</span> <span
  m=''4084460''>--</span> <span m=''4084810''>automatic</span> <span m=''4085290''>parallelization</span>
  <span m=''4085960''>of</span> <span m=''4086180''>normal</span> <span m=''4086590''>loop</span>
  <span m=''4087340''>can</span> <span m=''4087730''>be</span> <span m=''4087890''>done</span>
  <span m=''4088680''>by</span> <span m=''4088850''>mapping</span> <span m=''4089300''>into</span>
  <span m=''4089500''>some</span> <span m=''4089720''>nice</span> <span m=''4090060''>mathematical</span>
  <span m=''4091040''>framework,</span> <span m=''4091660''>and</span> <span m=''4092020''>basically</span>
  <span m=''4092440''>manipulating</span> <span m=''4092820''>in that</span> <span
  m=''4093660''>map.</span> <span m=''4095520''>So</span> <span m=''4095660''>there</span>
  <span m=''4095820''>are</span> <span m=''4095960''>many</span> <span m=''4096280''>other</span>
  <span m=''4096540''>things</span> <span m=''4097060''>that</span> <span m=''4097830''>really</span>
  <span m=''4098210''>complicates</span> <span m=''4098480''>the</span> <span m=''4098960''>life</span>
  <span m=''4099450''>take</span> <span m=''4099700''>out</span> <span m=''4099860''>of</span>
  <span m=''4100670''>parallelizing</span> <span m=''4101180''>programs.</span> <span
  m=''4102100''>So</span> <span m=''4102770''>like C,</span> <span m=''4102920''>there
  are</span> <span m=''4103040''>pointers,</span> <span m=''4103200''>you</span> <span
  m=''4103660''>have to deal with</span> <span m=''4104320''>that.</span> <span m=''4104860''>So</span>
  <span m=''4105850''>this</span> <span m=''4105970''>problem</span> <span m=''4106350''>is</span>
  <span m=''4106530''>not</span> <span m=''4106800''>this</span> <span m=''4107030''>simple,</span>
  <span m=''4107260''>but</span> <span m=''4108390''>what</span> <span m=''4108670''>compiler</span>
  <span m=''4109020''>writers</span> <span m=''4109250''>try</span> <span m=''4109520''>to</span>
  <span m=''4109590''>do</span> <span m=''4110050''>most</span> <span m=''4110400''>of
  the</span> <span m=''4110490''>time</span> <span m=''4110760''>is</span> <span m=''4110890''>trying</span>
  <span m=''4111070''>to</span> <span m=''4111150''>find</span> <span m=''4111420''>this</span>
  <span m=''4111570''>kind</span> <span m=''4111790''>of</span> <span m=''4111860''>thing.</span>
  <span m=''4112380''>Find</span> <span m=''4112750''>interesting</span> <span m=''4113180''>mathematical</span>
  <span m=''4113560''>models</span> <span m=''4113990''>and</span> <span m=''4114190''>do
  a</span> <span m=''4114350''>mapping</span> <span m=''4114750''>in</span> <span
  m=''4114960''>there and then</span> <span m=''4115200''>operating</span> <span m=''4115460''>that</span>
  <span m=''4116120''>model</span> <span m=''4116580''>and</span> <span m=''4116710''>hopefully</span>
  <span m=''4117120''>you</span> <span m=''4117230''>can</span> <span m=''4118150''>get</span>
  <span m=''4118670''>the</span> <span m=''4119380''>analysis</span> <span m=''4120060''>needed</span>
  <span m=''4120340''>and</span> <span m=''4120550''>even</span> <span m=''4120710''>the</span>
  <span m=''4120780''>transformation</span> <span m=''4121440''>needed</span> <span
  m=''4121940''>using</span> <span m=''4122180''>that</span> <span m=''4122360''>kind</span>
  <span m=''4122560''>of</span> <span m=''4122650''>a nice</span> <span m=''4122890''>model.</span>
  </p><p><span m=''4123760''>So</span> <span m=''4124900''>I</span> <span m=''4125480''>just</span>
  <span m=''4125750''>kind</span> <span m=''4125940''>of</span> <span m=''4126030''>gave</span>
  <span m=''4126320''>you</span> <span m=''4126490''>a</span> <span m=''4126790''>good</span>
  <span m=''4127130''>feel for</span> <span m=''4127980''>general</span> <span m=''4128770''>parallelizing</span>
  <span m=''4129260''>compilers.</span> <span m=''4129690''>We</span> <span m=''4129860''>will</span>
  <span m=''4130280''>take</span> <span m=''4130540''>a</span> <span m=''4130630''>ten-minute</span>
  <span m=''4131180''>break</span> <span m=''4131690''>and</span> <span m=''4132240''>talk</span>
  <span m=''4132470''>about</span> <span m=''4132690''>streaming.</span> <span m=''4134760''>We''ll</span>
  <span m=''4134870''>see if I can</span> <span m=''4135040''>make</span> <span m=''4135200''>this</span>
  <span m=''4135310''>computer</span> <span m=''4135580''>run</span> <span m=''4135780''>faster</span>
  <span m=''4135900''>in the</span> <span m=''4136490''>meantime.</span> </p>'
type: course
uid: 9fbaa99532b1034d0db2098164665871

---
None