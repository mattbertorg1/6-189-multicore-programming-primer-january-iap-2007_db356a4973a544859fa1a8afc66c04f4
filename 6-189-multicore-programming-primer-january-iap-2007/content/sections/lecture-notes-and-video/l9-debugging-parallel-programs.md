---
about_this_resource_text: <p><strong>Topics covered:</strong> Debugging parallel programs</p><p><strong>Instructor:</strong>
  Rodric Rabbah, IBM</p><p>Subtitles are provided through the generous assistance
  of Rohan Pai.</p>
course_id: 6-189-multicore-programming-primer-january-iap-2007
embedded_media:
- id: l9.jpg
  parent_uid: ea7393549a19439453ecf5bb638bd0bd
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-189-multicore-programming-primer-january-iap-2007/lecture-notes-and-video/l9-debugging-parallel-programs/l9.jpg
  title: 'L9: Debugging Parallel Programs'
  type: null
  uid: 8674e6abf14fadbf709e911b30232fbe
- id: Video-YouTube-Stream
  media_location: qR9y8dx_pW4
  parent_uid: ea7393549a19439453ecf5bb638bd0bd
  title: Video-YouTube-Stream
  type: Video
  uid: 090f4f465b52627225beacf5edd4c373
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/qR9y8dx_pW4/default.jpg
  parent_uid: ea7393549a19439453ecf5bb638bd0bd
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 99d2e44965df66210dea542a36c2f21c
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id341597759
  parent_uid: ea7393549a19439453ecf5bb638bd0bd
  title: Video-iTunes U-MP4
  type: Video
  uid: c66bed5cb0f4b2d63876bab8de0caac9
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT6.189IAP07/ocw-6.189-iap07-lec09_300k.mp4
  parent_uid: ea7393549a19439453ecf5bb638bd0bd
  title: Video-Internet Archive-MP4
  type: Video
  uid: f25d5180cc68aa71285014d3417819a0
- id: Thumbnail-OCW-JPG
  parent_uid: ea7393549a19439453ecf5bb638bd0bd
  title: Thumbnail-OCW-JPG
  type: Thumbnail
  uid: 60855730e8c3a8be18c2005cda2418eb
- id: 3Play-3PlayYouTubeid-MP4
  media_location: qR9y8dx_pW4
  parent_uid: ea7393549a19439453ecf5bb638bd0bd
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 925d587f7dca2bda6d92d2b73ac0a7d2
- id: qR9y8dx_pW4.srt
  parent_uid: ea7393549a19439453ecf5bb638bd0bd
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-189-multicore-programming-primer-january-iap-2007/lecture-notes-and-video/l9-debugging-parallel-programs/qR9y8dx_pW4.srt
  title: 3play caption file
  type: null
  uid: ab1fa37daa084b19f96904023d45b594
- id: qR9y8dx_pW4.pdf
  parent_uid: ea7393549a19439453ecf5bb638bd0bd
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-189-multicore-programming-primer-january-iap-2007/lecture-notes-and-video/l9-debugging-parallel-programs/qR9y8dx_pW4.pdf
  title: 3play pdf file
  type: null
  uid: c227dfaef1d6ab653f586e702f82aae1
- id: Caption-3Play YouTube id-SRT
  parent_uid: ea7393549a19439453ecf5bb638bd0bd
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: ae0d7ac5d6fa496cf2daa41edf2474ff
- id: Transcript-3Play YouTube id-PDF
  parent_uid: ea7393549a19439453ecf5bb638bd0bd
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: e11d98066376671029287cf72fd14f8c
inline_embed_id: 87239485l9:debuggingparallelprograms20663683
layout: video
order_index: null
parent_uid: 69885f30bae5c69316fc5492e4404278
related_resources_text: <p>Lecture Notes (<a target="_blank" title="Open in a new
  window." href="./resolveuid/af439a376ea05c1958306c7dda1883f7">PDF</a>)</p>
short_url: l9-debugging-parallel-programs
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-189-multicore-programming-primer-january-iap-2007/lecture-notes-and-video/l9-debugging-parallel-programs
template_type: Tabbed
title: 'L9: Debugging Parallel Programs'
transcript: '<p><span m=''30''>The</span> <span m=''130''>following</span> <span m=''540''>content</span>
  <span m=''1130''>is</span> <span m=''1240''>provided</span> <span m=''1710''>under
  a</span> <span m=''2020''>Creative</span> <span m=''2430''>Commons</span> <span
  m=''3850''>license.</span> <span m=''3990''>Your</span> <span m=''4110''>support</span>
  <span m=''4660''>will</span> <span m=''4790''>help</span> <span m=''5040''>MIT</span>
  <span m=''5470''>OpenCourseWare</span> <span m=''6310''>continue</span> <span m=''6790''>to</span>
  <span m=''6860''>offer</span> <span m=''7340''>high</span> <span m=''7540''>quality</span>
  <span m=''8050''>educational</span> <span m=''8660''>resources</span> <span m=''9260''>for</span>
  <span m=''9450''>free.</span> <span m=''10550''>To</span> <span m=''10660''>make</span>
  <span m=''10860''>a</span> <span m=''10920''>donation</span> <span m=''11660''>or</span>
  <span m=''11870''>view</span> <span m=''12340''>additional</span> <span m=''12740''>materials</span>
  <span m=''13260''>from</span> <span m=''13410''>hundreds</span> <span m=''13940''>of</span>
  <span m=''14070''>MIT</span> <span m=''14430''>courses,</span> <span m=''15370''>visit</span>
  <span m=''15720''>MIT</span> <span m=''16210''>OpenCourseWare</span> <span m=''17210''>at</span>
  <span m=''17510''>ocw.mit.edu.</span> </p><p><span m=''19950''>PROFESSOR:</span>
  <span m=''23220''>So,</span> <span m=''23720''>yesterday</span> <span m=''24170''>in
  the</span> <span m=''24310''>recitation</span> <span m=''25000''>we</span> <span
  m=''25820''>talked</span> <span m=''26070''>a</span> <span m=''26100''>little</span>
  <span m=''26250''>bit</span> <span m=''26360''>about</span> <span m=''26640''>how</span>
  <span m=''26810''>to</span> <span m=''26940''>debug</span> <span m=''27390''>programs</span>
  <span m=''27940''>on</span> <span m=''28100''>Cell.</span> <span m=''29260''>Today</span>
  <span m=''29470''>I''m</span> <span m=''29550''>going to</span> <span m=''29690''>talk</span>
  <span m=''29890''>a</span> <span m=''29930''>little</span> <span m=''30140''>more</span>
  <span m=''30430''>about</span> <span m=''31540''>debugging</span> <span m=''32420''>parallel</span>
  <span m=''32630''>programs</span> <span m=''33090''>in</span> <span m=''33210''>general</span>
  <span m=''33960''>and</span> <span m=''34420''>give</span> <span m=''34600''>you</span>
  <span m=''34730''>some</span> <span m=''35030''>common</span> <span m=''35370''>tips</span>
  <span m=''36120''>that</span> <span m=''36270''>might</span> <span m=''36460''>be</span>
  <span m=''36580''>helpful</span> <span m=''37040''>in</span> <span m=''37670''>helping</span>
  <span m=''37970''>you</span> <span m=''38100''>track</span> <span m=''38410''>down</span>
  <span m=''39430''>problems</span> <span m=''39940''>that</span> <span m=''40060''>you</span>
  <span m=''40840''>run</span> <span m=''40980''>into.</span> </p><p><span m=''45190''>As</span>
  <span m=''45450''>you</span> <span m=''45520''>might</span> <span m=''45740''>have</span>
  <span m=''46320''>gotten</span> <span m=''46570''>a</span> <span m=''46630''>feel</span>
  <span m=''46880''>for</span> <span m=''47130''>yesterday,</span> <span m=''47590''>debugging</span>
  <span m=''48170''>parallel</span> <span m=''48490''>programs</span> <span m=''49150''>is</span>
  <span m=''49320''>harder</span> <span m=''49950''>than</span> <span m=''50600''>normal</span>
  <span m=''51190''>sequential</span> <span m=''51650''>programs.</span> <span m=''52350''>So</span>
  <span m=''52690''>in</span> <span m=''52840''>normal</span> <span m=''53110''>sequential</span>
  <span m=''53500''>programs,</span> <span m=''53910''>you</span> <span m=''53990''>have</span>
  <span m=''54090''>your</span> <span m=''54190''>traditional</span> <span m=''54650''>set</span>
  <span m=''54800''>of</span> <span m=''54920''>bugs</span> <span m=''55610''>which</span>
  <span m=''55830''>parallel</span> <span m=''56110''>programs</span> <span m=''56470''>inherit.</span>
  <span m=''57220''>So</span> <span m=''57920''>that</span> <span m=''58220''>doesn''t</span>
  <span m=''58480''>get</span> <span m=''58720''>much</span> <span m=''58960''>harder,</span>
  <span m=''59620''>but</span> <span m=''59960''>then</span> <span m=''60120''>you</span>
  <span m=''60220''>add</span> <span m=''60480''>on</span> <span m=''60890''>new</span>
  <span m=''61110''>things</span> <span m=''61400''>I</span> <span m=''61460''>can</span>
  <span m=''61600''>go</span> <span m=''61760''>wrong</span> <span m=''62370''>because</span>
  <span m=''62640''>of parallelization.</span> <span m=''63490''>So</span> <span m=''63710''>things</span>
  <span m=''64010''>like</span> <span m=''64150''>synchronization,</span> <span m=''65140''>things</span>
  <span m=''65360''>like</span> <span m=''65540''>deadlocks,</span> <span m=''66100''>things</span>
  <span m=''66290''>like</span> <span m=''66430''>data</span> <span m=''66640''>races.</span>
  <span m=''67790''>So</span> <span m=''67900''>you</span> <span m=''67970''>have</span>
  <span m=''68080''>to</span> <span m=''68190''>get</span> <span m=''68340''>those</span>
  <span m=''68570''>right.</span> </p><p><span m=''69220''>Now</span> <span m=''69380''>you</span>
  <span m=''69480''>have</span> <span m=''69670''>to</span> <span m=''69820''>debug</span>
  <span m=''70490''>your</span> <span m=''70670''>program</span> <span m=''71030''>and</span>
  <span m=''71140''>figure</span> <span m=''71310''>out</span> <span m=''71380''>how</span>
  <span m=''71440''>to</span> <span m=''71560''>do</span> <span m=''71690''>that.</span>
  <span m=''72680''>One</span> <span m=''72820''>of</span> <span m=''72880''>the</span>
  <span m=''72940''>things</span> <span m=''73210''>you''ll</span> <span m=''73360''>see</span>
  <span m=''73530''>here</span> <span m=''73840''>is</span> <span m=''74320''>a</span>
  <span m=''74650''>lot</span> <span m=''74870''>of</span> <span m=''74950''>tools</span>
  <span m=''75380''>might</span> <span m=''75530''>not</span> <span m=''75700''>be</span>
  <span m=''76560''>as</span> <span m=''76890''>good</span> <span m=''77110''>as</span>
  <span m=''77240''>you''d</span> <span m=''77330''>like</span> <span m=''77590''>them</span>
  <span m=''77720''>to</span> <span m=''78210''>in</span> <span m=''78380''>terms</span>
  <span m=''78730''>of</span> <span m=''79020''>providing</span> <span m=''79440''>you
  the</span> <span m=''79600''>functionality</span> <span m=''80130''>for</span> <span
  m=''80270''>debugging.</span> <span m=''82840''>Add</span> <span m=''83060''>to</span>
  <span m=''83160''>that</span> <span m=''83390''>that</span> <span m=''84850''>bugs</span>
  <span m=''85200''>in</span> <span m=''85330''>parallel</span> <span m=''85620''>programs</span>
  <span m=''86080''>often</span> <span m=''86350''>just</span> <span m=''86490''>go</span>
  <span m=''86660''>away</span> <span m=''86940''>if</span> <span m=''87080''>you</span>
  <span m=''87210''>change</span> <span m=''90320''>one</span> <span m=''90520''>statement</span>
  <span m=''91660''>in</span> <span m=''91780''>your</span> <span m=''91890''>code
  --</span> <span m=''92190''>you</span> <span m=''92300''>reorder</span> <span m=''92640''>things</span>
  <span m=''93050''>and</span> <span m=''93150''>all</span> <span m=''93250''>of</span>
  <span m=''93340''>a</span> <span m=''93410''>sudden the</span> <span m=''93680''>bug
  is</span> <span m=''93990''>gone.</span> <span m=''94640''>It''s</span> <span m=''94790''>kind</span>
  <span m=''94990''>of</span> <span m=''95090''>like</span> <span m=''95480''>those</span>
  <span m=''95730''>pointer</span> <span m=''96070''>problems</span> <span m=''96550''>in</span>
  <span m=''96750''>C,</span> <span m=''97030''>where</span> <span m=''97360''>you</span>
  <span m=''97470''>might</span> <span m=''97710''>add</span> <span m=''97980''>a</span>
  <span m=''98010''>word,</span> <span m=''98530''>add a</span> <span m=''99250''>new</span>
  <span m=''99440''>variable</span> <span m=''99840''>somewhere</span> <span m=''100260''>and</span>
  <span m=''100940''>problem''s</span> <span m=''101310''>gone,</span> <span m=''101560''>or
  you</span> <span m=''101730''>add</span> <span m=''101860''>a</span> <span m=''101930''>print-off</span>
  <span m=''102470''>and the</span> <span m=''102540''>problem is</span> <span m=''102990''>gone.</span>
  <span m=''104130''>So</span> <span m=''104210''>here</span> <span m=''104460''>it</span>
  <span m=''104540''>gets</span> <span m=''104740''>harder</span> <span m=''104980''>because</span>
  <span m=''105260''>those</span> <span m=''105470''>things</span> <span m=''105740''>can</span>
  <span m=''106590''>get</span> <span m=''106790''>rid</span> <span m=''106930''>of</span>
  <span m=''107060''>deadlocks,</span> <span m=''108020''>so</span> <span m=''108280''>it</span>
  <span m=''108350''>makes</span> <span m=''108610''>it</span> <span m=''108700''>really</span>
  <span m=''108910''>hard</span> <span m=''109150''>to</span> <span m=''110260''>have</span>
  <span m=''110470''>an</span> <span m=''110530''>experiment</span> <span m=''110940''>that
  you</span> <span m=''111060''>can</span> <span m=''111220''>repeat</span> <span
  m=''111850''>and</span> <span m=''112340''>come</span> <span m=''112540''>down</span>
  <span m=''112800''>to</span> <span m=''112960''>where</span> <span m=''113140''>the</span>
  <span m=''113210''>problem</span> <span m=''113650''>is.</span> </p><p><span m=''115630''>So</span>
  <span m=''116290''>what</span> <span m=''116480''>might</span> <span m=''116660''>you</span>
  <span m=''116770''>want</span> <span m=''117130''>in</span> <span m=''117340''>a</span>
  <span m=''117410''>debugger.</span> <span m=''117910''>So</span> <span m=''118030''>this</span>
  <span m=''118170''>is</span> <span m=''118300''>a</span> <span m=''118360''>list</span>
  <span m=''118660''>that</span> <span m=''118780''>I''ve</span> <span m=''118940''>come</span>
  <span m=''119150''>up</span> <span m=''119280''>with,</span> <span m=''120490''>and</span>
  <span m=''120910''>if</span> <span m=''121020''>you</span> <span m=''121090''>have</span>
  <span m=''121190''>some</span> <span m=''121310''>ideas</span> <span m=''122050''>we''ll</span>
  <span m=''122270''>want</span> <span m=''122420''>to</span> <span m=''122500''>throw</span>
  <span m=''122670''>them</span> <span m=''122810''>out.</span> <span m=''123760''>I''m</span>
  <span m=''123980''>thinking</span> <span m=''124370''>in</span> <span m=''124450''>terms</span>
  <span m=''124690''>of</span> <span m=''124800''>debugging</span> <span m=''125260''>parallel</span>
  <span m=''125580''>program,</span> <span m=''125970''>what</span> <span m=''126080''>I</span>
  <span m=''126120''>want</span> <span m=''126500''>is a</span> <span m=''127160''>visual</span>
  <span m=''127640''>debugging</span> <span m=''128040''>system</span> <span m=''128710''>that</span>
  <span m=''128920''>really</span> <span m=''129190''>let''s</span> <span m=''129430''>me</span>
  <span m=''129600''>see</span> <span m=''129980''>all</span> <span m=''130210''>the</span>
  <span m=''130290''>processors</span> <span m=''130830''>that</span> <span m=''131000''>I</span>
  <span m=''131050''>have</span> <span m=''131300''>in</span> <span m=''131380''>my</span>
  <span m=''131490''>network</span> <span m=''132580''>in</span> <span m=''132820''>my</span>
  <span m=''133360''>multi-processor</span> <span m=''134090''>system.</span> <span
  m=''134790''>That</span> <span m=''135010''>includes</span> <span m=''135900''>actual</span>
  <span m=''136320''>computing</span> <span m=''137340''>and</span> <span m=''137680''>the</span>
  <span m=''137740''>actual</span> <span m=''138200''>network</span> <span m=''138840''>that</span>
  <span m=''139060''>they''re</span> <span m=''139240''>interconnecting</span> <span
  m=''139910''>all</span> <span m=''140040''>the</span> <span m=''140120''>processors</span>
  <span m=''140690''>that</span> <span m=''140800''>are</span> <span m=''141020''>going
  to</span> <span m=''141090''>be</span> <span m=''141170''>communicating</span> <span
  m=''141740''>with</span> <span m=''141850''>each</span> <span m=''142060''>other.</span>
  <span m=''143220''>So I''d</span> <span m=''143360''>like</span> <span m=''143530''>to</span>
  <span m=''143620''>be</span> <span m=''143700''>able</span> <span m=''143860''>to</span>
  <span m=''143960''>see</span> <span m=''144400''>what</span> <span m=''144710''>code</span>
  <span m=''145030''>is</span> <span m=''145160''>running</span> <span m=''145410''>on</span>
  <span m=''145520''>each</span> <span m=''145730''>processor.</span> <span m=''146610''>I''d</span>
  <span m=''146870''>like</span> <span m=''147000''>to</span> <span m=''147100''>see</span>
  <span m=''147290''>which</span> <span m=''147640''>edges</span> <span m=''147980''>are</span>
  <span m=''148070''>being</span> <span m=''148310''>used</span> <span m=''148550''>to</span>
  <span m=''148870''>send</span> <span m=''149110''>messages</span> <span m=''149490''>around.</span>
  <span m=''150300''>I</span> <span m=''150990''>might</span> <span m=''151170''>want</span>
  <span m=''151360''>to</span> <span m=''151420''>know</span> <span m=''151600''>which</span>
  <span m=''151870''>processors</span> <span m=''152290''>are</span> <span m=''152400''>blocked
  --</span> <span m=''152970''>that</span> <span m=''153010''>might</span> <span m=''153170''>help
  me</span> <span m=''153400''>identify</span> <span m=''153920''>deadlock</span>
  <span m=''154330''>problems.</span> </p><p><span m=''157250''>For</span> <span m=''157540''>these</span>
  <span m=''157750''>kinds</span> <span m=''157970''>of</span> <span m=''158070''>scenarios
  it</span> <span m=''158580''>might</span> <span m=''158860''>be</span> <span m=''158990''>tricky</span>
  <span m=''159380''>to</span> <span m=''159720''>define</span> <span m=''160110''>step,</span>
  <span m=''160830''>because</span> <span m=''161100''>there''s</span> <span m=''161280''>no</span>
  <span m=''161420''>global</span> <span m=''161720''>clock,</span> <span m=''162080''>you</span>
  <span m=''162170''>can''t</span> <span m=''162600''>force</span> <span m=''162940''>everybody</span>
  <span m=''163380''>to</span> <span m=''163510''>proceed</span> <span m=''163880''>through</span>
  <span m=''164430''>one</span> <span m=''164650''>step.</span> <span m=''165150''>What''s</span>
  <span m=''165580''>one</span> <span m=''165790''>step</span> <span m=''166030''>on</span>
  <span m=''166150''>one</span> <span m=''166350''>processor</span> <span m=''166840''>might</span>
  <span m=''167020''>be</span> <span m=''167180''>different</span> <span m=''167590''>on</span>
  <span m=''167700''>another,</span> <span m=''168340''>especially</span> <span m=''168740''>if</span>
  <span m=''168820''>they''re</span> <span m=''168930''>not</span> <span m=''169100''>all</span>
  <span m=''169270''>running</span> <span m=''169530''>the</span> <span m=''169600''>same</span>
  <span m=''169830''>code.</span> <span m=''170460''>So</span> <span m=''170730''>how</span>
  <span m=''170820''>do</span> <span m=''170900''>you</span> <span m=''170980''>actually</span>
  <span m=''171280''>do</span> <span m=''171420''>that</span> <span m=''171580''>without</span>
  <span m=''171850''>a</span> <span m=''173270''>global</span> <span m=''173600''>clock.</span>
  <span m=''175170''>So</span> <span m=''175340''>that</span> <span m=''175600''>can</span>
  <span m=''175730''>get</span> <span m=''175880''>a</span> <span m=''175910''>little</span>
  <span m=''176060''>bit</span> <span m=''176310''>tricky.</span> <span m=''178150''>It</span>
  <span m=''178230''>likely</span> <span m=''178560''>won''t</span> <span m=''178800''>help</span>
  <span m=''178970''>with</span> <span m=''179100''>data</span> <span m=''179320''>races,</span>
  <span m=''179990''>because</span> <span m=''180330''>I''m</span> <span m=''180700''>looking</span>
  <span m=''181000''>at</span> <span m=''181230''>global</span> <span m=''181510''>communication</span>
  <span m=''182120''>problems,</span> <span m=''182650''>I''m</span> <span m=''182750''>looking</span>
  <span m=''183040''>at</span> <span m=''183460''>trying to</span> <span m=''183660''>identify</span>
  <span m=''184270''>what''s</span> <span m=''184510''>deadlocked</span> <span m=''184870''>and</span>
  <span m=''184960''>what''s</span> <span m=''185130''>not.</span> <span m=''185680''>So
  if</span> <span m=''185850''>there are</span> <span m=''186030''>data</span> <span
  m=''186280''>races,</span> <span m=''186700''>this</span> <span m=''186810''>kind</span>
  <span m=''187010''>of</span> <span m=''187100''>tool</span> <span m=''187490''>may</span>
  <span m=''187760''>or</span> <span m=''187870''>may</span> <span m=''188040''>not</span>
  <span m=''188180''>help</span> <span m=''188420''>with</span> <span m=''188540''>that.</span>
  </p><p><span m=''189940''>In</span> <span m=''190060''>general,</span> <span m=''190390''>this</span>
  <span m=''190520''>is</span> <span m=''190880''>the</span> <span m=''190970''>tool
  that</span> <span m=''191260''>I</span> <span m=''191380''>would</span> <span m=''191560''>build</span>
  <span m=''192490''>for</span> <span m=''192750''>debugging.</span> <span m=''194060''>I</span>
  <span m=''194140''>looked</span> <span m=''194390''>around</span> <span m=''194710''>on</span>
  <span m=''194850''>the</span> <span m=''194910''>web</span> <span m=''195120''>to</span>
  <span m=''195220''>see</span> <span m=''195440''>what''s</span> <span m=''195700''>out</span>
  <span m=''195900''>there</span> <span m=''196060''>for</span> <span m=''196430''>debugging</span>
  <span m=''196750''>parallel</span> <span m=''197080''>programs, and</span> <span
  m=''197530''>I</span> <span m=''197640''>found</span> <span m=''198140''>this</span>
  <span m=''198340''>called</span> <span m=''198590''>TotalView.</span> <span m=''199820''>This</span>
  <span m=''199940''>is</span> <span m=''200040''>actually</span> <span m=''200400''>something</span>
  <span m=''200670''>you</span> <span m=''200730''>have</span> <span m=''200850''>to</span>
  <span m=''200950''>buy,</span> <span m=''201240''>it''s</span> <span m=''201410''>not</span>
  <span m=''201630''>free.</span> <span m=''202260''>I</span> <span m=''202540''>don''t</span>
  <span m=''202680''>know</span> <span m=''202740''>if</span> <span m=''202840''>they</span>
  <span m=''202920''>have</span> <span m=''203100''>evaluation</span> <span m=''203700''>licenses</span>
  <span m=''204280''>or</span> <span m=''204790''>licences</span> <span m=''205350''>for</span>
  <span m=''206010''>academic</span> <span m=''206700''>purposes.</span> <span m=''208070''>It</span>
  <span m=''208180''>kind</span> <span m=''208390''>of</span> <span m=''208470''>gets</span>
  <span m=''208640''>close</span> <span m=''208920''>to</span> <span m=''209030''>some</span>
  <span m=''209160''>of</span> <span m=''209220''>the</span> <span m=''209310''>things</span>
  <span m=''209940''>I</span> <span m=''210190''>was</span> <span m=''210370''>talking</span>
  <span m=''210710''>about.</span> <span m=''212330''>You have</span> <span m=''212460''>processors</span>
  <span m=''213170''>that</span> <span m=''213250''>shows</span> <span m=''213540''>your</span>
  <span m=''213650''>communication</span> <span m=''214270''>between</span> <span
  m=''214540''>those</span> <span m=''214700''>processors,</span> <span m=''215930''>how</span>
  <span m=''216090''>much</span> <span m=''216320''>data is</span> <span m=''216680''>being</span>
  <span m=''216920''>sent</span> <span m=''217210''>through.</span> <span m=''219040''>This</span>
  <span m=''219220''>particular</span> <span m=''219590''>version</span> <span m=''220480''>uses</span>
  <span m=''221240''>NPI,</span> <span m=''221950''>which</span> <span m=''222180''>we</span>
  <span m=''222290''>talked</span> <span m=''222530''>about in</span> <span m=''222730''>previous</span>
  <span m=''223080''>lectures.</span> <span m=''223780''>So</span> <span m=''223980''>it''s</span>
  <span m=''224180''>sort</span> <span m=''224490''>of</span> <span m=''224720''>helpful</span>
  <span m=''225210''>in</span> <span m=''225370''>being</span> <span m=''225550''>able</span>
  <span m=''225740''>to</span> <span m=''225840''>see</span> <span m=''226000''>the</span>
  <span m=''226570''>computation,</span> <span m=''227420''>looking</span> <span m=''227650''>at</span>
  <span m=''227750''>the</span> <span m=''227810''>communication,</span> <span m=''229000''>and</span>
  <span m=''229180''>tracking</span> <span m=''229520''>down</span> <span m=''229730''>bugs.</span>
  </p><p><span m=''231130''>But</span> <span m=''231340''>it</span> <span m=''231400''>doesn''t</span>
  <span m=''231690''>get</span> <span m=''231980''>much</span> <span m=''232260''>better</span>
  <span m=''232610''>from</span> <span m=''232910''>there.</span> <span m=''233930''>You</span>
  <span m=''234020''>know,</span> <span m=''234560''>how</span> <span m=''234690''>many</span>
  <span m=''234830''>people</span> <span m=''235030''>have used</span> <span m=''235310''>printouts</span>
  <span m=''235680''>for</span> <span m=''235810''>debugging?</span> <span m=''238600''>It''s</span>
  <span m=''238800''>the</span> <span m=''238860''>most</span> <span m=''239060''>popular</span>
  <span m=''239430''>way of</span> <span m=''239780''>debugging,</span> <span m=''240250''>and</span>
  <span m=''240790''>even</span> <span m=''241120''>I</span> <span m=''241330''>still</span>
  <span m=''241600''>use</span> <span m=''241820''>it</span> <span m=''241940''>for</span>
  <span m=''242080''>debugging</span> <span m=''243000''>some</span> <span m=''243170''>of</span>
  <span m=''243240''>the</span> <span m=''243320''>Cell</span> <span m=''243500''>programs</span>
  <span m=''243980''>we''ve</span> <span m=''244140''>been</span> <span m=''244270''>writing.</span>
  <span m=''246680''>I</span> <span m=''246810''>know</span> <span m=''246940''>the</span>
  <span m=''247060''>TAs</span> <span m=''247440''>actually use</span> <span m=''247860''>this</span>
  <span m=''248070''>is</span> <span m=''248170''>well.</span> <span m=''249490''>Yesterday</span>
  <span m=''249930''>you</span> <span m=''250190''>got</span> <span m=''251420''>a</span>
  <span m=''251580''>hands-on</span> <span m=''251990''>experience</span> <span m=''252470''>with</span>
  <span m=''252730''>GDB,</span> <span m=''253360''>and</span> <span m=''253890''>GDB
  is</span> <span m=''254310''>a</span> <span m=''254590''>nice</span> <span m=''255290''>debugger,</span>
  <span m=''255800''>but</span> <span m=''256100''>it</span> <span m=''256270''>lacks</span>
  <span m=''256600''>a</span> <span m=''256660''>lot</span> <span m=''256860''>of</span>
  <span m=''256940''>things</span> <span m=''257250''>that</span> <span m=''257350''>you</span>
  <span m=''257440''>might</span> <span m=''257640''>want,</span> <span m=''257980''>especially</span>
  <span m=''258360''>for</span> <span m=''258490''>debugging</span> <span m=''258880''>parallel</span>
  <span m=''259180''>programs.</span> <span m=''260830''>You</span> <span m=''260990''>saw,</span>
  <span m=''261360''>for</span> <span m=''261470''>example,</span> <span m=''261780''>that</span>
  <span m=''261880''>you</span> <span m=''261940''>have</span> <span m=''262060''>multiple</span>
  <span m=''262390''>threads,</span> <span m=''262790''>you</span> <span m=''262860''>need</span>
  <span m=''262970''>to</span> <span m=''263040''>be</span> <span m=''263120''>able</span>
  <span m=''263310''>switch</span> <span m=''263610''>between</span> <span m=''263900''>the</span>
  <span m=''263970''>threads,</span> <span m=''264670''>getting</span> <span m=''264900''>the</span>
  <span m=''264980''>context</span> <span m=''265490''>right,</span> <span m=''265770''>being</span>
  <span m=''265960''>able</span> <span m=''266130''>to</span> <span m=''266220''>name</span>
  <span m=''266450''>the</span> <span m=''266520''>variables</span> <span m=''267110''>is</span>
  <span m=''267250''>tricky.</span> <span m=''268190''>So</span> <span m=''268310''>there''s</span>
  <span m=''268470''>a</span> <span m=''268500''>lot</span> <span m=''268640''>of</span>
  <span m=''268710''>things</span> <span m=''269070''>that</span> <span m=''269200''>could</span>
  <span m=''269340''>be</span> <span m=''270390''>improved.</span> </p><p><span m=''272820''>There</span>
  <span m=''272920''>are</span> <span m=''273030''>some</span> <span m=''273180''>research</span>
  <span m=''273550''>debuggers,</span> <span m=''274040''>like</span> <span m=''274220''>something</span>
  <span m=''275970''>we''ve</span> <span m=''276170''>built</span> <span m=''276900''>as</span>
  <span m=''277100''>part</span> <span m=''277300''>of</span> <span m=''277370''>the</span>
  <span m=''277430''>streaming</span> <span m=''277720''>projects,</span> <span m=''278130''>StreamIt</span>
  <span m=''278450''>debugger.</span> <span m=''279160''>I''ll</span> <span m=''279260''>show</span>
  <span m=''279380''>you</span> <span m=''279470''>some</span> <span m=''279600''>screenshots</span>
  <span m=''279890''>of</span> <span m=''280170''>this</span> <span m=''280570''>so</span>
  <span m=''280660''>you</span> <span m=''280740''>can</span> <span m=''280870''>see</span>
  <span m=''281040''>what</span> <span m=''281130''>we</span> <span m=''281240''>can</span>
  <span m=''281370''>do.</span> <span m=''282290''>So</span> <span m=''282460''>in
  the</span> <span m=''282820''>StreamIt</span> <span m=''283070''>debugger,</span>
  <span m=''284070''>remember</span> <span m=''284920''>we</span> <span m=''285050''>have
  --</span> <span m=''285470''>so</span> <span m=''285640''>this</span> <span m=''285800''>is</span>
  <span m=''285930''>actually</span> <span m=''286250''>built</span> <span m=''286560''>in</span>
  <span m=''286760''>Eclipse</span> <span m=''287450''>and</span> <span m=''287740''>you</span>
  <span m=''287820''>can</span> <span m=''287970''>download</span> <span m=''288320''>this</span>
  <span m=''288470''>off</span> <span m=''288640''>the</span> <span m=''288720''>web</span>
  <span m=''288900''>as</span> <span m=''289010''>well.</span> <span m=''289900''>You</span>
  <span m=''289980''>can</span> <span m=''290140''>look</span> <span m=''290300''>at</span>
  <span m=''290370''>your</span> <span m=''290580''>stream</span> <span m=''290950''>graph.</span>
  <span m=''292230''>Unfortunately,</span> <span m=''292930''>I</span> <span m=''293200''>couldn''t</span>
  <span m=''293540''>get</span> <span m=''293680''>a</span> <span m=''293730''>split</span>
  <span m=''293990''>join</span> <span m=''294210''>in</span> <span m=''294300''>there,</span>
  <span m=''294990''>much</span> <span m=''295320''>to</span> <span m=''295410''>Bill''s</span>
  <span m=''295680''>dismay.</span> <span m=''296990''>So</span> <span m=''297200''>you</span>
  <span m=''297340''>can''t</span> <span m=''297610''>see,</span> <span m=''297830''>for</span>
  <span m=''297960''>example,</span> <span m=''298330''>the</span> <span m=''298450''>split</span>
  <span m=''298660''>join</span> <span m=''298990''>in all the</span> <span m=''299180''>communication.</span>
  <span m=''301740''>Each</span> <span m=''301920''>one</span> <span m=''302080''>of</span>
  <span m=''302160''>these</span> <span m=''302350''>is</span> <span m=''302420''>a</span>
  <span m=''303040''>filter,</span> <span m=''303420''>and</span> <span m=''303740''>if</span>
  <span m=''303860''>you</span> <span m=''303970''>recall</span> <span m=''304330''>the</span>
  <span m=''304410''>filter</span> <span m=''304850''>is</span> <span m=''305010''>the</span>
  <span m=''305110''>computational</span> <span m=''305730''>element</span> <span
  m=''306510''>in</span> <span m=''306760''>your</span> <span m=''306920''>stream</span>
  <span m=''307270''>graph</span> <span m=''307850''>and</span> <span m=''308710''>interconnected</span>
  <span m=''309390''>by</span> <span m=''309570''>channels.</span> </p><p><span m=''310300''>So</span>
  <span m=''310610''>channels</span> <span m=''311060''>communicate</span> <span m=''311580''>data.</span>
  <span m=''312210''>So</span> <span m=''312450''>what you see</span> <span m=''312820''>here</span>
  <span m=''313410''>--</span> <span m=''313690''>well, you</span> <span m=''314050''>might</span>
  <span m=''314380''>not</span> <span m=''314500''>be</span> <span m=''314570''>able
  to</span> <span m=''314730''>quite</span> <span m=''314940''>see</span> <span m=''315050''>it
  --</span> <span m=''315450''>actually</span> <span m=''315800''>see</span> <span
  m=''315980''>the</span> <span m=''316100''>data</span> <span m=''316360''>that''s</span>
  <span m=''316530''>being</span> <span m=''316740''>passed</span> <span m=''317010''>through</span>
  <span m=''317110''>from</span> <span m=''317300''>one</span> <span m=''317460''>filter</span>
  <span m=''317810''>to the other.</span> <span m=''318890''>You</span> <span m=''318950''>can</span>
  <span m=''319060''>actually</span> <span m=''319400''>go</span> <span m=''319590''>in</span>
  <span m=''319710''>there</span> <span m=''319890''>and</span> <span m=''320040''>change
  the</span> <span m=''320360''>value</span> <span m=''320680''>if</span> <span m=''320810''>you</span>
  <span m=''320890''>wanted</span> <span m=''321180''>to</span> <span m=''321370''>or</span>
  <span m=''321490''>highlight</span> <span m=''321900''>particular</span> <span m=''322550''>value</span>
  <span m=''323220''>and</span> <span m=''323430''>see</span> <span m=''323580''>how</span>
  <span m=''323780''>it</span> <span m=''323860''>flows</span> <span m=''324160''>down</span>
  <span m=''324380''>through the</span> <span m=''324580''>graph.</span> <span m=''325870''>If</span>
  <span m=''326040''>you</span> <span m=''326130''>had</span> <span m=''326290''>a</span>
  <span m=''326340''>split</span> <span m=''326610''>join,</span> <span m=''327220''>then</span>
  <span m=''327470''>you</span> <span m=''327550''>might</span> <span m=''327730''>be</span>
  <span m=''327830''>able</span> <span m=''328060''>to</span> <span m=''328260''>--</span>
  <span m=''328300''>in</span> <span m=''328520''>fact,</span> <span m=''328810''>you</span>
  <span m=''328880''>can</span> <span m=''329150''>do</span> <span m=''329230''>this.</span>
  <span m=''329420''>You</span> <span m=''329570''>can</span> <span m=''329730''>look</span>
  <span m=''329970''>at</span> <span m=''330500''>each</span> <span m=''331090''>path</span>
  <span m=''331540''>of</span> <span m=''331710''>the</span> <span m=''331920''>split</span>
  <span m=''332100''>join</span> <span m=''332530''>independently</span> <span m=''333400''>and</span>
  <span m=''333620''>you</span> <span m=''333730''>can</span> <span m=''333880''>look</span>
  <span m=''334050''>at</span> <span m=''334210''>it</span> <span m=''334360''>in</span>
  <span m=''334570''>sequence.</span> <span m=''335490''>Because</span> <span m=''335750''>the</span>
  <span m=''335820''>split</span> <span m=''336050''>join</span> <span m=''336320''>has</span>
  <span m=''336570''>nice</span> <span m=''336770''>semantics,</span> <span m=''337510''>it''s</span>
  <span m=''337710''>actually</span> <span m=''338300''>you</span> <span m=''338540''>can</span>
  <span m=''338670''>replicate</span> <span m=''339170''>the</span> <span m=''339830''>behavior</span>
  <span m=''341050''>because</span> <span m=''341390''>of</span> <span m=''341900''>the</span>
  <span m=''341980''>static</span> <span m=''342310''>nature is</span> <span m=''342640''>everything
  is</span> <span m=''343170''>deterministic.</span> </p><p><span m=''344800''>So</span>
  <span m=''345060''>this</span> <span m=''345220''>is</span> <span m=''345480''>very</span>
  <span m=''345760''>helpful.</span> <span m=''346050''>We</span> <span m=''346300''>we</span>
  <span m=''346430''>did</span> <span m=''346570''>a</span> <span m=''346620''>user</span>
  <span m=''346880''>study</span> <span m=''348450''>two</span> <span m=''348610''>years</span>
  <span m=''348830''>ago</span> <span m=''349060''>almost</span> <span m=''349370''>with</span>
  <span m=''350220''>something</span> <span m=''350420''>like</span> <span m=''350630''>30</span>
  <span m=''351120''>MIT</span> <span m=''351510''>students</span> <span m=''351820''>who</span>
  <span m=''351900''>use</span> <span m=''352060''>the</span> <span m=''352200''>C</span>
  <span m=''352380''>bugger and</span> <span m=''352680''>gave</span> <span m=''352770''>us</span>
  <span m=''352920''>feedback</span> <span m=''353380''>on</span> <span m=''353520''>it.</span>
  <span m=''356120''>So</span> <span m=''356310''>we</span> <span m=''356430''>gave</span>
  <span m=''356600''>them</span> <span m=''356790''>like</span> <span m=''356970''>10</span>
  <span m=''357140''>problems,</span> <span m=''358800''>10</span> <span m=''361150''>code</span>
  <span m=''361370''>snippets,</span> <span m=''361730''>each</span> <span m=''361900''>of</span>
  <span m=''361970''>them</span> <span m=''362100''>had</span> <span m=''362260''>a</span>
  <span m=''362320''>bug in it,</span> <span m=''362570''>we</span> <span m=''362690''>asked
  them</span> <span m=''362970''>to</span> <span m=''363070''>find</span> <span m=''363350''>it.</span>
  <span m=''364000''>So</span> <span m=''364210''>a</span> <span m=''364320''>lot</span>
  <span m=''364490''>of</span> <span m=''364560''>them</span> <span m=''364700''>found</span>
  <span m=''364940''>to</span> <span m=''365020''>debugger</span> <span m=''365420''>to</span>
  <span m=''365550''>be</span> <span m=''365640''>helpful</span> <span m=''365980''>in</span>
  <span m=''366090''>being</span> <span m=''366230''>able</span> <span m=''366410''>to</span>
  <span m=''366510''>track</span> <span m=''367280''>the</span> <span m=''367390''>flow
  of</span> <span m=''367840''>data</span> <span m=''368210''>and</span> <span m=''368350''>being</span>
  <span m=''368520''>able</span> <span m=''368700''>to</span> <span m=''368810''>see</span>
  <span m=''369010''>what</span> <span m=''369250''>goes</span> <span m=''369470''>wrong.</span>
  <span m=''369810''>So</span> <span m=''369950''>if</span> <span m=''370040''>you</span>
  <span m=''370120''>had,</span> <span m=''370330''>for</span> <span m=''370440''>example,</span>
  <span m=''371210''>a</span> <span m=''371490''>division</span> <span m=''372100''>that</span>
  <span m=''372330''>resulted</span> <span m=''372870''>in</span> <span m=''373210''>NaN</span>
  <span m=''373460''>and</span> <span m=''373530''>not</span> <span m=''373740''>a</span>
  <span m=''373780''>number,</span> <span m=''374620''>floating</span> <span m=''374980''>point</span>
  <span m=''375150''>division</span> <span m=''375500''>you</span> <span m=''375600''>can</span>
  <span m=''375750''>immediately</span> <span m=''376160''>see</span> <span m=''376340''>on</span>
  <span m=''376460''>a</span> <span m=''376530''>screen,</span> <span m=''376850''>so</span>
  <span m=''376960''>you</span> <span m=''377050''>know</span> <span m=''377140''>exactly</span>
  <span m=''377550''>where</span> <span m=''377670''>to</span> <span m=''377750''>go</span>
  <span m=''377880''>look</span> <span m=''378080''>for it.</span> <span m=''378880''>Doing</span>
  <span m=''379250''>that</span> <span m=''379420''>would</span> <span m=''380510''>print-offs</span>
  <span m=''380880''>might</span> <span m=''381040''>not</span> <span m=''381180''>be</span>
  <span m=''381320''>as</span> <span m=''381490''>easy.</span> <span m=''382110''>So</span>
  <span m=''382240''>sometimes</span> <span m=''382620''>visual</span> <span m=''382890''>debugging</span>
  <span m=''383260''>can</span> <span m=''383420''>be</span> <span m=''383550''>very</span>
  <span m=''383790''>nice.</span> </p><p><span m=''384930''>Unfortunately,</span>
  <span m=''385450''>visual</span> <span m=''385790''>debugging</span> <span m=''386150''>for
  the</span> <span m=''386380''>Cell</span> <span m=''387030''>isn''t</span> <span
  m=''387300''>that</span> <span m=''387490''>great.</span> <span m=''388110''>So</span>
  <span m=''388420''>this</span> <span m=''388660''>is</span> <span m=''389120''>the</span>
  <span m=''389430''>Cell</span> <span m=''390030''>plug-in</span> <span m=''391350''>in</span>
  <span m=''391480''>Eclipse.</span> <span m=''392240''>I''ve</span> <span m=''392600''>mentioned</span>
  <span m=''392890''>just</span> <span m=''393070''>to</span> <span m=''393260''>some</span>
  <span m=''393470''>of</span> <span m=''393590''>you</span> <span m=''394280''>if</span>
  <span m=''394430''>you</span> <span m=''394510''>want</span> <span m=''394720''>to</span>
  <span m=''394820''>run</span> <span m=''394950''>it</span> <span m=''395040''>you</span>
  <span m=''395180''>can</span> <span m=''395410''>run</span> <span m=''395560''>it</span>
  <span m=''395630''>from</span> <span m=''395780''>a</span> <span m=''395860''>Playstation</span>
  <span m=''396440''>3,</span> <span m=''396660''>but</span> <span m=''396940''>if</span>
  <span m=''398230''>more</span> <span m=''398500''>than</span> <span m=''398670''>one</span>
  <span m=''398820''>of</span> <span m=''398940''>you is</span> <span m=''399160''>running</span>
  <span m=''399420''>it</span> <span m=''399550''>then</span> <span m=''401030''>it</span>
  <span m=''401170''>becomes</span> <span m=''401480''>unusable</span> <span m=''401920''>because</span>
  <span m=''402210''>of</span> <span m=''402290''>memory</span> <span m=''403370''>issues.</span>
  <span m=''404360''>You</span> <span m=''404530''>can</span> <span m=''404770''>install</span>
  <span m=''405100''>this</span> <span m=''405300''>on</span> <span m=''405560''>other</span>
  <span m=''405780''>Linux</span> <span m=''406100''>machines</span> <span m=''407520''>and</span>
  <span m=''409300''>remotely</span> <span m=''410050''>debug</span> <span m=''410470''>on</span>
  <span m=''410610''>the</span> <span m=''410680''>Playstation</span> <span m=''411140''>3</span>
  <span m=''411300''>hardware.</span> <span m=''411750''>So</span> <span m=''413420''>the</span>
  <span m=''413530''>two</span> <span m=''413710''>remote</span> <span m=''413930''>machines</span>
  <span m=''414220''>can</span> <span m=''414360''>talk</span> <span m=''414620''>through</span>
  <span m=''414730''>GDB</span> <span m=''414970''>ports.</span> <span m=''415410''>I</span>
  <span m=''415470''>can</span> <span m=''415680''>talk</span> <span m=''415920''>to</span>
  <span m=''416000''>you</span> <span m=''416090''>about</span> <span m=''416270''>how</span>
  <span m=''416380''>to</span> <span m=''416480''>set</span> <span m=''416630''>that</span>
  <span m=''416790''>up</span> <span m=''416910''>if</span> <span m=''417020''>you</span>
  <span m=''417100''>want</span> <span m=''417320''>to,</span> <span m=''417770''>but
  it</span> <span m=''418030''>doesn''t</span> <span m=''418270''>really</span> <span
  m=''418570''>add</span> <span m=''418820''>anything</span> <span m=''419260''>over</span>
  <span m=''419840''>E-Max,</span> <span m=''420280''>for</span> <span m=''420390''>example.</span>
  <span m=''420830''>It</span> <span m=''420930''>just</span> <span m=''421430''>might</span>
  <span m=''421700''>look</span> <span m=''421880''>fancier</span> <span m=''422350''>than
  an</span> <span m=''422580''>E-Max</span> <span m=''422960''>window</span> <span
  m=''423120''>or</span> <span m=''423190''>a</span> <span m=''423410''>GDB</span>
  <span m=''423950''>on</span> <span m=''424060''>the</span> <span m=''424130''>command</span>
  <span m=''424580''>line</span> <span m=''424790''>prompt.</span> </p><p><span m=''425530''>So</span>
  <span m=''425710''>this</span> <span m=''425870''>is</span> <span m=''426020''>the</span>
  <span m=''426100''>code</span> <span m=''426400''>from</span> <span m=''426780''>yesterday.</span>
  <span m=''427200''>These</span> <span m=''427450''>are the</span> <span m=''427890''>exercises</span>
  <span m=''428470''>we</span> <span m=''428580''>asked</span> <span m=''428780''>you</span>
  <span m=''428900''>to</span> <span m=''428980''>do.</span> <span m=''429610''>You</span>
  <span m=''429710''>can</span> <span m=''429850''>look</span> <span m=''430010''>at</span>
  <span m=''430070''>the</span> <span m=''430150''>different</span> <span m=''430530''>threads.</span>
  <span m=''431130''>If</span> <span m=''431270''>you</span> <span m=''431450''>have</span>
  <span m=''431660''>debug</span> <span m=''431780''>Java</span> <span m=''432170''>programs</span>
  <span m=''432620''>in</span> <span m=''432680''>Eclipse</span> <span m=''433090''>this</span>
  <span m=''433190''>should</span> <span m=''433370''>look</span> <span m=''433490''>very</span>
  <span m=''433670''>familiar.</span> <span m=''434860''>You</span> <span m=''435020''>can</span>
  <span m=''435150''>look</span> <span m=''435310''>at the</span> <span m=''435440''>different</span>
  <span m=''436090''>variables.</span> <span m=''438030''>You</span> <span m=''438160''>still</span>
  <span m=''438320''>have  the</span> <span m=''438680''>naming</span> <span m=''438930''>problem.</span>
  <span m=''439760''>So</span> <span m=''439900''>yesterday,</span> <span m=''440210''>remember</span>
  <span m=''440500''>you</span> <span m=''440580''>had</span> <span m=''440700''>to</span>
  <span m=''440770''>qualify</span> <span m=''441570''>which</span> <span m=''442240''>control</span>
  <span m=''442610''>box</span> <span m=''442800''>you</span> <span m=''442900''>were</span>
  <span m=''443000''>looking</span> <span m=''443230''>at?</span> <span m=''443700''>Still</span>
  <span m=''444000''>the</span> <span m=''444070''>same</span> <span m=''444240''>kind</span>
  <span m=''444410''>of</span> <span m=''444510''>issue --</span> <span m=''444820''>have</span>
  <span m=''444940''>to</span> <span m=''445020''>do</span> <span m=''445110''>some</span>
  <span m=''445320''>trickery to</span> <span m=''445750''>find</span> <span m=''446070''>it</span>
  <span m=''446130''>here.</span> <span m=''447010''>It</span> <span m=''447070''>doesn''t</span>
  <span m=''447350''>have</span> <span m=''448340''>the</span> <span m=''448440''>nice</span>
  <span m=''448670''>visual</span> <span m=''448980''>aspect</span> <span m=''449390''>of</span>
  <span m=''449480''>showing</span> <span m=''449760''>you</span> <span m=''449840''>which</span>
  <span m=''450080''>code</span> <span m=''450410''>is</span> <span m=''450550''>running</span>
  <span m=''450830''>on</span> <span m=''450990''>which</span> <span m=''451220''>SPE,</span>
  <span m=''452140''>and</span> <span m=''452430''>you</span> <span m=''452490''>might</span>
  <span m=''452620''>not</span> <span m=''452760''>be</span> <span m=''452840''>able</span>
  <span m=''452980''>to</span> <span m=''453350''>find</span> <span m=''454090''>mailbox</span>
  <span m=''454600''>synchronization</span> <span m=''455530''>problems.</span> <span
  m=''457510''>Maybe</span> <span m=''457740''>those</span> <span m=''457910''>things</span>
  <span m=''458150''>will</span> <span m=''458310''>come</span> <span m=''458490''>in</span>
  <span m=''458550''>the</span> <span m=''458610''>future,</span> <span m=''459200''>and</span>
  <span m=''459400''>the</span> <span m=''459460''>fact,</span> <span m=''459700''>they</span>
  <span m=''460120''>likely</span> <span m=''460440''>will.</span> <span m=''461210''>But</span>
  <span m=''461350''>a</span> <span m=''461400''>lot</span> <span m=''461560''>of</span>
  <span m=''461620''>that</span> <span m=''461810''>is</span> <span m=''461930''>sort</span>
  <span m=''462110''>of</span> <span m=''462190''>still lacking.</span> </p><p><span
  m=''462950''>So</span> <span m=''463200''>what</span> <span m=''463320''>do</span>
  <span m=''463380''>you</span> <span m=''463460''>do</span> <span m=''463630''>in</span>
  <span m=''463730''>the</span> <span m=''463790''>meantime,</span> <span m=''464970''>In</span>
  <span m=''465090''>the</span> <span m=''465150''>next</span> <span m=''465390''>two</span>
  <span m=''465530''>weeks</span> <span m=''465770''>as</span> <span m=''465810''>you''re</span>
  <span m=''465970''>writing</span> <span m=''466220''>your</span> <span m=''466320''>programs?</span>
  <span m=''467650''>So I''ve</span> <span m=''467870''>looked</span> <span m=''468070''>around</span>
  <span m=''468460''>for</span> <span m=''469560''>some</span> <span m=''470110''>tips</span>
  <span m=''470530''>or</span> <span m=''470730''>some</span> <span m=''470960''>talks
  and</span> <span m=''471560''>lectures</span> <span m=''472090''>and</span> <span
  m=''472520''>what</span> <span m=''472670''>people</span> <span m=''472950''>have</span>
  <span m=''473170''>done</span> <span m=''473380''>in</span> <span m=''473480''>terms</span>
  <span m=''473810''>of</span> <span m=''474600''>improving</span> <span m=''475430''>the</span>
  <span m=''476350''>process</span> <span m=''477250''>for</span> <span m=''477520''>debugging</span>
  <span m=''477930''>parallel</span> <span m=''478340''>codes.</span> <span m=''479280''>Probably</span>
  <span m=''479590''>the</span> <span m=''479680''>best</span> <span m=''479880''>thing</span>
  <span m=''480020''>I''ve</span> <span m=''480080''>found</span> <span m=''480480''>is</span>
  <span m=''481100''>this</span> <span m=''481270''>talk</span> <span m=''481670''>that</span>
  <span m=''481730''>was</span> <span m=''481860''>given</span> <span m=''482160''>at</span>
  <span m=''482210''>University</span> <span m=''482650''>of</span> <span m=''482730''>Maryland</span>
  <span m=''483410''>on</span> <span m=''483730''>defect</span> <span m=''484100''>patterns.</span>
  <span m=''485190''>So</span> <span m=''487450''>the</span> <span m=''487710''>rest</span>
  <span m=''487920''>of</span> <span m=''488020''>these</span> <span m=''488130''>slides</span>
  <span m=''488510''>are</span> <span m=''488910''>largely</span> <span m=''489260''>drawn</span>
  <span m=''489540''>from</span> <span m=''489690''>that</span> <span m=''489850''>talk.</span>
  <span m=''491370''>I''m going to</span> <span m=''491500''>identify</span> <span
  m=''492040''>just</span> <span m=''492280''>a</span> <span m=''492340''>few</span>
  <span m=''492640''>of</span> <span m=''492750''>them to</span> <span m=''493250''>give</span>
  <span m=''493430''>you</span> <span m=''493520''>some</span> <span m=''493680''>examples</span>
  <span m=''494190''>so</span> <span m=''494280''>you</span> <span m=''494410''>can</span>
  <span m=''494550''>understand</span> <span m=''495250''>what</span> <span m=''495440''>to</span>
  <span m=''495570''>look</span> <span m=''495720''>for and</span> <span m=''496330''>what
  are some</span> <span m=''496700''>common</span> <span m=''497030''>symptoms,</span>
  <span m=''497790''>what</span> <span m=''498000''>are</span> <span m=''498070''>some</span>
  <span m=''498270''>common</span> <span m=''498600''>prevention</span> <span m=''499040''>techniques.</span>
  </p><p><span m=''500770''>So</span> <span m=''502320''>defect</span> <span m=''502830''>patterns,</span>
  <span m=''503310''>just</span> <span m=''503480''>like</span> <span m=''503620''>the</span>
  <span m=''503700''>programming</span> <span m=''504160''>patterns</span> <span m=''504540''>we</span>
  <span m=''504660''>talked</span> <span m=''504960''>about,</span> <span m=''505520''>are</span>
  <span m=''505650''>meant</span> <span m=''505910''>to</span> <span m=''505990''>help</span>
  <span m=''506270''>you</span> <span m=''506730''>conjure</span> <span m=''507120''>up</span>
  <span m=''507240''>to</span> <span m=''507320''>write</span> <span m=''507520''>contextual</span>
  <span m=''508030''>information.</span> <span m=''508600''>You</span> <span m=''508720''>had</span>
  <span m=''509780''>what</span> <span m=''509970''>are</span> <span m=''510030''>things</span>
  <span m=''510280''>you</span> <span m=''510350''>should</span> <span m=''510510''>look</span>
  <span m=''510670''>for</span> <span m=''511020''>if</span> <span m=''511130''>you''re</span>
  <span m=''511240''>communicating</span> <span m=''511690''>with</span> <span m=''511790''>somebody</span>
  <span m=''512080''>else.</span> <span m=''513190''>What</span> <span m=''513710''>kind</span>
  <span m=''513890''>of</span> <span m=''513960''>terminology</span> <span m=''514470''>do</span>
  <span m=''514570''>you</span> <span m=''514650''>use</span> <span m=''514900''>so
  that</span> <span m=''515060''>you</span> <span m=''515200''>don''t</span> <span
  m=''515350''>have</span> <span m=''515470''>to</span> <span m=''515560''>explain</span>
  <span m=''515960''>things</span> <span m=''516180''>down</span> <span m=''516410''>to</span>
  <span m=''517250''>every</span> <span m=''517490''>last</span> <span m=''517760''>detail.</span>
  <span m=''520370''>At</span> <span m=''520490''>the</span> <span m=''520580''>end
  of</span> <span m=''520690''>this</span> <span m=''520880''>course,</span> <span
  m=''521280''>one</span> <span m=''521470''>thing</span> <span m=''521630''>I''d</span>
  <span m=''521750''>like</span> <span m=''521940''>to</span> <span m=''522010''>do</span>
  <span m=''522200''>is</span> <span m=''522390''>maybe</span> <span m=''522930''>get</span>
  <span m=''523100''>some</span> <span m=''523230''>feedback</span> <span m=''523630''>from</span>
  <span m=''523780''>each</span> <span m=''523970''>of</span> <span m=''524060''>you
  as</span> <span m=''524540''>to</span> <span m=''524700''>what</span> <span m=''524870''>are</span>
  <span m=''524930''>some</span> <span m=''525090''>of</span> <span m=''525160''>the</span>
  <span m=''525220''>problems</span> <span m=''525610''>that</span> <span m=''525750''>you</span>
  <span m=''525870''>ran</span> <span m=''526090''>into</span> <span m=''526750''>in</span>
  <span m=''526940''>writing</span> <span m=''527240''>your</span> <span m=''527490''>programs,</span>
  <span m=''528330''>and</span> <span m=''528810''>how</span> <span m=''528920''>you</span>
  <span m=''529050''>actually</span> <span m=''529360''>went</span> <span m=''529520''>about</span>
  <span m=''529840''>debugging</span> <span m=''530460''>them,</span> <span m=''530570''>and</span>
  <span m=''530890''>maybe</span> <span m=''531030''>we</span> <span m=''531110''>can</span>
  <span m=''531220''>come</span> <span m=''531370''>up</span> <span m=''531500''>with</span>
  <span m=''531720''>Cell</span> <span m=''532570''>defect</span> <span m=''532980''>patterns,</span>
  <span m=''534150''>and</span> <span m=''534480''>maybe</span> <span m=''534710''>Cell</span>
  <span m=''535050''>defect</span> <span m=''536660''>recipes</span> <span m=''537150''>for</span>
  <span m=''537340''>resolving</span> <span m=''537770''>those</span> <span m=''537870''>defect</span>
  <span m=''538240''>patterns.</span> </p><p><span m=''542050''>So,</span> <span m=''542390''>probably</span>
  <span m=''543140''>the</span> <span m=''543440''>worst</span> <span m=''543910''>one</span>
  <span m=''544040''>of</span> <span m=''544160''>all,</span> <span m=''544950''>and</span>
  <span m=''545250''>the</span> <span m=''545440''>easiest</span> <span m=''545700''>one</span>
  <span m=''545840''>to</span> <span m=''545920''>fix</span> <span m=''546680''>is</span>
  <span m=''546880''>that</span> <span m=''547050''>you</span> <span m=''547170''>have</span>
  <span m=''547900''>new</span> <span m=''548130''>language</span> <span m=''548520''>features</span>
  <span m=''548900''>or</span> <span m=''548980''>new</span> <span m=''549130''>language</span>
  <span m=''549480''>extensions</span> <span m=''550510''>that</span> <span m=''550660''>are</span>
  <span m=''550810''>not</span> <span m=''551110''>well</span> <span m=''551270''>understood.</span>
  <span m=''552050''>This is</span> <span m=''552150''>especially</span> <span m=''552600''>true</span>
  <span m=''552850''>when</span> <span m=''552970''>you</span> <span m=''553060''>take</span>
  <span m=''553600''>a</span> <span m=''553740''>class of</span> <span m=''554580''>students</span>
  <span m=''555290''>and</span> <span m=''556010''>they</span> <span m=''556320''>don''t</span>
  <span m=''556520''>really</span> <span m=''556770''>know</span> <span m=''557400''>the</span>
  <span m=''557520''>language,</span> <span m=''557920''>they don''t know</span> <span
  m=''558190''>all the</span> <span m=''558490''>tools,</span> <span m=''559090''>and</span>
  <span m=''559510''>you</span> <span m=''559580''>ask</span> <span m=''559760''>them</span>
  <span m=''559880''>to</span> <span m=''559990''>do</span> <span m=''560400''>a</span>
  <span m=''560640''>project</span> <span m=''561190''>in</span> <span m=''561400''>four</span>
  <span m=''561780''>weeks</span> <span m=''562330''>and</span> <span m=''563150''>you</span>
  <span m=''563310''>expect</span> <span m=''563600''>things</span> <span m=''563800''>to</span>
  <span m=''563890''>work.</span> <span m=''564120''>So</span> <span m=''564320''>there''s</span>
  <span m=''564490''>a</span> <span m=''564520''>lot</span> <span m=''564730''>for</span>
  <span m=''565220''>everybody</span> <span m=''565630''>to</span> <span m=''566320''>pick</span>
  <span m=''566560''>up</span> <span m=''566720''>and</span> <span m=''566820''>understand.</span>
  </p><p><span m=''568410''>So</span> <span m=''568520''>you</span> <span m=''568600''>might</span>
  <span m=''568780''>have</span> <span m=''569100''>inconsistent</span> <span m=''569810''>types</span>
  <span m=''570510''>that</span> <span m=''570670''>you</span> <span m=''570750''>use</span>
  <span m=''571100''>in</span> <span m=''571260''>terms</span> <span m=''571510''>of</span>
  <span m=''571620''>calling a</span> <span m=''571950''>function.</span> <span m=''573240''>There</span>
  <span m=''573440''>might</span> <span m=''573610''>be</span> <span m=''573810''>alignment</span>
  <span m=''574210''>issues,</span> <span m=''574960''>which</span> <span m=''575180''>some</span>
  <span m=''575330''>of</span> <span m=''575430''>you</span> <span m=''575500''>have</span>
  <span m=''575690''>run</span> <span m=''575850''>into.</span> <span m=''576900''>You</span>
  <span m=''577020''>might</span> <span m=''577170''>use  the</span> <span m=''577400''>wrong</span>
  <span m=''577720''>functions.</span> <span m=''578830''>You</span> <span m=''579030''>know</span>
  <span m=''579200''>the</span> <span m=''579330''>functionality</span> <span m=''579800''>you</span>
  <span m=''579880''>want but</span> <span m=''580230''>you</span> <span m=''580340''>just</span>
  <span m=''580540''>don''t</span> <span m=''580760''>know</span> <span m=''581190''>how</span>
  <span m=''581420''>to</span> <span m=''581480''>name</span> <span m=''581700''>it
  and</span> <span m=''582130''>so</span> <span m=''582320''>you</span> <span m=''582400''>might</span>
  <span m=''582540''>use the</span> <span m=''582750''>wrong</span> <span m=''582980''>function.</span>
  <span m=''584510''>Some</span> <span m=''584700''>of</span> <span m=''584810''>these</span>
  <span m=''585030''>are</span> <span m=''585180''>easy</span> <span m=''585490''>to</span>
  <span m=''585560''>fix</span> <span m=''585900''>because</span> <span m=''586430''>you</span>
  <span m=''586520''>might</span> <span m=''586670''>get</span> <span m=''586820''>a</span>
  <span m=''587300''>compile</span> <span m=''587690''>time</span> <span m=''587880''>error.</span>
  <span m=''588470''>If</span> <span m=''588610''>you</span> <span m=''588690''>have</span>
  <span m=''588920''>mismatch</span> <span m=''589370''>in</span> <span m=''589780''>function</span>
  <span m=''590110''>parameters</span> <span m=''590360''>then</span> <span m=''590960''>you</span>
  <span m=''591150''>can</span> <span m=''591260''>fix</span> <span m=''591480''>that</span>
  <span m=''591630''>very</span> <span m=''591790''>easily.</span> <span m=''592840''>Some</span>
  <span m=''593110''>defects</span> <span m=''593790''>--</span> <span m=''594380''>you</span>
  <span m=''594480''>know,</span> <span m=''594580''>very</span> <span m=''594810''>natural</span>
  <span m=''595140''>parallel programs</span> <span m=''595780''>might</span> <span
  m=''596000''>not</span> <span m=''596220''>come</span> <span m=''596420''>up</span>
  <span m=''596570''>until</span> <span m=''596860''>run</span> <span m=''597050''>time,</span>
  <span m=''597680''>so</span> <span m=''597820''>you</span> <span m=''597900''>might</span>
  <span m=''598080''>end</span> <span m=''598230''>up</span> <span m=''598390''>with</span>
  <span m=''598730''>crashes</span> <span m=''599440''>or</span> <span m=''599670''>just</span>
  <span m=''599860''>erroneous</span> <span m=''600290''>behavior.</span> <span m=''602220''>I</span>
  <span m=''602440''>really</span> <span m=''602680''>think</span> <span m=''602820''>this
  is</span> <span m=''602960''>probably the</span> <span m=''603280''>easiest</span>
  <span m=''603700''>one to</span> <span m=''603840''>fix,</span> <span m=''604560''>and</span>
  <span m=''604810''>the</span> <span m=''604870''>prevention</span> <span m=''605480''>technique</span>
  <span m=''605970''>that</span> <span m=''606800''>I</span> <span m=''607030''>would</span>
  <span m=''607140''>recommend</span> <span m=''607610''>is</span> <span m=''609000''>if</span>
  <span m=''609340''>there''s</span> <span m=''609510''>something you''re</span> <span
  m=''609870''>unfamiliar</span> <span m=''610400''>about</span> <span m=''611100''>or</span>
  <span m=''611360''>you''re</span> <span m=''611520''>not</span> <span m=''611670''>sure</span>
  <span m=''611910''>about</span> <span m=''612110''>how</span> <span m=''612230''>to</span>
  <span m=''612330''>use</span> <span m=''612460''>something,</span> <span m=''613060''>ask.</span>
  <span m=''613830''>But</span> <span m=''613980''>also,</span> <span m=''615390''>you
  don''t</span> <span m=''615580''>need</span> <span m=''615730''>to</span> <span
  m=''615810''>know</span> <span m=''616080''>all</span> <span m=''616350''>the</span>
  <span m=''616430''>functions</span> <span m=''616830''>that</span> <span m=''616930''>are</span>
  <span m=''617020''>available</span> <span m=''617580''>in</span> <span m=''619130''>something</span>
  <span m=''619430''>like</span> <span m=''619940''>the</span> <span m=''620050''>Cell</span>
  <span m=''620230''>language</span> <span m=''620600''>extensions</span> <span m=''621080''>for</span>
  <span m=''621200''>C.</span> </p><p><span m=''622440''>Yes,</span> <span m=''622720''>there</span>
  <span m=''622850''>are</span> <span m=''622970''>a</span> <span m=''623000''>lot</span>
  <span m=''623150''>of</span> <span m=''623230''>functions --</span> <span m=''623590''>you</span>
  <span m=''623680''>know, the</span> <span m=''623760''>manuals,</span> <span m=''624450''>hundreds</span>
  <span m=''624780''>of</span> <span m=''624880''>pages,</span> <span m=''625660''>and</span>
  <span m=''626080''>you</span> <span m=''626200''>can''t</span> <span m=''626410''>possibly</span>
  <span m=''626790''>go</span> <span m=''626890''>through</span> <span m=''627100''>it</span>
  <span m=''627210''>all</span> <span m=''627410''>and</span> <span m=''627510''>nobody</span>
  <span m=''627740''>becomes</span> <span m=''628060''>an</span> <span m=''628150''>expert</span>
  <span m=''628520''>in</span> <span m=''628600''>everything.</span> <span m=''629280''>But</span>
  <span m=''629490''>understand</span> <span m=''630020''>just</span> <span m=''630190''>a</span>
  <span m=''630240''>few</span> <span m=''630460''>basic</span> <span m=''630800''>concepts</span>
  <span m=''631450''>and</span> <span m=''631720''>features.</span> <span m=''632500''>So,</span>
  <span m=''633500''>David</span> <span m=''633950''>identified</span> <span m=''634770''>a</span>
  <span m=''635120''>bunch</span> <span m=''635400''>that</span> <span m=''635540''>he</span>
  <span m=''635680''>found</span> <span m=''636200''>useful</span> <span m=''636560''>for</span>
  <span m=''636730''>writing</span> <span m=''637330''>the</span> <span m=''637390''>programs,</span>
  <span m=''638750''>and</span> <span m=''639010''>some</span> <span m=''639160''>of</span>
  <span m=''639220''>the</span> <span m=''639280''>ones</span> <span m=''639560''>that</span>
  <span m=''640330''>are</span> <span m=''640850''>up</span> <span m=''641070''>on</span>
  <span m=''641690''>the</span> <span m=''641850''>web</span> <span m=''642080''>page</span>
  <span m=''642380''>under</span> <span m=''642540''>the</span> <span m=''642630''>recipes</span>
  <span m=''643300''>for</span> <span m=''643860''>this</span> <span m=''644010''>course</span>
  <span m=''645910''>list</span> <span m=''646140''>a</span> <span m=''646190''>few</span>
  <span m=''646380''>more.</span> <span m=''647210''>And so</span> <span m=''647840''>this</span>
  <span m=''648020''>might</span> <span m=''648210''>help</span> <span m=''648410''>you</span>
  <span m=''648650''>in</span> <span m=''648790''>just</span> <span m=''649000''>understanding</span>
  <span m=''649930''>how</span> <span m=''650270''>these</span> <span m=''650760''>functions</span>
  <span m=''651100''>work,</span> <span m=''651540''>understanding</span> <span m=''652040''>basic</span>
  <span m=''652380''>mechanisms</span> <span m=''652870''>that</span> <span m=''652980''>they</span>
  <span m=''653070''>give</span> <span m=''653290''>you,</span> <span m=''653620''>and</span>
  <span m=''653850''>that''s</span> <span m=''654040''>good</span> <span m=''654200''>enough</span>
  <span m=''654440''>because</span> <span m=''654690''>it''ll</span> <span m=''654810''>help</span>
  <span m=''655040''>you</span> <span m=''655130''>get</span> <span m=''655300''>by.</span>
  <span m=''655790''>Certainly</span> <span m=''656110''>for</span> <span m=''656510''>doing</span>
  <span m=''657330''>the</span> <span m=''657440''>project</span> <span m=''658230''>under</span>
  <span m=''658770''>short</span> <span m=''659060''>time</span> <span m=''659250''>constraints,</span>
  <span m=''659880''>you don''t</span> <span m=''660020''>need</span> <span m=''660220''>to</span>
  <span m=''660310''>know</span> <span m=''660490''>all</span> <span m=''660700''>the</span>
  <span m=''660890''>advanced</span> <span m=''661080''>features</span> <span m=''661570''>that</span>
  <span m=''661740''>Cell</span> <span m=''661830''>might</span> <span m=''661980''>have.</span>
  <span m=''662940''>Or</span> <span m=''663150''>you</span> <span m=''663280''>can</span>
  <span m=''663650''>probably</span> <span m=''663920''>just</span> <span m=''664120''>pick</span>
  <span m=''664300''>them</span> <span m=''664440''>up</span> <span m=''664560''>on</span>
  <span m=''664690''>the</span> <span m=''664760''>fly</span> <span m=''665040''>as</span>
  <span m=''665260''>you</span> <span m=''665360''>need</span> <span m=''665580''>them.</span>
  </p><p><span m=''667550''>So</span> <span m=''667700''>what</span> <span m=''668070''>are</span>
  <span m=''668160''>some</span> <span m=''668330''>more</span> <span m=''668580''>interesting</span>
  <span m=''669010''>problems</span> <span m=''669700''>that</span> <span m=''669850''>come</span>
  <span m=''670040''>up.</span> <span m=''670980''>I</span> <span m=''671060''>think</span>
  <span m=''671680''>one</span> <span m=''672250''>that</span> <span m=''672490''>is</span>
  <span m=''672710''>probably</span> <span m=''673190''>not</span> <span m=''673420''>too</span>
  <span m=''673520''>unfamiliar</span> <span m=''674140''>is</span> <span m=''674390''>this</span>
  <span m=''674560''>space</span> <span m=''675030''>decomposition</span> <span m=''675610''>problems.</span>
  <span m=''676760''>So,</span> <span m=''676930''>if</span> <span m=''677030''>you</span>
  <span m=''677110''>remember,</span> <span m=''677480''>space</span> <span m=''677820''>decomposition</span>
  <span m=''678590''>is</span> <span m=''678730''>really</span> <span m=''678970''>data</span>
  <span m=''679210''>distribution.</span> <span m=''680230''>You</span> <span m=''680370''>have</span>
  <span m=''680680''>a</span> <span m=''680760''>serial</span> <span m=''681080''>program</span>
  <span m=''681880''>that</span> <span m=''682060''>you</span> <span m=''682180''>want</span>
  <span m=''682420''>to</span> <span m=''682580''>parallelize.</span> <span m=''683320''>And</span>
  <span m=''683660''>what</span> <span m=''683780''>that</span> <span m=''683940''>means</span>
  <span m=''684180''>if</span> <span m=''684280''>you</span> <span m=''684390''>have</span>
  <span m=''684530''>to</span> <span m=''684610''>actually</span> <span m=''684960''>send</span>
  <span m=''685230''>data</span> <span m=''685450''>around</span> <span m=''685790''>to</span>
  <span m=''685880''>different</span> <span m=''686160''>processors</span> <span m=''686990''>so</span>
  <span m=''687190''>that</span> <span m=''687330''>each</span> <span m=''687530''>one</span>
  <span m=''687980''>knows</span> <span m=''688240''>how</span> <span m=''688360''>to</span>
  <span m=''688450''>compute</span> <span m=''688810''>locally.</span> <span m=''691030''>Here</span>
  <span m=''691350''>you</span> <span m=''691460''>might</span> <span m=''691650''>get</span>
  <span m=''691820''>things</span> <span m=''692100''>like</span> <span m=''692380''>segmentation</span>
  <span m=''692940''>faults,</span> <span m=''693640''>alignment</span> <span m=''694440''>problems,</span>
  <span m=''695280''>you</span> <span m=''695430''>might</span> <span m=''695530''>have</span>
  <span m=''695900''>index</span> <span m=''696240''>out</span> <span m=''696420''>of</span>
  <span m=''696710''>range</span> <span m=''697050''>errors.</span> <span m=''699650''>What</span>
  <span m=''699850''>this</span> <span m=''700010''>comes</span> <span m=''700260''>of</span>
  <span m=''700520''>is</span> <span m=''701730''>forgetting</span> <span m=''702220''>to</span>
  <span m=''702310''>change</span> <span m=''702600''>things</span> <span m=''702810''>or</span>
  <span m=''702900''>overlooking</span> <span m=''703510''>some</span> <span m=''703740''>simple</span>
  <span m=''704030''>things</span> <span m=''704320''>that</span> <span m=''704430''>don''t</span>
  <span m=''704630''>carryover</span> <span m=''705160''>from</span> <span m=''705350''>the</span>
  <span m=''705420''>sequential</span> <span m=''705880''>case</span> <span m=''706250''>that</span>
  <span m=''706340''>are</span> <span m=''706380''>parallel</span> <span m=''706740''>case.</span>
  <span m=''707670''>So</span> <span m=''707840''>what</span> <span m=''707960''>you</span>
  <span m=''708030''>might</span> <span m=''708200''>want to</span> <span m=''708410''>do</span>
  <span m=''708550''>is</span> <span m=''708900''>validate</span> <span m=''709360''>your</span>
  <span m=''709480''>distributions</span> <span m=''710200''>and</span> <span m=''710340''>your</span>
  <span m=''710420''>memory</span> <span m=''710680''>partitions</span> <span m=''711560''>correctly.</span>
  <span m=''711980''>So</span> <span m=''712300''>what''s</span> <span m=''712620''>an</span>
  <span m=''712710''>example?</span> </p><p><span m=''714970''>So</span> <span m=''715170''>suppose</span>
  <span m=''715510''>you</span> <span m=''715610''>had</span> <span m=''716760''>an</span>
  <span m=''716890''>array</span> <span m=''717600''>or</span> <span m=''718110''>a</span>
  <span m=''718240''>list</span> <span m=''718570''>of</span> <span m=''718700''>cells,</span>
  <span m=''719610''>each</span> <span m=''719740''>cell</span> <span m=''719980''>has</span>
  <span m=''720150''>a</span> <span m=''720210''>number.</span> <span m=''721120''>What</span>
  <span m=''721220''>you</span> <span m=''721290''>want to</span> <span m=''721510''>do</span>
  <span m=''721700''>is</span> <span m=''722800''>at</span> <span m=''723020''>each</span>
  <span m=''723130''>step</span> <span m=''723240''>of the</span> <span m=''723280''>computation</span>
  <span m=''724230''>for</span> <span m=''724420''>any</span> <span m=''724670''>given</span>
  <span m=''724930''>cell,</span> <span m=''725270''>you</span> <span m=''725450''>want</span>
  <span m=''725720''>add</span> <span m=''726290''>the</span> <span m=''726410''>value</span>
  <span m=''726750''>to</span> <span m=''726860''>the</span> <span m=''726930''>left</span>
  <span m=''727160''>of</span> <span m=''727220''>it</span> <span m=''727550''>and</span>
  <span m=''727700''>the</span> <span m=''727760''>value</span> <span m=''728130''>to
  the right of it.</span> <span m=''729210''>So</span> <span m=''729500''>here</span>
  <span m=''729680''>we</span> <span m=''729980''>have cell</span> <span m=''730130''>zero</span>
  <span m=''730470''>has the</span> <span m=''730720''>value</span> <span m=''731060''>2.</span>
  <span m=''731660''>We''ll</span> <span m=''731950''>assume</span> <span m=''732330''>that</span>
  <span m=''732450''>the</span> <span m=''732560''>n</span> <span m=''732730''>disconnectors</span>
  <span m=''733240''>are</span> <span m=''733330''>first,</span> <span m=''733630''>so</span>
  <span m=''733730''>this</span> <span m=''733890''>is</span> <span m=''734010''>like</span>
  <span m=''734150''>a</span> <span m=''734220''>circular</span> <span m=''734640''>list,</span>
  <span m=''735800''>a</span> <span m=''735900''>circular</span> <span m=''736270''>buffer.</span>
  <span m=''737910''>So</span> <span m=''738170''>adding</span> <span m=''739810''>the</span>
  <span m=''740150''>left</span> <span m=''740420''>and</span> <span m=''740530''>right</span>
  <span m=''740710''>neighbor</span> <span m=''741030''>would</span> <span m=''741180''>get</span>
  <span m=''741370''>me,</span> <span m=''741880''>in this</span> <span m=''742060''>case,</span>
  <span m=''742300''>3</span> <span m=''742510''>plus</span> <span m=''742730''>1,</span>
  <span m=''742980''>4.</span> <span m=''744600''>And</span> <span m=''744940''>so</span>
  <span m=''745090''>on</span> <span m=''745270''>and</span> <span m=''745370''>so</span>
  <span m=''745550''>forth.</span> <span m=''746570''>You</span> <span m=''746640''>want
  to</span> <span m=''746830''>repeat</span> <span m=''747150''>this</span> <span
  m=''747260''>computation</span> <span m=''747910''>for</span> <span m=''748040''>n</span>
  <span m=''748240''>steps.</span> <span m=''748710''>So this</span> <span m=''748890''>might</span>
  <span m=''749090''>be</span> <span m=''749210''>very</span> <span m=''749420''>common</span>
  <span m=''749800''>in</span> <span m=''750360''>computations</span> <span m=''750890''>where</span>
  <span m=''751010''>you''re</span> <span m=''751100''>doing</span> <span m=''751300''>unit</span>
  <span m=''751630''>[? book ?]</span> <span m=''751720''>communication.</span> </p><p><span
  m=''754190''>So</span> <span m=''754480''>what''s</span> <span m=''754770''>a</span>
  <span m=''754860''>straightforward</span> <span m=''755710''>sequential</span> <span
  m=''756330''>implementation?</span> <span m=''757560''>Well,</span> <span m=''758430''>you</span>
  <span m=''758560''>can</span> <span m=''758660''>use</span> <span m=''758830''>two</span>
  <span m=''759020''>buffers --</span> <span m=''759850''>one</span> <span m=''760050''>for</span>
  <span m=''760170''>the</span> <span m=''760250''>current</span> <span m=''760470''>time</span>
  <span m=''760680''>step,</span> <span m=''761340''>and</span> <span m=''761780''>you</span>
  <span m=''761880''>do</span> <span m=''761990''>all</span> <span m=''762150''>the</span>
  <span m=''762220''>calculations</span> <span m=''762750''>in that.</span> <span
  m=''763330''>Then</span> <span m=''764320''>you</span> <span m=''764930''>use</span>
  <span m=''765830''>another</span> <span m=''766400''>buffer</span> <span m=''766670''>for</span>
  <span m=''766840''>next</span> <span m=''767170''>time</span> <span m=''767380''>step.</span>
  <span m=''767970''>Then</span> <span m=''768060''>you</span> <span m=''768170''>swap</span>
  <span m=''768460''>the</span> <span m=''768550''>two.</span> <span m=''770530''>So</span>
  <span m=''770740''>the</span> <span m=''770870''>code</span> <span m=''771150''>might</span>
  <span m=''771390''>look</span> <span m=''771620''>something</span> <span m=''771890''>like</span>
  <span m=''772050''>this.</span> <span m=''772830''>Sequential</span> <span m=''773290''>c</span>
  <span m=''773480''>code,</span> <span m=''774370''>my</span> <span m=''774530''>two</span>
  <span m=''774780''>buffers,</span> <span m=''775400''>here''s</span> <span m=''775690''>my</span>
  <span m=''775840''>loop.</span> <span m=''776470''>I</span> <span m=''776610''>write</span>
  <span m=''776830''>into</span> <span m=''777040''>one</span> <span m=''777260''>buffer</span>
  <span m=''777990''>and</span> <span m=''778180''>then</span> <span m=''778510''>I</span>
  <span m=''778640''>switch</span> <span m=''778960''>the</span> <span m=''779030''>two</span>
  <span m=''779160''>buffers</span> <span m=''779510''>around.</span> </p><p><span
  m=''780380''>Any</span> <span m=''780540''>questions</span> <span m=''780920''>so
  far?</span> </p><p><span m=''783450''>So</span> <span m=''783580''>now,</span> <span
  m=''784150''>what</span> <span m=''784290''>are</span> <span m=''784350''>some</span>
  <span m=''784500''>things</span> <span m=''784720''>that</span> <span m=''784820''>can</span>
  <span m=''784930''>go</span> <span m=''785060''>wrong</span> <span m=''786680''>when</span>
  <span m=''786840''>you</span> <span m=''786930''>try to</span> <span m=''787140''>parallelize</span>
  <span m=''787630''>this?</span> <span m=''791060''>So</span> <span m=''791210''>how</span>
  <span m=''791310''>would</span> <span m=''791450''>you</span> <span m=''791530''>actually</span>
  <span m=''791860''>parallelize</span> <span m=''792400''>this code?</span> <span
  m=''793580''>Well,</span> <span m=''793870''>we</span> <span m=''793990''>saw</span>
  <span m=''794260''>in</span> <span m=''794460''>some</span> <span m=''794620''>of</span>
  <span m=''794720''>your</span> <span m=''794850''>labs,</span> <span m=''795240''>for</span>
  <span m=''795380''>example,</span> <span m=''795750''>that</span> <span m=''795870''>you</span>
  <span m=''795990''>can</span> <span m=''796110''>take</span> <span m=''796310''>a</span>
  <span m=''796360''>big</span> <span m=''796550''>array,</span> <span m=''796940''>split
  it</span> <span m=''797090''>up</span> <span m=''797260''>in</span> <span m=''797330''>smaller</span>
  <span m=''797690''>chunks</span> <span m=''798450''>and</span> <span m=''798620''>assign</span>
  <span m=''799020''>each</span> <span m=''799280''>chunk</span> <span m=''800070''>to</span>
  <span m=''800260''>one</span> <span m=''800480''>particular</span> <span m=''800790''>processor.</span>
  <span m=''801450''>So</span> <span m=''801600''>we</span> <span m=''801710''>can</span>
  <span m=''801850''>use</span> <span m=''802010''>that</span> <span m=''802130''>technique</span>
  <span m=''802450''>here.</span> <span m=''803610''>So</span> <span m=''803810''>each</span>
  <span m=''804080''>processor,</span> <span m=''805390''>we</span> <span m=''805510''>have</span>
  <span m=''805680''>n</span> <span m=''805850''>of</span> <span m=''805940''>them,</span>
  <span m=''807160''>rather</span> <span m=''807390''>size</span> <span m=''807690''>of</span>
  <span m=''807760''>them,</span> <span m=''808540''>and</span> <span m=''809230''>it''s</span>
  <span m=''809390''>going to</span> <span m=''809590''>get</span> <span m=''809780''>some</span>
  <span m=''810000''>number</span> <span m=''810230''>of</span> <span m=''810370''>elements.</span>
  <span m=''812000''>So</span> <span m=''812180''>each</span> <span m=''812410''>time</span>
  <span m=''812640''>step,</span> <span m=''813130''>we</span> <span m=''813230''>have</span>
  <span m=''813340''>to</span> <span m=''813430''>compute</span> <span m=''813910''>locally</span>
  <span m=''814780''>all</span> <span m=''814960''>the</span> <span m=''815060''>communications,</span>
  <span m=''815740''>but</span> <span m=''815870''>then</span> <span m=''816060''>there''s</span>
  <span m=''816520''>some</span> <span m=''817060''>special</span> <span m=''817420''>cases</span>
  <span m=''817870''>that</span> <span m=''817980''>we</span> <span m=''818050''>need</span>
  <span m=''818170''>to</span> <span m=''818240''>treat</span> <span m=''818560''>at</span>
  <span m=''818710''>the</span> <span m=''818790''>boundaries,</span> <span m=''819150''>right.</span>
  <span m=''820270''>So</span> <span m=''820400''>if</span> <span m=''820490''>I</span>
  <span m=''820570''>have</span> <span m=''820840''>this</span> <span m=''821000''>chunk</span>
  <span m=''821330''>and</span> <span m=''821450''>I</span> <span m=''821480''>need</span>
  <span m=''821660''>to</span> <span m=''821750''>do</span> <span m=''821860''>my</span>
  <span m=''821990''>new</span> <span m=''822190''>neighbor</span> <span m=''822430''>communication,</span>
  <span m=''823340''>I</span> <span m=''823450''>don''t</span> <span m=''823640''>have</span>
  <span m=''823820''>this</span> <span m=''823950''>particular</span> <span m=''824380''>cells.</span>
  <span m=''824800''>I</span> <span m=''824880''>have</span> <span m=''825000''>to</span>
  <span m=''825110''>go</span> <span m=''825240''>out there</span> <span m=''825420''>and</span>
  <span m=''825600''>request</span> <span m=''825970''>it.</span> <span m=''827230''>Similarly,</span>
  <span m=''827610''>somebody</span> <span m=''827890''>has</span> <span m=''828090''>to</span>
  <span m=''828180''>send</span> <span m=''828400''>me</span> <span m=''828750''>this</span>
  <span m=''828890''>particular</span> <span m=''829300''>data</span> <span m=''829470''>item.</span>
  <span m=''829960''>So</span> <span m=''830130''>there''s</span> <span m=''830330''>some</span>
  <span m=''830650''>data</span> <span m=''830890''>exchange</span> <span m=''831290''>that</span>
  <span m=''832150''>has</span> <span m=''832340''>to</span> <span m=''832420''>happen.</span>
  </p><p><span m=''834890''>So</span> <span m=''835200''>in</span> <span m=''835310''>the</span>
  <span m=''835390''>decomposition,</span> <span m=''837020''>you</span> <span m=''837220''>write</span>
  <span m=''837290''>your</span> <span m=''837410''>parallel</span> <span m=''837780''>code.</span>
  <span m=''839300''>Here,</span> <span m=''839600''>each</span> <span m=''839830''>buffer</span>
  <span m=''840680''>is</span> <span m=''840810''>a</span> <span m=''840870''>different</span>
  <span m=''841190''>size.</span> <span m=''841930''>What</span> <span m=''842100''>you</span>
  <span m=''842180''>do</span> <span m=''842380''>is</span> <span m=''842690''>you</span>
  <span m=''842900''>have</span> <span m=''843300''>some</span> <span m=''843620''>local,</span>
  <span m=''844640''>which</span> <span m=''844860''>says</span> <span m=''845160''>this</span>
  <span m=''845290''>is</span> <span m=''845400''>how</span> <span m=''845550''>much</span>
  <span m=''845870''>of</span> <span m=''845980''>the</span> <span m=''846050''>data</span>
  <span m=''846180''>I''m</span> <span m=''846340''>getting,</span> <span m=''847210''>and</span>
  <span m=''847450''>has a</span> <span m=''847630''>total</span> <span m=''848120''>number</span>
  <span m=''848430''>of</span> <span m=''848510''>elements,</span> <span m=''849110''>besides
  the</span> <span m=''849490''>number of</span> <span m=''849730''>processors.</span>
  <span m=''851490''>Local</span> <span m=''851840''>essentially</span> <span m=''852210''>tells</span>
  <span m=''852450''>me</span> <span m=''852540''>the</span> <span m=''852620''>size</span>
  <span m=''852890''>of</span> <span m=''852950''>my</span> <span m=''853080''>chunk.</span>
  <span m=''854540''>I''m</span> <span m=''854670''>iterating</span> <span m=''855140''>through</span>
  <span m=''855400''>from</span> <span m=''855760''>zero</span> <span m=''856360''>and</span>
  <span m=''856470''>local</span> <span m=''857070''>and</span> <span m=''857270''>I''m</span>
  <span m=''857360''>doing</span> <span m=''857900''>essentially</span> <span m=''858250''>the</span>
  <span m=''858320''>same</span> <span m=''858530''>computation.</span> <span m=''859710''>So</span>
  <span m=''860020''>what''s</span> <span m=''860230''>a</span> <span m=''860290''>bug</span>
  <span m=''860670''>in</span> <span m=''860760''>here?</span> <span m=''861400''>Anybody</span>
  <span m=''861770''>see it?</span> <span m=''862260''>Sort</span> <span m=''862460''>of</span>
  <span m=''862820''>giving you</span> <span m=''863120''>some</span> <span m=''863270''>hints</span>
  <span m=''863510''>of</span> <span m=''863620''>things</span> <span m=''864000''>highlighted</span>
  <span m=''864430''>in</span> <span m=''864520''>red or</span> <span m=''865040''>there''s</span>
  <span m=''865300''>something</span> <span m=''865600''>wrong</span> <span m=''865780''>with</span>
  <span m=''865880''>the</span> <span m=''865950''>things</span> <span m=''866170''>highlighted
  in</span> <span m=''866620''>red.</span> <span m=''876790''>There''s</span> <span
  m=''877110''>another</span> <span m=''877370''>hint.</span> <span m=''878090''>So</span>
  <span m=''878330''>this</span> <span m=''878510''>is</span> <span m=''878730''>essentially</span>
  <span m=''879050''>the</span> <span m=''879130''>computations</span> <span m=''879740''>going</span>
  <span m=''879970''>on at</span> <span m=''880160''>every</span> <span m=''880330''>processor,</span>
  <span m=''881140''>this</span> <span m=''881300''>is</span> <span m=''881430''>my</span>
  <span m=''881550''>buffer,</span> <span m=''882510''>and</span> <span m=''883220''>at</span>
  <span m=''883360''>every</span> <span m=''883570''>step</span> <span m=''883850''>I</span>
  <span m=''883880''>have</span> <span m=''884030''>to</span> <span m=''884130''>do</span>
  <span m=''884230''>the</span> <span m=''884300''>calculations,</span> <span m=''884970''>taking</span>
  <span m=''885190''>care</span> <span m=''885450''>of</span> <span m=''885790''>the</span>
  <span m=''885910''>boundary</span> <span m=''886210''>edges.</span> <span m=''891840''>Anybody</span>
  <span m=''892190''>want</span> <span m=''892380''>to</span> <span m=''892780''>take</span>
  <span m=''893020''>a</span> <span m=''893250''>stab?</span> <span m=''895100''>Mark?</span>
  </p><p><span m=''895450''>AUDIENCE:</span> <span m=''896425''>Is</span> <span m=''896913''>it
  that</span> <span m=''897401''>the nextbuffer</span> <span m=''898377''>zero</span>
  <span m=''899353''>needs</span> <span m=''900328''>to look at data from 1?</span>
  </p><p><span m=''904720''>PROFESSOR: Next</span> <span m=''905030''>buffer</span>
  <span m=''905320''>zero,</span> <span m=''905980''>right.</span> <span m=''906820''>So</span>
  <span m=''907620''>what</span> <span m=''907800''>might</span> <span m=''907940''>be
  a</span> <span m=''908090''>fix</span> <span m=''908360''>to that?</span> <span
  m=''912910''>So the  next</span> <span m=''913220''>buffer is</span> <span m=''913930''>zero.</span>
  <span m=''914810''>So if</span> <span m=''915110''>this is</span> <span m=''915230''>zero</span>
  <span m=''915980''>then</span> <span m=''916640''>buffer of x</span> <span m=''917290''>minus</span>
  <span m=''917700''>1</span> <span m=''918590''>plus</span> <span m=''918850''>this</span>
  <span m=''919090''>points</span> <span m=''919410''>to</span> <span m=''919520''>what?</span>
  </p><p><span m=''923160''>AUDIENCE:</span> <span m=''923235''>So you need to  start</span>
  <span m=''923310''>at</span> <span m=''923753''>1</span> <span m=''924196''>and
  iterate.</span> </p><p><span m=''924640''>PROFESSOR: Right,</span> <span m=''925610''>exactly.</span>
  <span m=''926840''>It''s</span> <span m=''926970''>a</span> <span m=''927030''>local</span>
  <span m=''927280''>plus</span> <span m=''927610''>1,</span> <span m=''928850''>if</span>
  <span m=''929310''>you were</span> <span m=''929440''>going</span> <span m=''929560''>to</span>
  <span m=''929630''>do</span> <span m=''929730''>these.</span> <span m=''930780''>So</span>
  <span m=''931270''>that''s</span> <span m=''931550''>one</span> <span m=''931780''>bug.</span>
  <span m=''932150''>The</span> <span m=''932250''>other</span> <span m=''932400''>thing</span>
  <span m=''932670''>is</span> <span m=''933040''>the</span> <span m=''933120''>assumption</span>
  <span m=''933590''>that</span> <span m=''934200''>your</span> <span m=''934500''>data</span>
  <span m=''934810''>elements</span> <span m=''935730''>might</span> <span m=''935980''>be</span>
  <span m=''936140''>divisible</span> <span m=''936590''>by</span> <span m=''936890''>the</span>
  <span m=''936960''>number of</span> <span m=''937180''>processors</span> <span m=''937650''>that</span>
  <span m=''937800''>you</span> <span m=''937890''>have.</span> <span m=''938130''>So</span>
  <span m=''938230''>you</span> <span m=''938310''>pick</span> <span m=''938520''>the</span>
  <span m=''938610''>decomposition</span> <span m=''939670''>that</span> <span m=''939810''>might</span>
  <span m=''939990''>not</span> <span m=''940260''>be</span> <span m=''940430''>symmetric</span>
  <span m=''940880''>across</span> <span m=''941190''>all</span> <span m=''941340''>processors.</span>
  <span m=''942110''>So</span> <span m=''942290''>it''s</span> <span m=''942460''>more</span>
  <span m=''942700''>subtle,</span> <span m=''943190''>I</span> <span m=''943430''>think,</span>
  <span m=''944640''>to</span> <span m=''944770''>keep</span> <span m=''945760''>in</span>
  <span m=''945830''>mind.</span> <span m=''946320''>So</span> <span m=''946720''>that''s</span>
  <span m=''946920''>one</span> <span m=''947100''>particular</span> <span m=''947440''>kind</span>
  <span m=''947650''>of</span> <span m=''947740''>problem</span> <span m=''948070''>that</span>
  <span m=''948180''>might</span> <span m=''948320''>come</span> <span m=''948490''>up</span>
  <span m=''948640''>on</span> <span m=''948730''>your</span> <span m=''948860''>decomposing</span>
  <span m=''949510''>data</span> <span m=''950110''>and</span> <span m=''950240''>replicating</span>
  <span m=''950720''>among</span> <span m=''951030''>different</span> <span m=''951350''>processors.</span>
  <span m=''952610''>So</span> <span m=''952720''>you</span> <span m=''952790''>have</span>
  <span m=''952910''>to</span> <span m=''953010''>be</span> <span m=''953110''>careful</span>
  <span m=''953510''>about</span> <span m=''954530''>what</span> <span m=''954660''>are</span>
  <span m=''954740''>your</span> <span m=''955820''>boundary</span> <span m=''956380''>cases</span>
  <span m=''957080''>going</span> <span m=''957300''>to</span> <span m=''957390''>be</span>
  <span m=''957550''>and</span> <span m=''957680''>how</span> <span m=''957780''>are</span>
  <span m=''957850''>you</span> <span m=''957910''>going</span> <span m=''958060''>to</span>
  <span m=''958170''>deal</span> <span m=''958300''>with</span> <span m=''958440''>those.</span>
  </p><p><span m=''960650''>The</span> <span m=''961830''>more</span> <span m=''962170''>difficult</span>
  <span m=''962600''>one is</span> <span m=''962970''>synchronization.</span> <span
  m=''963870''>So</span> <span m=''964110''>synchronization is</span> <span m=''964910''>when</span>
  <span m=''965080''>you''re</span> <span m=''965610''>sending</span> <span m=''965950''>data</span>
  <span m=''966220''>from</span> <span m=''966420''>one</span> <span m=''966630''>processor</span>
  <span m=''967100''>to</span> <span m=''967240''>the</span> <span m=''967400''>other</span>
  <span m=''967820''>and</span> <span m=''968270''>you</span> <span m=''968340''>might</span>
  <span m=''968510''>end</span> <span m=''968650''>up</span> <span m=''968770''>with</span>
  <span m=''968870''>deadlock,</span> <span m=''969530''>because one</span> <span
  m=''969780''>is</span> <span m=''969840''>trying</span> <span m=''970080''>to</span>
  <span m=''970160''>send,</span> <span m=''970650''>the</span> <span m=''970740''>other''s</span>
  <span m=''970950''>trying</span> <span m=''971360''>to send,</span> <span m=''971920''>and</span>
  <span m=''972040''>neither</span> <span m=''972230''>can</span> <span m=''972370''>make</span>
  <span m=''972530''>progress</span> <span m=''972920''>until</span> <span m=''973170''>the</span>
  <span m=''973280''>other''s</span> <span m=''973540''>received.</span> <span m=''975020''>So</span>
  <span m=''975150''>your</span> <span m=''975240''>program</span> <span m=''975620''>hangs,</span>
  <span m=''976080''>you</span> <span m=''976210''>get</span> <span m=''978050''>non-deterministic</span>
  <span m=''978790''>behavior or</span> <span m=''979390''>output,</span> <span m=''980730''>every</span>
  <span m=''980920''>time</span> <span m=''981130''>you</span> <span m=''981190''>run</span>
  <span m=''981330''>your</span> <span m=''981390''>program</span> <span m=''981850''>you</span>
  <span m=''981920''>get a</span> <span m=''982110''>different</span> <span m=''982390''>result</span>
  <span m=''983140''>--</span> <span m=''983390''>that</span> <span m=''983520''>can</span>
  <span m=''983660''>drive</span> <span m=''983870''>you</span> <span m=''983990''>crazy.</span>
  <span m=''984910''>So</span> <span m=''985270''>some of</span> <span m=''985400''>the</span>
  <span m=''985570''>defects</span> <span m=''985900''>can</span> <span m=''986020''>be</span>
  <span m=''986130''>very</span> <span m=''986350''>subtle.</span> <span m=''987910''>This
  is</span> <span m=''988070''>probably</span> <span m=''988370''>where</span> <span
  m=''988540''>you''ll</span> <span m=''988730''>spend</span> <span m=''988950''>most</span>
  <span m=''989160''>of</span> <span m=''989220''>your</span> <span m=''989350''>time</span>
  <span m=''989560''>trying</span> <span m=''989750''>to</span> <span m=''989810''>figure</span>
  <span m=''990050''>it</span> <span m=''990150''>out.</span> <span m=''992400''>So</span>
  <span m=''992570''>one</span> <span m=''992720''>of</span> <span m=''992800''>the</span>
  <span m=''992860''>ways</span> <span m=''993070''>to</span> <span m=''993590''>prevent</span>
  <span m=''994130''>this</span> <span m=''994270''>is to</span> <span m=''994430''>actually</span>
  <span m=''994820''>look</span> <span m=''995030''>at</span> <span m=''995100''>how</span>
  <span m=''995290''>you''re</span> <span m=''995460''>orchestrating</span> <span
  m=''995880''>your</span> <span m=''996040''>communication</span> <span m=''997090''>and</span>
  <span m=''997400''>doing</span> <span m=''997590''>it</span> <span m=''997680''>very</span>
  <span m=''997890''>carefully.</span> </p><p><span m=''998700''>So</span> <span m=''999180''>look</span>
  <span m=''999380''>at,</span> <span m=''999650''>for</span> <span m=''999750''>example,</span>
  <span m=''1001390''>what''s</span> <span m=''1001620''>going</span> <span m=''1001830''>on</span>
  <span m=''1001970''>here.</span> <span m=''1002660''>So this</span> <span m=''1002810''>is</span>
  <span m=''1002910''>the</span> <span m=''1002990''>same</span> <span m=''1003190''>problem,</span>
  <span m=''1004140''>and</span> <span m=''1004610''>what</span> <span m=''1004750''>I''m</span>
  <span m=''1004850''>doing</span> <span m=''1005170''>is</span> <span m=''1005350''>now</span>
  <span m=''1005500''>this</span> <span m=''1005620''>is</span> <span m=''1005740''>the</span>
  <span m=''1005820''>parallel</span> <span m=''1006200''>version</span> <span m=''1006590''>and</span>
  <span m=''1006770''>I''m</span> <span m=''1006870''>sending</span> <span m=''1008310''>the</span>
  <span m=''1008430''>boundary</span> <span m=''1008780''>cases,</span> <span m=''1009440''>the</span>
  <span m=''1009600''>boundary</span> <span m=''1010220''>cells</span> <span m=''1010970''>to</span>
  <span m=''1011180''>the</span> <span m=''1011260''>different</span> <span m=''1011530''>processors.</span>
  <span m=''1012870''>This</span> <span m=''1012980''>is</span> <span m=''1013110''>an</span>
  <span m=''1013220''>SPMD</span> <span m=''1013760''>program.</span> <span m=''1014290''>So
  an</span> <span m=''1014600''>SPMD</span> <span m=''1014970''>program</span> <span
  m=''1016500''>has</span> <span m=''1016880''>every</span> <span m=''1017090''>processor</span>
  <span m=''1017580''>running</span> <span m=''1017910''>essentially</span> <span
  m=''1018240''>the</span> <span m=''1018310''>same</span> <span m=''1018530''>code.</span>
  <span m=''1019380''>So</span> <span m=''1019600''>this</span> <span m=''1019760''>code
  is</span> <span m=''1020060''>replicated</span> <span m=''1020610''>over</span>
  <span m=''1020820''>n</span> <span m=''1020980''>processors</span> <span m=''1021550''>and</span>
  <span m=''1021640''>everybody''s</span> <span m=''1021970''>trying</span> <span
  m=''1022130''>to</span> <span m=''1022230''>do</span> <span m=''1022330''>this</span>
  <span m=''1022410''>same</span> <span m=''1022620''>thing.</span> <span m=''1023290''>So</span>
  <span m=''1023570''>what''s</span> <span m=''1024080''>the</span> <span m=''1024170''>problem</span>
  <span m=''1024440''>with</span> <span m=''1024530''>this</span> <span m=''1025670''>code?</span>
  <span m=''1026500''>We''re</span> <span m=''1026660''>doing</span> <span m=''1027260''>send</span>
  <span m=''1028300''>of</span> <span m=''1029640''>next</span> <span m=''1029930''>buffer</span>
  <span m=''1030170''>zero.</span> <span m=''1031060''>Here,</span> <span m=''1031290''>rank</span>
  <span m=''1031580''>essentially</span> <span m=''1031980''>just</span> <span m=''1032170''>says</span>
  <span m=''1033100''>each</span> <span m=''1033320''>processor</span> <span m=''1033740''>has</span>
  <span m=''1033920''>a</span> <span m=''1033970''>rank.</span> <span m=''1034880''>So</span>
  <span m=''1034990''>this</span> <span m=''1035110''>is</span> <span m=''1035210''>a</span>
  <span m=''1035270''>way of</span> <span m=''1035560''>identifying</span> <span m=''1036180''>things.</span>
  <span m=''1037360''>So</span> <span m=''1037510''>I''m</span> <span m=''1037620''>trying</span>
  <span m=''1037840''>to</span> <span m=''1037940''>send</span> <span m=''1038120''>it</span>
  <span m=''1038210''>to</span> <span m=''1038780''>my</span> <span m=''1039350''>previous</span>
  <span m=''1039690''>guy,</span> <span m=''1039950''>I''m</span> <span m=''1040040''>trying</span>
  <span m=''1040220''>to</span> <span m=''1040280''>send</span> <span m=''1040450''>it</span>
  <span m=''1040530''>to</span> <span m=''1040610''>the</span> <span m=''1040670''>next</span>
  <span m=''1040940''>guy,</span> <span m=''1041670''>and</span> <span m=''1041860''>here</span>
  <span m=''1042070''>I''m</span> <span m=''1042200''>sending</span> <span m=''1042980''>the</span>
  <span m=''1043260''>value</span> <span m=''1043630''>at</span> <span m=''1043740''>the</span>
  <span m=''1044210''>far</span> <span m=''1044510''>extreme</span> <span m=''1044810''>of</span>
  <span m=''1044880''>the</span> <span m=''1044940''>buffer</span> <span m=''1046030''>to</span>
  <span m=''1046230''>the</span> <span m=''1046290''>next</span> <span m=''1046540''>processor</span>
  <span m=''1046960''>and then to the</span> <span m=''1047340''>previous</span> <span
  m=''1047680''>processor.</span> <span m=''1048560''>Anybody</span> <span m=''1048850''>see</span>
  <span m=''1049070''>what''s</span> <span m=''1049190''>wrong</span> <span m=''1049400''>here?</span>
  </p><p><span m=''1049630''>AUDIENCE:</span> <span m=''1050625''>So are</span> <span
  m=''1051122''>these</span> <span m=''1051620''>blocking</span> <span m=''1052117''>things?</span>
  </p><p><span m=''1053610''>PROFESSOR:</span> <span m=''1053800''>Yeah,</span> <span
  m=''1054030''>imagine</span> <span m=''1054460''>they''re</span> <span m=''1054580''>blocking</span>
  <span m=''1054950''>things.</span> </p><p><span m=''1055160''>AUDIENCE:</span> <span
  m=''1056651''>Why will that deadlock?</span> </p><p><span m=''1060630''>PROFESSOR:
  Right.</span> <span m=''1062100''>So</span> <span m=''1062300''>this</span> <span
  m=''1062470''>will</span> <span m=''1062630''>deadlock,</span> <span m=''1063530''>right.</span>
  <span m=''1065380''>So</span> <span m=''1065540''>this will</span> <span m=''1065860''>deadlock</span>
  <span m=''1066230''>because</span> <span m=''1067030''>this</span> <span m=''1067210''>processor</span>
  <span m=''1067580''>is</span> <span m=''1067740''>trying</span> <span m=''1068020''>to</span>
  <span m=''1068110''>send</span> <span m=''1068390''>here,</span> <span m=''1068700''>this</span>
  <span m=''1068820''>processor is</span> <span m=''1069350''>trying</span> <span
  m=''1069590''>to</span> <span m=''1069650''>send</span> <span m=''1069920''>here,</span>
  <span m=''1070420''>but</span> <span m=''1070590''>neither is</span> <span m=''1070970''>receiving</span>
  <span m=''1071390''>yet,</span> <span m=''1071620''>so</span> <span m=''1071840''>neither</span>
  <span m=''1072190''>makes</span> <span m=''1072400''>progress.</span> <span m=''1073410''>So</span>
  <span m=''1073550''>how</span> <span m=''1073690''>would</span> <span m=''1073840''>you</span>
  <span m=''1073970''>fix</span> <span m=''1074270''>it</span> <span m=''1075010''>at</span>
  <span m=''1075360''>this</span> <span m=''1075520''>point?</span> <span m=''1075940''>You</span>
  <span m=''1076540''>might</span> <span m=''1077110''>not</span> <span m=''1077390''>want</span>
  <span m=''1077640''>to</span> <span m=''1077730''>use</span> <span m=''1077970''>a</span>
  <span m=''1078100''>blocking</span> <span m=''1078500''>send</span> <span m=''1078900''>all</span>
  <span m=''1079000''>the</span> <span m=''1079110''>time.</span> <span m=''1079950''>So</span>
  <span m=''1080170''>if</span> <span m=''1080300''>your</span> <span m=''1080650''>architecture</span>
  <span m=''1081570''>allows</span> <span m=''1081970''>you</span> <span m=''1082060''>to</span>
  <span m=''1082640''>have</span> <span m=''1082830''>different</span> <span m=''1083180''>flavors</span>
  <span m=''1083600''>of</span> <span m=''1083690''>communication,</span> <span m=''1084610''>so</span>
  <span m=''1084850''>synchronous</span> <span m=''1085410''>versus</span> <span m=''1085750''>an
  asynchronous,</span> <span m=''1086800''>a</span> <span m=''1086890''>blocking</span>
  <span m=''1087310''>versus</span> <span m=''1087680''>non-blocking,</span> <span
  m=''1088560''>you''ll</span> <span m=''1088680''>want</span> <span m=''1088890''>to</span>
  <span m=''1089010''>avoid</span> <span m=''1089880''>using</span> <span m=''1090180''>constructs</span>
  <span m=''1090690''>that</span> <span m=''1090780''>can</span> <span m=''1090930''>lead</span>
  <span m=''1091260''>you to</span> <span m=''1091330''>deadlock</span> <span m=''1091790''>if</span>
  <span m=''1091950''>you</span> <span m=''1092060''>don''t</span> <span m=''1092210''>need</span>
  <span m=''1092360''>to.</span> </p><p><span m=''1094020''>The</span> <span m=''1094100''>other</span>
  <span m=''1094430''>mechanism --</span> <span m=''1095120''>this was</span> <span
  m=''1095950''>pointed</span> <span m=''1096230''>out</span> <span m=''1096290''>briefly</span>
  <span m=''1096770''>in</span> <span m=''1097370''>the</span> <span m=''1097430''>talk</span>
  <span m=''1097700''>on</span> <span m=''1097820''>parallel</span> <span m=''1098060''>programming
  --</span> <span m=''1098750''>you</span> <span m=''1098920''>want to</span> <span
  m=''1099110''>order</span> <span m=''1099790''>your</span> <span m=''1099980''>sends</span>
  <span m=''1100280''>and</span> <span m=''1100390''>receives</span> <span m=''1100800''>properly.</span>
  <span m=''1101440''>So</span> <span m=''1101710''>alternate</span> <span m=''1102180''>them.</span>
  <span m=''1102330''>So</span> <span m=''1102760''>you</span> <span m=''1102850''>have</span>
  <span m=''1102940''>a</span> <span m=''1103030''>send in</span> <span m=''1103450''>one</span>
  <span m=''1103630''>processor,</span> <span m=''1103970''>a</span> <span m=''1104160''>receive</span>
  <span m=''1104520''>in the</span> <span m=''1104680''>other.</span> <span m=''1105970''>You</span>
  <span m=''1106070''>can</span> <span m=''1106210''>use</span> <span m=''1106410''>that</span>
  <span m=''1106610''>to</span> <span m=''1106910''>prevent</span> <span m=''1107710''>deadlock</span>
  <span m=''1108150''>and</span> <span m=''1108240''>get</span> <span m=''1108350''>the</span>
  <span m=''1108430''>communication</span> <span m=''1109010''>patterns</span> <span
  m=''1109410''>right.</span> <span m=''1110890''>There</span> <span m=''1111000''>could</span>
  <span m=''1111140''>be</span> <span m=''1111240''>more</span> <span m=''1111470''>interesting</span>
  <span m=''1111840''>cases</span> <span m=''1112200''>that</span> <span m=''1112320''>come</span>
  <span m=''1112480''>up</span> <span m=''1112640''>if</span> <span m=''1112800''>you''re</span>
  <span m=''1112920''>communicating</span> <span m=''1113600''>over a</span> <span
  m=''1113880''>network</span> <span m=''1114540''>where you</span> <span m=''1114820''>might</span>
  <span m=''1115020''>end</span> <span m=''1115130''>up</span> <span m=''1115230''>with</span>
  <span m=''1115420''>cyclic</span> <span m=''1115660''>patterns</span> <span m=''1117190''>leading</span>
  <span m=''1117480''>to</span> <span m=''1118160''>loops,</span> <span m=''1118880''>and</span>
  <span m=''1119450''>that</span> <span m=''1119950''>also</span> <span m=''1120320''>can</span>
  <span m=''1120470''>create</span> <span m=''1120640''>some</span> <span m=''1120700''>problems</span>
  <span m=''1121000''>for</span> <span m=''1121250''>you.</span> </p><p><span m=''1124770''>The</span>
  <span m=''1124960''>last</span> <span m=''1125320''>two</span> <span m=''1125780''>I''ll</span>
  <span m=''1125950''>talk</span> <span m=''1126240''>about</span> <span m=''1126610''>aren''t</span>
  <span m=''1126920''>really</span> <span m=''1127740''>bugs</span> <span m=''1128160''>in</span>
  <span m=''1128320''>that</span> <span m=''1128780''>they</span> <span m=''1128890''>might</span>
  <span m=''1129080''>not</span> <span m=''1129220''>cause</span> <span m=''1129470''>your</span>
  <span m=''1129540''>program</span> <span m=''1129880''>to</span> <span m=''1129980''>break</span>
  <span m=''1130470''>or</span> <span m=''1130770''>compute</span> <span m=''1131090''>incorrectly.</span>
  <span m=''1132050''>Things</span> <span m=''1132250''>might</span> <span m=''1132430''>work</span>
  <span m=''1132690''>properly,</span> <span m=''1133160''>but</span> <span m=''1133310''>you</span>
  <span m=''1133380''>might</span> <span m=''1133530''>not</span> <span m=''1133680''>get</span>
  <span m=''1133810''>the</span> <span m=''1133890''>actual</span> <span m=''1134160''>performance</span>
  <span m=''1134660''>that</span> <span m=''1134730''>you''re</span> <span m=''1134860''>expecting.</span>
  <span m=''1136460''>So</span> <span m=''1137920''>these</span> <span m=''1138260''>are</span>
  <span m=''1138890''>performance</span> <span m=''1139420''>bucks</span> <span m=''1139640''>or</span>
  <span m=''1139740''>performance</span> <span m=''1140230''>defects.</span> <span
  m=''1141660''>So</span> <span m=''1141960''>side</span> <span m=''1142210''>effects
  of</span> <span m=''1142540''>parallelization</span> <span m=''1143020''>is</span>
  <span m=''1143770''>often</span> <span m=''1144560''>case</span> <span m=''1144940''>that</span>
  <span m=''1145390''>you''re</span> <span m=''1145490''>focusing</span> <span m=''1145940''>on</span>
  <span m=''1146050''>your</span> <span m=''1146160''>parallel</span> <span m=''1146550''>code</span>
  <span m=''1147220''>and</span> <span m=''1147350''>you</span> <span m=''1147410''>might</span>
  <span m=''1147560''>ignore</span> <span m=''1147880''>things</span> <span m=''1148130''>that</span>
  <span m=''1148220''>are</span> <span m=''1148280''>going</span> <span m=''1148540''>on</span>
  <span m=''1148700''>in your</span> <span m=''1148810''>sequential</span> <span m=''1149230''>code,</span>
  <span m=''1149820''>and</span> <span m=''1150300''>that</span> <span m=''1150440''>might</span>
  <span m=''1150650''>lead</span> <span m=''1150870''>you</span> <span m=''1150960''>to,</span>
  <span m=''1151170''>essentially you''ve</span> <span m=''1151640''>spent</span>
  <span m=''1151940''>all</span> <span m=''1152060''>this</span> <span m=''1152200''>time</span>
  <span m=''1152430''>trying</span> <span m=''1152600''>to</span> <span m=''1152660''>parallelize
  your</span> <span m=''1153090''>code,</span> <span m=''1153470''>but</span> <span
  m=''1154720''>your</span> <span m=''1155060''>end</span> <span m=''1155270''>result</span>
  <span m=''1155630''>is</span> <span m=''1155730''>not</span> <span m=''1155880''>getting</span>
  <span m=''1156070''>the</span> <span m=''1156140''>performance</span> <span m=''1156570''>that</span>
  <span m=''1156660''>you</span> <span m=''1156760''>expect</span> <span m=''1157210''>because</span>
  <span m=''1157900''>things</span> <span m=''1158210''>look</span> <span m=''1158360''>sequential.</span>
  <span m=''1159030''>So</span> <span m=''1159270''>what''s</span> <span m=''1159490''>wrong</span>
  <span m=''1159730''>here?</span> </p><p><span m=''1161120''>So</span> <span m=''1161330''>as</span>
  <span m=''1161430''>an</span> <span m=''1161510''>example,</span> <span m=''1162790''>imagine</span>
  <span m=''1163300''>that</span> <span m=''1163900''>we''re</span> <span m=''1164070''>doing</span>
  <span m=''1164960''>instead</span> <span m=''1165310''>of</span> <span m=''1165890''>reading</span>
  <span m=''1166240''>data</span> <span m=''1166480''>from</span> <span m=''1166770''>a</span>
  <span m=''1167590''>--</span> <span m=''1170160''>so,</span> <span m=''1170340''>in</span>
  <span m=''1170510''>the</span> <span m=''1170600''>previous</span> <span m=''1170930''>case</span>
  <span m=''1171150''>I</span> <span m=''1171210''>didn''t</span> <span m=''1171400''>show</span>
  <span m=''1171540''>you</span> <span m=''1171640''>how</span> <span m=''1171770''>we</span>
  <span m=''1171920''>were</span> <span m=''1172020''>reading</span> <span m=''1172340''>data</span>
  <span m=''1172600''>into the</span> <span m=''1172930''>different</span> <span m=''1173210''>buffers,</span>
  <span m=''1174290''>but</span> <span m=''1174470''>suppose</span> <span m=''1174720''>we</span>
  <span m=''1174830''>were</span> <span m=''1174950''>getting</span> <span m=''1175190''>it</span>
  <span m=''1175290''>from</span> <span m=''1175440''>some</span> <span m=''1175590''>files,</span>
  <span m=''1176060''>so</span> <span m=''1176170''>input</span> <span m=''1176390''>buffer.</span>
  <span m=''1177240''>So now</span> <span m=''1177400''>we</span> <span m=''1177520''>have</span>
  <span m=''1177690''>an</span> <span m=''1177760''>SPMD</span> <span m=''1178220''>program</span>
  <span m=''1178580''>again,</span> <span m=''1178930''>everybody''s</span> <span
  m=''1179400''>trying</span> <span m=''1179660''>to</span> <span m=''1179750''>read</span>
  <span m=''1179930''>from</span> <span m=''1180080''>this</span> <span m=''1180240''>buffer.</span>
  <span m=''1181010''>What could</span> <span m=''1181270''>go</span> <span m=''1181400''>wrong</span>
  <span m=''1181660''>here?</span> <span m=''1182930''>Anybody have</span> <span m=''1183190''>an</span>
  <span m=''1183580''>idea?</span> <span m=''1185150''>So</span> <span m=''1185470''>every</span>
  <span m=''1185810''>processor</span> <span m=''1186290''>is</span> <span m=''1186530''>opening</span>
  <span m=''1186790''>the</span> <span m=''1186880''>file</span> <span m=''1187250''>and</span>
  <span m=''1187350''>then</span> <span m=''1187700''>it''s</span> <span m=''1187880''>going</span>
  <span m=''1188050''>to</span> <span m=''1188120''>figure</span> <span m=''1188340''>out</span>
  <span m=''1188470''>how</span> <span m=''1188580''>much</span> <span m=''1188800''>to</span>
  <span m=''1188900''>skip</span> <span m=''1189650''>and</span> <span m=''1189800''>it''ll</span>
  <span m=''1189980''>start</span> <span m=''1190210''>reading</span> <span m=''1190480''>from</span>
  <span m=''1190650''>that</span> <span m=''1190800''>location. So</span> <span m=''1191690''>everybody''s</span>
  <span m=''1192160''>reading</span> <span m=''1192520''>from</span> <span m=''1192720''>a</span>
  <span m=''1192770''>file, so</span> <span m=''1193050''>that''s</span> <span m=''1193280''>OK,</span>
  <span m=''1193530''>nobody''s</span> <span m=''1193830''>modifying it. But</span>
  <span m=''1194850''>what</span> <span m=''1195090''>can</span> <span m=''1195210''>go</span>
  <span m=''1195320''>wrong</span> <span m=''1195600''>here?</span> </p><p><span m=''1195950''>AUDIENCE:</span>
  <span m=''1199395''>[INAUDIBLE PHRASE].</span> </p><p><span m=''1207270''>PROFESSOR:
  Right.</span> <span m=''1209760''>So</span> <span m=''1210010''>essentially,</span>
  <span m=''1210400''>sequentialize</span> <span m=''1211440''>your</span> <span m=''1211680''>execution</span>
  <span m=''1212300''>because</span> <span m=''1212740''>reading</span> <span m=''1213010''>from</span>
  <span m=''1213210''>the</span> <span m=''1213280''>file</span> <span m=''1213560''>system</span>
  <span m=''1214110''>becomes</span> <span m=''1214430''>the</span> <span m=''1214510''>bottleneck.</span>
  <span m=''1216770''>So</span> <span m=''1216900''>you''ll</span> <span m=''1216990''>want</span>
  <span m=''1217210''>to</span> <span m=''1217280''>schedule</span> <span m=''1217690''>input
  and</span> <span m=''1218100''>output</span> <span m=''1218400''>carefully.</span>
  <span m=''1219550''>You</span> <span m=''1219620''>might</span> <span m=''1219840''>find</span>
  <span m=''1220240''>that</span> <span m=''1220460''>not</span> <span m=''1220690''>everybody</span>
  <span m=''1221120''>needs</span> <span m=''1221340''>to</span> <span m=''1221450''>do</span>
  <span m=''1221580''>the</span> <span m=''1221680''>input</span> <span m=''1221960''>and</span>
  <span m=''1222060''>output.</span> <span m=''1222860''>Only</span> <span m=''1223600''>one</span>
  <span m=''1223840''>processor</span> <span m=''1224680''>has</span> <span m=''1224910''>to</span>
  <span m=''1224990''>do</span> <span m=''1225110''>the</span> <span m=''1225210''>input</span>
  <span m=''1225880''>and</span> <span m=''1226230''>then it</span> <span m=''1226390''>can</span>
  <span m=''1226520''>distribute it</span> <span m=''1227110''>to</span> <span m=''1227380''>all
  the</span> <span m=''1227620''>different</span> <span m=''1227880''>processors.</span>
  <span m=''1228370''>So,</span> <span m=''1229070''>in</span> <span m=''1229270''>the</span>
  <span m=''1229500''>Master/Slave</span> <span m=''1230200''>model,</span> <span
  m=''1230700''>which</span> <span m=''1231610''>a</span> <span m=''1231670''>lot</span>
  <span m=''1231840''>of</span> <span m=''1231950''>you are</span> <span m=''1232120''>using</span>
  <span m=''1232390''>for</span> <span m=''1232530''>the</span> <span m=''1232590''>Cell</span>
  <span m=''1232840''>programming,</span> <span m=''1233710''>the</span> <span m=''1233930''>Master</span>
  <span m=''1234390''>can</span> <span m=''1234530''>just</span> <span m=''1234770''>read</span>
  <span m=''1235840''>the</span> <span m=''1236220''>data</span> <span m=''1236550''>from</span>
  <span m=''1236700''>the</span> <span m=''1236760''>input</span> <span m=''1236970''>files
  and</span> <span m=''1237290''>distribute it to</span> <span m=''1238070''>everybody</span>
  <span m=''1238490''>else. So this</span> <span m=''1238920''>avoids</span> <span
  m=''1239260''>some</span> <span m=''1239380''>of</span> <span m=''1239440''>the</span>
  <span m=''1239500''>problems</span> <span m=''1239900''>with</span> <span m=''1240310''>input
  and</span> <span m=''1240670''>output.</span> <span m=''1241740''>You</span> <span
  m=''1241800''>can</span> <span m=''1241900''>have</span> <span m=''1242070''>similar</span>
  <span m=''1242350''>kinds</span> <span m=''1242550''>of</span> <span m=''1242620''>problems</span>
  <span m=''1243050''>if</span> <span m=''1243170''>you''re</span> <span m=''1243330''>reading</span>
  <span m=''1245150''>from</span> <span m=''1245410''>other</span> <span m=''1245620''>devices.</span>
  <span m=''1246130''>It</span> <span m=''1246830''>doesn''t</span> <span m=''1247170''>have</span>
  <span m=''1247300''>to</span> <span m=''1247400''>be</span> <span m=''1247530''>the</span>
  <span m=''1247610''>file</span> <span m=''1247850''>system.</span> <span m=''1248740''>So</span>
  <span m=''1248910''>here''s</span> <span m=''1249180''>another</span> <span m=''1249700''>one,</span>
  <span m=''1250050''>a</span> <span m=''1250210''>little</span> <span m=''1250380''>more</span>
  <span m=''1250550''>subtle.</span> <span m=''1252520''>So</span> <span m=''1254160''>you''re</span>
  <span m=''1254510''>generating</span> <span m=''1255090''>data--.</span> </p><p><span
  m=''1255810''>Hey,</span> <span m=''1255990''>Allen,</span> <span m=''1256190''>what''s</span>
  <span m=''1256693''>up?</span> </p><p><span m=''1257196''>AUDIENCE:</span> <span
  m=''1257700''>I</span> <span m=''1258203''>somehow missed the</span> <span m=''1258707''>distinction</span>
  <span m=''1259210''>between</span> <span m=''1259714''>when you''re</span> <span
  m=''1260217''>waiting for</span> <span m=''1260721''>the master</span> <span m=''1261224''>to
  read all the</span> <span m=''1261728''>dat aand</span> <span m=''1262231''>distribute
  it, and</span> <span m=''1262735''>waiting for the</span> <span m=''1263238''>other</span>
  <span m=''1263741''>[? processes ?]</span> <span m=''1264245''>to</span> <span m=''1264748''>get
  through</span> <span m=''1265252''>so I can read my</span> <span m=''1265755''>private</span>
  <span m=''1266259''>data,</span> <span m=''1266762''>isn''t</span> <span m=''1267266''>it
  going to</span> <span m=''1267769''>be about the</span> <span m=''1268273''>same</span>
  <span m=''1268776''>time</span> <span m=''1269280''>on</span> <span m=''1269555''>this?</span>
  </p><p><span m=''1270910''>PROFESSOR: No.</span> <span m=''1271090''>So</span> <span
  m=''1271510''>here,</span> <span m=''1271930''>just</span> <span m=''1272620''>essentially,
  the</span> <span m=''1273150''>Master</span> <span m=''1273880''>reads</span> <span
  m=''1274280''>the</span> <span m=''1274360''>file as</span> <span m=''1274830''>part</span>
  <span m=''1275130''>of the</span> <span m=''1275430''>initialization.</span> <span
  m=''1277410''>Then</span> <span m=''1277560''>you</span> <span m=''1277670''>distribute
  it.</span> <span m=''1278050''>So</span> <span m=''1278270''>distribution</span>
  <span m=''1278800''>can</span> <span m=''1278910''>happen</span> <span m=''1279180''>at</span>
  <span m=''1279260''>run</span> <span m=''1279400''>time.</span> <span m=''1279770''>So,</span>
  <span m=''1281360''>the</span> <span m=''1281500''>initialization</span> <span m=''1282150''>you</span>
  <span m=''1282250''>don''t</span> <span m=''1282390''>care</span> <span m=''1282580''>about</span>
  <span m=''1282800''>because</span> <span m=''1283250''>hopefully</span> <span m=''1283630''>that''s</span>
  <span m=''1283780''>a</span> <span m=''1283840''>small</span> <span m=''1284040''>part</span>
  <span m=''1284300''>of the</span> <span m=''1284360''>code.</span> <span m=''1288680''>So
  this</span> <span m=''1289300''>code</span> <span m=''1289520''>is</span> <span
  m=''1289620''>guarded</span> <span m=''1289910''>by</span> <span m=''1290090''>rank</span>
  <span m=''1290360''>equals</span> <span m=''1290670''>Master, so</span> <span m=''1291060''>only</span>
  <span m=''1291380''>it</span> <span m=''1291550''>does this</span> <span m=''1291740''>code.</span>
  <span m=''1292270''>Then</span> <span m=''1292440''>here</span> <span m=''1292740''>you</span>
  <span m=''1292850''>might</span> <span m=''1293360''>have</span> <span m=''1293610''>the</span>
  <span m=''1293680''>command</span> <span m=''1293960''>that</span> <span m=''1294070''>says</span>
  <span m=''1294410''>wait</span> <span m=''1294690''>until</span> <span m=''1295200''>I''ve</span>
  <span m=''1295330''>received</span> <span m=''1295770''>it</span> <span m=''1295890''>and</span>
  <span m=''1296010''>then</span> <span m=''1296120''>execute,</span> <span m=''1296870''>or</span>
  <span m=''1297560''>on</span> <span m=''1297740''>the</span> <span m=''1297810''>cells,</span>
  <span m=''1298380''>then</span> <span m=''1298680''>these</span> <span m=''1298830''>might</span>
  <span m=''1298940''>be</span> <span m=''1299150''>the</span> <span m=''1299280''>SPE</span>
  <span m=''1299800''>create</span> <span m=''1300180''>threads</span> <span m=''1300530''>that</span>
  <span m=''1300730''>happen</span> <span m=''1301020''>after</span> <span m=''1301270''>you''ve</span>
  <span m=''1301390''>read the</span> <span m=''1301650''>data.</span> <span m=''1302340''>So</span>
  <span m=''1302560''>hopefully,</span> <span m=''1302900''>initialization</span>
  <span m=''1303520''>time</span> <span m=''1303830''>is</span> <span m=''1304660''>not</span>
  <span m=''1304780''>something</span> <span m=''1305080''>you have</span> <span m=''1305200''>concern</span>
  <span m=''1305560''>about</span> <span m=''1305790''>too</span> <span m=''1305920''>much.</span>
  </p><p><span m=''1308830''>So</span> <span m=''1309170''>if</span> <span m=''1309270''>you''re</span>
  <span m=''1309410''>generating</span> <span m=''1310540''>data</span> <span m=''1310950''>on</span>
  <span m=''1311150''>the</span> <span m=''1311220''>fly</span> <span m=''1311590''>or</span>
  <span m=''1311660''>dynamically,</span> <span m=''1312770''>so</span> <span m=''1312930''>here</span>
  <span m=''1313140''>we</span> <span m=''1313230''>might</span> <span m=''1313570''>use</span>
  <span m=''1314180''>the Srand</span> <span m=''1314680''>function</span> <span m=''1315100''>to</span>
  <span m=''1315480''>sort</span> <span m=''1315680''>of</span> <span m=''1315780''>start</span>
  <span m=''1316110''>with</span> <span m=''1316250''>a</span> <span m=''1316290''>random</span>
  <span m=''1316580''>seeing</span> <span m=''1317350''>and</span> <span m=''1317490''>then</span>
  <span m=''1317690''>fill</span> <span m=''1317990''>in</span> <span m=''1318100''>the</span>
  <span m=''1318190''>buffer</span> <span m=''1318830''>with</span> <span m=''1319090''>some</span>
  <span m=''1319280''>random</span> <span m=''1319710''>data.</span> <span m=''1320330''>So</span>
  <span m=''1320490''>what</span> <span m=''1320550''>could</span> <span m=''1320680''>go</span>
  <span m=''1320790''>wrong</span> <span m=''1321010''>here?</span> <span m=''1324250''>So
  in</span> <span m=''1324600''>Srand,</span> <span m=''1327090''>when</span> <span
  m=''1327250''>you''re</span> <span m=''1327320''>using</span> <span m=''1327640''>a</span>
  <span m=''1327710''>random</span> <span m=''1328010''>function --</span> <span m=''1328530''>sorry,</span>
  <span m=''1330070''>this</span> <span m=''1330260''>is</span> <span m=''1330380''>the</span>
  <span m=''1330450''>same</span> <span m=''1330650''>function.</span> <span m=''1332340''>When
  you''re</span> <span m=''1332470''>using</span> <span m=''1333030''>a</span> <span
  m=''1333190''>random,</span> <span m=''1334130''>a pseudo</span> <span m=''1334190''>random</span>
  <span m=''1334420''>number</span> <span m=''1334640''>generator,</span> <span m=''1335460''>you</span>
  <span m=''1335580''>have</span> <span m=''1335750''>to</span> <span m=''1335890''>give</span>
  <span m=''1336080''>it</span> <span m=''1336150''>a</span> <span m=''1336190''>seed,</span>
  <span m=''1336590''>then</span> <span m=''1336820''>if</span> <span m=''1336940''>everybody</span>
  <span m=''1337390''>starts</span> <span m=''1337730''>off</span> <span m=''1337910''>with
  the</span> <span m=''1338060''>same</span> <span m=''1338460''>seed,</span> <span
  m=''1338780''>then</span> <span m=''1339320''>you</span> <span m=''1339480''>might</span>
  <span m=''1339630''>end</span> <span m=''1339780''>up</span> <span m=''1339890''>with</span>
  <span m=''1340000''>the</span> <span m=''1340060''>same</span> <span m=''1340830''>random</span>
  <span m=''1341090''>number</span> <span m=''1341340''>sequence.</span> <span m=''1342640''>If</span>
  <span m=''1343120''>that''s</span> <span m=''1343410''>something</span> <span m=''1343980''>you''re</span>
  <span m=''1344150''>using</span> <span m=''1344510''>to</span> <span m=''1344890''>parallelize</span>
  <span m=''1345400''>your</span> <span m=''1345960''>computation,</span> <span m=''1346520''>you</span>
  <span m=''1346670''>might,</span> <span m=''1346900''>in</span> <span m=''1347010''>effect,</span>
  <span m=''1347360''>end</span> <span m=''1347550''>up</span> <span m=''1347720''>with</span>
  <span m=''1348110''>the</span> <span m=''1348220''>same</span> <span m=''1348460''>kind</span>
  <span m=''1348750''>of</span> <span m=''1350010''>sequence</span> <span m=''1350520''>on</span>
  <span m=''1350640''>each</span> <span m=''1350810''>processor</span> <span m=''1351270''>and</span>
  <span m=''1351390''>you</span> <span m=''1351490''>lose</span> <span m=''1351710''>all</span>
  <span m=''1351820''>kinds</span> <span m=''1352050''>of</span> <span m=''1352630''>parallelization.</span>
  <span m=''1354250''>So</span> <span m=''1354940''>there''s</span> <span m=''1355090''>some</span>
  <span m=''1355230''>hidden</span> <span m=''1355670''>serialization</span> <span
  m=''1356150''>issues</span> <span m=''1356610''>in</span> <span m=''1356740''>some</span>
  <span m=''1356860''>of</span> <span m=''1356920''>the</span> <span m=''1356980''>functions</span>
  <span m=''1357360''>that</span> <span m=''1357470''>you</span> <span m=''1357560''>might</span>
  <span m=''1357730''>use</span> <span m=''1358660''>that</span> <span m=''1358830''>you</span>
  <span m=''1358940''>should</span> <span m=''1359110''>be</span> <span m=''1359230''>aware</span>
  <span m=''1359530''>of.</span> </p><p><span m=''1362350''>The last</span> <span
  m=''1362610''>one</span> <span m=''1362730''>I''ll</span> <span m=''1362840''>talk</span>
  <span m=''1363080''>about</span> <span m=''1363410''>is</span> <span m=''1364430''>performance</span>
  <span m=''1365000''>scalability</span> <span m=''1365650''>defect.</span> <span
  m=''1366570''>So</span> <span m=''1366770''>here</span> <span m=''1367180''>you</span>
  <span m=''1367610''>parallelize</span> <span m=''1368070''>your</span> <span m=''1368170''>code,</span>
  <span m=''1369060''>things</span> <span m=''1369330''>look</span> <span m=''1369510''>good,</span>
  <span m=''1370050''>but</span> <span m=''1370170''>you''re</span> <span m=''1370250''>still</span>
  <span m=''1370440''>not</span> <span m=''1370620''>getting --</span> <span m=''1371300''>you''ve</span>
  <span m=''1371420''>taken</span> <span m=''1371640''>care</span> <span m=''1371790''>of</span>
  <span m=''1371880''>all</span> <span m=''1372050''>your</span> <span m=''1372190''>IO</span>
  <span m=''1372340''>issue,</span> <span m=''1373330''>you''re</span> <span m=''1373770''>still</span>
  <span m=''1373870''>not</span> <span m=''1374030''>getting</span> <span m=''1374300''>the</span>
  <span m=''1374620''>performance</span> <span m=''1374690''>you</span> <span m=''1374840''>want.</span>
  <span m=''1375370''>So,</span> <span m=''1375620''>why</span> <span m=''1375980''>is</span>
  <span m=''1376100''>that?</span> <span m=''1377710''>You</span> <span m=''1377960''>might</span>
  <span m=''1378140''>have --</span> <span m=''1378760''>remember</span> <span m=''1379210''>your</span>
  <span m=''1379480''>Amdahl''s</span> <span m=''1380150''>law,</span> <span m=''1380740''>and</span>
  <span m=''1381300''>what</span> <span m=''1381430''>you</span> <span m=''1381510''>want</span>
  <span m=''1381770''>is</span> <span m=''1381910''>an</span> <span m=''1381990''>efficiency</span>
  <span m=''1382770''>that''s</span> <span m=''1383080''>linear.</span> <span m=''1383580''>Every</span>
  <span m=''1383790''>time</span> <span m=''1383990''>you</span> <span m=''1384050''>add</span>
  <span m=''1384220''>one</span> <span m=''1384430''>processor</span> <span m=''1385250''>you</span>
  <span m=''1385380''>want</span> <span m=''1387950''>a</span> <span m=''1388180''>straight</span>
  <span m=''1388500''>line</span> <span m=''1388640''>curve</span> <span m=''1388960''>between
  the</span> <span m=''1389700''>number of</span> <span m=''1389990''>processors</span>
  <span m=''1390560''>and</span> <span m=''1390690''>speed</span> <span m=''1390930''>up.</span>
  <span m=''1391410''>This</span> <span m=''1391500''>should</span> <span m=''1391600''>be</span>
  <span m=''1391710''>a</span> <span m=''1391780''>linear</span> <span m=''1392100''>relationship.</span>
  <span m=''1393490''>So</span> <span m=''1393800''>you</span> <span m=''1393930''>might</span>
  <span m=''1394220''>see</span> <span m=''1394430''>sublinear</span> <span m=''1394960''>speed</span>
  <span m=''1395180''>ups,</span> <span m=''1395820''>and</span> <span m=''1396090''>you</span>
  <span m=''1396180''>want</span> <span m=''1396370''>to</span> <span m=''1396440''>figure</span>
  <span m=''1396660''>out</span> <span m=''1396830''>why</span> <span m=''1397100''>that</span>
  <span m=''1397290''>is.</span> </p><p><span m=''1397980''>Some</span> <span m=''1398100''>of</span>
  <span m=''1398160''>the</span> <span m=''1398220''>common</span> <span m=''1398510''>causes</span>
  <span m=''1398880''>here,</span> <span m=''1399220''>and</span> <span m=''1399280''>this</span>
  <span m=''1399520''>will</span> <span m=''1399680''>be</span> <span m=''1399990''>the</span>
  <span m=''1400490''>end</span> <span m=''1400680''>up</span> <span m=''1400800''>focus</span>
  <span m=''1401150''>of the</span> <span m=''1401260''>next</span> <span m=''1401560''>talk</span>
  <span m=''1401820''>is,</span> <span m=''1402500''>unbalanced</span> <span m=''1403020''>amount</span>
  <span m=''1403210''>of</span> <span m=''1403280''>computation.</span> <span m=''1404100''>Remember,</span>
  <span m=''1404380''>dynamic</span> <span m=''1404840''>load</span> <span m=''1405000''>balancing</span>
  <span m=''1405420''>versus</span> <span m=''1405740''>static</span> <span m=''1406060''>load</span>
  <span m=''1406250''>balancing.</span> <span m=''1407050''>Your</span> <span m=''1407160''>work</span>
  <span m=''1407360''>estimation</span> <span m=''1407860''>might</span> <span m=''1408010''>be</span>
  <span m=''1408120''>wrong</span> <span m=''1408400''>and</span> <span m=''1408520''>so</span>
  <span m=''1408660''>you</span> <span m=''1408750''>might</span> <span m=''1408910''>end</span>
  <span m=''1409070''>up</span> <span m=''1409210''>with</span> <span m=''1410090''>some</span>
  <span m=''1410300''>processors</span> <span m=''1410820''>idling,</span> <span m=''1411430''>other</span>
  <span m=''1411730''>processors</span> <span m=''1412660''>doing</span> <span m=''1412880''>too</span>
  <span m=''1413020''>much</span> <span m=''1413200''>work.</span> <span m=''1414940''>So</span>
  <span m=''1415050''>the</span> <span m=''1415170''>way</span> <span m=''1415330''>to</span>
  <span m=''1415440''>prevent</span> <span m=''1415800''>this</span> <span m=''1415990''>is
  to</span> <span m=''1416260''>actually</span> <span m=''1416650''>look</span> <span
  m=''1416860''>at</span> <span m=''1416960''>the</span> <span m=''1417050''>work</span>
  <span m=''1417280''>that''s</span> <span m=''1417410''>being</span> <span m=''1417700''>done</span>
  <span m=''1418260''>and</span> <span m=''1418580''>figure</span> <span m=''1418830''>out</span>
  <span m=''1418960''>whether</span> <span m=''1419300''>it''s</span> <span m=''1419510''>actually</span>
  <span m=''1420370''>roughly</span> <span m=''1420770''>the</span> <span m=''1420860''>same</span>
  <span m=''1421060''>amount</span> <span m=''1421270''>of</span> <span m=''1421380''>work</span>
  <span m=''1421590''>everywhere.</span> <span m=''1422380''>Here</span> <span m=''1422610''>you</span>
  <span m=''1422730''>might</span> <span m=''1422920''>need</span> <span m=''1423120''>profiling</span>
  <span m=''1423610''>tools</span> <span m=''1423890''>to</span> <span m=''1423980''>help,</span>
  <span m=''1424530''>and</span> <span m=''1424860''>so</span> <span m=''1424960''>I''m</span>
  <span m=''1425040''>going to</span> <span m=''1425190''>talk</span> <span m=''1425390''>about</span>
  <span m=''1425580''>this in</span> <span m=''1425770''>a</span> <span m=''1425910''>lot</span>
  <span m=''1426080''>more</span> <span m=''1426250''>detail</span> <span m=''1426970''>in
  the</span> <span m=''1427140''>next</span> <span m=''1428260''>lecture.</span> </p><p><span
  m=''1429930''>So in</span> <span m=''1430190''>summary,</span> <span m=''1431550''>there</span>
  <span m=''1431670''>are</span> <span m=''1431940''>lots</span> <span m=''1432210''>of</span>
  <span m=''1432330''>different</span> <span m=''1432910''>bugs</span> <span m=''1433550''>that</span>
  <span m=''1433690''>you</span> <span m=''1433800''>might</span> <span m=''1433980''>come</span>
  <span m=''1434140''>up</span> <span m=''1435050''>with.</span> <span m=''1436030''>There''s</span>
  <span m=''1436660''>a</span> <span m=''1437460''>few</span> <span m=''1437710''>that</span>
  <span m=''1437870''>I''ve</span> <span m=''1438000''>identified</span> <span m=''1438590''>here,</span>
  <span m=''1438920''>some</span> <span m=''1439130''>common</span> <span m=''1439490''>things</span>
  <span m=''1439810''>you</span> <span m=''1439890''>should</span> <span m=''1440050''>look</span>
  <span m=''1440220''>out</span> <span m=''1440420''>for.</span> <span m=''1441070''>So</span>
  <span m=''1441270''>the</span> <span m=''1441380''>erroneous</span> <span m=''1441680''>use</span>
  <span m=''1442170''>of</span> <span m=''1442260''>language</span> <span m=''1442600''>features</span>
  <span m=''1443040''>understand</span> <span m=''1443520''>only a</span> <span m=''1443730''>few</span>
  <span m=''1443920''>basic</span> <span m=''1444240''>concepts</span> <span m=''1445050''>of</span>
  <span m=''1445510''>the</span> <span m=''1445690''>entire</span> <span m=''1446040''>language</span>
  <span m=''1446370''>extension</span> <span m=''1446790''>set</span> <span m=''1446980''>that</span>
  <span m=''1447090''>you</span> <span m=''1447190''>have.</span> <span m=''1448620''>Space</span>
  <span m=''1449090''>decomposition,</span> <span m=''1449750''>side</span> <span
  m=''1449970''>effects</span> <span m=''1450270''>from</span> <span m=''1450340''>parallelization.</span>
  <span m=''1451540''>Don''t</span> <span m=''1451980''>ignore</span> <span m=''1452250''>sequential</span>
  <span m=''1452770''>code.</span> <span m=''1454330''>Last</span> <span m=''1454600''>one</span>
  <span m=''1454720''>is</span> <span m=''1454870''>trying</span> <span m=''1455070''>to</span>
  <span m=''1455500''>understand</span> <span m=''1455940''>your</span> <span m=''1456030''>performance</span>
  <span m=''1456430''>scalability.</span> <span m=''1457390''>But</span> <span m=''1457490''>there</span>
  <span m=''1457600''>are</span> <span m=''1457690''>other</span> <span m=''1457850''>kinds</span>
  <span m=''1458100''>of</span> <span m=''1458200''>bugs,</span> <span m=''1458570''>like</span>
  <span m=''1458760''>data</span> <span m=''1458990''>races, for example.</span> <span
  m=''1459990''>So what</span> <span m=''1460280''>can</span> <span m=''1460380''>you</span>
  <span m=''1460470''>do</span> <span m=''1460610''>with</span> <span m=''1460760''>those?</span>
  <span m=''1462200''>So</span> <span m=''1462350''>remember,</span> <span m=''1462660''>data</span>
  <span m=''1462920''>races</span> <span m=''1463560''>you</span> <span m=''1463760''>have</span>
  <span m=''1463980''>different</span> <span m=''1464400''>concurrent</span> <span
  m=''1464800''>threads</span> <span m=''1465060''>and</span> <span m=''1465170''>they''re</span>
  <span m=''1465280''>trying to</span> <span m=''1465640''>update</span> <span m=''1465990''>the</span>
  <span m=''1466090''>same</span> <span m=''1466400''>memory</span> <span m=''1466640''>location.</span>
  <span m=''1468010''>So</span> <span m=''1468300''>depending</span> <span m=''1468710''>on</span>
  <span m=''1468920''>who</span> <span m=''1469100''>gets</span> <span m=''1469340''>to</span>
  <span m=''1469430''>write</span> <span m=''1469630''>first</span> <span m=''1470030''>and</span>
  <span m=''1470160''>when</span> <span m=''1470290''>you</span> <span m=''1470400''>actually</span>
  <span m=''1470710''>do</span> <span m=''1470830''>your</span> <span m=''1470930''>read,</span>
  <span m=''1471470''>you</span> <span m=''1471620''>might</span> <span m=''1471800''>get</span>
  <span m=''1472040''>a</span> <span m=''1472120''>different</span> <span m=''1472720''>result.</span>
  </p><p><span m=''1474540''>So</span> <span m=''1474900''>with</span> <span m=''1475240''>data</span>
  <span m=''1475420''>race</span> <span m=''1475680''>detection,</span> <span m=''1476950''>these</span>
  <span m=''1477190''>things</span> <span m=''1477440''>are</span> <span m=''1477540''>actually</span>
  <span m=''1477880''>getting</span> <span m=''1478130''>better.</span> <span m=''1478840''>There
  are</span> <span m=''1479050''>tools</span> <span m=''1479420''>out</span> <span
  m=''1479600''>there</span> <span m=''1479820''>that</span> <span m=''1479950''>will</span>
  <span m=''1480450''>essentially</span> <span m=''1480760''>generate</span> <span
  m=''1481140''>traces</span> <span m=''1482060''>as</span> <span m=''1482350''>your</span>
  <span m=''1482480''>program</span> <span m=''1482880''>is</span> <span m=''1482990''>running.</span>
  <span m=''1483530''>So</span> <span m=''1483640''>for</span> <span m=''1483770''>each</span>
  <span m=''1484000''>thread</span> <span m=''1484580''>you</span> <span m=''1484740''>instrumented</span>
  <span m=''1485540''>and</span> <span m=''1485740''>you</span> <span m=''1485810''>look</span>
  <span m=''1486010''>at</span> <span m=''1486140''>every</span> <span m=''1486450''>load</span>
  <span m=''1486680''>stored</span> <span m=''1486980''>at</span> <span m=''1487080''>executes.</span>
  <span m=''1488120''>Then</span> <span m=''1488230''>what</span> <span m=''1488330''>you</span>
  <span m=''1488420''>do</span> <span m=''1488600''>is</span> <span m=''1488750''>you</span>
  <span m=''1488860''>look</span> <span m=''1489070''>at</span> <span m=''1489210''>the</span>
  <span m=''1489300''>load</span> <span m=''1489550''>in</span> <span m=''1489660''>stores</span>
  <span m=''1490700''>between</span> <span m=''1491040''>the</span> <span m=''1491110''>difference</span>
  <span m=''1491470''>threads</span> <span m=''1491700''>and</span> <span m=''1491870''>see</span>
  <span m=''1492020''>if</span> <span m=''1492130''>there''s</span> <span m=''1492310''>any</span>
  <span m=''1492490''>intersections,</span> <span m=''1493410''>any</span> <span m=''1493830''>orderings</span>
  <span m=''1494300''>that</span> <span m=''1494460''>might</span> <span m=''1494520''>give</span>
  <span m=''1494760''>you</span> <span m=''1496090''>erroneous</span> <span m=''1496560''>behavior.</span>
  <span m=''1497600''>So</span> <span m=''1497690''>this</span> <span m=''1497830''>is</span>
  <span m=''1497920''>getting</span> <span m=''1498440''>better,</span> <span m=''1498800''>it''s</span>
  <span m=''1498970''>getting</span> <span m=''1499270''>more</span> <span m=''1499470''>automated.</span>
  <span m=''1500770''>Intel</span> <span m=''1501090''>Threadchecker</span> <span
  m=''1501260''>is</span> <span m=''1501770''>one</span> <span m=''1501950''>example.</span>
  <span m=''1502610''>There are</span> <span m=''1502840''>others.</span> <span m=''1505310''>I</span>
  <span m=''1505580''>really</span> <span m=''1505840''>think</span> <span m=''1506070''>the</span>
  <span m=''1506140''>trend in</span> <span m=''1506470''>debugging</span> <span m=''1506890''>will</span>
  <span m=''1507030''>be</span> <span m=''1507220''>towards</span> <span m=''1507670''>trace-based</span>
  <span m=''1510040''>systems.</span> <span m=''1510890''>You''ll</span> <span m=''1511070''>have</span>
  <span m=''1511360''>things</span> <span m=''1511570''>like</span> <span m=''1511720''>checkpointing.</span>
  <span m=''1512430''>So as</span> <span m=''1512710''>your</span> <span m=''1512760''>program</span>
  <span m=''1513090''>is</span> <span m=''1513220''>running</span> <span m=''1513780''>you
  can</span> <span m=''1514180''>take</span> <span m=''1514370''>a</span> <span m=''1514450''>snapshot</span>
  <span m=''1515370''>of</span> <span m=''1515550''>where</span> <span m=''1515810''>it
  is</span> <span m=''1515970''>in the</span> <span m=''1516080''>execution,</span>
  <span m=''1517020''>and</span> <span m=''1517190''>then you</span> <span m=''1517340''>can</span>
  <span m=''1517490''>use</span> <span m=''1517660''>that</span> <span m=''1517830''>snapshot</span>
  <span m=''1518260''>later</span> <span m=''1518430''>on</span> <span m=''1518590''>to</span>
  <span m=''1519000''>inspect it</span> <span m=''1519910''>and</span> <span m=''1520070''>see</span>
  <span m=''1520240''>what</span> <span m=''1520430''>went</span> <span m=''1520640''>wrong.</span>
  </p><p><span m=''1521390''>I</span> <span m=''1521700''>think</span> <span m=''1521860''>you</span>
  <span m=''1521920''>might</span> <span m=''1522070''>even</span> <span m=''1522300''>have</span>
  <span m=''1522490''>features</span> <span m=''1522880''>like</span> <span m=''1523040''>replay.</span>
  <span m=''1523380''>In</span> <span m=''1523540''>fact,</span> <span m=''1523800''>some</span>
  <span m=''1523900''>people</span> <span m=''1524120''>are</span> <span m=''1524220''>working</span>
  <span m=''1524500''>on</span> <span m=''1524610''>this</span> <span m=''1525100''>in</span>
  <span m=''1525750''>research</span> <span m=''1526350''>and</span> <span m=''1526710''>in</span>
  <span m=''1526800''>industry.</span> <span m=''1528120''>So</span> <span m=''1528300''>you</span>
  <span m=''1528470''>might</span> <span m=''1528690''>be</span> <span m=''1528780''>able</span>
  <span m=''1528980''>to</span> <span m=''1529140''>say</span> <span m=''1529940''>uh-oh,</span>
  <span m=''1530130''>something</span> <span m=''1530480''>went</span> <span m=''1530640''>wrong.</span>
  <span m=''1531000''>Here''s</span> <span m=''1531260''>my</span> <span m=''1531370''>list</span>
  <span m=''1531560''>of</span> <span m=''1531630''>checkpoints,</span> <span m=''1532360''>can</span>
  <span m=''1532530''>you</span> <span m=''1532650''>replay the</span> <span m=''1533210''>execution</span>
  <span m=''1533840''>from</span> <span m=''1534030''>this</span> <span m=''1534190''>particular</span>
  <span m=''1535300''>stage in the</span> <span m=''1535760''>computation.</span>
  <span m=''1536360''>So</span> <span m=''1536510''>it</span> <span m=''1536580''>helps</span>
  <span m=''1536820''>you</span> <span m=''1537470''>focus</span> <span m=''1537880''>down</span>
  <span m=''1538580''>in</span> <span m=''1539420''>the</span> <span m=''1539530''>entire</span>
  <span m=''1539920''>lifetime</span> <span m=''1540120''>of</span> <span m=''1540540''>execution</span>
  <span m=''1541250''>on a</span> <span m=''1541470''>particular</span> <span m=''1541820''>chunk</span>
  <span m=''1542200''>where</span> <span m=''1542320''>things</span> <span m=''1542970''>have</span>
  <span m=''1543220''>gone</span> <span m=''1543420''>wrong.</span> <span m=''1545710''>This</span>
  <span m=''1546150''>is</span> <span m=''1546280''>sort</span> <span m=''1546450''>of</span>
  <span m=''1546630''>a</span> <span m=''1546690''>personal</span> <span m=''1548410''>dream.</span>
  <span m=''1548900''>I</span> <span m=''1549010''>think</span> <span m=''1549210''>one</span>
  <span m=''1549400''>day</span> <span m=''1549550''>we''ll</span> <span m=''1549690''>have</span>
  <span m=''1549940''>the</span> <span m=''1550020''>equivalent</span> <span m=''1550470''>of</span>
  <span m=''1550590''>a</span> <span m=''1550660''>TiVo</span> <span m=''1550990''>for</span>
  <span m=''1551170''>your</span> <span m=''1551300''>programs,</span> <span m=''1553040''>and</span>
  <span m=''1553180''>you</span> <span m=''1553250''>can</span> <span m=''1553350''>use</span>
  <span m=''1553530''>it</span> <span m=''1553620''>for</span> <span m=''1553750''>debugging.</span>
  <span m=''1554350''>So my</span> <span m=''1554510''>program is</span> <span m=''1554970''>running,</span>
  <span m=''1555230''>something</span> <span m=''1555520''>goes</span> <span m=''1555750''>wrong,</span>
  <span m=''1556220''>I</span> <span m=''1556340''>can</span> <span m=''1556470''>rewind</span>
  <span m=''1556900''>it,</span> <span m=''1557340''>I</span> <span m=''1557470''>can</span>
  <span m=''1557610''>inspect things,</span> <span m=''1558280''>do</span> <span m=''1558390''>my</span>
  <span m=''1558550''>traditional</span> <span m=''1558970''>debugging,</span> <span
  m=''1559420''>change</span> <span m=''1559690''>things</span> <span m=''1559890''>maybe</span>
  <span m=''1560260''>even,</span> <span m=''1560720''>and</span> <span m=''1560890''>then</span>
  <span m=''1561080''>start</span> <span m=''1562250''>replaying</span> <span m=''1562700''>things</span>
  <span m=''1562990''>and</span> <span m=''1565250''>letting</span> <span m=''1565440''>the</span>
  <span m=''1565510''>program</span> <span m=''1565920''>execute.</span> <span m=''1567580''>In</span>
  <span m=''1567810''>fact,</span> <span m=''1568060''>we''re</span> <span m=''1568160''>working</span>
  <span m=''1568450''>on</span> <span m=''1568560''>things</span> <span m=''1568820''>like</span>
  <span m=''1568970''>this</span> <span m=''1569440''>here</span> <span m=''1569730''>at</span>
  <span m=''1569860''>MIT</span> <span m=''1570320''>and with</span> <span m=''1570470''>collaborators</span>
  <span m=''1571090''>elsewhere.</span> </p><p><span m=''1572140''>So,</span> <span
  m=''1572680''>this</span> <span m=''1572840''>was</span> <span m=''1573360''>a</span>
  <span m=''1573690''>short</span> <span m=''1574190''>lecture.</span> <span m=''1575890''>We''ll</span>
  <span m=''1575990''>take</span> <span m=''1576170''>a</span> <span m=''1576230''>break.</span>
  <span m=''1576530''>You</span> <span m=''1576670''>can</span> <span m=''1576810''>do</span>
  <span m=''1577010''>the</span> <span m=''1577300''>quizzes.</span> <span m=''1578240''>Note</span>
  <span m=''1578440''>on</span> <span m=''1578550''>the</span> <span m=''1578610''>quizzes,</span>
  <span m=''1579060''>there are</span> <span m=''1579220''>two</span> <span m=''1579410''>different</span>
  <span m=''1579690''>kinds</span> <span m=''1579940''>of</span> <span m=''1580030''>questions.</span>
  <span m=''1580720''>They''re very</span> <span m=''1581100''>similar,</span> <span
  m=''1581780''>just</span> <span m=''1582080''>one</span> <span m=''1582280''>word</span>
  <span m=''1582580''>is</span> <span m=''1583000''>different,</span> <span m=''1584250''>and</span>
  <span m=''1584450''>so</span> <span m=''1584570''>you''ll</span> <span m=''1584910''>want</span>
  <span m=''1585150''>to</span> <span m=''1585260''>just</span> <span m=''1585430''>keep</span>
  <span m=''1585610''>that in</span> <span m=''1585800''>mind</span> <span m=''1586010''>when</span>
  <span m=''1586140''>you''re</span> <span m=''1586270''>discussing</span> <span m=''1586720''>it</span>
  <span m=''1586800''>with</span> <span m=''1586950''>others.</span> <span m=''1588310''>Then</span>
  <span m=''1589120''>about</span> <span m=''1589510''>5,</span> <span m=''1589780''>10</span>
  <span m=''1589950''>minutes</span> <span m=''1590200''>and</span> <span m=''1590290''>then</span>
  <span m=''1590380''>we''ll</span> <span m=''1590710''>continue</span> <span m=''1591130''>with</span>
  <span m=''1591240''>the</span> <span m=''1591320''>rest</span> <span m=''1591660''>of</span>
  <span m=''1591720''>the</span> <span m=''1591790''>talk,</span> <span m=''1592650''>lecture</span>
  <span m=''1593080''>2.</span> <span m=''1593710''>Thanks.</span> </p>'
type: course
uid: ea7393549a19439453ecf5bb638bd0bd

---
None