---
about_this_resource_text: <p><strong>Topics covered:</strong> SIMD programming on
  Cell</p><p><strong>Instructor:</strong> Phil Sung</p>
course_id: 6-189-multicore-programming-primer-january-iap-2007
embedded_media:
- id: r6.jpg
  parent_uid: 43100f5929a9b823e22a5f55efec95f5
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-189-multicore-programming-primer-january-iap-2007/recitations/r6-simd-programming-on-cell/r6.jpg
  title: 'R6: SIMD Programming on Cell'
  type: null
  uid: 700f511135cf513133ed6dec65995a90
- id: Video-YouTube-Stream
  media_location: zg1bHfos6U8
  parent_uid: 43100f5929a9b823e22a5f55efec95f5
  title: Video-YouTube-Stream
  type: Video
  uid: f61c3f0a42b86bad41158d7f4fb100cf
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/zg1bHfos6U8/default.jpg
  parent_uid: 43100f5929a9b823e22a5f55efec95f5
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 86a4c82c294021d219d29eeedb7ba34b
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id341597759
  parent_uid: 43100f5929a9b823e22a5f55efec95f5
  title: Video-iTunes U-MP4
  type: Video
  uid: 15331270a5be240db43c345d93b21d13
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT6.189IAP07/ocw-6.189-iap07-rec06_300k.mp4
  parent_uid: 43100f5929a9b823e22a5f55efec95f5
  title: Video-Internet Archive-MP4
  type: Video
  uid: eb30db1545d13d1ff7f1e167026494fd
- id: Thumbnail-OCW-JPG
  parent_uid: 43100f5929a9b823e22a5f55efec95f5
  title: Thumbnail-OCW-JPG
  type: Thumbnail
  uid: e241d8d73cfa8a435d3c568e669b70f5
- id: 3Play-3PlayYouTubeid-MP4
  media_location: zg1bHfos6U8
  parent_uid: 43100f5929a9b823e22a5f55efec95f5
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 12dcbfd677a742f89ad5a22c90ed129a
- id: zg1bHfos6U8.srt
  parent_uid: 43100f5929a9b823e22a5f55efec95f5
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-189-multicore-programming-primer-january-iap-2007/recitations/r6-simd-programming-on-cell/zg1bHfos6U8.srt
  title: 3play caption file
  type: null
  uid: 3c4ffcfa723a64555eb96c0c6e00bda8
- id: zg1bHfos6U8.pdf
  parent_uid: 43100f5929a9b823e22a5f55efec95f5
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-189-multicore-programming-primer-january-iap-2007/recitations/r6-simd-programming-on-cell/zg1bHfos6U8.pdf
  title: 3play pdf file
  type: null
  uid: de46c10e54422c5ff8b33db624276458
- id: Caption-3Play YouTube id-SRT
  parent_uid: 43100f5929a9b823e22a5f55efec95f5
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: bce907f1c3e0528043fc2d4c8abcbe00
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 43100f5929a9b823e22a5f55efec95f5
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 269e319d5d62703e4968d6e1bddc9fac
inline_embed_id: 4987637r6:simdprogrammingoncell81363972
layout: video
order_index: null
parent_uid: 1a7273101a37c171a13d06e2fa6799d5
related_resources_text: '<p class="instruction">Special software is required to use
  some of the files in this section: .<a href="/help/faq-technical-requirements/#zip">zip</a>,
  <a href="/help/faq-technical-requirements/#c">.c</a>, <a href="/help/faq-technical-requirements/#h">.h</a>,
  and <a href="/help/faq-technical-requirements/#s">.s</a>.</p><p><strong>Lecture
  Notes:</strong><br /> SIMD programming on Cell (<a href="./resolveuid/0410c29ef913477b9b5d4769f628a678"
  target="_blank" title="Open in a new window." alt="Open in a new window.">PDF</a>)</p>
  <p><strong>Supporting Files:</strong><br /> rec6.zip (<a href="./resolveuid/91d1d7ff7f74386e25a9ad3981c8cb3b"
  target="_blank" title="Open in a new window." alt="Open in a new window.">ZIP</a>)
  (The ZIP file contains: 4 .o files, sim_spu, sim, 3 .d files, sim_spu.a, 5 .h files,
  10 makefile files, and 14 .c files.)</p>'
short_url: r6-simd-programming-on-cell
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-189-multicore-programming-primer-january-iap-2007/recitations/r6-simd-programming-on-cell
template_type: Tabbed
title: 'R6: SIMD Programming on Cell'
transcript: '<p><span m=''40''>The</span> <span m=''170''>following</span> <span m=''610''>content</span>
  <span m=''1200''>is</span> <span m=''1320''>provided</span> <span m=''1760''>under</span>
  <span m=''2040''>a</span> <span m=''2080''>Creative</span> <span m=''2480''>Commons</span>
  <span m=''2890''>license.</span> <span m=''4000''>Your</span> <span m=''4190''>support</span>
  <span m=''4690''>will</span> <span m=''4850''>help</span> <span m=''5090''>MIT</span>
  <span m=''5550''>OpenCourseWare</span> <span m=''6340''>continue</span> <span m=''6850''>to</span>
  <span m=''6930''>offer</span> <span m=''7340''>high</span> <span m=''7580''>quality</span>
  <span m=''8100''>educational</span> <span m=''8730''>resources</span> <span m=''9350''>for</span>
  <span m=''9500''>free.</span> <span m=''10710''>To</span> <span m=''10720''>make</span>
  <span m=''10920''>a</span> <span m=''10960''>donation,</span> <span m=''11650''>or</span>
  <span m=''11920''>view</span> <span m=''12360''>additional</span> <span m=''12780''>materials</span>
  <span m=''13320''>from</span> <span m=''13470''>hundreds</span> <span m=''13900''>of</span>
  <span m=''14010''>MIT</span> <span m=''14440''>courses,</span> <span m=''15540''>visit</span>
  <span m=''15770''>MIT</span> <span m=''16190''>OpenCourseWare</span> <span m=''17240''>at</span>
  <span m=''17400''>ocw.mit.edu.</span> </p><p><span m=''21241''>PROFESSOR:</span>
  <span m=''21640''>So</span> <span m=''21940''>this</span> <span m=''22120''>hour</span>
  <span m=''22350''>we''re</span> <span m=''22450''>going</span> <span m=''22550''>to</span>
  <span m=''22610''>talk</span> <span m=''22800''>about</span> <span m=''23270''>SIMD</span>
  <span m=''23730''>programming</span> <span m=''24140''>with</span> <span m=''24550''>cell.</span>
  <span m=''27750''>First</span> <span m=''27940''>we''ll</span> <span m=''28020''>talk</span>
  <span m=''28200''>a</span> <span m=''28250''>little</span> <span m=''28390''>bit</span>
  <span m=''28500''>about</span> <span m=''28740''>what</span> <span m=''28950''>SIMD</span>
  <span m=''29200''>is</span> <span m=''29900''>and</span> <span m=''30150''>then</span>
  <span m=''31930''>about</span> <span m=''32180''>the</span> <span m=''32310''>facilities</span>
  <span m=''32810''>that</span> <span m=''33110''>cell</span> <span m=''33470''>and</span>
  <span m=''33570''>the</span> <span m=''33640''>compiler</span> <span m=''34050''>provide</span>
  <span m=''34720''>for</span> <span m=''34980''>programming</span> <span m=''35440''>with</span>
  <span m=''35685''>SIMD.</span> <span m=''36460''>And</span> <span m=''36660''>then</span>
  <span m=''36810''>some</span> <span m=''37020''>design</span> <span m=''37350''>considerations</span>
  <span m=''37910''>that</span> <span m=''37980''>you</span> <span m=''38050''>have</span>
  <span m=''38140''>to</span> <span m=''38200''>keep</span> <span m=''38350''>in</span>
  <span m=''38420''>mind</span> <span m=''38730''>when</span> <span m=''38930''>you''re</span>
  <span m=''39180''>doing</span> <span m=''39420''>things.</span> </p><p><span m=''42850''>All</span>
  <span m=''42950''>right</span> <span m=''43170''>so</span> <span m=''43320''>the</span>
  <span m=''43460''>situation</span> <span m=''43930''>these</span> <span m=''44090''>days</span>
  <span m=''44310''>is</span> <span m=''44440''>that</span> <span m=''45040''>most</span>
  <span m=''45380''>compute</span> <span m=''45790''>bound</span> <span m=''46020''>applications</span>
  <span m=''46600''>are</span> <span m=''47330''>running</span> <span m=''47630''>through</span>
  <span m=''48820''>a</span> <span m=''48900''>large</span> <span m=''49240''>piece</span>
  <span m=''49410''>of</span> <span m=''49500''>data</span> <span m=''49870''>and</span>
  <span m=''50170''>running</span> <span m=''50390''>the</span> <span m=''50460''>same</span>
  <span m=''50740''>computations</span> <span m=''51350''>on</span> <span m=''51480''>it</span>
  <span m=''51580''>over</span> <span m=''51830''>and</span> <span m=''51900''>over</span>
  <span m=''52080''>again,</span> <span m=''52630''>or</span> <span m=''52720''>rather</span>
  <span m=''53020''>running</span> <span m=''53310''>the</span> <span m=''53410''>same</span>
  <span m=''53650''>computations</span> <span m=''54140''>across</span> <span m=''54800''>all</span>
  <span m=''55000''>the</span> <span m=''55070''>pieces</span> <span m=''55360''>of</span>
  <span m=''55470''>different</span> <span m=''55740''>data.</span> <span m=''56860''>And</span>
  <span m=''57230''>very</span> <span m=''57450''>frequently</span> <span m=''58360''>there''ll</span>
  <span m=''58640''>be</span> <span m=''58960''>no</span> <span m=''59770''>dependence</span>
  <span m=''60280''>between</span> <span m=''60610''>iterations</span> <span m=''61230''>when</span>
  <span m=''61360''>you''re</span> <span m=''61540''>going</span> <span m=''61780''>through</span>
  <span m=''61890''>this</span> <span m=''62060''>data.</span> <span m=''63110''>So</span>
  <span m=''63290''>that</span> <span m=''63460''>means</span> <span m=''64410''>there''s</span>
  <span m=''64700''>opportunities</span> <span m=''65379''>for</span> <span m=''65580''>you</span>
  <span m=''65780''>to</span> <span m=''66060''>data</span> <span m=''66330''>parallelize.</span>
  </p><p><span m=''69970''>So</span> <span m=''70380''>as</span> <span m=''70530''>an</span>
  <span m=''70610''>example,</span> <span m=''72820''>if</span> <span m=''72880''>we</span>
  <span m=''72990''>have</span> <span m=''73570''>for</span> <span m=''73700''>example,</span>
  <span m=''75390''>say</span> <span m=''75550''>we''re</span> <span m=''75660''>multiplying</span>
  <span m=''77280''>a0</span> <span m=''77840''>and</span> <span m=''78080''>b0</span>
  <span m=''78430''>to</span> <span m=''78490''>get</span> <span m=''78690''>c0.</span>
  <span m=''80510''>And</span> <span m=''82890''>suppose</span> <span m=''83240''>we</span>
  <span m=''83340''>want</span> <span m=''83620''>to</span> <span m=''83900''>actually</span>
  <span m=''84250''>perform</span> <span m=''84580''>this</span> <span m=''84730''>operation</span>
  <span m=''85200''>across</span> <span m=''85640''>all</span> <span m=''85830''>the</span>
  <span m=''85950''>elements</span> <span m=''86670''>of</span> <span m=''87580''>arrays</span>
  <span m=''88120''>a,</span> <span m=''88310''>b</span> <span m=''88470''>and</span>
  <span m=''88590''>c.</span> <span m=''89250''>So</span> <span m=''89370''>instead</span>
  <span m=''89630''>of</span> <span m=''89730''>multiplying</span> <span m=''90350''>two</span>
  <span m=''90600''>elements</span> <span m=''91200''>or</span> <span m=''91350''>two</span>
  <span m=''91820''>integers</span> <span m=''92190''>together,</span> <span m=''92970''>we''re</span>
  <span m=''93150''>actually</span> <span m=''93450''>going</span> <span m=''93560''>to</span>
  <span m=''93620''>be</span> <span m=''94510''>taking</span> <span m=''95980''>two</span>
  <span m=''96620''>arrays</span> <span m=''97990''>an</span> <span m=''98260''>element-wise</span>
  <span m=''98920''>multiplying</span> <span m=''99400''>each</span> <span m=''100250''>of</span>
  <span m=''100490''>the--</span> <span m=''102110''>multiplying</span> <span m=''102500''>each</span>
  <span m=''102660''>of</span> <span m=''102740''>the</span> <span m=''103490''>pairs</span>
  <span m=''103790''>element-wise</span> <span m=''104800''>and</span> <span m=''105120''>writing</span>
  <span m=''105390''>the</span> <span m=''105510''>results</span> <span m=''105900''>to</span>
  <span m=''106030''>a</span> <span m=''106070''>third</span> <span m=''106290''>array.</span>
  </p><p><span m=''106940''>So</span> <span m=''107070''>the</span> <span m=''107140''>picture''s</span>
  <span m=''107430''>going</span> <span m=''107520''>to</span> <span m=''107580''>look</span>
  <span m=''107780''>something</span> <span m=''108030''>like</span> <span m=''108200''>this.</span>
  <span m=''109010''>And</span> <span m=''110920''>you</span> <span m=''111110''>would</span>
  <span m=''111240''>of</span> <span m=''111330''>course</span> <span m=''111570''>represent</span>
  <span m=''111960''>this</span> <span m=''112120''>using</span> <span m=''112850''>for</span>
  <span m=''113080''>example,</span> <span m=''113410''>four</span> <span m=''113650''>loop.</span>
  <span m=''116140''>Now</span> <span m=''116480''>what</span> <span m=''116620''>we''re</span>
  <span m=''116730''>going</span> <span m=''116830''>to</span> <span m=''116900''>do</span>
  <span m=''117200''>is</span> <span m=''119050''>instead</span> <span m=''119400''>of--</span>
  <span m=''120530''>let''s</span> <span m=''120900''>see,</span> <span m=''121660''>so</span>
  <span m=''121750''>you</span> <span m=''121860''>can</span> <span m=''121970''>think</span>
  <span m=''122120''>of</span> <span m=''122200''>this</span> <span m=''122410''>as</span>
  <span m=''123440''>kind</span> <span m=''123620''>of</span> <span m=''124090''>an</span>
  <span m=''124210''>operation</span> <span m=''124930''>that''s</span> <span m=''125130''>abstractly</span>
  <span m=''125590''>operating</span> <span m=''125990''>on</span> <span m=''126700''>these</span>
  <span m=''127490''>entire</span> <span m=''127960''>arrays.</span> </p><p><span
  m=''129289''>And</span> <span m=''129729''>we''re</span> <span m=''129850''>not</span>
  <span m=''129979''>going</span> <span m=''130070''>to</span> <span m=''130340''>go</span>
  <span m=''130560''>quite</span> <span m=''130800''>that</span> <span m=''130979''>far,</span>
  <span m=''131620''>but</span> <span m=''131810''>what</span> <span m=''131950''>we''re</span>
  <span m=''132050''>going</span> <span m=''132150''>to</span> <span m=''132210''>do</span>
  <span m=''132460''>is</span> <span m=''133790''>we''re</span> <span m=''134350''>going</span>
  <span m=''134580''>to</span> <span m=''135160''>think</span> <span m=''135320''>of</span>
  <span m=''135380''>these</span> <span m=''135510''>operations</span> <span m=''136050''>as</span>
  <span m=''136250''>acting</span> <span m=''136610''>on</span> <span m=''137130''>these</span>
  <span m=''137420''>kind</span> <span m=''137550''>of</span> <span m=''137640''>bundles</span>
  <span m=''138160''>of</span> <span m=''138270''>elements.</span> </p><p><span m=''139300''>So</span>
  <span m=''139420''>we''re</span> <span m=''139530''>going</span> <span m=''139620''>to</span>
  <span m=''139680''>bundle</span> <span m=''140130''>our</span> <span m=''140880''>arrayed</span>
  <span m=''141140''>elements</span> <span m=''141480''>into</span> <span m=''141670''>groups</span>
  <span m=''141950''>of</span> <span m=''142050''>four.</span> <span m=''143100''>And</span>
  <span m=''143300''>then</span> <span m=''144500''>each</span> <span m=''144720''>time</span>
  <span m=''144970''>we''re</span> <span m=''145050''>going</span> <span m=''145130''>to</span>
  <span m=''145220''>take</span> <span m=''145640''>a</span> <span m=''145750''>group</span>
  <span m=''146120''>and</span> <span m=''146270''>multiply</span> <span m=''146680''>with</span>
  <span m=''146840''>another</span> <span m=''147090''>group</span> <span m=''147300''>using</span>
  <span m=''147580''>this</span> <span m=''147750''>element-wise</span> <span m=''148390''>multiplication</span>
  <span m=''149320''>and</span> <span m=''149820''>write</span> <span m=''150000''>the</span>
  <span m=''150070''>result</span> <span m=''150460''>to</span> <span m=''150510''>this</span>
  <span m=''150800''>third</span> <span m=''151170''>bundle.</span> <span m=''152290''>OK</span>
  <span m=''152620''>does</span> <span m=''153110''>that</span> <span m=''153220''>make</span>
  <span m=''153370''>sense?</span> </p><p><span m=''155480''>Now</span> <span m=''155810''>the</span>
  <span m=''155930''>thing</span> <span m=''156100''>about</span> <span m=''156390''>this</span>
  <span m=''156550''>kind</span> <span m=''156720''>of</span> <span m=''156990''>model</span>
  <span m=''157320''>is</span> <span m=''157440''>that</span> <span m=''158590''>cell</span>
  <span m=''158910''>is</span> <span m=''159010''>going</span> <span m=''159110''>to</span>
  <span m=''159180''>provide</span> <span m=''159570''>very</span> <span m=''159790''>good</span>
  <span m=''159930''>hardware</span> <span m=''160290''>support</span> <span m=''160780''>for</span>
  <span m=''160980''>something</span> <span m=''161250''>that</span> <span m=''161410''>looks</span>
  <span m=''161990''>kind</span> <span m=''162140''>of</span> <span m=''162180''>like</span>
  <span m=''162340''>this.</span> </p><p><span m=''163181''>AUDIENCE:</span> <span
  m=''163652''>Is</span> <span m=''163809''>that</span> <span m=''163966''>actual</span>
  <span m=''164123''>cell</span> <span m=''164594''>[INAUDIBLE]</span> </p><p><span
  m=''168770''>PROFESSOR:</span> <span m=''169160''>Yes,</span> <span m=''169710''>I''ll</span>
  <span m=''170000''>get</span> <span m=''170150''>into</span> <span m=''170340''>this.</span>
  <span m=''170630''>In</span> <span m=''170780''>fact,</span> <span m=''171090''>this</span>
  <span m=''171240''>is</span> <span m=''171580''>what</span> <span m=''171810''>we''ll</span>
  <span m=''171930''>be</span> <span m=''172050''>talking</span> <span m=''172300''>about</span>
  <span m=''172940''>the</span> <span m=''173020''>syntax</span> <span m=''173500''>and</span>
  <span m=''174320''>meaning</span> <span m=''174630''>of</span> <span m=''174770''>this</span>
  <span m=''175040''>kind</span> <span m=''175250''>of</span> <span m=''175340''>thing.</span>
  <span m=''175940''>All</span> <span m=''176330''>right?</span> </p><p><span m=''179250''>So</span>
  <span m=''181850''>for</span> <span m=''181980''>this</span> <span m=''182170''>kind</span>
  <span m=''182370''>of</span> <span m=''182470''>thing</span> <span m=''182650''>to</span>
  <span m=''182720''>happen</span> <span m=''183530''>we</span> <span m=''183690''>need</span>
  <span m=''184020''>the</span> <span m=''184110''>compiler</span> <span m=''184600''>to</span>
  <span m=''184700''>support</span> <span m=''185210''>two</span> <span m=''185320''>different</span>
  <span m=''185580''>things.</span> <span m=''186240''>First</span> <span m=''186640''>is</span>
  <span m=''187300''>we</span> <span m=''187430''>need</span> <span m=''187600''>to</span>
  <span m=''187670''>be</span> <span m=''187810''>able</span> <span m=''187990''>to</span>
  <span m=''188340''>address</span> <span m=''188820''>these</span> <span m=''189040''>kind</span>
  <span m=''189200''>of</span> <span m=''189280''>bundles</span> <span m=''189680''>of</span>
  <span m=''189770''>elements</span> <span m=''190470''>and</span> <span m=''191100''>these</span>
  <span m=''191260''>are</span> <span m=''191310''>going</span> <span m=''191410''>to</span>
  <span m=''191460''>be</span> <span m=''191580''>called</span> <span m=''192050''>vectors.</span>
  </p><p><span m=''193000''>And</span> <span m=''193280''>second</span> <span m=''193590''>we</span>
  <span m=''193690''>need</span> <span m=''193960''>to</span> <span m=''194190''>be</span>
  <span m=''194300''>able</span> <span m=''194440''>to</span> <span m=''194520''>perform</span>
  <span m=''194960''>operations</span> <span m=''195590''>on</span> <span m=''195780''>these</span>
  <span m=''196040''>vectors.</span> <span m=''198530''>So</span> <span m=''200420''>cell</span>
  <span m=''200860''>and</span> <span m=''201110''>the</span> <span m=''201350''>XLC</span>
  <span m=''201760''>compiler</span> <span m=''204190''>give</span> <span m=''204340''>us</span>
  <span m=''204400''>support</span> <span m=''204780''>for</span> <span m=''204860''>this.</span>
  <span m=''205590''>And</span> <span m=''206090''>what</span> <span m=''206250''>they''re</span>
  <span m=''206390''>going</span> <span m=''206490''>to</span> <span m=''206550''>do</span>
  <span m=''206780''>is</span> <span m=''206950''>provide</span> <span m=''207650''>first,</span>
  <span m=''208150''>registers</span> <span m=''208790''>which</span> <span m=''208960''>are</span>
  <span m=''209030''>capable</span> <span m=''209470''>of</span> <span m=''209530''>holding</span>
  <span m=''209880''>vectors.</span> <span m=''210940''>Now</span> <span m=''211070''>normally</span>
  <span m=''211630''>you</span> <span m=''211780''>think</span> <span m=''211920''>of</span>
  <span m=''212000''>a</span> <span m=''212080''>register</span> <span m=''212510''>as</span>
  <span m=''212590''>holding</span> <span m=''214620''>on</span> <span m=''215670''>a</span>
  <span m=''216330''>32-bit</span> <span m=''217230''>machine,</span> <span m=''217550''>one</span>
  <span m=''217780''>machine</span> <span m=''218100''>word</span> <span m=''218300''>will</span>
  <span m=''218440''>hold</span> <span m=''219160''>a</span> <span m=''219300''>32-bit</span>
  <span m=''219910''>int,</span> <span m=''220140''>for</span> <span m=''220260''>example.</span>
  </p><p><span m=''221550''>What</span> <span m=''221580''>we''re</span> <span m=''221680''>going</span>
  <span m=''221770''>to</span> <span m=''221810''>have</span> <span m=''222010''>on</span>
  <span m=''222090''>the</span> <span m=''222150''>cell</span> <span m=''222500''>is</span>
  <span m=''223110''>these</span> <span m=''223510''>128-bit</span> <span m=''224530''>registers</span>
  <span m=''225370''>which</span> <span m=''225570''>are</span> <span m=''225650''>going</span>
  <span m=''225820''>to</span> <span m=''225860''>be</span> <span m=''225960''>able</span>
  <span m=''226130''>to</span> <span m=''226200''>hold</span> <span m=''226510''>for</span>
  <span m=''226600''>example</span> <span m=''226960''>four</span> <span m=''227270''>ints</span>
  <span m=''227480''>right</span> <span m=''227680''>next</span> <span m=''227900''>to</span>
  <span m=''227980''>each</span> <span m=''228120''>other.</span> <span m=''229540''>So</span>
  <span m=''229710''>we''re</span> <span m=''229810''>going</span> <span m=''229890''>to</span>
  <span m=''229930''>be</span> <span m=''230100''>able</span> <span m=''230260''>to</span>
  <span m=''231140''>take</span> <span m=''231730''>this</span> <span m=''231890''>bundle</span>
  <span m=''232200''>of</span> <span m=''232300''>ints</span> <span m=''232550''>and</span>
  <span m=''232800''>operate</span> <span m=''233055''>it--</span> <span m=''233550''>operate</span>
  <span m=''233910''>on</span> <span m=''234070''>it</span> <span m=''234240''>as</span>
  <span m=''234450''>a</span> <span m=''234480''>unit.</span> </p><p><span m=''236770''>And</span>
  <span m=''238220''>the</span> <span m=''238390''>second</span> <span m=''238640''>part</span>
  <span m=''238870''>is</span> <span m=''239070''>we''re</span> <span m=''239210''>going</span>
  <span m=''239290''>to</span> <span m=''239330''>have</span> <span m=''239600''>operations</span>
  <span m=''240170''>that</span> <span m=''240320''>act</span> <span m=''240600''>on</span>
  <span m=''241060''>these</span> <span m=''241330''>vector</span> <span m=''241610''>registers.</span>
  <span m=''242800''>So</span> <span m=''243970''>the</span> <span m=''244420''>cell</span>
  <span m=''244710''>is</span> <span m=''244810''>going</span> <span m=''244900''>to</span>
  <span m=''244950''>support</span> <span m=''245330''>special</span> <span m=''245690''>assembly</span>
  <span m=''246060''>instructions</span> <span m=''247250''>and</span> <span m=''247580''>it''s</span>
  <span m=''247690''>going</span> <span m=''247780''>to</span> <span m=''247820''>be</span>
  <span m=''247900''>able</span> <span m=''248050''>to</span> <span m=''248160''>interpret</span>
  <span m=''248550''>those</span> <span m=''248790''>as</span> <span m=''248950''>acting</span>
  <span m=''249300''>on</span> <span m=''250130''>particular</span> <span m=''250980''>vectors.</span>
  </p><p><span m=''252020''>But</span> <span m=''252110''>also</span> <span m=''252330''>we''re</span>
  <span m=''252440''>going</span> <span m=''252540''>to</span> <span m=''252580''>have</span>
  <span m=''252910''>C++</span> <span m=''253630''>language</span> <span m=''253960''>extensions</span>
  <span m=''254480''>which</span> <span m=''254630''>are</span> <span m=''254700''>called</span>
  <span m=''254970''>intrinsics.</span> <span m=''255780''>And</span> <span m=''255940''>those</span>
  <span m=''256110''>are</span> <span m=''256170''>going</span> <span m=''256279''>to</span>
  <span m=''256480''>give</span> <span m=''256620''>us</span> <span m=''256750''>access</span>
  <span m=''257180''>to</span> <span m=''257269''>these</span> <span m=''257430''>special</span>
  <span m=''257829''>assembly</span> <span m=''258269''>instructions,</span> <span
  m=''259010''>but</span> <span m=''260450''>not</span> <span m=''260649''>require</span>
  <span m=''261040''>us</span> <span m=''261180''>to</span> <span m=''262430''>be</span>
  <span m=''262540''>poking</span> <span m=''262790''>around</span> <span m=''263050''>in</span>
  <span m=''263120''>the</span> <span m=''263220''>assembly.</span> </p><p><span m=''265200''>All</span>
  <span m=''265270''>right</span> <span m=''265990''>now</span> <span m=''267160''>the</span>
  <span m=''267270''>big</span> <span m=''267450''>draw</span> <span m=''267610''>of</span>
  <span m=''267770''>this</span> <span m=''268450''>is</span> <span m=''268590''>that</span>
  <span m=''268760''>these</span> <span m=''268950''>operations</span> <span m=''269560''>are</span>
  <span m=''269690''>going</span> <span m=''269790''>to</span> <span m=''269840''>be</span>
  <span m=''270640''>pretty</span> <span m=''270970''>much</span> <span m=''271200''>as</span>
  <span m=''271430''>fast</span> <span m=''271820''>as</span> <span m=''272760''>single</span>
  <span m=''273080''>operations,</span> <span m=''273830''>which</span> <span m=''273910''>means</span>
  <span m=''274130''>that</span> <span m=''274210''>if</span> <span m=''274275''>we</span>
  <span m=''274340''>take</span> <span m=''274510''>advantage</span> <span m=''274860''>of</span>
  <span m=''274900''>them</span> <span m=''275170''>we</span> <span m=''275270''>can</span>
  <span m=''275370''>make</span> <span m=''275430''>our</span> <span m=''275530''>code</span>
  <span m=''275780''>run</span> <span m=''276430''>say</span> <span m=''276650''>four</span>
  <span m=''276870''>times</span> <span m=''277120''>as</span> <span m=''277240''>fast.</span>
  </p><p><span m=''281790''>OK</span> <span m=''282020''>so</span> <span m=''282950''>how</span>
  <span m=''283110''>do</span> <span m=''283190''>we</span> <span m=''283450''>refer</span>
  <span m=''283990''>to</span> <span m=''284100''>these</span> <span m=''284590''>vectors</span>
  <span m=''285020''>when</span> <span m=''285170''>we''re</span> <span m=''285300''>coding?</span>
  <span m=''288470''>XLC</span> <span m=''288770''>is</span> <span m=''288980''>going</span>
  <span m=''289080''>to</span> <span m=''289120''>provide</span> <span m=''289440''>us</span>
  <span m=''289590''>with</span> <span m=''290160''>these</span> <span m=''290590''>intrinsics.</span>
  <span m=''291540''>And</span> <span m=''292180''>we</span> <span m=''292310''>have</span>
  <span m=''292590''>these</span> <span m=''292790''>vector</span> <span m=''293070''>data</span>
  <span m=''293320''>types</span> <span m=''294150''>and</span> <span m=''294340''>each</span>
  <span m=''294540''>one</span> <span m=''294730''>is</span> <span m=''294830''>just</span>
  <span m=''295000''>going</span> <span m=''295090''>to</span> <span m=''295140''>specify</span>
  <span m=''296170''>how</span> <span m=''296490''>to</span> <span m=''296610''>interpret</span>
  <span m=''297220''>a</span> <span m=''297300''>consecutive</span> <span m=''298460''>group</span>
  <span m=''298660''>of</span> <span m=''298750''>128-bits</span> <span m=''300120''>as</span>
  <span m=''300340''>some</span> <span m=''300550''>sort</span> <span m=''300800''>of</span>
  <span m=''300980''>vector.</span> </p><p><span m=''301830''>And</span> <span m=''301980''>you</span>
  <span m=''302040''>can</span> <span m=''302130''>have</span> <span m=''302230''>vectors</span>
  <span m=''302610''>of</span> <span m=''303000''>varying</span> <span m=''304270''>element</span>
  <span m=''304590''>sizes</span> <span m=''305040''>and</span> <span m=''305250''>varying</span>
  <span m=''306980''>number</span> <span m=''307250''>of</span> <span m=''307320''>elements.</span>
  <span m=''308400''>So</span> <span m=''309640''>when</span> <span m=''309790''>you''re</span>
  <span m=''309890''>programming</span> <span m=''310320''>on</span> <span m=''310450''>the</span>
  <span m=''310580''>PPU</span> <span m=''310950''>or</span> <span m=''311060''>the</span>
  <span m=''311190''>SPU</span> <span m=''311710''>you</span> <span m=''311860''>get</span>
  <span m=''312170''>these</span> <span m=''313050''>four</span> <span m=''313330''>different</span>
  <span m=''313610''>kinds</span> <span m=''313950''>of</span> <span m=''315030''>vector</span>
  <span m=''315690''>data</span> <span m=''315920''>types.</span> <span m=''316680''>You</span>
  <span m=''316820''>can</span> <span m=''316930''>declare</span> <span m=''317270''>things</span>
  <span m=''317590''>as</span> <span m=''317780''>for</span> <span m=''317880''>example,</span>
  <span m=''318400''>vector</span> <span m=''318760''>signed</span> <span m=''319130''>int,</span>
  <span m=''320990''>which</span> <span m=''321120''>is</span> <span m=''321730''>what</span>
  <span m=''322000''>I</span> <span m=''322030''>mentioned</span> <span m=''322380''>in</span>
  <span m=''322450''>the</span> <span m=''322580''>example.</span> <span m=''323120''>Which</span>
  <span m=''323370''>is</span> <span m=''323490''>where</span> <span m=''323630''>you</span>
  <span m=''323740''>have</span> <span m=''324570''>four</span> <span m=''324990''>ints</span>
  <span m=''325260''>next</span> <span m=''325480''>to</span> <span m=''325563''>each</span>
  <span m=''325646''>other</span> <span m=''325800''>each</span> <span m=''326050''>32-bits.</span>
  </p><p><span m=''327020''>You</span> <span m=''327170''>could</span> <span m=''327260''>also</span>
  <span m=''327490''>have</span> <span m=''327970''>vectors</span> <span m=''328430''>which</span>
  <span m=''328640''>contains</span> <span m=''329060''>16-bit</span> <span m=''329740''>integers</span>
  <span m=''330260''>or</span> <span m=''330480''>8-bit</span> <span m=''330770''>integers.</span>
  <span m=''331930''>And</span> <span m=''335390''>you</span> <span m=''335510''>could</span>
  <span m=''335620''>also</span> <span m=''335790''>have</span> <span m=''336100''>vectors</span>
  <span m=''336850''>of</span> <span m=''337160''>floating</span> <span m=''337700''>point--</span>
  <span m=''338220''>floating</span> <span m=''338550''>point</span> <span m=''339030''>numbers.</span>
  </p><p><span m=''341970''>I</span> <span m=''342060''>should</span> <span m=''342210''>mention</span>
  <span m=''342430''>that</span> <span m=''342570''>all</span> <span m=''342760''>of</span>
  <span m=''342870''>these</span> <span m=''343680''>signed</span> <span m=''345150''>integer</span>
  <span m=''345490''>types</span> <span m=''345810''>also</span> <span m=''346040''>have</span>
  <span m=''346430''>unsigned</span> <span m=''346800''>equivalence.</span> <span
  m=''347950''>Anyway,</span> <span m=''348180''>so</span> <span m=''348290''>you</span>
  <span m=''348420''>can</span> <span m=''348730''>just</span> <span m=''348920''>declare</span>
  <span m=''349230''>these</span> <span m=''349470''>anywhere</span> <span m=''349810''>in</span>
  <span m=''349880''>your</span> <span m=''350000''>code</span> <span m=''350300''>and</span>
  <span m=''350410''>use</span> <span m=''350620''>them</span> <span m=''350920''>as</span>
  <span m=''351120''>if</span> <span m=''351240''>they</span> <span m=''351340''>were</span>
  <span m=''351530''>a</span> <span m=''351570''>C++</span> <span m=''352580''>data</span>
  <span m=''352820''>type.</span> <span m=''353750''>All</span> <span m=''353840''>right</span>
  <span m=''354000''>any</span> <span m=''354120''>questions?</span> </p><p><span
  m=''356270''>On</span> <span m=''356410''>the</span> <span m=''356520''>SPU</span>
  <span m=''356950''>you</span> <span m=''357130''>also</span> <span m=''357340''>get</span>
  <span m=''357630''>some</span> <span m=''357830''>additional</span> <span m=''358840''>vector</span>
  <span m=''359110''>data</span> <span m=''359320''>types.</span> <span m=''360120''>One</span>
  <span m=''360280''>is</span> <span m=''360420''>vector</span> <span m=''360740''>signed</span>
  <span m=''361230''>long-long,</span> <span m=''361840''>which</span> <span m=''362020''>is</span>
  <span m=''362160''>64-bit</span> <span m=''362840''>ints</span> <span m=''363235''>and</span>
  <span m=''363630''>you</span> <span m=''363700''>can</span> <span m=''363800''>fit</span>
  <span m=''363960''>two</span> <span m=''364120''>of</span> <span m=''364170''>those</span>
  <span m=''364380''>in</span> <span m=''364540''>128.</span> <span m=''365490''>And</span>
  <span m=''365700''>you</span> <span m=''365770''>can</span> <span m=''365880''>also</span>
  <span m=''366220''>fit</span> <span m=''366820''>two</span> <span m=''367520''>double</span>
  <span m=''367790''>precision</span> <span m=''368340''>floating</span> <span m=''368660''>point</span>
  <span m=''368860''>numbers</span> <span m=''369250''>in</span> <span m=''369450''>128-bits.</span>
  </p><p><span m=''372550''>Now</span> <span m=''373370''>the</span> <span m=''373560''>compiler''s</span>
  <span m=''374050''>actually</span> <span m=''374330''>support</span> <span m=''374760''>these</span>
  <span m=''375250''>types</span> <span m=''375700''>pretty</span> <span m=''375880''>nicely.</span>
  <span m=''376590''>So</span> <span m=''376710''>not</span> <span m=''376890''>only</span>
  <span m=''377050''>can</span> <span m=''377160''>you</span> <span m=''377270''>declare</span>
  <span m=''377660''>variables</span> <span m=''378070''>of</span> <span m=''378165''>these</span>
  <span m=''378260''>types</span> <span m=''378580''>pretty</span> <span m=''378770''>much</span>
  <span m=''378940''>anywhere</span> <span m=''379170''>in</span> <span m=''379220''>your</span>
  <span m=''379330''>code,</span> <span m=''379950''>you</span> <span m=''380050''>can</span>
  <span m=''380140''>also</span> <span m=''380350''>declare</span> <span m=''381050''>pointers</span>
  <span m=''381470''>to</span> <span m=''381560''>these</span> <span m=''381750''>types</span>
  <span m=''382090''>and</span> <span m=''382330''>arrays</span> <span m=''382680''>of</span>
  <span m=''382780''>these</span> <span m=''382960''>types.</span> <span m=''383850''>All</span>
  <span m=''383930''>right.</span> <span m=''384960''>And</span> <span m=''385200''>so</span>
  <span m=''385510''>they</span> <span m=''385690''>look</span> <span m=''385870''>pretty</span>
  <span m=''386040''>much</span> <span m=''386300''>like</span> <span m=''387240''>natural</span>
  <span m=''387790''>C++</span> <span m=''388410''>types,</span> <span m=''389130''>except</span>
  <span m=''389480''>that</span> <span m=''389690''>they</span> <span m=''389820''>translate</span>
  <span m=''390320''>directly</span> <span m=''390810''>into</span> <span m=''391210''>these</span>
  <span m=''391410''>particular</span> <span m=''392220''>types</span> <span m=''392560''>that</span>
  <span m=''392690''>the</span> <span m=''392970''>hardware</span> <span m=''393410''>supports.</span>
  </p><p><span m=''398510''>Now</span> <span m=''398720''>in</span> <span m=''398860''>order</span>
  <span m=''399020''>to</span> <span m=''399140''>manipulate</span> <span m=''399730''>these</span>
  <span m=''400550''>vector</span> <span m=''402150''>data,</span> <span m=''404600''>we''re</span>
  <span m=''404700''>going</span> <span m=''404790''>to</span> <span m=''404830''>have</span>
  <span m=''405070''>the--</span> <span m=''405480''>we''re</span> <span m=''405650''>going</span>
  <span m=''405740''>to</span> <span m=''405780''>have</span> <span m=''406290''>compiler</span>
  <span m=''406710''>extensions</span> <span m=''407220''>called</span> <span m=''407510''>intrinsics,</span>
  <span m=''408680''>which</span> <span m=''408840''>are</span> <span m=''408920''>going</span>
  <span m=''409100''>to</span> <span m=''409160''>provide</span> <span m=''409570''>access</span>
  <span m=''409920''>to</span> <span m=''410540''>the</span> <span m=''410660''>assembly</span>
  <span m=''411060''>level</span> <span m=''411290''>features</span> <span m=''411610''>that</span>
  <span m=''411710''>we</span> <span m=''411780''>want.</span> <span m=''412620''>Remember</span>
  <span m=''413970''>we''re</span> <span m=''414140''>going</span> <span m=''414230''>to</span>
  <span m=''414270''>have</span> <span m=''414560''>specific</span> <span m=''415100''>assembly</span>
  <span m=''415430''>instructions</span> <span m=''415870''>that</span> <span m=''415990''>correspond</span>
  <span m=''416470''>to</span> <span m=''416580''>for</span> <span m=''416700''>example,</span>
  <span m=''417300''>multiplying</span> <span m=''418100''>two</span> <span m=''421660''>vectors</span>
  <span m=''422000''>which</span> <span m=''422140''>contain</span> <span m=''422640''>each</span>
  <span m=''422980''>four,</span> <span m=''423330''>32-bit</span> <span m=''423920''>integers.</span>
  </p><p><span m=''426080''>And</span> <span m=''428070''>instead</span> <span m=''428330''>of</span>
  <span m=''428420''>writing</span> <span m=''428720''>out--</span> <span m=''429490''>instead</span>
  <span m=''429780''>of</span> <span m=''430190''>going</span> <span m=''430540''>into</span>
  <span m=''430760''>the</span> <span m=''430870''>assembly</span> <span m=''431370''>and</span>
  <span m=''432850''>actually</span> <span m=''433110''>inserting</span> <span m=''433380''>that</span>
  <span m=''433490''>instruction</span> <span m=''433900''>ourselves,</span> <span
  m=''435050''>we</span> <span m=''435250''>just</span> <span m=''435470''>use</span>
  <span m=''435800''>a</span> <span m=''435980''>compiler</span> <span m=''436400''>intrinsic</span>
  <span m=''436840''>inside</span> <span m=''437250''>our</span> <span m=''437300''>C++</span>
  <span m=''437350''>code.</span> <span m=''438320''>And</span> <span m=''438460''>what</span>
  <span m=''438570''>it</span> <span m=''438640''>does</span> <span m=''438880''>is</span>
  <span m=''439020''>it</span> <span m=''439130''>provides</span> <span m=''439500''>this</span>
  <span m=''440050''>notation</span> <span m=''440520''>that</span> <span m=''440630''>looks</span>
  <span m=''440810''>a</span> <span m=''440850''>lot</span> <span m=''441030''>like</span>
  <span m=''441190''>a</span> <span m=''441230''>function</span> <span m=''441590''>call,</span>
  <span m=''442380''>but</span> <span m=''442510''>the</span> <span m=''442590''>compiler</span>
  <span m=''442980''>automatically</span> <span m=''443490''>translates</span> <span
  m=''444020''>it</span> <span m=''444160''>into</span> <span m=''444370''>the</span>
  <span m=''444450''>correct</span> <span m=''444820''>assembly</span> <span m=''445170''>instruction.</span>
  </p><p><span m=''446700''>And</span> <span m=''446730''>again</span> <span m=''447260''>you</span>
  <span m=''447350''>don''t</span> <span m=''447460''>have</span> <span m=''447550''>to</span>
  <span m=''447650''>worry</span> <span m=''447890''>about</span> <span m=''448570''>going</span>
  <span m=''448770''>into</span> <span m=''448930''>the</span> <span m=''449030''>assembly</span>
  <span m=''449620''>and</span> <span m=''449840''>messing</span> <span m=''450090''>around</span>
  <span m=''450410''>with</span> <span m=''451290''>this</span> <span m=''451590''>instruction</span>
  <span m=''452020''>that''s</span> <span m=''452100''>supposed</span> <span m=''452320''>to</span>
  <span m=''452380''>apply</span> <span m=''452710''>to</span> <span m=''452830''>these</span>
  <span m=''453060''>registers.</span> <span m=''453415''>You</span> <span m=''453770''>don''t</span>
  <span m=''453900''>have</span> <span m=''454000''>to</span> <span m=''454080''>worry</span>
  <span m=''454190''>about</span> <span m=''454350''>register</span> <span m=''454710''>allocation</span>
  <span m=''455200''>at</span> <span m=''455345''>all.</span> <span m=''456730''>The</span>
  <span m=''456840''>compiler</span> <span m=''457250''>just</span> <span m=''458210''>figures</span>
  <span m=''458470''>out</span> <span m=''458620''>the</span> <span m=''458690''>right</span>
  <span m=''458860''>thing</span> <span m=''459000''>for</span> <span m=''459100''>you.</span>
  <span m=''459930''>And</span> <span m=''460110''>to</span> <span m=''460200''>use</span>
  <span m=''460410''>these</span> <span m=''460590''>in</span> <span m=''460670''>your</span>
  <span m=''460790''>SPU</span> <span m=''461170''>program</span> <span m=''461480''>you''re</span>
  <span m=''461540''>going</span> <span m=''461620''>to</span> <span m=''461660''>want</span>
  <span m=''461800''>to</span> <span m=''461910''>include</span> <span m=''463220''>SPU_intrinsics.h.</span>
  </p><p><span m=''467040''>Now</span> <span m=''467230''>what''s</span> <span m=''467320''>a</span>
  <span m=''467360''>little</span> <span m=''467530''>bit</span> <span m=''467670''>confusing</span>
  <span m=''468110''>is</span> <span m=''468180''>that</span> <span m=''468300''>you''re</span>
  <span m=''468400''>going</span> <span m=''468490''>to</span> <span m=''468530''>have</span>
  <span m=''468810''>slightly</span> <span m=''469250''>different</span> <span m=''470610''>intrinsics</span>
  <span m=''471090''>available</span> <span m=''471470''>on</span> <span m=''471590''>the</span>
  <span m=''471660''>PPU</span> <span m=''472170''>and</span> <span m=''472270''>the</span>
  <span m=''472380''>SPU,</span> <span m=''473110''>because</span> <span m=''473300''>those</span>
  <span m=''473470''>are</span> <span m=''473550''>actually</span> <span m=''473900''>going</span>
  <span m=''474030''>to</span> <span m=''474080''>have</span> <span m=''474370''>different</span>
  <span m=''474690''>instruction</span> <span m=''475150''>sets.</span> <span m=''477480''>But</span>
  <span m=''477590''>anyway</span> <span m=''477880''>as</span> <span m=''478040''>an</span>
  <span m=''478100''>example,</span> <span m=''478540''>you</span> <span m=''479220''>can</span>
  <span m=''479350''>declare</span> <span m=''480830''>two</span> <span m=''482770''>variables</span>
  <span m=''483320''>of</span> <span m=''483520''>type</span> <span m=''483820''>vector</span>
  <span m=''484180''>signed</span> <span m=''484510''>int</span> <span m=''485460''>and</span>
  <span m=''485680''>then</span> <span m=''486330''>you</span> <span m=''486460''>can</span>
  <span m=''486560''>multiply</span> <span m=''487010''>them</span> <span m=''487190''>using</span>
  <span m=''487490''>this</span> <span m=''487620''>intrinsic</span> <span m=''488090''>called</span>
  <span m=''488420''>SPU</span> <span m=''489040''>add.</span> <span m=''490880''>All</span>
  <span m=''490960''>right</span> <span m=''491350''>and</span> <span m=''491560''>assign</span>
  <span m=''491860''>them</span> <span m=''492000''>to</span> <span m=''492140''>a</span>
  <span m=''492180''>third</span> <span m=''492480''>vector</span> <span m=''492830''>signed</span>
  <span m=''493100''>int.</span> <span m=''494170''>Questions?</span> <span m=''495660''>Yep.</span>
  </p><p><span m=''496834''>AUDIENCE:</span> <span m=''497316''>In</span> <span m=''497800''>what</span>
  <span m=''498190''>way</span> <span m=''498350''>are</span> <span m=''498510''>they</span>
  <span m=''498670''>introduced</span> <span m=''498820''>if</span> <span m=''499227''>you''re</span>
  <span m=''499328''>on</span> <span m=''499430''>the</span> <span m=''499532''>SPU</span>
  <span m=''499634''>or</span> <span m=''499769''>the</span> <span m=''499905''>PPU?</span>
  <span m=''500940''>Is</span> <span m=''501050''>it</span> <span m=''501160''>just--</span>
  <span m=''502680''>not</span> <span m=''503030''>entirely</span> <span m=''503670''>the</span>
  <span m=''503740''>same</span> <span m=''504140''>set</span> <span m=''504740''>of</span>
  <span m=''505140''>operations</span> <span m=''505620''>available?</span> <span
  m=''506040''>Or</span> <span m=''506105''>are</span> <span m=''506170''>there</span>
  <span m=''506380''>actually</span> <span m=''506620''>semantic</span> <span m=''507170''>differences?</span>
  <span m=''508210''>Could</span> <span m=''508370''>make</span> <span m=''508540''>a</span>
  <span m=''508590''>little</span> <span m=''508780''>header</span> <span m=''509010''>file</span>
  <span m=''509320''>that</span> <span m=''509540''>masks</span> <span m=''509980''>over</span>
  <span m=''510150''>the</span> <span m=''510320''>differences</span> <span m=''511080''>mostly.</span>
  </p><p><span m=''512679''>PROFESSOR:</span> <span m=''512984''>There</span> <span
  m=''513289''>are</span> <span m=''513470''>going</span> <span m=''513559''>to</span>
  <span m=''513600''>be</span> <span m=''513690''>some</span> <span m=''513929''>operations</span>
  <span m=''514490''>that</span> <span m=''514610''>are</span> <span m=''514760''>only</span>
  <span m=''515010''>available</span> <span m=''515450''>on</span> <span m=''515610''>one</span>
  <span m=''515909''>and</span> <span m=''515980''>not</span> <span m=''516130''>the</span>
  <span m=''516270''>other.</span> <span m=''517190''>But</span> <span m=''517250''>in</span>
  <span m=''517340''>general,</span> <span m=''518780''>if</span> <span m=''518950''>you</span>
  <span m=''519059''>look</span> <span m=''519200''>at</span> <span m=''519260''>the</span>
  <span m=''519330''>names,</span> <span m=''519720''>if</span> <span m=''519809''>the</span>
  <span m=''519900''>names</span> <span m=''520179''>correspond,</span> <span m=''521720''>and</span>
  <span m=''521820''>I''ll</span> <span m=''522000''>go</span> <span m=''522190''>into</span>
  <span m=''522309''>that</span> <span m=''522470''>in</span> <span m=''522690''>a</span>
  <span m=''522710''>little</span> <span m=''522929''>bit,</span> <span m=''523450''>then</span>
  <span m=''523900''>they</span> <span m=''524195''>should</span> <span m=''524490''>perform</span>
  <span m=''524780''>essentially</span> <span m=''525220''>the</span> <span m=''525350''>same</span>
  <span m=''525760''>function.</span> </p><p><span m=''528120''>AUDIENCE:</span> <span
  m=''528615''>[INAUDIBLE]</span> <span m=''529605''>mostly</span> <span m=''530100''>was</span>
  <span m=''530347''>the</span> <span m=''530595''>[INAUDIBLE]</span> <span m=''535545''>also</span>
  <span m=''536050''>some</span> <span m=''536310''>name</span> <span m=''536548''>differences</span>
  <span m=''536787''>where</span> <span m=''537025''>there</span> <span m=''537264''>really</span>
  <span m=''537359''>don''t</span> <span m=''537454''>need</span> <span m=''537550''>to</span>
  <span m=''537645''>be.</span> <span m=''538695''>For</span> <span m=''539172''>instance,</span>
  <span m=''540126''>if</span> <span m=''540285''>you</span> <span m=''540444''>try</span>
  <span m=''540603''>to</span> <span m=''540722''>do</span> <span m=''540841''>a</span>
  <span m=''540960''>shift</span> <span m=''542034''>on</span> <span m=''542511''>the</span>
  <span m=''542988''>PPU</span> <span m=''543465''>I</span> <span m=''543703''>believe</span>
  <span m=''543942''>it''s</span> <span m=''544419''>a</span> <span m=''545390''>[INAUDIBLE]</span>
  <span m=''547520''>SL,</span> <span m=''548405''>shift</span> <span m=''548680''>logical</span>
  <span m=''548990''>right,</span> <span m=''549450''>shift</span> <span m=''549750''>logical</span>
  <span m=''551500''>left</span> <span m=''551870''>or</span> <span m=''552270''>shift</span>
  <span m=''552610''>arithmetic</span> <span m=''553080''>right.</span> <span m=''553930''>Sort</span>
  <span m=''554100''>of</span> <span m=''554190''>things</span> <span m=''554370''>you</span>
  <span m=''554470''>would</span> <span m=''554820''>remember.</span> <span m=''555530''>On</span>
  <span m=''555850''>the</span> <span m=''559110''>SPU</span> <span m=''560440''>it''s</span>
  <span m=''561140''>the</span> <span m=''561310''>acronym</span> <span m=''561830''>for</span>
  <span m=''562710''>rotate</span> <span m=''563250''>and</span> <span m=''563490''>mask</span>
  <span m=''564240''>for</span> <span m=''564320''>shift.</span> <span m=''565900''>So</span>
  <span m=''567970''>R-O-T-M-A-R</span> <span m=''568920''>or</span> <span m=''569270''>something</span>
  <span m=''569480''>like</span> <span m=''569690''>that.</span> <span m=''572880''>So</span>
  <span m=''573670''>yes</span> <span m=''573840''>there''s</span> <span m=''574040''>some</span>
  <span m=''574090''>differences</span> <span m=''574480''>that</span> <span m=''574605''>don''t</span>
  <span m=''574730''>need</span> <span m=''574860''>to</span> <span m=''574990''>be</span>
  <span m=''575120''>there.</span> </p><p><span m=''584294''>PROFESSOR:</span> <span
  m=''584800''>OK</span> <span m=''584970''>so</span> <span m=''585200''>to</span>
  <span m=''585750''>actually</span> <span m=''586050''>create</span> <span m=''586380''>these</span>
  <span m=''586550''>vectors</span> <span m=''587010''>there''s</span> <span m=''587190''>a</span>
  <span m=''587240''>couple</span> <span m=''587540''>of</span> <span m=''587640''>different</span>
  <span m=''587940''>notations</span> <span m=''588390''>you</span> <span m=''588490''>can</span>
  <span m=''588590''>use.</span> <span m=''589540''>The</span> <span m=''589680''>first</span>
  <span m=''590050''>is,</span> <span m=''591280''>you</span> <span m=''591430''>can</span>
  <span m=''591520''>use</span> <span m=''591700''>this</span> <span m=''591850''>thing</span>
  <span m=''592050''>which</span> <span m=''592250''>looks</span> <span m=''592450''>like</span>
  <span m=''592700''>a</span> <span m=''593120''>cast</span> <span m=''593720''>to,</span>
  <span m=''593920''>for</span> <span m=''594060''>example,</span> <span m=''594440''>vector</span>
  <span m=''594760''>signed</span> <span m=''595060''>int.</span> <span m=''595800''>So</span>
  <span m=''595890''>you</span> <span m=''596070''>do</span> <span m=''596280''>vector</span>
  <span m=''596580''>signed</span> <span m=''596830''>int</span> <span m=''596990''>in</span>
  <span m=''597190''>parentheses</span> <span m=''598040''>and</span> <span m=''598370''>then</span>
  <span m=''598750''>a</span> <span m=''598840''>list</span> <span m=''599430''>of</span>
  <span m=''600450''>four</span> <span m=''601410''>integers</span> <span m=''601800''>you</span>
  <span m=''601910''>want</span> <span m=''602010''>to</span> <span m=''602060''>fill</span>
  <span m=''602270''>in.</span> <span m=''602770''>And</span> <span m=''602940''>that</span>
  <span m=''603080''>will</span> <span m=''604290''>create</span> <span m=''605100''>an</span>
  <span m=''605190''>integer</span> <span m=''605480''>vector</span> <span m=''605850''>and</span>
  <span m=''605940''>assign</span> <span m=''606240''>it</span> <span m=''606360''>to</span>
  <span m=''606690''>a.</span> </p><p><span m=''607950''>You</span> <span m=''608080''>can</span>
  <span m=''608210''>also,</span> <span m=''610400''>I</span> <span m=''610470''>believe</span>
  <span m=''610660''>you</span> <span m=''610750''>can</span> <span m=''610880''>also</span>
  <span m=''611060''>use</span> <span m=''611290''>that</span> <span m=''611440''>notation</span>
  <span m=''611910''>with</span> <span m=''612120''>just</span> <span m=''612700''>one</span>
  <span m=''613040''>integer</span> <span m=''613930''>and</span> <span m=''614170''>it</span>
  <span m=''614300''>will</span> <span m=''615110''>fill</span> <span m=''615360''>in</span>
  <span m=''615460''>that</span> <span m=''615620''>integer</span> <span m=''615980''>in</span>
  <span m=''616140''>all</span> <span m=''616370''>four</span> <span m=''616830''>positions.</span>
  <span m=''618770''>There''s</span> <span m=''618980''>also</span> <span m=''619210''>an</span>
  <span m=''619320''>SPU</span> <span m=''620570''>intrinsic</span> <span m=''621130''>called</span>
  <span m=''621430''>splats</span> <span m=''621830''>that</span> <span m=''621950''>you</span>
  <span m=''622040''>can</span> <span m=''622150''>use</span> <span m=''622470''>to</span>
  <span m=''622670''>basically</span> <span m=''623120''>copy</span> <span m=''623470''>the</span>
  <span m=''623570''>same</span> <span m=''623860''>integer</span> <span m=''624250''>to</span>
  <span m=''624820''>all</span> <span m=''625030''>four</span> <span m=''625220''>components.</span>
  </p><p><span m=''626327''>AUDIENCE:</span> <span m=''626814''>How</span> <span m=''626911''>does</span>
  <span m=''627008''>it</span> <span m=''627106''>know</span> <span m=''627203''>you''re</span>
  <span m=''627301''>not</span> <span m=''627788''>using</span> <span m=''628031''>a</span>
  <span m=''628275''>comma</span> <span m=''628518''>operator?</span> </p><p><span
  m=''633145''>PROFESSOR:</span> <span m=''633640''>Yeah</span> <span m=''634100''>I</span>
  <span m=''634560''>don''t--</span> <span m=''635780''>is</span> <span m=''635890''>that</span>
  <span m=''636020''>right</span> <span m=''636190''>David,</span> <span m=''636370''>with</span>
  <span m=''636520''>the</span> <span m=''636670''>parentheses</span> <span m=''637370''>in</span>
  <span m=''637450''>the</span> <span m=''637600''>second</span> <span m=''637860''>part?</span>
  <span m=''638090''>OK.</span> </p><p><span m=''639778''>AUDIENCE:</span> <span m=''640254''>Whatever.</span>
  </p><p><span m=''642158''>AUDIENCE:</span> <span m=''642634''>Another</span> <span
  m=''643110''>caveat</span> <span m=''643348''>here</span> <span m=''643586''>from</span>
  <span m=''643824''>someone</span> <span m=''644062''>who''s</span> <span m=''644300''>been</span>
  <span m=''644538''>in</span> <span m=''644696''>the</span> <span m=''644855''>trenches</span>
  <span m=''645490''>is</span> <span m=''645970''>that</span> <span m=''646760''>XLC</span>
  <span m=''647430''>likes</span> <span m=''647740''>this</span> <span m=''647970''>notation.</span>
  <span m=''648520''>GCC</span> <span m=''649240''>sometimes</span> <span m=''649720''>likes</span>
  <span m=''650930''>curly</span> <span m=''651200''>brace</span> <span m=''652770''>notations</span>
  <span m=''653180''>instead.</span> </p><p><span m=''653875''>PROFESSOR:</span> <span
  m=''654150''>So</span> <span m=''654540''>I''d seen</span> <span m=''654690''>both</span>
  <span m=''654855''>of</span> <span m=''655020''>those</span> <span m=''655186''>and</span>
  <span m=''655434''>I do know which to do.</span> </p><p><span m=''655682''>[INTERPOSING
  VOICES]</span> </p><p><span m=''656178''>AUDIENCE:</span> <span m=''656674''>[INAUDIBLE].</span>
  </p><p><span m=''664610''>PROFESSOR:</span> <span m=''665120''>OK</span> <span m=''665750''>great</span>
  <span m=''666050''>thanks.</span> <span m=''670430''>All</span> <span m=''670540''>right.</span>
  </p><p><span m=''671810''>And</span> <span m=''672120''>after</span> <span m=''672330''>you''ve</span>
  <span m=''672570''>assigned</span> <span m=''672950''>some</span> <span m=''673090''>of</span>
  <span m=''673140''>these</span> <span m=''673280''>variables</span> <span m=''673670''>in</span>
  <span m=''673780''>order</span> <span m=''673970''>to</span> <span m=''674760''>get</span>
  <span m=''674910''>back</span> <span m=''675080''>the</span> <span m=''675160''>pieces</span>
  <span m=''675500''>out,</span> <span m=''676950''>one</span> <span m=''677100''>way</span>
  <span m=''677220''>you</span> <span m=''677300''>can</span> <span m=''677420''>do</span>
  <span m=''677560''>it</span> <span m=''677640''>is</span> <span m=''677840''>to</span>
  <span m=''678440''>use</span> <span m=''678720''>this</span> <span m=''679250''>union</span>
  <span m=''679820''>trick</span> <span m=''680800''>where</span> <span m=''681710''>you</span>
  <span m=''682120''>assign</span> <span m=''682890''>or</span> <span m=''683080''>rather</span>
  <span m=''683340''>you</span> <span m=''683740''>allocate</span> <span m=''684430''>something</span>
  <span m=''684730''>of</span> <span m=''684860''>vector</span> <span m=''685130''>signed</span>
  <span m=''685390''>int</span> <span m=''686100''>and</span> <span m=''686280''>then</span>
  <span m=''687590''>you</span> <span m=''687770''>tell</span> <span m=''689000''>C++</span>
  <span m=''689490''>that</span> <span m=''689590''>it</span> <span m=''689650''>can</span>
  <span m=''689920''>find</span> <span m=''690550''>an</span> <span m=''690710''>array</span>
  <span m=''690940''>of</span> <span m=''691010''>integers</span> <span m=''691450''>in</span>
  <span m=''691530''>the</span> <span m=''691600''>same</span> <span m=''691850''>place.</span>
  <span m=''692420''>And</span> <span m=''692620''>what</span> <span m=''692760''>that</span>
  <span m=''692890''>will</span> <span m=''693010''>do</span> <span m=''693230''>is</span>
  <span m=''693410''>pull</span> <span m=''693730''>out</span> <span m=''693850''>the</span>
  <span m=''693930''>components.</span> </p><p><span m=''697410''>So</span> <span
  m=''697770''>if</span> <span m=''697990''>you</span> <span m=''698270''>define</span>
  <span m=''698690''>this</span> <span m=''698960''>union</span> <span m=''699390''>this</span>
  <span m=''699550''>way,</span> <span m=''699800''>then</span> <span m=''699820''>you</span>
  <span m=''699910''>get</span> <span m=''700030''>a</span> <span m=''700080''>type</span>
  <span m=''700310''>called</span> <span m=''700570''>intVec.</span> <span m=''701660''>And</span>
  <span m=''703040''>any</span> <span m=''703190''>time</span> <span m=''703360''>you</span>
  <span m=''703450''>have</span> <span m=''703660''>an</span> <span m=''703780''>intVec</span>
  <span m=''704600''>you</span> <span m=''704730''>can</span> <span m=''704860''>either</span>
  <span m=''705060''>do</span> <span m=''705300''>dot</span> <span m=''706160''>Vec</span>
  <span m=''706490''>to</span> <span m=''706580''>get</span> <span m=''706750''>at</span>
  <span m=''706910''>the</span> <span m=''707210''>vector</span> <span m=''707570''>signed</span>
  <span m=''707870''>int,</span> <span m=''708360''>the</span> <span m=''709680''>vector</span>
  <span m=''709940''>data</span> <span m=''710160''>type.</span> <span m=''710680''>Or</span>
  <span m=''711010''>you</span> <span m=''711120''>can</span> <span m=''711240''>use</span>
  <span m=''711610''>dot</span> <span m=''711840''>vals</span> <span m=''712480''>to--</span>
  <span m=''714010''>with</span> <span m=''714310''>an</span> <span m=''714530''>array</span>
  <span m=''714925''>index</span> <span m=''715122''>get</span> <span m=''715320''>at</span>
  <span m=''715450''>the</span> <span m=''715840''>components</span> <span m=''717460''>of</span>
  <span m=''717500''>the</span> <span m=''718000''>vector.</span> <span m=''719730''>And</span>
  <span m=''719840''>you</span> <span m=''719910''>could</span> <span m=''720020''>also</span>
  <span m=''720190''>use</span> <span m=''720390''>this</span> <span m=''720730''>intrinsic</span>
  <span m=''721150''>call</span> <span m=''721390''>SPU</span> <span m=''721790''>extract</span>
  <span m=''724210''>to</span> <span m=''724370''>pick</span> <span m=''724560''>out</span>
  <span m=''724870''>the</span> <span m=''725210''>same</span> <span m=''725460''>components.</span>
  </p><p><span m=''731290''>XLC</span> <span m=''731690''>provides</span> <span m=''732260''>a</span>
  <span m=''732350''>bunch</span> <span m=''732640''>of</span> <span m=''732750''>different</span>
  <span m=''733020''>vector</span> <span m=''733310''>operations</span> <span m=''733920''>that</span>
  <span m=''734500''>you</span> <span m=''734590''>can</span> <span m=''734700''>use.</span>
  <span m=''735330''>There''s</span> <span m=''735720''>integer</span> <span m=''736090''>operations,</span>
  <span m=''736810''>floating</span> <span m=''737160''>point</span> <span m=''737380''>operations,</span>
  <span m=''738590''>there</span> <span m=''738840''>are</span> <span m=''739940''>a</span>
  <span m=''739980''>permutation</span> <span m=''740600''>and</span> <span m=''740700''>formatting</span>
  <span m=''741880''>operations</span> <span m=''742450''>which</span> <span m=''742610''>you</span>
  <span m=''742690''>can</span> <span m=''742760''>use</span> <span m=''743020''>to</span>
  <span m=''743530''>shuffle</span> <span m=''743860''>data</span> <span m=''744050''>around</span>
  <span m=''744450''>inside</span> <span m=''745120''>vector.</span> <span m=''746240''>And</span>
  <span m=''746640''>there''s</span> <span m=''746810''>also</span> <span m=''747140''>load</span>
  <span m=''747410''>and</span> <span m=''747510''>store</span> <span m=''747790''>instructions.</span>
  <span m=''749510''>And</span> <span m=''749680''>I</span> <span m=''749710''>believe</span>
  <span m=''749990''>we</span> <span m=''750080''>have</span> <span m=''750220''>a</span>
  <span m=''750280''>reference</span> <span m=''750870''>linked</span> <span m=''751380''>off</span>
  <span m=''751600''>the</span> <span m=''752610''>course</span> <span m=''752830''>website</span>
  <span m=''753200''>if</span> <span m=''755700''>you</span> <span m=''755790''>want</span>
  <span m=''755890''>to</span> <span m=''755930''>figure</span> <span m=''756180''>out</span>
  <span m=''756240''>more</span> <span m=''756410''>about</span> <span m=''756590''>these.</span>
  <span m=''757000''>I''m</span> <span m=''757200''>only</span> <span m=''757320''>going</span>
  <span m=''757420''>to</span> <span m=''758000''>touch</span> <span m=''758230''>on</span>
  <span m=''758390''>a</span> <span m=''758440''>few</span> <span m=''758620''>of</span>
  <span m=''758710''>them.</span> </p><p><span m=''761310''>OK</span> <span m=''761480''>so</span>
  <span m=''763060''>the</span> <span m=''763330''>arithmetic</span> <span m=''763970''>and</span>
  <span m=''764830''>logical</span> <span m=''765210''>operations</span> <span m=''767010''>like</span>
  <span m=''767210''>I</span> <span m=''767250''>said,</span> <span m=''767610''>most</span>
  <span m=''767730''>of</span> <span m=''767790''>these</span> <span m=''767990''>are</span>
  <span m=''768050''>the</span> <span m=''768140''>same</span> <span m=''768380''>between</span>
  <span m=''768740''>the</span> <span m=''768820''>PPU</span> <span m=''769320''>and</span>
  <span m=''769410''>the</span> <span m=''769510''>SPU.</span> <span m=''770290''>There''s</span>
  <span m=''770520''>some</span> <span m=''770830''>that</span> <span m=''770950''>are</span>
  <span m=''771160''>named</span> <span m=''771510''>slightly</span> <span m=''771870''>differently</span>
  <span m=''775510''>and</span> <span m=''776110''>some</span> <span m=''776320''>that</span>
  <span m=''776440''>are</span> <span m=''776560''>not</span> <span m=''776760''>available</span>
  <span m=''777130''>on</span> <span m=''777240''>the</span> <span m=''777310''>PPU.</span>
  <span m=''778280''>So</span> <span m=''778480''>these</span> <span m=''778660''>are</span>
  <span m=''778720''>all</span> <span m=''778880''>things</span> <span m=''779100''>you</span>
  <span m=''779220''>would</span> <span m=''779310''>expect,</span> <span m=''780070''>add,</span>
  <span m=''780430''>subtract.</span> </p><p><span m=''781540''>Madd</span> <span
  m=''781820''>is</span> <span m=''782120''>multiply</span> <span m=''782720''>and</span>
  <span m=''782840''>then</span> <span m=''783020''>add</span> <span m=''783450''>with</span>
  <span m=''784010''>three--</span> <span m=''785090''>with</span> <span m=''785470''>three</span>
  <span m=''785720''>arguments.</span> <span m=''787280''>Multiply,</span> <span m=''788850''>re</span>
  <span m=''789090''>is</span> <span m=''789350''>for</span> <span m=''789540''>reciprocal.</span>
  <span m=''791000''>You</span> <span m=''791170''>can</span> <span m=''791260''>also</span>
  <span m=''791450''>do</span> <span m=''792090''>bit-wise</span> <span m=''792660''>and,</span>
  <span m=''792970''>or</span> <span m=''793620''>xor</span> <span m=''794460''>and</span>
  <span m=''794710''>I</span> <span m=''794730''>believe</span> <span m=''794960''>there</span>
  <span m=''795080''>are</span> <span m=''795110''>other</span> <span m=''795300''>logical</span>
  <span m=''795660''>operations</span> <span m=''796140''>there</span> <span m=''796310''>too.</span>
  </p><p><span m=''797940''>Now</span> <span m=''798110''>the</span> <span m=''798200''>thing</span>
  <span m=''798370''>is</span> <span m=''798570''>you</span> <span m=''798670''>have</span>
  <span m=''798800''>to</span> <span m=''798900''>worry</span> <span m=''799110''>about</span>
  <span m=''799620''>which</span> <span m=''800200''>PPU</span> <span m=''800700''>or</span>
  <span m=''800890''>SPU</span> <span m=''801220''>instruction</span> <span m=''801640''>you''re</span>
  <span m=''801750''>using.</span> <span m=''802540''>But</span> <span m=''802560''>you</span>
  <span m=''802770''>usually</span> <span m=''803100''>don''t</span> <span m=''803260''>have</span>
  <span m=''803400''>to</span> <span m=''803500''>worry</span> <span m=''803740''>about</span>
  <span m=''805800''>selecting</span> <span m=''806370''>the</span> <span m=''808350''>right</span>
  <span m=''808540''>vector</span> <span m=''808820''>type.</span> <span m=''810370''>The</span>
  <span m=''810550''>compiler</span> <span m=''810930''>should</span> <span m=''811090''>figure</span>
  <span m=''811360''>out</span> <span m=''811640''>which</span> <span m=''811940''>vector</span>
  <span m=''812200''>types</span> <span m=''812450''>you''re</span> <span m=''812590''>using</span>
  <span m=''813180''>and</span> <span m=''814480''>substitute</span> <span m=''814960''>the</span>
  <span m=''815060''>appropriate</span> <span m=''815780''>assembly</span> <span m=''816200''>instruction</span>
  <span m=''816590''>that</span> <span m=''816740''>produces</span> <span m=''817380''>a</span>
  <span m=''817470''>result</span> <span m=''817860''>of</span> <span m=''818260''>the</span>
  <span m=''818400''>same</span> <span m=''819100''>vector</span> <span m=''819370''>type.</span>
  <span m=''820590''>So</span> <span m=''821365''>all</span> <span m=''821800''>these</span>
  <span m=''821980''>operations</span> <span m=''822510''>are</span> <span m=''822760''>what</span>
  <span m=''822890''>we</span> <span m=''822980''>call</span> <span m=''823180''>generic.</span>
  <span m=''823960''>And</span> <span m=''824320''>they</span> <span m=''826070''>stand</span>
  <span m=''826370''>in</span> <span m=''826540''>for</span> <span m=''826790''>all</span>
  <span m=''827010''>the</span> <span m=''827140''>specific</span> <span m=''827590''>instructions,</span>
  <span m=''828210''>which</span> <span m=''828340''>are--</span> <span m=''829830''>which</span>
  <span m=''830010''>only</span> <span m=''830180''>apply</span> <span m=''830420''>to</span>
  <span m=''830520''>a</span> <span m=''830570''>single</span> <span m=''830970''>vector</span>
  <span m=''831240''>type.</span> <span m=''831900''>Does</span> <span m=''831950''>that</span>
  <span m=''832000''>make</span> <span m=''832120''>sense?</span> </p><p><span m=''836830''>OK</span>
  <span m=''837150''>so</span> <span m=''837400''>one</span> <span m=''837610''>handy</span>
  <span m=''837880''>thing</span> <span m=''838130''>is</span> <span m=''838990''>a</span>
  <span m=''839140''>permutation</span> <span m=''839700''>operation.</span> <span
  m=''840680''>And</span> <span m=''840900''>this</span> <span m=''841030''>allows</span>
  <span m=''841300''>you</span> <span m=''841460''>to</span> <span m=''841760''>rearrange</span>
  <span m=''842640''>the</span> <span m=''842910''>bytes</span> <span m=''843220''>inside</span>
  <span m=''843560''>a</span> <span m=''843600''>vector</span> <span m=''844070''>or</span>
  <span m=''844180''>two</span> <span m=''844340''>vectors</span> <span m=''844760''>arbitrarily.</span>
  <span m=''846250''>And</span> <span m=''846420''>so</span> <span m=''846530''>the</span>
  <span m=''846630''>syntax</span> <span m=''846990''>is</span> <span m=''847170''>SPU</span>
  <span m=''847680''>shuffle</span> <span m=''848930''>a, b</span> <span m=''849450''>which</span>
  <span m=''849620''>are</span> <span m=''849690''>your</span> <span m=''849840''>source</span>
  <span m=''850200''>vectors</span> <span m=''851100''>and</span> <span m=''851510''>pattern</span>
  <span m=''852020''>which</span> <span m=''852130''>tells</span> <span m=''852420''>you</span>
  <span m=''852610''>how</span> <span m=''852780''>to</span> <span m=''852930''>shuffle</span>
  <span m=''853260''>them.</span> <span m=''854100''>And</span> <span m=''854290''>pattern</span>
  <span m=''854600''>is</span> <span m=''854690''>going</span> <span m=''854800''>to</span>
  <span m=''854840''>be</span> <span m=''854970''>interpreted</span> <span m=''855610''>as</span>
  <span m=''856450''>a</span> <span m=''857590''>vector</span> <span m=''857930''>of</span>
  <span m=''858320''>16-bytes.</span> </p><p><span m=''861040''>And</span> <span m=''861260''>each</span>
  <span m=''861560''>byte</span> <span m=''861820''>is</span> <span m=''861940''>going</span>
  <span m=''862050''>to</span> <span m=''862120''>tell</span> <span m=''862390''>you--</span>
  <span m=''862970''>each</span> <span m=''863170''>byte</span> <span m=''863330''>is</span>
  <span m=''863430''>going</span> <span m=''863520''>to</span> <span m=''863580''>tell</span>
  <span m=''863720''>the</span> <span m=''863780''>compiler</span> <span m=''864610''>how</span>
  <span m=''864770''>to</span> <span m=''864840''>pick</span> <span m=''865080''>out</span>
  <span m=''865260''>one</span> <span m=''865410''>of</span> <span m=''865470''>these</span>
  <span m=''865700''>bytes</span> <span m=''866280''>in</span> <span m=''866480''>the</span>
  <span m=''866610''>result.</span> <span m=''868560''>And</span> <span m=''869230''>how</span>
  <span m=''869440''>the</span> <span m=''869520''>byte</span> <span m=''869740''>is</span>
  <span m=''869830''>interpreted</span> <span m=''870430''>is</span> <span m=''871190''>the</span>
  <span m=''873690''>low,</span> <span m=''875510''>the</span> <span m=''875750''>low</span>
  <span m=''875980''>four</span> <span m=''876250''>bits</span> <span m=''876490''>are</span>
  <span m=''876570''>going</span> <span m=''876670''>to</span> <span m=''876740''>specify</span>
  <span m=''878470''>which</span> <span m=''878800''>position</span> <span m=''881330''>the</span>
  <span m=''881420''>source</span> <span m=''881730''>is</span> <span m=''881840''>going</span>
  <span m=''881940''>to</span> <span m=''881980''>come</span> <span m=''882190''>from.</span>
  </p><p><span m=''882790''>And</span> <span m=''883570''>the</span> <span m=''884690''>fourth</span>
  <span m=''885050''>byte</span> <span m=''885200''>is</span> <span m=''885320''>going</span>
  <span m=''885410''>to</span> <span m=''885470''>specify</span> <span m=''885910''>whether</span>
  <span m=''886120''>you''re</span> <span m=''886210''>going</span> <span m=''886290''>to</span>
  <span m=''886350''>pull</span> <span m=''886570''>from</span> <span m=''886830''>a</span>
  <span m=''887030''>or</span> <span m=''887170''>b.</span> <span m=''888080''>So</span>
  <span m=''888310''>as</span> <span m=''888450''>an</span> <span m=''888520''>example,</span>
  <span m=''890190''>here''s</span> <span m=''890540''>the</span> <span m=''890630''>pattern</span>
  <span m=''891090''>VC</span> <span m=''892050''>and</span> <span m=''892600''>if</span>
  <span m=''892740''>you</span> <span m=''892850''>look</span> <span m=''892980''>at</span>
  <span m=''893050''>the</span> <span m=''893150''>second</span> <span m=''893490''>byte</span>
  <span m=''893720''>which</span> <span m=''893920''>is</span> <span m=''894570''>one,</span>
  <span m=''895540''>which</span> <span m=''895720''>is</span> <span m=''895820''>one,</span>
  <span m=''896340''>four</span> <span m=''897930''>in</span> <span m=''898300''>hex.</span>
  <span m=''899240''>Then</span> <span m=''899460''>that</span> <span m=''899610''>means</span>
  <span m=''900010''>the</span> <span m=''901720''>destination</span> <span m=''902320''>register</span>
  <span m=''902750''>is</span> <span m=''902850''>going</span> <span m=''902950''>to</span>
  <span m=''903030''>contain</span> <span m=''903780''>the</span> <span m=''904030''>fourth</span>
  <span m=''904800''>byte</span> <span m=''905780''>or</span> <span m=''906430''>the</span>
  <span m=''906600''>fourth</span> <span m=''906880''>byte</span> <span m=''907120''>of</span>
  <span m=''907840''>b,</span> <span m=''908140''>all</span> <span m=''908600''>right.</span>
  </p><p><span m=''909160''>So</span> <span m=''909210''>four</span> <span m=''909500''>means</span>
  <span m=''910200''>select</span> <span m=''910550''>the</span> <span m=''910790''>element</span>
  <span m=''911160''>numbered</span> <span m=''911420''>four</span> <span m=''911770''>and</span>
  <span m=''911930''>one</span> <span m=''912160''>means</span> <span m=''913190''>select</span>
  <span m=''913530''>from</span> <span m=''913660''>b.</span> <span m=''914046''>Does</span>
  <span m=''914432''>that</span> <span m=''914820''>make</span> <span m=''914950''>sense?</span>
  <span m=''915520''>And</span> <span m=''915620''>this</span> <span m=''915730''>is</span>
  <span m=''915880''>very</span> <span m=''916110''>versatile</span> <span m=''916730''>by</span>
  <span m=''917260''>putting</span> <span m=''917510''>in</span> <span m=''917600''>the</span>
  <span m=''917710''>right,</span> <span m=''919140''>by</span> <span m=''919310''>putting</span>
  <span m=''919510''>in</span> <span m=''919580''>the</span> <span m=''919650''>right</span>
  <span m=''920000''>pattern</span> <span m=''920310''>vector</span> <span m=''920930''>you</span>
  <span m=''921050''>can</span> <span m=''921800''>arrange</span> <span m=''922200''>for</span>
  <span m=''922460''>all</span> <span m=''922650''>these</span> <span m=''922890''>bytes</span>
  <span m=''923140''>to</span> <span m=''923210''>be</span> <span m=''923300''>shuffled</span>
  <span m=''923640''>around</span> <span m=''923880''>however</span> <span m=''924170''>you</span>
  <span m=''924280''>want.</span> </p><p><span m=''925977''>AUDIENCE:</span> <span
  m=''926476''>The</span> <span m=''926575''>pattern</span> <span m=''926675''>is</span>
  <span m=''926775''>a</span> <span m=''926875''>constant</span> <span m=''926975''>[INAUDIBLE].</span>
  </p><p><span m=''927474''>PROFESSOR:</span> <span m=''927973''>Pardon?</span> </p><p><span
  m=''928472''>AUDIENCE: The</span> <span m=''928971''>pattern</span> <span m=''929220''>is</span>
  <span m=''929282''>a</span> <span m=''929345''>constant</span> <span m=''929407''>in</span>
  <span m=''929470''>intermediate</span> <span m=''929969''>parameter.</span> </p><p><span
  m=''934715''>PROFESSOR:</span> <span m=''934970''>You</span> <span m=''935040''>can</span>
  <span m=''935170''>fill</span> <span m=''935390''>in</span> <span m=''935480''>the</span>
  <span m=''935590''>parameter</span> <span m=''936150''>at</span> <span m=''936300''>run</span>
  <span m=''936520''>time</span> <span m=''937320''>if</span> <span m=''937850''>that''s</span>
  <span m=''937990''>what</span> <span m=''938100''>you''re</span> <span m=''938340''>asking.</span>
  </p><p><span m=''939302''>AUDIENCE:</span> <span m=''939783''>[INAUDIBLE]</span>
  </p><p><span m=''941707''>AUDIENCE:</span> <span m=''942188''>[INAUDIBLE]</span>
  </p><p><span m=''950365''>PROFESSOR:</span> <span m=''950870''>OK,</span> <span
  m=''952320''>also</span> <span m=''952590''>useful</span> <span m=''953010''>are</span>
  <span m=''953140''>these</span> <span m=''953370''>rotation</span> <span m=''953800''>operations</span>
  <span m=''954920''>which</span> <span m=''955100''>will</span> <span m=''955250''>let</span>
  <span m=''955390''>you</span> <span m=''956570''>shift</span> <span m=''956860''>your</span>
  <span m=''956960''>vector</span> <span m=''957300''>left</span> <span m=''957490''>or</span>
  <span m=''957600''>right</span> <span m=''957860''>by</span> <span m=''958070''>some</span>
  <span m=''958290''>amount.</span> </p><p><span m=''962550''>Now</span> <span m=''963610''>one</span>
  <span m=''963790''>thing</span> <span m=''963990''>to</span> <span m=''964110''>be</span>
  <span m=''964230''>aware</span> <span m=''964470''>of</span> <span m=''964550''>is</span>
  <span m=''964670''>that</span> <span m=''965160''>on</span> <span m=''965350''>the</span>
  <span m=''965470''>SPU</span> <span m=''966120''>you</span> <span m=''966320''>only</span>
  <span m=''966570''>have</span> <span m=''966810''>these</span> <span m=''967090''>128-bit</span>
  <span m=''968200''>registers.</span> <span m=''969340''>So</span> <span m=''969390''>on</span>
  <span m=''969480''>the</span> <span m=''969540''>PPU</span> <span m=''970810''>you</span>
  <span m=''970960''>have</span> <span m=''971780''>different</span> <span m=''972050''>registers</span>
  <span m=''972660''>which</span> <span m=''972870''>are</span> <span m=''973510''>suitable</span>
  <span m=''973980''>for</span> <span m=''974330''>holding</span> <span m=''974610''>different</span>
  <span m=''974900''>types.</span> <span m=''975240''>For</span> <span m=''975340''>example,</span>
  <span m=''975660''>there''s</span> <span m=''976680''>word-sized</span> <span m=''977270''>registers</span>
  <span m=''977700''>for</span> <span m=''977820''>holding</span> <span m=''978860''>ints</span>
  <span m=''980010''>and</span> <span m=''980980''>PPU</span> <span m=''981290''>also</span>
  <span m=''981530''>has</span> <span m=''981710''>these</span> <span m=''981890''>128-bit</span>
  <span m=''982730''>registers.</span> <span m=''983230''>But</span> <span m=''983360''>the</span>
  <span m=''983470''>SPU</span> <span m=''983790''>has</span> <span m=''983990''>nothing</span>
  <span m=''984280''>else.</span> </p><p><span m=''985280''>So</span> <span m=''985380''>that</span>
  <span m=''985410''>means</span> <span m=''985830''>whenever</span> <span m=''986130''>you''re</span>
  <span m=''986280''>using</span> <span m=''988220''>scalar</span> <span m=''988610''>types</span>
  <span m=''988910''>on</span> <span m=''989050''>the</span> <span m=''989160''>SPU</span>
  <span m=''989940''>they''re</span> <span m=''990120''>all</span> <span m=''990330''>going</span>
  <span m=''990450''>to</span> <span m=''990500''>be</span> <span m=''990730''>using</span>
  <span m=''991120''>these</span> <span m=''991560''>large</span> <span m=''991930''>registers.</span>
  <span m=''992530''>No</span> <span m=''992620''>matter</span> <span m=''992860''>what</span>
  <span m=''993110''>the</span> <span m=''993340''>size</span> <span m=''993660''>of</span>
  <span m=''993730''>the</span> <span m=''993810''>scalar</span> <span m=''994200''>you''re</span>
  <span m=''994440''>using.</span> <span m=''996860''>And</span> <span m=''998900''>depending</span>
  <span m=''999240''>on</span> <span m=''999330''>the</span> <span m=''999390''>size</span>
  <span m=''999660''>of</span> <span m=''999710''>the</span> <span m=''999790''>scalar</span>
  <span m=''1000290''>you''re</span> <span m=''1000472''>using</span> <span m=''1001580''>it''s</span>
  <span m=''1001800''>going</span> <span m=''1001890''>to</span> <span m=''1001950''>go</span>
  <span m=''1002240''>in</span> <span m=''1002410''>a</span> <span m=''1002480''>particular</span>
  <span m=''1002940''>position</span> <span m=''1003450''>inside</span> <span m=''1003990''>this</span>
  <span m=''1005570''>wide</span> <span m=''1005800''>register.</span> <span m=''1006150''>It''s</span>
  <span m=''1006310''>called</span> <span m=''1006500''>a</span> <span m=''1007000''>quadword</span>
  <span m=''1007540''>register,</span> <span m=''1007960''>because</span> <span m=''1008210''>it''s</span>
  <span m=''1008790''>16-bytes.</span> </p><p><span m=''1012000''>Now</span> <span
  m=''1012120''>the</span> <span m=''1012210''>thing</span> <span m=''1012360''>to</span>
  <span m=''1012430''>watch</span> <span m=''1012650''>out</span> <span m=''1012810''>for</span>
  <span m=''1013030''>is</span> <span m=''1013140''>that</span> <span m=''1014410''>whenever</span>
  <span m=''1014710''>you</span> <span m=''1014900''>load</span> <span m=''1015190''>something</span>
  <span m=''1015500''>from</span> <span m=''1015670''>memory</span> <span m=''1016060''>into--</span>
  <span m=''1017030''>whenever</span> <span m=''1017290''>you</span> <span m=''1017360''>load</span>
  <span m=''1017750''>a</span> <span m=''1017910''>scalar</span> <span m=''1018250''>from</span>
  <span m=''1018390''>memory</span> <span m=''1018720''>into</span> <span m=''1018930''>one</span>
  <span m=''1019070''>of</span> <span m=''1019120''>these</span> <span m=''1019290''>registers,</span>
  <span m=''1021640''>there''s</span> <span m=''1021830''>going</span> <span m=''1021930''>to</span>
  <span m=''1021970''>have</span> <span m=''1022090''>to</span> <span m=''1022180''>be</span>
  <span m=''1022310''>a</span> <span m=''1022370''>little</span> <span m=''1022600''>extra</span>
  <span m=''1022960''>processing</span> <span m=''1023470''>done</span> <span m=''1023970''>in</span>
  <span m=''1024109''>order</span> <span m=''1024310''>to</span> <span m=''1024680''>shift--</span>
  <span m=''1026109''>in</span> <span m=''1026250''>order</span> <span m=''1026410''>to</span>
  <span m=''1026510''>possibly</span> <span m=''1026960''>shift</span> <span m=''1027450''>the</span>
  <span m=''1027619''>scalar</span> <span m=''1027990''>into</span> <span m=''1028160''>the</span>
  <span m=''1028260''>right</span> <span m=''1028520''>place</span> <span m=''1029240''>inside</span>
  <span m=''1029609''>this</span> <span m=''1029760''>register.</span> </p><p><span
  m=''1031950''>And</span> <span m=''1034270''>furthermore,</span> <span m=''1034630''>the</span>
  <span m=''1034720''>hardware</span> <span m=''1035089''>is</span> <span m=''1035180''>always</span>
  <span m=''1035450''>going</span> <span m=''1035680''>to</span> <span m=''1035869''>want</span>
  <span m=''1036089''>to</span> <span m=''1036160''>grab</span> <span m=''1036460''>one</span>
  <span m=''1036670''>of</span> <span m=''1036720''>these</span> <span m=''1036910''>quadwords</span>
  <span m=''1037490''>all</span> <span m=''1037750''>at</span> <span m=''1037819''>a</span>
  <span m=''1037869''>time.</span> <span m=''1038720''>So</span> <span m=''1039260''>loading</span>
  <span m=''1039560''>a</span> <span m=''1039619''>scalar</span> <span m=''1040030''>is</span>
  <span m=''1040140''>not</span> <span m=''1040319''>going</span> <span m=''1040420''>to</span>
  <span m=''1040460''>be</span> <span m=''1040630''>any</span> <span m=''1040900''>cheaper</span>
  <span m=''1041470''>than</span> <span m=''1041720''>loading</span> <span m=''1042220''>one</span>
  <span m=''1042359''>of</span> <span m=''1042420''>these</span> <span m=''1042609''>quadword</span>
  <span m=''1043060''>registers.</span> <span m=''1044260''>So</span> <span m=''1044630''>one</span>
  <span m=''1044859''>possible</span> <span m=''1045319''>you''re</span> <span m=''1045420''>going</span>
  <span m=''1045510''>to</span> <span m=''1045569''>want</span> <span m=''1045829''>to</span>
  <span m=''1046460''>load</span> <span m=''1046720''>an</span> <span m=''1046810''>entire</span>
  <span m=''1047180''>quadword</span> <span m=''1047970''>register</span> <span m=''1048369''>at</span>
  <span m=''1048420''>a</span> <span m=''1048480''>time.</span> <span m=''1049430''>And</span>
  <span m=''1049880''>if</span> <span m=''1049990''>you</span> <span m=''1050060''>just</span>
  <span m=''1050240''>need</span> <span m=''1050350''>a</span> <span m=''1050410''>part</span>
  <span m=''1050610''>of</span> <span m=''1050690''>it,</span> <span m=''1051870''>then</span>
  <span m=''1052250''>you</span> <span m=''1052350''>can</span> <span m=''1052450''>figure</span>
  <span m=''1052680''>that</span> <span m=''1052830''>out</span> <span m=''1052980''>later.</span>
  <span m=''1053600''>But</span> <span m=''1053730''>you</span> <span m=''1053800''>might</span>
  <span m=''1053940''>as</span> <span m=''1054030''>well</span> <span m=''1054190''>get</span>
  <span m=''1054320''>the</span> <span m=''1054390''>whole</span> <span m=''1054610''>thing.</span>
  </p><p><span m=''1056840''>Questions?</span> </p><p><span m=''1058708''>AUDIENCE:</span>
  <span m=''1059174''>So</span> <span m=''1060530''>when</span> <span m=''1060670''>you--</span>
  <span m=''1061290''>just</span> <span m=''1061650''>a</span> <span m=''1062050''>scalar</span>
  <span m=''1062320''>question.</span> <span m=''1063360''>So</span> <span m=''1063520''>when</span>
  <span m=''1063630''>you</span> <span m=''1063790''>load</span> <span m=''1064770''>a</span>
  <span m=''1064860''>scalar</span> <span m=''1065270''>value</span> <span m=''1065620''>that''s</span>
  <span m=''1065860''>not</span> <span m=''1066150''>aligned--</span> <span m=''1068580''>it''s</span>
  <span m=''1068760''>not</span> <span m=''1068950''>aligned</span> <span m=''1069360''>with</span>
  <span m=''1069545''>the</span> <span m=''1069730''>preferred</span> <span m=''1072110''>position</span>
  <span m=''1073210''>is</span> <span m=''1073380''>that--</span> <span m=''1073710''>is</span>
  <span m=''1073890''>there</span> <span m=''1074070''>overhead</span> <span m=''1074430''>associated</span>
  <span m=''1074660''>with</span> <span m=''1075086''>that?</span> </p><p><span m=''1075512''>PROFESSOR:</span>
  <span m=''1075940''>I''m</span> <span m=''1076110''>not</span> <span m=''1076270''>sure</span>
  <span m=''1076440''>how</span> <span m=''1076530''>much</span> <span m=''1076740''>overhead</span>
  <span m=''1077040''>is</span> <span m=''1077160''>associated</span> <span m=''1077710''>with</span>
  <span m=''1077850''>that.</span> <span m=''1079280''>Pardon?</span> <span m=''1079540''>Oh</span>
  <span m=''1079646''>do</span> <span m=''1079753''>you</span> <span m=''1079860''>know?</span>
  </p><p><span m=''1080230''>AUDIENCE:</span> <span m=''1080689''>Well,</span> <span
  m=''1080918''>unlike</span> <span m=''1081148''>scalar</span> <span m=''1081377''>it''s</span>
  <span m=''1081607''>[INAUDIBLE],</span> <span m=''1082066''>it</span> <span m=''1082219''>can</span>
  <span m=''1082372''>only</span> <span m=''1082984''>load</span> <span m=''1083443''>on</span>
  <span m=''1085530''>16-byte</span> <span m=''1085770''>boundaries.</span> <span
  m=''1087080''>So</span> <span m=''1087290''>it''s</span> <span m=''1087380''>going</span>
  <span m=''1087520''>to</span> <span m=''1088840''>load</span> <span m=''1089170''>the--</span>
  <span m=''1089620''>load</span> <span m=''1089940''>something</span> <span m=''1090240''>that</span>
  <span m=''1090400''>includes</span> <span m=''1090560''>that</span> <span m=''1090721''>and</span>
  <span m=''1091202''>that''s</span> <span m=''1091298''>going</span> <span m=''1091394''>to</span>
  <span m=''1091490''>have</span> <span m=''1091586''>to</span> <span m=''1091683''>shift</span>
  <span m=''1091843''>to</span> <span m=''1092003''>the</span> <span m=''1092164''>another</span>
  <span m=''1092645''>position.</span> </p><p><span m=''1095531''>PROFESSOR:</span>
  <span m=''1096020''>So</span> <span m=''1096190''>do</span> <span m=''1096370''>unaligned--</span>
  <span m=''1097400''>when</span> <span m=''1097640''>it</span> <span m=''1097690''>has</span>
  <span m=''1097870''>to</span> <span m=''1098060''>shift</span> <span m=''1098430''>the</span>
  <span m=''1098890''>scalar</span> <span m=''1099170''>around,</span> <span m=''1099500''>does</span>
  <span m=''1099710''>that</span> <span m=''1099890''>actually</span> <span m=''1100230''>take</span>
  <span m=''1100410''>longer</span> <span m=''1100690''>than</span> <span m=''1101750''>went</span>
  <span m=''1101950''>in--</span> <span m=''1102430''>when</span> <span m=''1102620''>it''s</span>
  <span m=''1103040''>natural?</span> </p><p><span m=''1104655''>AUDIENCE:</span>
  <span m=''1105070''>I</span> <span m=''1105190''>don''t</span> <span m=''1105380''>know</span>
  <span m=''1105620''>if</span> <span m=''1105770''>it''s--</span> <span m=''1106220''>well</span>
  <span m=''1106520''>what</span> <span m=''1106820''>you</span> <span m=''1107040''>can</span>
  <span m=''1107260''>do,</span> <span m=''1107730''>you</span> <span m=''1108590''>can</span>
  <span m=''1108680''>set</span> <span m=''1109100''>some</span> <span m=''1109295''>flags</span>
  <span m=''1109392''>in</span> <span m=''1109490''>XLC</span> <span m=''1110080''>that</span>
  <span m=''1110340''>say,</span> <span m=''1111340''>align</span> <span m=''1111740''>all</span>
  <span m=''1112040''>of</span> <span m=''1112133''>my</span> <span m=''1112226''>scalars</span>
  <span m=''1113350''>correctly.</span> <span m=''1114340''>And</span> <span m=''1115450''>we''ll</span>
  <span m=''1115680''>waste</span> <span m=''1116480''>4x</span> <span m=''1116830''>overhead.</span>
  <span m=''1117730''>It''ll</span> <span m=''1117940''>even</span> <span m=''1118050''>say</span>
  <span m=''1118250''>align</span> <span m=''1118640''>my</span> <span m=''1118940''>array,</span>
  <span m=''1119300''>have</span> <span m=''1119520''>my</span> <span m=''1119680''>elements</span>
  <span m=''1120820''>so</span> <span m=''1120980''>that</span> <span m=''1121300''>I</span>
  <span m=''1121410''>can</span> <span m=''1121520''>have</span> <span m=''1121630''>the</span>
  <span m=''1121685''>scalar</span> <span m=''1121740''>array</span> <span m=''1121865''>at</span>
  <span m=''1121990''>the</span> <span m=''1122250''>back--</span> <span m=''1122336''>I</span>
  <span m=''1122423''>can</span> <span m=''1122510''>load</span> <span m=''1123170''>and</span>
  <span m=''1123306''>it</span> <span m=''1123443''>will</span> <span m=''1123580''>waste</span>
  <span m=''1123810''>the</span> <span m=''1123915''>overhead''s</span> <span m=''1124020''>that</span>
  <span m=''1124140''>everything</span> <span m=''1124260''>in</span> <span m=''1124425''>the</span>
  <span m=''1124590''>array</span> <span m=''1124870''>is</span> <span m=''1125150''>[INAUDIBLE].</span>
  <span m=''1126760''>So</span> <span m=''1126960''>you</span> <span m=''1127400''>can</span>
  <span m=''1127710''>have</span> <span m=''1127840''>the</span> <span m=''1127920''>compiler</span>
  <span m=''1128790''>trade</span> <span m=''1128990''>off</span> <span m=''1129110''>space</span>
  <span m=''1129380''>versus</span> <span m=''1129630''>time</span> <span m=''1129920''>for</span>
  <span m=''1130156''>you</span> <span m=''1130393''>off</span> <span m=''1130550''>two</span>
  <span m=''1130708''>switches.</span> </p><p><span m=''1130866''>PROFESSOR:</span>
  <span m=''1131339''>I</span> <span m=''1131575''>see.</span> </p><p><span m=''1137490''>OK</span>
  <span m=''1138390''>so</span> <span m=''1138600''>we''re</span> <span m=''1138700''>going</span>
  <span m=''1138780''>to</span> <span m=''1138830''>want</span> <span m=''1139020''>to</span>
  <span m=''1139200''>look</span> <span m=''1139410''>at</span> <span m=''1139570''>the</span>
  <span m=''1139930''>sim</span> <span m=''1140230''>application</span> <span m=''1140820''>from</span>
  <span m=''1141220''>recitation</span> <span m=''1141720''>two.</span> <span m=''1142140''>And</span>
  <span m=''1142410''>we</span> <span m=''1142530''>want</span> <span m=''1142700''>to</span>
  <span m=''1142750''>adapt</span> <span m=''1143050''>that</span> <span m=''1143230''>to</span>
  <span m=''1143310''>make</span> <span m=''1143510''>use</span> <span m=''1143730''>of</span>
  <span m=''1143840''>SIMD</span> <span m=''1144360''>data</span> <span m=''1144610''>types</span>
  <span m=''1145040''>and</span> <span m=''1145550''>intrinsics.</span> <span m=''1148300''>So</span>
  <span m=''1148540''>what</span> <span m=''1148700''>we''ve</span> <span m=''1148860''>done</span>
  <span m=''1149120''>is,</span> <span m=''1149450''>remember</span> <span m=''1149810''>we</span>
  <span m=''1149920''>had</span> <span m=''1150120''>these</span> <span m=''1150630''>x,
  y, z</span> <span m=''1152380''>coordinates</span> <span m=''1152830''>that</span>
  <span m=''1152960''>we</span> <span m=''1153050''>were</span> <span m=''1153140''>manipulating.</span>
  <span m=''1154330''>What</span> <span m=''1154395''>we''re</span> <span m=''1154460''>going</span>
  <span m=''1154550''>to</span> <span m=''1154620''>do</span> <span m=''1154810''>is</span>
  <span m=''1154950''>we''re</span> <span m=''1155050''>going</span> <span m=''1155130''>to</span>
  <span m=''1155200''>pad</span> <span m=''1155500''>each</span> <span m=''1155750''>one.</span>
  <span m=''1156320''>It</span> <span m=''1156490''>was</span> <span m=''1156640''>three</span>
  <span m=''1156890''>words</span> <span m=''1157170''>before</span> <span m=''1157335''>and</span>
  <span m=''1157500''>we''re</span> <span m=''1157580''>going</span> <span m=''1157660''>to</span>
  <span m=''1157700''>pad</span> <span m=''1157930''>each</span> <span m=''1158120''>one</span>
  <span m=''1158380''>so</span> <span m=''1158490''>that</span> <span m=''1158640''>it</span>
  <span m=''1158710''>fills</span> <span m=''1158950''>a</span> <span m=''1159000''>quadword.</span>
  </p><p><span m=''1160510''>And</span> <span m=''1160870''>so</span> <span m=''1161000''>for</span>
  <span m=''1161130''>each</span> <span m=''1161320''>quadword</span> <span m=''1162400''>of</span>
  <span m=''1162520''>course</span> <span m=''1162910''>the</span> <span m=''1162980''>first</span>
  <span m=''1163210''>three</span> <span m=''1163400''>words</span> <span m=''1163670''>are</span>
  <span m=''1163740''>going</span> <span m=''1163830''>to</span> <span m=''1163890''>correspond</span>
  <span m=''1164590''>to</span> <span m=''1165230''>the</span> <span m=''1165330''>x,</span>
  <span m=''1165483''>y,</span> <span m=''1165636''>z</span> <span m=''1165790''>components.</span>
  <span m=''1166640''>And</span> <span m=''1166820''>we</span> <span m=''1166910''>can</span>
  <span m=''1167010''>grab</span> <span m=''1167260''>those</span> <span m=''1167440''>out</span>
  <span m=''1167600''>using</span> <span m=''1168580''>SPU</span> <span m=''1169340''>extract</span>
  <span m=''1169850''>or</span> <span m=''1170140''>some</span> <span m=''1170320''>other</span>
  <span m=''1170500''>intrinsics.</span> <span m=''1172670''>Now</span> <span m=''1173670''>when</span>
  <span m=''1173910''>we''re</span> <span m=''1174010''>doing</span> <span m=''1174200''>manipulations</span>
  <span m=''1174880''>with</span> <span m=''1175050''>these</span> <span m=''1176230''>components</span>
  <span m=''1176660''>for</span> <span m=''1176750''>example,</span> <span m=''1177350''>we</span>
  <span m=''1177450''>wanted</span> <span m=''1177630''>to</span> <span m=''1179130''>find</span>
  <span m=''1179370''>the</span> <span m=''1179440''>displacement</span> <span m=''1180000''>between</span>
  <span m=''1180790''>two</span> <span m=''1181260''>locations.</span> <span m=''1182150''>And</span>
  <span m=''1182270''>that''s</span> <span m=''1182460''>just</span> <span m=''1182650''>subtracting</span>
  <span m=''1183280''>two</span> <span m=''1183410''>of</span> <span m=''1183540''>these</span>
  <span m=''1183730''>coordinates.</span> </p><p><span m=''1184640''>So</span> <span
  m=''1184780''>we</span> <span m=''1184870''>can</span> <span m=''1184980''>do</span>
  <span m=''1185130''>that</span> <span m=''1185350''>subtraction</span> <span m=''1185910''>which</span>
  <span m=''1186520''>before</span> <span m=''1186880''>required</span> <span m=''1187300''>three</span>
  <span m=''1187970''>floating</span> <span m=''1188300''>point</span> <span m=''1189200''>subtractions.</span>
  <span m=''1190060''>We</span> <span m=''1190170''>can</span> <span m=''1190260''>replace</span>
  <span m=''1190600''>that</span> <span m=''1190760''>with</span> <span m=''1190880''>a</span>
  <span m=''1190930''>single</span> <span m=''1191340''>SIMD</span> <span m=''1191680''>instruction.</span>
  <span m=''1192645''>Does</span> <span m=''1193080''>that</span> <span m=''1193200''>make</span>
  <span m=''1193330''>sense?</span> <span m=''1196400''>OK</span> <span m=''1196750''>so</span>
  <span m=''1201080''>all</span> <span m=''1201360''>this--</span> <span m=''1201900''>most</span>
  <span m=''1202130''>of</span> <span m=''1202170''>this</span> <span m=''1202300''>has</span>
  <span m=''1202470''>already</span> <span m=''1202690''>been</span> <span m=''1202880''>done</span>
  <span m=''1203580''>and</span> <span m=''1205000''>we''re</span> <span m=''1205330''>providing</span>
  <span m=''1205720''>most</span> <span m=''1205940''>of</span> <span m=''1205990''>the</span>
  <span m=''1206070''>implementation</span> <span m=''1207200''>of</span> <span m=''1209440''>this</span>
  <span m=''1209600''>SIMD</span> <span m=''1209890''>version</span> <span m=''1210390''>of</span>
  <span m=''1210600''>sim.</span> </p><p><span m=''1211320''>And</span> <span m=''1211930''>what</span>
  <span m=''1212100''>we</span> <span m=''1212180''>want</span> <span m=''1212390''>you</span>
  <span m=''1212540''>to</span> <span m=''1212640''>do</span> <span m=''1212870''>is</span>
  <span m=''1213550''>download</span> <span m=''1214160''>this,</span> <span m=''1215140''>download</span>
  <span m=''1215440''>the</span> <span m=''1215510''>tarball</span> <span m=''1215870''>for</span>
  <span m=''1215970''>this</span> <span m=''1216120''>recitation</span> <span m=''1217150''>and</span>
  <span m=''1217470''>then</span> <span m=''1218220''>go</span> <span m=''1218410''>in</span>
  <span m=''1218490''>there</span> <span m=''1218700''>and</span> <span m=''1218820''>what</span>
  <span m=''1218920''>we</span> <span m=''1219000''>want</span> <span m=''1219115''>you</span>
  <span m=''1219230''>to</span> <span m=''1219310''>do</span> <span m=''1219490''>is</span>
  <span m=''1219660''>fill</span> <span m=''1219930''>in</span> <span m=''1220020''>one</span>
  <span m=''1220160''>of</span> <span m=''1220210''>the</span> <span m=''1220280''>blanks.</span>
  <span m=''1221650''>All</span> <span m=''1221710''>right.</span> <span m=''1222190''>So</span>
  <span m=''1222300''>there''s</span> <span m=''1222450''>just</span> <span m=''1222680''>one</span>
  <span m=''1222870''>function</span> <span m=''1223230''>here</span> <span m=''1223430''>that''s</span>
  <span m=''1223630''>been</span> <span m=''1223790''>left</span> <span m=''1224080''>unimplemented.</span>
  <span m=''1226910''>And</span> <span m=''1228650''>to</span> <span m=''1228890''>see</span>
  <span m=''1229030''>if</span> <span m=''1229110''>you</span> <span m=''1229200''>know</span>
  <span m=''1229320''>what''s</span> <span m=''1229450''>going</span> <span m=''1229610''>on,</span>
  <span m=''1230210''>see</span> <span m=''1230360''>if</span> <span m=''1230430''>you</span>
  <span m=''1230550''>can</span> <span m=''1230940''>fill</span> <span m=''1231130''>in</span>
  <span m=''1231250''>the</span> <span m=''1231320''>implementation</span> <span m=''1231900''>for</span>
  <span m=''1231990''>this.</span> <span m=''1233470''>Any</span> <span m=''1233580''>questions?</span>
  </p><p><span m=''1234120''>So</span> <span m=''1234180''>this</span> <span m=''1234340''>question--</span>
  <span m=''1234710''>this</span> <span m=''1235230''>function</span> <span m=''1235490''>you</span>
  <span m=''1235560''>want</span> <span m=''1235660''>to</span> <span m=''1235700''>implement</span>
  <span m=''1236080''>is</span> <span m=''1239120''>basically</span> <span m=''1239480''>going</span>
  <span m=''1239600''>to</span> <span m=''1239670''>take</span> <span m=''1240030''>a</span>
  <span m=''1240240''>vector</span> <span m=''1240550''>float</span> <span m=''1241390''>and</span>
  <span m=''1241780''>if</span> <span m=''1241880''>that</span> <span m=''1242090''>float</span>
  <span m=''1242330''>contains</span> <span m=''1244000''>a,</span> <span m=''1244098''>b,</span>
  <span m=''1244196''>c</span> <span m=''1244590''>and</span> <span m=''1244710''>d</span>
  <span m=''1245470''>you</span> <span m=''1245630''>want</span> <span m=''1245760''>to</span>
  <span m=''1245820''>return</span> <span m=''1246200''>a--</span> <span m=''1246600''>you</span>
  <span m=''1246680''>want</span> <span m=''1246780''>to</span> <span m=''1246820''>return</span>
  <span m=''1247130''>a</span> <span m=''1247150''>vector</span> <span m=''1247540''>which</span>
  <span m=''1248420''>each</span> <span m=''1248590''>of</span> <span m=''1248680''>whose</span>
  <span m=''1248980''>elements</span> <span m=''1249840''>is</span> <span m=''1250130''>a</span>
  <span m=''1250270''>plus</span> <span m=''1250500''>b</span> <span m=''1250640''>plus</span>
  <span m=''1250830''>c</span> <span m=''1250980''>plus</span> <span m=''1251200''>d.</span>
  <span m=''1252840''>Questions?</span> </p><p></p><p><span m=''1257200''>AUDIENCE:</span>
  <span m=''1257690''>What</span> <span m=''1258180''>directory</span> <span m=''1258343''>under</span>
  <span m=''1258506''>the--</span> </p><p><span m=''1260630''>AUDIENCE:</span> <span
  m=''1261120''>[INAUDIBLE].</span> </p><p><span m=''1263080''>PROFESSOR:</span> <span
  m=''1263570''>So</span> <span m=''1263710''>we''re</span> <span m=''1263780''>going</span>
  <span m=''1263880''>to</span> <span m=''1263930''>go</span> <span m=''1264110''>into</span>
  <span m=''1264560''>sim</span> <span m=''1264830''>a</span> <span m=''1265135''>list.</span>
  </p><p><span m=''1273200''>AUDIENCE:</span> <span m=''1273685''>But</span> <span
  m=''1274170''>we</span> <span m=''1274331''>can</span> <span m=''1274493''>stay</span>
  <span m=''1274655''>around</span> <span m=''1274897''>afterwards</span> <span m=''1275140''>and</span>
  <span m=''1275237''>help</span> <span m=''1275334''>you</span> <span m=''1275431''>figure</span>
  <span m=''1275528''>out</span> <span m=''1276110''>what''s</span> <span m=''1276271''>going</span>
  <span m=''1276433''>on.</span> </p><p><span m=''1278050''>PROFESSOR:</span> <span
  m=''1278560''>OK</span> <span m=''1278770''>so</span> <span m=''1278960''>here''s</span>
  <span m=''1280690''>one</span> <span m=''1280850''>implementation.</span> <span
  m=''1283950''>Basically</span> <span m=''1285770''>we''re</span> <span m=''1285900''>going</span>
  <span m=''1285990''>to</span> <span m=''1286060''>just</span> <span m=''1286250''>declare</span>
  <span m=''1286580''>another</span> <span m=''1287000''>vector</span> <span m=''1287290''>float</span>
  <span m=''1288220''>and</span> <span m=''1290130''>that</span> <span m=''1290310''>vector</span>
  <span m=''1290590''>float</span> <span m=''1290930''>we''re</span> <span m=''1291090''>going</span>
  <span m=''1291330''>to--</span> <span m=''1294430''>that''s</span> <span m=''1294610''>basically</span>
  <span m=''1294950''>we''re</span> <span m=''1295060''>just</span> <span m=''1295210''>going</span>
  <span m=''1295410''>to</span> <span m=''1298920''>do</span> <span m=''1299420''>these</span>
  <span m=''1299660''>swaps.</span> <span m=''1300560''>So</span> <span m=''1300760''>notice</span>
  <span m=''1301000''>in</span> <span m=''1301070''>this</span> <span m=''1301230''>one</span>
  <span m=''1301900''>we''re</span> <span m=''1302020''>swapping</span> <span m=''1302850''>the</span>
  <span m=''1302940''>first</span> <span m=''1303250''>and</span> <span m=''1303370''>second--</span>
  <span m=''1307040''>we''re</span> <span m=''1307200''>swapping</span> <span m=''1307350''>the</span>
  <span m=''1307590''>first</span> <span m=''1307890''>and</span> <span m=''1308030''>second</span>
  <span m=''1308570''>words.</span> </p><p><span m=''1309800''>So</span> <span m=''1309960''>that</span>
  <span m=''1310070''>means</span> <span m=''1310820''>down</span> <span m=''1311020''>here</span>
  <span m=''1311230''>we''re</span> <span m=''1311320''>going</span> <span m=''1311410''>to</span>
  <span m=''1311470''>want</span> <span m=''1311700''>to</span> <span m=''1312030''>carry</span>
  <span m=''1312980''>bits</span> <span m=''1313790''>four,</span> <span m=''1314090''>five,</span>
  <span m=''1314320''>six,</span> <span m=''1314550''>seven</span> <span m=''1315060''>and</span>
  <span m=''1315220''>then--</span> <span m=''1315500''>or</span> <span m=''1315750''>bytes</span>
  <span m=''1316050''>four,</span> <span m=''1316270''>five,</span> <span m=''1316470''>six,</span>
  <span m=''1316700''>seven</span> <span m=''1317030''>first</span> <span m=''1317440''>and</span>
  <span m=''1317560''>then</span> <span m=''1317730''>bytes</span> <span m=''1317920''>0,</span>
  <span m=''1318120''>1,</span> <span m=''1318310''>2,</span> <span m=''1318700''>3.</span>
  <span m=''1319920''>And</span> <span m=''1320110''>then</span> <span m=''1320250''>over</span>
  <span m=''1320400''>here</span> <span m=''1320560''>we</span> <span m=''1320640''>want</span>
  <span m=''1320890''>bytes</span> <span m=''1321255''>12,</span> <span m=''1321437''>13,</span>
  <span m=''1321620''>14,</span> <span m=''1322841''>15</span> <span m=''1323250''>and</span>
  <span m=''1323470''>then</span> <span m=''1323880''>8,</span> <span m=''1324003''>9,</span>
  <span m=''1324126''>10,</span> <span m=''1324620''>11.</span> <span m=''1325710''>Everyone</span>
  <span m=''1325950''>see</span> <span m=''1326040''>what''s</span> <span m=''1326180''>going</span>
  <span m=''1326340''>on</span> <span m=''1326460''>for</span> <span m=''1326540''>the</span>
  <span m=''1326630''>first</span> <span m=''1326930''>shuffle?</span> <span m=''1329930''>And</span>
  <span m=''1330050''>then</span> <span m=''1330160''>we''re</span> <span m=''1330260''>going</span>
  <span m=''1330350''>to</span> <span m=''1330420''>just</span> <span m=''1330620''>add</span>
  <span m=''1330820''>that</span> <span m=''1330980''>to</span> <span m=''1331080''>our</span>
  <span m=''1331260''>original</span> <span m=''1331620''>vector</span> <span m=''1332320''>to</span>
  <span m=''1332430''>get</span> <span m=''1332600''>this.</span> </p><p><span m=''1334420''>And</span>
  <span m=''1335260''>we</span> <span m=''1335360''>can</span> <span m=''1335440''>do</span>
  <span m=''1335530''>that</span> <span m=''1335670''>again,</span> <span m=''1337180''>this</span>
  <span m=''1337440''>time</span> <span m=''1337670''>now</span> <span m=''1337840''>we</span>
  <span m=''1337920''>just</span> <span m=''1338060''>want</span> <span m=''1338250''>to</span>
  <span m=''1338360''>swap</span> <span m=''1339550''>these</span> <span m=''1339800''>two</span>
  <span m=''1339900''>halves.</span> <span m=''1341700''>So</span> <span m=''1342580''>the</span>
  <span m=''1342680''>shuffle</span> <span m=''1342970''>pattern</span> <span m=''1343270''>is</span>
  <span m=''1343360''>going</span> <span m=''1343460''>to</span> <span m=''1343510''>be</span>
  <span m=''1343730''>8,</span> <span m=''1343932''>9,</span> <span m=''1344134''>10,</span>
  <span m=''1344336''>11,</span> <span m=''1344437''>12,</span> <span m=''1344538''>13,</span>
  <span m=''1344942''>14,</span> <span m=''1345144''>15</span> <span m=''1345750''>followed</span>
  <span m=''1346030''>by</span> <span m=''1346880''>0,</span> <span m=''1347277''>1,</span>
  <span m=''1347674''>2,</span> <span m=''1347872''>3,</span> <span m=''1347971''>4,</span>
  <span m=''1348004''>5,</span> <span m=''1348037''>6,</span> <span m=''1348071''>7.</span>
  </p><p><span m=''1352210''>Make</span> <span m=''1352415''>sense?</span> </p><p><span
  m=''1358750''>OK</span> <span m=''1360410''>so</span> <span m=''1360550''>the</span>
  <span m=''1360640''>way</span> <span m=''1360810''>we</span> <span m=''1361000''>translated</span>
  <span m=''1362436''>the</span> <span m=''1362810''>program</span> <span m=''1363090''>we</span>
  <span m=''1363180''>just</span> <span m=''1363370''>used</span> <span m=''1363610''>into</span>
  <span m=''1363930''>SIMD</span> <span m=''1364490''>was</span> <span m=''1365420''>we</span>
  <span m=''1365610''>used</span> <span m=''1366410''>a</span> <span m=''1367140''>struct</span>
  <span m=''1367395''>of</span> <span m=''1367650''>arrays.</span> <span m=''1368230''>Basically</span>
  <span m=''1368660''>each</span> <span m=''1368790''>of</span> <span m=''1368880''>these</span>
  <span m=''1369070''>structs</span> <span m=''1369400''>that</span> <span m=''1369510''>we</span>
  <span m=''1369610''>had</span> <span m=''1370180''>from</span> <span m=''1370380''>our</span>
  <span m=''1370610''>previous</span> <span m=''1370960''>implementation</span> <span
  m=''1371530''>just</span> <span m=''1371700''>carried</span> <span m=''1371970''>over</span>
  <span m=''1372470''>and</span> <span m=''1372630''>we</span> <span m=''1372710''>just</span>
  <span m=''1373100''>put</span> <span m=''1373240''>all</span> <span m=''1373460''>those</span>
  <span m=''1373630''>into</span> <span m=''1373860''>an</span> <span m=''1373920''>array.</span>
  <span m=''1374260''>So</span> <span m=''1374370''>the</span> <span m=''1374470''>structs</span>
  <span m=''1374840''>were</span> <span m=''1375310''>right</span> <span m=''1375440''>next</span>
  <span m=''1375630''>to</span> <span m=''1375700''>each</span> <span m=''1375810''>other.</span>
  </p><p><span m=''1377600''>Alternatively</span> <span m=''1378350''>we</span> <span
  m=''1378490''>could</span> <span m=''1378620''>have</span> <span m=''1378840''>laid</span>
  <span m=''1379090''>out</span> <span m=''1379310''>the,</span> <span m=''1380970''>laid</span>
  <span m=''1381200''>out</span> <span m=''1381310''>the</span> <span m=''1381370''>data</span>
  <span m=''1381590''>in</span> <span m=''1381720''>memory</span> <span m=''1382190''>in</span>
  <span m=''1382280''>a</span> <span m=''1382330''>different</span> <span m=''1382590''>way</span>
  <span m=''1383390''>and</span> <span m=''1383660''>this</span> <span m=''1383770''>is</span>
  <span m=''1383880''>called</span> <span m=''1384770''>an</span> <span m=''1384870''>array</span>
  <span m=''1385100''>of</span> <span m=''1385180''>structs</span> <span m=''1385580''>layout.</span>
  <span m=''1386630''>Instead</span> <span m=''1386940''>what</span> <span m=''1387060''>we</span>
  <span m=''1387160''>can</span> <span m=''1387270''>do</span> <span m=''1387450''>is</span>
  <span m=''1388410''>put</span> <span m=''1388580''>all</span> <span m=''1388790''>the</span>
  <span m=''1388880''>like</span> <span m=''1389130''>fields</span> <span m=''1389680''>next</span>
  <span m=''1389940''>to</span> <span m=''1390050''>each</span> <span m=''1390210''>other</span>
  <span m=''1390830''>so</span> <span m=''1391010''>that</span> <span m=''1391210''>we</span>
  <span m=''1391320''>have,</span> <span m=''1391790''>for</span> <span m=''1391800''>example,</span>
  <span m=''1392200''>an</span> <span m=''1392280''>array</span> <span m=''1392500''>of</span>
  <span m=''1392590''>all</span> <span m=''1392730''>the</span> <span m=''1392830''>x</span>
  <span m=''1393010''>components,</span> <span m=''1393520''>then</span> <span m=''1393740''>an</span>
  <span m=''1393850''>array</span> <span m=''1394010''>of</span> <span m=''1394090''>all</span>
  <span m=''1394190''>the</span> <span m=''1394260''>y</span> <span m=''1394440''>components,</span>
  <span m=''1395380''>then</span> <span m=''1395590''>an</span> <span m=''1395690''>array</span>
  <span m=''1395920''>of</span> <span m=''1396030''>all</span> <span m=''1396190''>the</span>
  <span m=''1396250''>z</span> <span m=''1396440''>components.</span> <span m=''1397930''>And</span>
  <span m=''1398520''>when</span> <span m=''1398670''>you</span> <span m=''1399320''>reorder</span>
  <span m=''1399960''>the</span> <span m=''1400080''>data</span> <span m=''1400330''>this</span>
  <span m=''1400510''>way</span> <span m=''1401610''>you</span> <span m=''1401760''>get</span>
  <span m=''1402270''>different</span> <span m=''1402570''>ways</span> <span m=''1402830''>you</span>
  <span m=''1402960''>can</span> <span m=''1403250''>use</span> <span m=''1403570''>to</span>
  <span m=''1403850''>process</span> <span m=''1404280''>it.</span> </p><p><span m=''1405980''>So</span>
  <span m=''1406170''>for</span> <span m=''1406290''>example,</span> <span m=''1407830''>now</span>
  <span m=''1408640''>each</span> <span m=''1408870''>quadword</span> <span m=''1409460''>instead</span>
  <span m=''1409770''>of</span> <span m=''1409850''>containing</span> <span m=''1410720''>the</span>
  <span m=''1410890''>data</span> <span m=''1411170''>for</span> <span m=''1411340''>a</span>
  <span m=''1411390''>single</span> <span m=''1411700''>point</span> <span m=''1411980''>is</span>
  <span m=''1412100''>going</span> <span m=''1412200''>to</span> <span m=''1412560''>contain</span>
  <span m=''1413610''>the</span> <span m=''1413730''>data</span> <span m=''1414000''>for</span>
  <span m=''1414390''>the</span> <span m=''1414530''>same</span> <span m=''1414790''>component</span>
  <span m=''1415380''>of</span> <span m=''1415530''>four</span> <span m=''1415790''>consecutive</span>
  <span m=''1416280''>points.</span> <span m=''1417260''>Everyone</span> <span m=''1417520''>see</span>
  <span m=''1417650''>that?</span> <span m=''1420640''>And</span> <span m=''1420770''>actually</span>
  <span m=''1421110''>we</span> <span m=''1421230''>can</span> <span m=''1421430''>implement</span>
  <span m=''1421890''>the</span> <span m=''1422610''>algorithm</span> <span m=''1423080''>from</span>
  <span m=''1423260''>before</span> <span m=''1425020''>in</span> <span m=''1425140''>this</span>
  <span m=''1425350''>new</span> <span m=''1425510''>layout.</span> </p><p><span m=''1426690''>But</span>
  <span m=''1427070''>we</span> <span m=''1427150''>have</span> <span m=''1427260''>to</span>
  <span m=''1427330''>be</span> <span m=''1427430''>a</span> <span m=''1427490''>little</span>
  <span m=''1427660''>bit</span> <span m=''1427780''>more</span> <span m=''1427960''>clever</span>
  <span m=''1428340''>in</span> <span m=''1428420''>how</span> <span m=''1428660''>we''re</span>
  <span m=''1429590''>putting</span> <span m=''1429850''>together</span> <span m=''1430100''>the</span>
  <span m=''1430200''>elements.</span> <span m=''1430880''>Before</span> <span m=''1431170''>we</span>
  <span m=''1431270''>were</span> <span m=''1431350''>able</span> <span m=''1431600''>to</span>
  <span m=''1431670''>just</span> <span m=''1432160''>subtract</span> <span m=''1433700''>each--</span>
  <span m=''1434170''>subtract</span> <span m=''1434850''>or</span> <span m=''1435060''>multiply</span>
  <span m=''1435510''>the</span> <span m=''1436050''>quadwords</span> <span m=''1436820''>with</span>
  <span m=''1437170''>each</span> <span m=''1437330''>other,</span> <span m=''1438000''>because</span>
  <span m=''1439020''>those</span> <span m=''1439290''>would</span> <span m=''1439400''>just</span>
  <span m=''1439560''>correspond</span> <span m=''1440120''>to</span> <span m=''1440350''>for</span>
  <span m=''1440460''>example,</span> <span m=''1441430''>subtracting</span> <span
  m=''1442550''>the</span> <span m=''1442750''>coordinates</span> <span m=''1443150''>of</span>
  <span m=''1443240''>two</span> <span m=''1443370''>points.</span> </p><p><span m=''1445540''>Now</span>
  <span m=''1445590''>this</span> <span m=''1445760''>time</span> <span m=''1445990''>we</span>
  <span m=''1446090''>have</span> <span m=''1446290''>to</span> <span m=''1447410''>do</span>
  <span m=''1447550''>some</span> <span m=''1447730''>additional</span> <span m=''1448150''>computation</span>
  <span m=''1448670''>in</span> <span m=''1448780''>order</span> <span m=''1449150''>to</span>
  <span m=''1449560''>put</span> <span m=''1449740''>all</span> <span m=''1449880''>the</span>
  <span m=''1449940''>pieces</span> <span m=''1450260''>together.</span> <span m=''1451630''>The</span>
  <span m=''1451720''>trick</span> <span m=''1452000''>behind</span> <span m=''1452390''>this</span>
  <span m=''1454340''>structure</span> <span m=''1454740''>of</span> <span m=''1454810''>arrays</span>
  <span m=''1455130''>implementation</span> <span m=''1455740''>which</span> <span
  m=''1455910''>I''ll</span> <span m=''1456090''>just</span> <span m=''1456450''>gloss</span>
  <span m=''1456720''>over</span> <span m=''1456970''>is,</span> <span m=''1459670''>if</span>
  <span m=''1459830''>we''re</span> <span m=''1459930''>storing</span> <span m=''1460270''>state</span>
  <span m=''1460570''>for</span> <span m=''1461070''>eight</span> <span m=''1461320''>objects</span>
  <span m=''1462320''>then</span> <span m=''1462560''>we''re</span> <span m=''1462660''>going</span>
  <span m=''1462830''>to</span> <span m=''1462870''>need--</span> <span m=''1464430''>eight</span>
  <span m=''1464650''>objects</span> <span m=''1465040''>hold</span> <span m=''1465340''>the--</span>
  <span m=''1467380''>hold</span> <span m=''1468477''>24.</span> <span m=''1470310''>Rather</span>
  <span m=''1471810''>for</span> <span m=''1471950''>each</span> <span m=''1472130''>object</span>
  <span m=''1472530''>we</span> <span m=''1472630''>need</span> <span m=''1472660''>the</span>
  <span m=''1472720''>position</span> <span m=''1473130''>and</span> <span m=''1473190''>the</span>
  <span m=''1473250''>velocity.</span> <span m=''1473850''>And</span> <span m=''1474180''>for</span>
  <span m=''1474330''>each</span> <span m=''1474460''>of</span> <span m=''1474510''>those</span>
  <span m=''1474690''>we</span> <span m=''1474790''>have</span> <span m=''1475030''>x,</span>
  <span m=''1475240''>y</span> <span m=''1475450''>and</span> <span m=''1475570''>z.</span>
  <span m=''1475860''>So</span> <span m=''1475980''>that</span> <span m=''1476090''>means</span>
  <span m=''1476440''>to</span> <span m=''1476560''>store</span> <span m=''1476810''>state</span>
  <span m=''1477070''>for</span> <span m=''1477180''>each</span> <span m=''1477410''>object,</span>
  <span m=''1477980''>for</span> <span m=''1478155''>eight</span> <span m=''1478330''>objects</span>
  <span m=''1478720''>we</span> <span m=''1478820''>need</span> <span m=''1479480''>8</span>
  <span m=''1479680''>times</span> <span m=''1480000''>6</span> <span m=''1480270''>is</span>
  <span m=''1480430''>48</span> <span m=''1481970''>words.</span> </p><p><span m=''1483570''>And</span>
  <span m=''1483720''>so</span> <span m=''1483840''>we</span> <span m=''1483940''>can</span>
  <span m=''1484030''>put</span> <span m=''1484200''>those</span> <span m=''1484450''>in</span>
  <span m=''1484720''>12</span> <span m=''1485090''>quadwords</span> <span m=''1485370''>if</span>
  <span m=''1485700''>we</span> <span m=''1485840''>pack</span> <span m=''1486080''>them</span>
  <span m=''1486200''>right.</span> <span m=''1488290''>And</span> <span m=''1489210''>when</span>
  <span m=''1489380''>we</span> <span m=''1489500''>do</span> <span m=''1489950''>SIMD</span>
  <span m=''1490360''>operations</span> <span m=''1490840''>on</span> <span m=''1490940''>these</span>
  <span m=''1491050''>quadwords</span> <span m=''1491540''>that</span> <span m=''1491650''>we</span>
  <span m=''1491770''>pull</span> <span m=''1492000''>out,</span> <span m=''1492770''>we</span>
  <span m=''1492920''>can</span> <span m=''1493080''>get</span> <span m=''1494380''>four</span>
  <span m=''1494980''>pair</span> <span m=''1495250''>interactions.</span> <span m=''1496220''>So</span>
  <span m=''1496380''>suppose</span> <span m=''1496750''>this</span> <span m=''1496870''>is</span>
  <span m=''1496990''>a</span> <span m=''1497050''>quadword</span> <span m=''1497590''>and</span>
  <span m=''1497710''>it''s</span> <span m=''1497890''>contained--</span> <span m=''1498290''>and</span>
  <span m=''1498450''>it</span> <span m=''1498510''>contains</span> <span m=''1499390''>data</span>
  <span m=''1499760''>corresponding</span> <span m=''1500420''>to</span> <span m=''1500850''>elements</span>
  <span m=''1501260''>a,</span> <span m=''1501353''>b,</span> <span m=''1501446''>c</span>
  <span m=''1501820''>and</span> <span m=''1501940''>d.</span> <span m=''1502550''>And</span>
  <span m=''1502680''>over</span> <span m=''1502840''>here</span> <span m=''1503040''>we</span>
  <span m=''1503150''>have</span> <span m=''1503310''>a</span> <span m=''1503350''>quadword</span>
  <span m=''1503760''>containing</span> <span m=''1504560''>data</span> <span m=''1504840''>corresponding</span>
  <span m=''1505140''>to</span> <span m=''1505440''>elements</span> <span m=''1505830''>one,</span>
  <span m=''1506090''>two,</span> <span m=''1506390''>three,</span> <span m=''1506640''>and</span>
  <span m=''1506660''>four.</span> </p><p><span m=''1508270''>With</span> <span m=''1508990''>some</span>
  <span m=''1509180''>SIMD</span> <span m=''1509490''>operations</span> <span m=''1510360''>we</span>
  <span m=''1510600''>can</span> <span m=''1510730''>kind</span> <span m=''1510910''>of</span>
  <span m=''1510990''>figure</span> <span m=''1511190''>out</span> <span m=''1511320''>the</span>
  <span m=''1511410''>pairwise</span> <span m=''1511840''>interaction</span> <span
  m=''1512840''>between</span> <span m=''1513170''>objects</span> <span m=''1513600''>a</span>
  <span m=''1513800''>and</span> <span m=''1513970''>one,</span> <span m=''1514550''>between</span>
  <span m=''1514830''>b</span> <span m=''1515010''>and</span> <span m=''1515190''>two,</span>
  <span m=''1515490''>c</span> <span m=''1515710''>and</span> <span m=''1515830''>three</span>
  <span m=''1516420''>and</span> <span m=''1516650''>d</span> <span m=''1516840''>and</span>
  <span m=''1516980''>four.</span> <span m=''1519210''>But</span> <span m=''1519320''>of</span>
  <span m=''1519390''>course</span> <span m=''1519630''>we</span> <span m=''1520920''>have</span>
  <span m=''1521020''>to</span> <span m=''1521110''>be</span> <span m=''1521230''>able</span>
  <span m=''1521400''>to</span> <span m=''1522610''>find</span> <span m=''1522820''>the</span>
  <span m=''1522890''>interactions</span> <span m=''1523340''>between</span> <span
  m=''1523890''>any</span> <span m=''1524120''>pair.</span> <span m=''1524400''>It''s</span>
  <span m=''1524500''>not</span> <span m=''1524650''>just</span> <span m=''1524830''>these</span>
  <span m=''1525010''>pairs</span> <span m=''1525300''>that</span> <span m=''1525450''>lineup.</span>
  <span m=''1526240''>So</span> <span m=''1526450''>what</span> <span m=''1526505''>we</span>
  <span m=''1526560''>have</span> <span m=''1526720''>to</span> <span m=''1526820''>do</span>
  <span m=''1527020''>is</span> <span m=''1527150''>rotate</span> <span m=''1528010''>the</span>
  <span m=''1528120''>quadword</span> <span m=''1529810''>over</span> <span m=''1530070''>by</span>
  <span m=''1530200''>one</span> <span m=''1530460''>word</span> <span m=''1531050''>and</span>
  <span m=''1531210''>then</span> <span m=''1531380''>do</span> <span m=''1531490''>the</span>
  <span m=''1531570''>same</span> <span m=''1531790''>thing</span> <span m=''1531920''>again.</span>
  <span m=''1532850''>We</span> <span m=''1532950''>do</span> <span m=''1533050''>that</span>
  <span m=''1533220''>four</span> <span m=''1533400''>times</span> <span m=''1533670''>in</span>
  <span m=''1533760''>all</span> <span m=''1533940''>and</span> <span m=''1534040''>then</span>
  <span m=''1534370''>we</span> <span m=''1534510''>add</span> <span m=''1534680''>up</span>
  <span m=''1534800''>the</span> <span m=''1534880''>results.</span> </p><p><span
  m=''1537320''>So</span> <span m=''1537420''>as</span> <span m=''1537510''>you</span>
  <span m=''1537600''>can</span> <span m=''1537700''>see</span> <span m=''1537860''>this</span>
  <span m=''1538340''>implementation</span> <span m=''1538650''>is</span> <span m=''1538960''>a</span>
  <span m=''1539020''>little</span> <span m=''1539160''>bit</span> <span m=''1539280''>more</span>
  <span m=''1539550''>involved</span> <span m=''1540380''>and</span> <span m=''1540820''>less--</span>
  <span m=''1542400''>it</span> <span m=''1542580''>maps</span> <span m=''1542870''>to</span>
  <span m=''1543000''>the</span> <span m=''1543290''>original</span> <span m=''1544340''>implementation</span>
  <span m=''1545150''>less</span> <span m=''1545420''>directly.</span> </p><p><span
  m=''1548490''>On</span> <span m=''1548630''>the</span> <span m=''1548760''>other</span>
  <span m=''1548880''>hand,</span> <span m=''1549740''>it</span> <span m=''1549750''>does</span>
  <span m=''1549930''>give</span> <span m=''1550090''>us</span> <span m=''1550190''>a</span>
  <span m=''1550260''>really</span> <span m=''1550500''>dramatic</span> <span m=''1550930''>speedup.</span>
  <span m=''1553240''>Because</span> <span m=''1553500''>we''re</span> <span m=''1553630''>using</span>
  <span m=''1554740''>more</span> <span m=''1555190''>of</span> <span m=''1555370''>the</span>
  <span m=''1556120''>vector</span> <span m=''1556460''>words.</span> <span m=''1558370''>Notice</span>
  <span m=''1558620''>that</span> <span m=''1558750''>in</span> <span m=''1559220''>the</span>
  <span m=''1559310''>first</span> <span m=''1559650''>packing</span> <span m=''1559980''>we</span>
  <span m=''1560280''>had.</span> <span m=''1560580''>We</span> <span m=''1560640''>had</span>
  <span m=''1560700''>x,</span> <span m=''1560915''>y</span> <span m=''1561130''>and</span>
  <span m=''1561210''>z</span> <span m=''1561440''>and</span> <span m=''1561540''>then</span>
  <span m=''1561650''>the</span> <span m=''1561720''>fourth</span> <span m=''1562030''>blank</span>
  <span m=''1562290''>was</span> <span m=''1562450''>unused.</span> <span m=''1564530''>Anyway,</span>
  <span m=''1564740''>this</span> <span m=''1564900''>time</span> <span m=''1566140''>the</span>
  <span m=''1566630''>structure</span> <span m=''1566980''>of</span> <span m=''1567040''>a</span>
  <span m=''1567110''>race</span> <span m=''1567320''>implementation</span> <span
  m=''1567990''>is</span> <span m=''1568110''>actually</span> <span m=''1568870''>7</span>
  <span m=''1569195''>1/2</span> <span m=''1569850''>times</span> <span m=''1570210''>faster</span>
  <span m=''1571130''>than</span> <span m=''1572240''>the</span> <span m=''1572520''>array</span>
  <span m=''1572750''>of</span> <span m=''1572830''>structures</span> <span m=''1573210''>implementation.</span>
  </p><p><span m=''1574990''>So</span> <span m=''1575850''>choosing</span> <span m=''1576180''>this</span>
  <span m=''1576330''>data</span> <span m=''1576540''>layout</span> <span m=''1576820''>correctly</span>
  <span m=''1577600''>can</span> <span m=''1577920''>actually</span> <span m=''1578260''>be</span>
  <span m=''1578810''>one</span> <span m=''1579000''>of</span> <span m=''1579080''>the</span>
  <span m=''1579770''>really</span> <span m=''1580040''>big</span> <span m=''1580220''>determinants</span>
  <span m=''1580740''>of</span> <span m=''1581140''>how</span> <span m=''1581350''>your</span>
  <span m=''1581480''>program</span> <span m=''1581780''>performs.</span> </p><p><span
  m=''1582350''>AUDIENCE:</span> <span m=''1582815''>The scalar</span> <span m=''1583280''>version</span>
  <span m=''1583745''>was</span> <span m=''1583900''>like</span> <span m=''1584055''>what</span>
  <span m=''1584210''>480,</span> <span m=''1585360''>something</span> <span m=''1585573''>like</span>
  <span m=''1585679''>that?</span> <span m=''1585786''>Or</span> <span m=''1586212''>is</span>
  <span m=''1586354''>it</span> <span m=''1586496''>not</span> <span m=''1586638''>comparable?</span>
  </p><p><span m=''1589204''>PROFESSOR:</span> <span m=''1589616''>I</span> <span
  m=''1590192''>let''s</span> <span m=''1590273''>see,</span> <span m=''1591540''>David,</span>
  <span m=''1591670''>do</span> <span m=''1591785''>you</span> <span m=''1591900''>remember?</span>
  </p><p><span m=''1592681''>AUDIENCE:</span> <span m=''1593132''>[INAUDIBLE]</span>
  </p><p><span m=''1595387''>PROFESSOR:</span> <span m=''1595840''>OK</span> <span
  m=''1596070''>so--</span> </p><p><span m=''1596830''>AUDIENCE:</span> <span m=''1597321''>[INAUDIBLE].</span>
  </p><p><span m=''1598794''>AUDIENCE:</span> <span m=''1599285''>No</span> <span
  m=''1599780''>that</span> <span m=''1599860''>was</span> <span m=''1600200''>just</span>
  <span m=''1600390''>on</span> <span m=''1600517''>the</span> <span m=''1600645''>PPU.</span>
  </p><p><span m=''1601290''>AUDIENCE:</span> <span m=''1601680''>[INAUDIBLE]</span>
  </p><p><span m=''1608484''>[INTERPOSING VOICES]</span> </p><p><span m=''1614210''>AUDIENCE:</span>
  <span m=''1614470''>[INAUDIBLE]</span> </p><p><span m=''1616970''>PROFESSOR:</span>
  <span m=''1617470''>OK,</span> <span m=''1617700''>so</span> <span m=''1617820''>something</span>
  <span m=''1618110''>like</span> <span m=''1618340''>400</span> <span m=''1618900''>for</span>
  <span m=''1619200''>the</span> <span m=''1620040''>double</span> <span m=''1620280''>buffered</span>
  <span m=''1620530''>one</span> <span m=''1620800''>and</span> <span m=''1620950''>300</span>
  <span m=''1621440''>for</span> <span m=''1622325''>array</span> <span m=''1622720''>of</span>
  <span m=''1623200''>structs.</span> </p><p><span m=''1627370''>OK</span> <span m=''1628000''>one</span>
  <span m=''1628210''>other</span> <span m=''1628390''>thing</span> <span m=''1628590''>to</span>
  <span m=''1628680''>worry</span> <span m=''1628850''>about</span> <span m=''1629170''>is</span>
  <span m=''1630540''>when</span> <span m=''1630770''>you''re</span> <span m=''1630950''>dealing</span>
  <span m=''1631270''>with</span> <span m=''1631420''>these--</span> <span m=''1632650''>when</span>
  <span m=''1632830''>you''re</span> <span m=''1633020''>dealing</span> <span m=''1633270''>with</span>
  <span m=''1633390''>these</span> <span m=''1633570''>SIMD</span> <span m=''1633770''>instructions,</span>
  <span m=''1634210''>you</span> <span m=''1634290''>want</span> <span m=''1634390''>to</span>
  <span m=''1634430''>make</span> <span m=''1634600''>sure</span> <span m=''1634800''>that</span>
  <span m=''1634990''>all</span> <span m=''1635220''>your</span> <span m=''1635350''>data</span>
  <span m=''1635690''>are</span> <span m=''1635950''>aligned</span> <span m=''1636280''>correctly</span>
  <span m=''1636670''>in</span> <span m=''1636770''>memory.</span> <span m=''1638100''>And</span>
  <span m=''1638480''>like</span> <span m=''1638660''>I</span> <span m=''1638710''>said</span>
  <span m=''1638880''>before,</span> <span m=''1639720''>when</span> <span m=''1639860''>you''re</span>
  <span m=''1639970''>pulling</span> <span m=''1640240''>things</span> <span m=''1640490''>in</span>
  <span m=''1640600''>from</span> <span m=''1640740''>memory</span> <span m=''1641490''>you</span>
  <span m=''1641610''>want</span> <span m=''1641700''>to</span> <span m=''1641740''>make</span>
  <span m=''1641890''>sure</span> <span m=''1642090''>that</span> <span m=''1642420''>whatever</span>
  <span m=''1642670''>you''re</span> <span m=''1642780''>pulling</span> <span m=''1643110''>in</span>
  <span m=''1643270''>is</span> <span m=''1643360''>going</span> <span m=''1643460''>to</span>
  <span m=''1643500''>be</span> <span m=''1643620''>aligned</span> <span m=''1644020''>on</span>
  <span m=''1644220''>a</span> <span m=''1644280''>quadword</span> <span m=''1644800''>boundary.</span>
  </p><p><span m=''1647270''>And</span> <span m=''1647540''>you</span> <span m=''1647640''>can</span>
  <span m=''1647740''>use</span> <span m=''1648020''>the</span> <span m=''1648230''>align</span>
  <span m=''1648950''>compiler</span> <span m=''1649010''>directive</span> <span m=''1649440''>to</span>
  <span m=''1650150''>tell</span> <span m=''1650320''>the</span> <span m=''1650400''>compiler,</span>
  <span m=''1651030''>I</span> <span m=''1651140''>want</span> <span m=''1651370''>this</span>
  <span m=''1651540''>piece</span> <span m=''1651740''>of</span> <span m=''1651820''>data</span>
  <span m=''1652110''>aligned</span> <span m=''1652800''>at</span> <span m=''1652920''>a</span>
  <span m=''1652970''>particular</span> <span m=''1653400''>place.</span> <span m=''1654350''>And</span>
  <span m=''1655280''>if</span> <span m=''1655400''>you</span> <span m=''1655520''>do</span>
  <span m=''1655650''>that</span> <span m=''1655810''>on</span> <span m=''1656060''>all</span>
  <span m=''1656330''>your</span> <span m=''1656950''>arrays</span> <span m=''1657270''>for</span>
  <span m=''1657390''>example,</span> <span m=''1657820''>and</span> <span m=''1657940''>make</span>
  <span m=''1658090''>sure</span> <span m=''1658230''>that</span> <span m=''1658390''>your</span>
  <span m=''1658640''>array--</span> <span m=''1659430''>the</span> <span m=''1659610''>array</span>
  <span m=''1659820''>elements</span> <span m=''1660170''>are</span> <span m=''1660240''>going</span>
  <span m=''1660340''>to</span> <span m=''1660400''>fit</span> <span m=''1660620''>neatly</span>
  <span m=''1661030''>into</span> <span m=''1662300''>quadwords</span> <span m=''1662920''>then</span>
  <span m=''1663270''>you</span> <span m=''1663640''>should</span> <span m=''1663800''>be</span>
  <span m=''1663950''>OK.</span> </p><p><span m=''1666330''>Again</span> <span m=''1667660''>like</span>
  <span m=''1667870''>I</span> <span m=''1667900''>said</span> <span m=''1668050''>before,</span>
  <span m=''1668690''>you</span> <span m=''1668860''>also</span> <span m=''1669050''>want</span>
  <span m=''1669190''>to</span> <span m=''1669260''>transfer</span> <span m=''1669770''>only</span>
  <span m=''1670110''>multiples</span> <span m=''1670680''>of</span> <span m=''1670760''>16-bytes</span>
  <span m=''1671550''>on</span> <span m=''1674430''>the</span> <span m=''1674630''>load</span>
  <span m=''1674860''>and</span> <span m=''1675000''>store.</span> <span m=''1677370''>And</span>
  <span m=''1677500''>so</span> <span m=''1677630''>when</span> <span m=''1678060''>you''re</span>
  <span m=''1678150''>doing</span> <span m=''1678330''>processing</span> <span m=''1679270''>it</span>
  <span m=''1679580''>may</span> <span m=''1679720''>help,</span> <span m=''1680060''>it</span>
  <span m=''1680130''>may</span> <span m=''1680250''>help</span> <span m=''1680450''>you</span>
  <span m=''1680580''>if</span> <span m=''1680660''>you</span> <span m=''1681210''>actually</span>
  <span m=''1681550''>pad</span> <span m=''1681840''>the</span> <span m=''1681960''>end</span>
  <span m=''1682090''>of</span> <span m=''1682170''>your--</span> <span m=''1683540''>pad</span>
  <span m=''1683760''>the</span> <span m=''1683870''>end</span> <span m=''1683990''>of</span>
  <span m=''1684060''>your</span> <span m=''1684340''>array''s</span> <span m=''1685190''>so</span>
  <span m=''1685310''>that</span> <span m=''1685450''>they</span> <span m=''1685540''>fill</span>
  <span m=''1685770''>out</span> <span m=''1685840''>a</span> <span m=''1685870''>multiple</span>
  <span m=''1686240''>of</span> <span m=''1686300''>16-bytes.</span> <span m=''1687410''>Because</span>
  <span m=''1687580''>it''s</span> <span m=''1687980''>easier</span> <span m=''1688260''>to</span>
  <span m=''1688410''>just</span> <span m=''1688660''>do</span> <span m=''1688770''>that</span>
  <span m=''1688980''>processing</span> <span m=''1689530''>with</span> <span m=''1689740''>the</span>
  <span m=''1690060''>SIMD</span> <span m=''1690460''>instruction</span> <span m=''1691240''>rather</span>
  <span m=''1691440''>than</span> <span m=''1692270''>just</span> <span m=''1692480''>have</span>
  <span m=''1692790''>one</span> <span m=''1693080''>or</span> <span m=''1693170''>two</span>
  <span m=''1693320''>elements</span> <span m=''1693680''>hanging</span> <span m=''1693940''>off</span>
  <span m=''1694590''>and</span> <span m=''1695760''>have</span> <span m=''1695920''>to</span>
  <span m=''1696010''>worry</span> <span m=''1696190''>about</span> <span m=''1696410''>those.</span>
  </p><p><span m=''1698192''>AUDIENCE:</span> <span m=''1698686''>Question.</span>
  </p><p><span m=''1699180''>PROFESSOR: Yep.</span> </p><p><span m=''1699674''>AUDIENCE:
  Is</span> <span m=''1699772''>it</span> <span m=''1699871''>a</span> <span m=''1699970''>good</span>
  <span m=''1700069''>idea</span> <span m=''1700168''>to</span> <span m=''1700662''>pass</span>
  <span m=''1701156''>parameters</span> <span m=''1701403''>2.2</span> <span m=''1701650''>[INAUDIBLE]</span>
  <span m=''1706590''>I</span> <span m=''1707084''>mean,</span> <span m=''1707578''>which</span>
  <span m=''1707701''>one</span> <span m=''1707825''>is</span> <span m=''1707948''>preferred?</span>
  <span m=''1708566''>[INAUDIBLE].</span> </p><p><span m=''1711036''>AUDIENCE:</span>
  <span m=''1711530''>So</span> <span m=''1711694''>you</span> <span m=''1711859''>should</span>
  <span m=''1712024''>[INAUDIBLE]</span> <span m=''1718446''>for</span> <span m=''1718940''>figuring</span>
  <span m=''1719434''>out</span> <span m=''1719598''>whether</span> <span m=''1719763''>something</span>
  <span m=''1719928''>can</span> <span m=''1720422''>scale easily</span> <span m=''1720916''>or</span>
  <span m=''1721163''>not.</span> <span m=''1721410''>So</span> <span m=''1721904''>you</span>
  <span m=''1722068''>might</span> <span m=''1722233''>make</span> <span m=''1722398''>[INAUDIBLE].</span>
  <span m=''1725362''>So</span> <span m=''1725856''>in</span> <span m=''1726103''>cases</span>
  <span m=''1726350''>where</span> <span m=''1726597''>you</span> <span m=''1726844''>can</span>
  <span m=''1727091''>avoid</span> <span m=''1727338''>using</span> <span m=''1727832''>pointers,
  you should</span> <span m=''1728326''>do</span> <span m=''1728820''>that.</span>
  </p><p><span m=''1732772''>PROFESSOR:</span> <span m=''1733290''>OK.</span> </p><p><span
  m=''1733600''>[SIDE CONVERSATION]</span> </p><p></p><p><span m=''1807380''>PROFESSOR:</span>
  <span m=''1807880''>So</span> <span m=''1808620''>one</span> <span m=''1808840''>last</span>
  <span m=''1809080''>thing</span> <span m=''1809520''>that</span> <span m=''1809680''>I</span>
  <span m=''1811230''>should</span> <span m=''1811380''>mention.</span> <span m=''1812040''>I</span>
  <span m=''1812140''>haven''t</span> <span m=''1812330''>really</span> <span m=''1812520''>let</span>
  <span m=''1812680''>on,</span> <span m=''1812870''>but</span> <span m=''1815210''>compilers</span>
  <span m=''1815760''>can</span> <span m=''1816070''>actually</span> <span m=''1816470''>generate</span>
  <span m=''1816840''>some</span> <span m=''1816990''>of</span> <span m=''1817050''>these</span>
  <span m=''1817200''>SIMD</span> <span m=''1817520''>instructions</span> <span m=''1818020''>by</span>
  <span m=''1818140''>themselves.</span> <span m=''1818960''>If</span> <span m=''1819310''>you</span>
  <span m=''1819450''>declare</span> <span m=''1819820''>your</span> <span m=''1820400''>types</span>
  <span m=''1820660''>to</span> <span m=''1820740''>be</span> <span m=''1820980''>vector</span>
  <span m=''1821360''>and</span> <span m=''1821430''>then</span> <span m=''1821540''>use</span>
  <span m=''1821840''>just</span> <span m=''1822040''>regular</span> <span m=''1822440''>operations</span>
  <span m=''1823480''>apparently</span> <span m=''1824510''>GCC</span> <span m=''1825150''>and</span>
  <span m=''1825550''>XLC</span> <span m=''1826040''>yes,</span> <span m=''1826340''>will</span>
  <span m=''1827200''>substitute</span> <span m=''1827720''>the</span> <span m=''1827810''>correct</span>
  <span m=''1828210''>intrinsics</span> <span m=''1828680''>for</span> <span m=''1828790''>you.</span>
  </p><p><span m=''1829880''>Of</span> <span m=''1830060''>course</span> <span m=''1830340''>that</span>
  <span m=''1830470''>doesn''t</span> <span m=''1830660''>get</span> <span m=''1830770''>you</span>
  <span m=''1830920''>all</span> <span m=''1831140''>the</span> <span m=''1831250''>operations</span>
  <span m=''1831660''>which</span> <span m=''1831830''>are</span> <span m=''1831900''>available</span>
  <span m=''1832360''>with</span> <span m=''1832510''>intrinsics,</span> <span m=''1834030''>but</span>
  <span m=''1836280''>anyway</span> <span m=''1836840''>automatically</span> <span
  m=''1838950''>simbianizing</span> <span m=''1839660''>your</span> <span m=''1840820''>code</span>
  <span m=''1841050''>is</span> <span m=''1841150''>something</span> <span m=''1841410''>that''s</span>
  <span m=''1841720''>really</span> <span m=''1841980''>worth</span> <span m=''1842240''>looking</span>
  <span m=''1842510''>into.</span> <span m=''1842870''>As</span> <span m=''1843190''>we</span>
  <span m=''1843400''>saw</span> <span m=''1844040''>it</span> <span m=''1844140''>can</span>
  <span m=''1844320''>give</span> <span m=''1844480''>you</span> <span m=''1844580''>a</span>
  <span m=''1844640''>great</span> <span m=''1844830''>performance</span> <span m=''1845240''>improvement.</span>
  </p><p><span m=''1845950''>And</span> <span m=''1846080''>the</span> <span m=''1846150''>thing</span>
  <span m=''1846340''>is</span> <span m=''1846930''>that</span> <span m=''1847920''>compilers</span>
  <span m=''1848440''>are</span> <span m=''1848540''>still</span> <span m=''1848800''>not</span>
  <span m=''1849010''>very</span> <span m=''1849240''>good</span> <span m=''1849500''>at</span>
  <span m=''1850640''>automatically</span> <span m=''1851170''>doing</span> <span
  m=''1851370''>this</span> <span m=''1851500''>transformation.</span> <span m=''1852680''>So</span>
  <span m=''1852810''>unlike</span> <span m=''1853120''>instruction</span> <span m=''1853560''>scheduling</span>
  <span m=''1854040''>where</span> <span m=''1854530''>if</span> <span m=''1854620''>your</span>
  <span m=''1854710''>passing</span> <span m=''1855140''>05</span> <span m=''1855700''>your</span>
  <span m=''1855900''>compiler</span> <span m=''1856310''>will</span> <span m=''1856470''>do</span>
  <span m=''1856600''>a</span> <span m=''1856650''>much</span> <span m=''1856850''>better</span>
  <span m=''1857060''>job</span> <span m=''1857360''>than</span> <span m=''1857530''>you</span>
  <span m=''1857710''>would</span> <span m=''1857790''>have</span> <span m=''1857870''>time</span>
  <span m=''1858080''>to</span> <span m=''1858160''>do.</span> <span m=''1858900''>This</span>
  <span m=''1859110''>is</span> <span m=''1859190''>something</span> <span m=''1859460''>that</span>
  <span m=''1859600''>you</span> <span m=''1859700''>should</span> <span m=''1860460''>probably</span>
  <span m=''1861140''>reserve</span> <span m=''1861450''>some</span> <span m=''1861590''>time</span>
  <span m=''1861770''>for.</span> </p><p><span m=''1863580''>That''s</span> <span
  m=''1863980''>all.</span> <span m=''1864150''>If</span> <span m=''1864240''>you</span>
  <span m=''1864310''>have</span> <span m=''1864410''>any</span> <span m=''1864510''>questions</span>
  <span m=''1864880''>you</span> <span m=''1864960''>can</span> <span m=''1865300''>stick</span>
  <span m=''1865470''>around</span> <span m=''1865730''>and</span> <span m=''1865865''>I''ll</span>
  <span m=''1866000''>try</span> <span m=''1866300''>and</span> <span m=''1866400''>help</span>
  <span m=''1866500''>you.</span> </p>'
type: course
uid: 43100f5929a9b823e22a5f55efec95f5

---
None