---
about_this_resource_text: <p><strong>Topics covered:</strong> Cilk (Courtesy of Bradley
  Kuszmaul and Charles Leiserson. Used with permission.)</p><p><strong>Instructor:</strong>
  Bradley Kuszmaul</p><p>Subtitles are provided through the generous assistance of
  Rohan Pai.</p>
course_id: 6-189-multicore-programming-primer-january-iap-2007
embedded_media:
- id: l15.jpg
  parent_uid: 2edc2cbc9083e459e08f8478bb72036d
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-189-multicore-programming-primer-january-iap-2007/lecture-notes-and-video/l15-cilk/l15.jpg
  title: 'L15: Cilk'
  type: null
  uid: db792a600be52ffbee2a522da017afb6
- id: Video-YouTube-Stream
  media_location: X3_SfVMyE3k
  parent_uid: 2edc2cbc9083e459e08f8478bb72036d
  title: Video-YouTube-Stream
  type: Video
  uid: 11cb757f31d1bc7346228a70af89afd0
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/X3_SfVMyE3k/default.jpg
  parent_uid: 2edc2cbc9083e459e08f8478bb72036d
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 8466c112446ffbc32865a732437ad6ad
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id341597759
  parent_uid: 2edc2cbc9083e459e08f8478bb72036d
  title: Video-iTunes U-MP4
  type: Video
  uid: 6caa88e470c38d36c55a3acde0bdca24
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT6.189IAP07/ocw-6.189-iap07-lec15_300k.mp4
  parent_uid: 2edc2cbc9083e459e08f8478bb72036d
  title: Video-Internet Archive-MP4
  type: Video
  uid: 718dab21bd4956a5348bb0091bafe65a
- id: Thumbnail-OCW-JPG
  parent_uid: 2edc2cbc9083e459e08f8478bb72036d
  title: Thumbnail-OCW-JPG
  type: Thumbnail
  uid: 7e7f173a7324245429df2724e97f6827
- id: 3Play-3PlayYouTubeid-MP4
  media_location: X3_SfVMyE3k
  parent_uid: 2edc2cbc9083e459e08f8478bb72036d
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: b1e609d148e134ac89863038c544c14e
- id: X3_SfVMyE3k.srt
  parent_uid: 2edc2cbc9083e459e08f8478bb72036d
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-189-multicore-programming-primer-january-iap-2007/lecture-notes-and-video/l15-cilk/X3_SfVMyE3k.srt
  title: 3play caption file
  type: null
  uid: 185004ee3855520c30478ee2a26ea941
- id: X3_SfVMyE3k.pdf
  parent_uid: 2edc2cbc9083e459e08f8478bb72036d
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-189-multicore-programming-primer-january-iap-2007/lecture-notes-and-video/l15-cilk/X3_SfVMyE3k.pdf
  title: 3play pdf file
  type: null
  uid: 2410516361a8bb9b91ca43135977bb16
- id: Caption-3Play YouTube id-SRT
  parent_uid: 2edc2cbc9083e459e08f8478bb72036d
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: fb016be52b2663edb105298ea26ce4e0
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 2edc2cbc9083e459e08f8478bb72036d
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 81069d8af96bad04400ef0d35d431a0a
inline_embed_id: 46523203l15:cilk84562766
layout: video
order_index: null
parent_uid: 69885f30bae5c69316fc5492e4404278
related_resources_text: <p>Lecture Notes (<a target="_blank" title="Open in a new
  window." href="./resolveuid/34fc9599295ed0f54349a4d5ff989c2c">PDF - 1.4 MB</a>)</p>
short_url: l15-cilk
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-189-multicore-programming-primer-january-iap-2007/lecture-notes-and-video/l15-cilk
template_type: Tabbed
title: 'L15: Cilk'
transcript: '<p><span m=''30''>The</span> <span m=''130''>following</span> <span m=''540''>content</span>
  <span m=''1150''>is</span> <span m=''1250''>provided</span> <span m=''1710''>under</span>
  <span m=''1970''>a</span> <span m=''2030''>Creative</span> <span m=''2420''>Commons</span>
  <span m=''2700''>license.</span> <span m=''3860''>Your</span> <span m=''4110''>support</span>
  <span m=''4650''>will</span> <span m=''4790''>help</span> <span m=''5050''>MIT</span>
  <span m=''5460''>OpenCourseWare</span> <span m=''6280''>continue</span> <span m=''6790''>to</span>
  <span m=''6870''>offer</span> <span m=''7370''>high</span> <span m=''7540''>quality</span>
  <span m=''8050''>educational</span> <span m=''8650''>resources</span> <span m=''9250''>for</span>
  <span m=''9450''>free.</span> <span m=''10540''>To</span> <span m=''10670''>make</span>
  <span m=''10860''>a</span> <span m=''10920''>donation</span> <span m=''11630''>or</span>
  <span m=''11840''>view</span> <span m=''12310''>additional</span> <span m=''12740''>materials</span>
  <span m=''13250''>from</span> <span m=''13410''>hundreds</span> <span m=''13860''>of</span>
  <span m=''13940''>MIT</span> <span m=''14410''>courses,</span> <span m=''15360''>visit</span>
  <span m=''15720''>MIT</span> <span m=''15850''>OpenCourseWare</span> <span m=''16350''>at</span>
  <span m=''16610''>ocw.mit.edu.</span> </p><p><span m=''21030''>PROFESSOR: I</span>
  <span m=''21180''>guess</span> <span m=''23633''>[OBSCURED]</span> <span m=''26076''>Let''s
  get</span> <span m=''26564''>going.</span> <span m=''28030''>OK,</span> <span m=''28660''>should</span>
  <span m=''29180''>I</span> <span m=''29700''>introduce</span> <span m=''30220''>you?</span>
  </p><p><span m=''30300''>BRADLEY KUSZMAUL: If</span> <span m=''30403''>you</span>
  <span m=''30506''>want.</span> <span m=''30610''>I</span> <span m=''30750''>can
  introduce</span> <span m=''31130''>myself.</span> </p><p><span m=''31810''>PROFESSOR:
  We</span> <span m=''32160''>have</span> <span m=''32675''>Bradley Kuszmaul</span>
  <span m=''33190''>who''s</span> <span m=''33705''>been</span> <span m=''34220''>doing</span>
  <span m=''34735''>articles</span> <span m=''35250''>on</span> <span m=''35970''>Cilk?</span>
  <span m=''36921''>He''s</span> <span m=''37396''>a</span> <span m=''37872''>very</span>
  <span m=''38347''>interesting</span> <span m=''38823''>paralleling</span> <span
  m=''40370''>and</span> <span m=''42060''>also</span> <span m=''42585''>what you
  can</span> <span m=''43635''>say</span> <span m=''44160''>about the</span> <span
  m=''44682''>program</span> <span m=''45205''>It''s</span> <span m=''45728''>a</span>
  <span m=''46251''>very</span> <span m=''46774''>interesting</span> <span m=''47297''>project</span>
  <span m=''47820''>that</span> <span m=''48910''>coming</span> <span m=''49440''>for</span>
  <span m=''49930''>a while,</span> <span m=''50420''>and</span> <span m=''50911''>there''s</span>
  <span m=''51401''>a</span> <span m=''51892''>lot</span> <span m=''52382''>of interesting</span>
  <span m=''52873''>things</span> <span m=''53363''>he''s</span> <span m=''53854''>developed,</span>
  <span m=''54344''>and</span> <span m=''54835''>multi core</span> <span m=''55816''>becoming</span>
  <span m=''56306''>very</span> <span m=''56797''>important.</span> </p><p><span m=''59740''>BRADLEY
  KUSZMAUL: So</span> <span m=''59880''>how</span> <span m=''59980''>many of you</span>
  <span m=''60310''>people</span> <span m=''60640''>have</span> <span m=''60860''>ever</span>
  <span m=''61950''>heard</span> <span m=''62190''>of</span> <span m=''62320''>Cilk?</span>
  <span m=''64070''>Have</span> <span m=''64400''>used it?</span> <span m=''65870''>So</span>
  <span m=''67080''>those</span> <span m=''67300''>of</span> <span m=''67390''>you</span>
  <span m=''67720''>who</span> <span m=''67810''>have</span> <span m=''67900''>used</span>
  <span m=''67990''>it</span> <span m=''68110''>may</span> <span m=''69110''>find</span>
  <span m=''69370''>this</span> <span m=''69600''>talk</span> <span m=''70030''>old</span>
  <span m=''70340''>or</span> <span m=''70860''>whatever.</span> <span m=''73400''>So</span>
  <span m=''73550''>Cilk</span> <span m=''74190''>is</span> <span m=''74520''>a</span>
  <span m=''74850''>system</span> <span m=''75270''>that</span> <span m=''75410''>runs</span>
  <span m=''75790''>on</span> <span m=''76000''>a</span> <span m=''76080''>shared-memory</span>
  <span m=''76840''>multiprocessor.</span> <span m=''77750''>So</span> <span m=''77900''>this</span>
  <span m=''78130''>is</span> <span m=''78420''>not</span> <span m=''79250''>like</span>
  <span m=''79560''>the</span> <span m=''79760''>system</span> <span m=''80100''>you''ve</span>
  <span m=''80250''>been</span> <span m=''80920''>programming</span> <span m=''81560''>for</span>
  <span m=''81690''>this</span> <span m=''81900''>class.</span> <span m=''82720''>This</span>
  <span m=''82940''>kind</span> <span m=''83120''>of</span> <span m=''83200''>machine</span>
  <span m=''83680''>you</span> <span m=''83810''>have</span> <span m=''84030''>processors,</span>
  <span m=''84870''>which</span> <span m=''84980''>each</span> <span m=''85230''>have</span>
  <span m=''85440''>cache</span> <span m=''86560''>and</span> <span m=''86820''>some</span>
  <span m=''87190''>sort</span> <span m=''87360''>of</span> <span m=''87430''>a</span>
  <span m=''87480''>network</span> <span m=''87920''>and</span> <span m=''88010''>a</span>
  <span m=''88040''>bunch</span> <span m=''88230''>of</span> <span m=''88320''>memory</span>
  <span m=''88840''>and</span> <span m=''89660''>when the</span> <span m=''90200''>processors</span>
  <span m=''90920''>do</span> <span m=''91380''>memory</span> <span m=''91750''>operations</span>
  <span m=''92960''>they</span> <span m=''93230''>are</span> <span m=''93490''>all</span>
  <span m=''93720''>on</span> <span m=''93810''>the</span> <span m=''93880''>same</span>
  <span m=''94110''>address</span> <span m=''94480''>space</span> <span m=''94890''>and</span>
  <span m=''95030''>it''s</span> <span m=''95970''>typically--</span> <span m=''96780''>the</span>
  <span m=''96870''>memory</span> <span m=''97150''>system</span> <span m=''97440''>provides</span>
  <span m=''97790''>some</span> <span m=''97980''>sort</span> <span m=''98160''>of</span>
  <span m=''98220''>coherence</span> <span m=''98800''>like</span> <span m=''99000''>strong</span>
  <span m=''99380''>consistency</span> <span m=''100110''>or</span> <span m=''100260''>maybe</span>
  <span m=''100500''>released</span> <span m=''100840''>consistency.</span> <span
  m=''104690''>We''re</span> <span m=''104880''>interested</span> <span m=''105260''>in</span>
  <span m=''105360''>the</span> <span m=''105440''>case</span> <span m=''105870''>where</span>
  <span m=''106340''>the</span> <span m=''107050''>distance</span> <span m=''108430''>from</span>
  <span m=''109180''>processors</span> <span m=''110050''>to</span> <span m=''110170''>other</span>
  <span m=''110380''>processors</span> <span m=''111080''>into</span> <span m=''111350''>a</span>
  <span m=''111400''>processors</span> <span m=''111950''>to</span> <span m=''112070''>memory</span>
  <span m=''112420''>may be</span> <span m=''112820''>nonuniform</span> <span m=''114360''>and</span>
  <span m=''114520''>so</span> <span m=''114660''>it''s</span> <span m=''114800''>important</span>
  <span m=''115240''>to</span> <span m=''115320''>use</span> <span m=''115550''>the</span>
  <span m=''115630''>cache</span> <span m=''115980''>well</span> <span m=''116560''>in</span>
  <span m=''116710''>this</span> <span m=''116840''>kind</span> <span m=''117040''>of</span>
  <span m=''117140''>machine</span> <span m=''117500''>because</span> <span m=''122180''>you</span>
  <span m=''122320''>can''t</span> <span m=''122500''>just</span> <span m=''122650''>ignore</span>
  <span m=''122930''>the</span> <span m=''123040''>cache.</span> <span m=''123600''>So</span>
  <span m=''124490''>sort</span> <span m=''124690''>of</span> <span m=''124780''>the</span>
  <span m=''124880''>technology</span> <span m=''125510''>that</span> <span m=''125576''>I''m</span>
  <span m=''125643''>going</span> <span m=''125710''>to</span> <span m=''125800''>talk</span>
  <span m=''126090''>about</span> <span m=''126590''>for</span> <span m=''126810''>this</span>
  <span m=''127020''>kind</span> <span m=''127300''>of</span> <span m=''127400''>system</span>
  <span m=''127850''>is</span> <span m=''127980''>called</span> <span m=''128300''>Cilk.</span>
  <span m=''129310''>Cilk</span> <span m=''129560''>is</span> <span m=''129770''>a</span>
  <span m=''129930''>C</span> <span m=''130220''>language</span> <span m=''130870''>and</span>
  <span m=''131280''>it</span> <span m=''131580''>does</span> <span m=''131920''>dynamic</span>
  <span m=''132440''>multithreading</span> <span m=''133240''>and</span> <span m=''133400''>it</span>
  <span m=''133470''>has</span> <span m=''133660''>a provably</span> <span m=''134320''>good</span>
  <span m=''134510''>runtime</span> <span m=''134940''>system.</span> <span m=''135390''>So
  I''ll</span> <span m=''135550''>talk</span> <span m=''135780''>about</span> <span
  m=''136010''>what</span> <span m=''136380''>those</span> <span m=''136620''>all</span>
  <span m=''136830''>mean.</span> </p><p><span m=''138630''>Cilk</span> <span m=''138970''>runs</span>
  <span m=''139320''>on</span> <span m=''139770''>shared-memory</span> <span m=''140280''>machines</span>
  <span m=''140770''>like</span> <span m=''140970''>Suns</span> <span m=''141380''>and</span>
  <span m=''141700''>SGIs</span> <span m=''142420''>and</span> <span m=''143150''>well,</span>
  <span m=''143380''>you</span> <span m=''143710''>probably</span> <span m=''144030''>can''t</span>
  <span m=''144210''>find</span> <span m=''144420''>Alphaservers</span> <span m=''145130''>anymore.</span>
  <span m=''145920''>It runs</span> <span m=''146300''>on</span> <span m=''147250''>SMPs</span>
  <span m=''147920''>like</span> <span m=''148120''>that</span> <span m=''148250''>are</span>
  <span m=''148410''>in</span> <span m=''148510''>everybody''s</span> <span m=''148890''>laptops</span>
  <span m=''149470''>now.</span> <span m=''150260''>There''s</span> <span m=''150405''>been</span>
  <span m=''150830''>several</span> <span m=''151760''>interesting</span> <span m=''152150''>applications</span>
  <span m=''153290''>written</span> <span m=''153560''>in</span> <span m=''153690''>Cilk</span>
  <span m=''154630''>including</span> <span m=''155190''>virus</span> <span m=''155530''>shell</span>
  <span m=''155820''>assembly,</span> <span m=''157490''>graphics</span> <span m=''157930''>rendering,</span>
  <span m=''158440''>n-body</span> <span m=''158830''>simulation.</span> <span m=''160050''>We</span>
  <span m=''160240''>did</span> <span m=''160570''>a</span> <span m=''160800''>bunch
  of</span> <span m=''160910''>chess</span> <span m=''161230''>programs</span> <span
  m=''161790''>because</span> <span m=''162840''>they</span> <span m=''162960''>were</span>
  <span m=''163180''>sort</span> <span m=''163350''>of</span> <span m=''163460''>the</span>
  <span m=''164120''>raison d''etre</span> <span m=''165160''>for</span> <span m=''165940''>Cilk.</span>
  <span m=''168740''>One</span> <span m=''168900''>of</span> <span m=''168980''>the</span>
  <span m=''169070''>features</span> <span m=''169570''>about</span> <span m=''169810''>Cilk
  is</span> <span m=''170010''>that</span> <span m=''170210''>it</span> <span m=''170380''>automatically</span>
  <span m=''171270''>manages</span> <span m=''171900''>a</span> <span m=''172010''>lot</span>
  <span m=''172200''>of</span> <span m=''172280''>the</span> <span m=''172360''>low-level</span>
  <span m=''172830''>issues.</span> <span m=''173300''>You</span> <span m=''173450''>don''t</span>
  <span m=''173650''>have</span> <span m=''173840''>to</span> <span m=''173950''>do</span>
  <span m=''175140''>load</span> <span m=''175410''>balancing,</span> <span m=''176080''>you</span>
  <span m=''176180''>don''t</span> <span m=''176330''>have</span> <span m=''176430''>to</span>
  <span m=''176510''>write</span> <span m=''177340''>in</span> <span m=''177460''>protocols.</span>
  <span m=''179210''>You</span> <span m=''179300''>basically</span> <span m=''179730''>write</span>
  <span m=''179960''>programs</span> <span m=''181030''>that</span> <span m=''181310''>look</span>
  <span m=''181500''>a</span> <span m=''181560''>lot</span> <span m=''181770''>more</span>
  <span m=''182000''>like</span> <span m=''182240''>the</span> <span m=''182310''>ordinary</span>
  <span m=''182680''>Cilk</span> <span m=''182970''>programs</span> <span m=''183510''>instead</span>
  <span m=''183810''>of</span> <span m=''183890''>saying</span> <span m=''185700''>first</span>
  <span m=''185970''>I''m</span> <span m=''186050''>going to</span> <span m=''186250''>do</span>
  <span m=''186440''>this</span> <span m=''186980''>and</span> <span m=''187150''>then</span>
  <span m=''187590''>I''m</span> <span m=''187680''>going</span> <span m=''187930''>to</span>
  <span m=''188030''>set this</span> <span m=''188200''>variable</span> <span m=''188750''>and</span>
  <span m=''188900''>then</span> <span m=''189040''>somebody</span> <span m=''189370''>else</span>
  <span m=''189620''>is</span> <span m=''189700''>going</span> <span m=''189860''>to</span>
  <span m=''189950''>read</span> <span m=''190250''>that</span> <span m=''190480''>variable</span>
  <span m=''190990''>and</span> <span m=''191600''>that''s</span> <span m=''191810''>a</span>
  <span m=''191870''>protocol</span> <span m=''192490''>and</span> <span m=''192600''>those</span>
  <span m=''192750''>are</span> <span m=''192840''>very</span> <span m=''193070''>difficult</span>
  <span m=''193460''>to</span> <span m=''194150''>get</span> <span m=''194380''>right.</span>
  </p><p><span m=''195240''>AUDIENCE: [OBSCURED]</span> </p><p><span m=''197720''>BRADLEY
  KUSZMAUL: Yeah,</span> <span m=''198390''>I''ll</span> <span m=''198500''>mention</span>
  <span m=''198830''>that</span> <span m=''199460''>a little</span> <span m=''200050''>bit
  later.</span> <span m=''200900''>We</span> <span m=''201030''>had</span> <span m=''202070''>award-winning</span>
  <span m=''202830''>chess</span> <span m=''203190''>player.</span> <span m=''204390''>So</span>
  <span m=''204900''>to</span> <span m=''205040''>explain</span> <span m=''205540''>what</span>
  <span m=''205650''>Cilk''s</span> <span m=''206320''>about</span> <span m=''206770''>I''ll</span>
  <span m=''207200''>talk</span> <span m=''207440''>about</span> <span m=''207710''>Fibonacci.</span>
  <span m=''208390''>Now</span> <span m=''208530''>Fibonacci,</span> <span m=''209960''>this</span>
  <span m=''210190''>is</span> <span m=''211190''>just to</span> <span m=''211420''>review</span>
  <span m=''211770''>in</span> <span m=''211870''>case</span> <span m=''212100''>you</span>
  <span m=''212200''>don''t</span> <span m=''212410''>know</span> <span m=''212510''>C.</span>
  <span m=''213080''>You all</span> <span m=''213240''>know</span> <span m=''213380''>C</span>
  <span m=''213660''>right?</span> <span m=''214400''>So</span> <span m=''215400''>Fibonacci</span>
  <span m=''215610''>is</span> <span m=''216140''>the</span> <span m=''216240''>function</span>
  <span m=''216950''>that</span> <span m=''217850''>each</span> <span m=''218100''>number</span>
  <span m=''218470''>is</span> <span m=''218660''>the</span> <span m=''218750''>sum</span>
  <span m=''218990''>of</span> <span m=''219080''>the</span> <span m=''219150''>previous</span>
  <span m=''219630''>two</span> <span m=''219890''>Fibonacci</span> <span m=''220470''>numbers.</span>
  <span m=''221330''>And</span> <span m=''221640''>this</span> <span m=''221860''>is</span>
  <span m=''221990''>an</span> <span m=''222100''>implementation</span> <span m=''223480''>that</span>
  <span m=''224310''>basically</span> <span m=''224900''>does</span> <span m=''225210''>that</span>
  <span m=''226340''>computation</span> <span m=''226970''>directly.</span> <span
  m=''227400''>The</span> <span m=''227510''>Fibonacci</span> <span m=''227790''>of</span>
  <span m=''227980''>n</span> <span m=''228120''>if</span> <span m=''228250''>n</span>
  <span m=''228550''>is</span> <span m=''228830''>less</span> <span m=''228980''>than</span>
  <span m=''229380''>2,</span> <span m=''229630''>it''s</span> <span m=''229820''>just</span>
  <span m=''230110''>n.</span> <span m=''230410''>So</span> <span m=''230630''>Fibonacci</span>
  <span m=''231020''>of</span> <span m=''231230''>zero is</span> <span m=''231750''>zero,</span>
  <span m=''232180''>1</span> <span m=''232540''>is</span> <span m=''232700''>1.</span>
  <span m=''233840''>2,</span> <span m=''234290''>the</span> <span m=''234410''>Fibonacci''s--</span>
  <span m=''235120''>well,</span> <span m=''235370''>then</span> <span m=''235500''>you</span>
  <span m=''235560''>have</span> <span m=''235650''>to</span> <span m=''235750''>do</span>
  <span m=''235850''>the</span> <span m=''236530''>recursion,</span> <span m=''237140''>so</span>
  <span m=''237820''>you compute</span> <span m=''238380''>Fibonacci</span> <span
  m=''238520''>of</span> <span m=''238610''>n</span> <span m=''238950''>minus</span>
  <span m=''239210''>1</span> <span m=''239760''>and</span> <span m=''240010''>Fibonacci</span>
  <span m=''240130''>of</span> <span m=''240210''>n</span> <span m=''240390''>minus</span>
  <span m=''240580''>2</span> <span m=''240740''>and</span> <span m=''241420''>sum
  them</span> <span m=''241750''>together</span> <span m=''242200''>and</span> <span
  m=''242320''>that''s</span> <span m=''242570''>Fibonacci</span> <span m=''242690''>of</span>
  <span m=''242940''>n.</span> <span m=''244500''>One</span> <span m=''245630''>observation</span>
  <span m=''246360''>about</span> <span m=''246620''>this</span> <span m=''246750''>function</span>
  <span m=''247100''>is</span> <span m=''247250''>it''s</span> <span m=''247400''>a</span>
  <span m=''247480''>really</span> <span m=''247890''>slow</span> <span m=''249330''>implementation</span>
  <span m=''250090''>of</span> <span m=''250170''>Fibonacci.</span> <span m=''252430''>You</span>
  <span m=''252520''>all</span> <span m=''252700''>know</span> <span m=''252770''>how</span>
  <span m=''252870''>to</span> <span m=''252950''>do</span> <span m=''253050''>this</span>
  <span m=''253210''>faster?</span> <span m=''253610''>How</span> <span m=''253780''>fast</span>
  <span m=''254120''>can</span> <span m=''254210''>you</span> <span m=''254300''>do</span>
  <span m=''254430''>Fibonacci?</span> <span m=''256570''>You</span> <span m=''256720''>all</span>
  <span m=''256860''>know</span> <span m=''257030''>this,</span> <span m=''259060''>How</span>
  <span m=''259240''>fast</span> <span m=''259540''>is</span> <span m=''259640''>this</span>
  <span m=''259860''>one?</span> </p><p><span m=''260703''>AUDIENCE: [OBSCURED].</span>
  </p><p><span m=''262960''>BRADLEY KUSZMAUL: So</span> <span m=''263600''>for</span>
  <span m=''263880''>those of you</span> <span m=''264010''>who don''t</span> <span
  m=''264180''>know--</span> <span m=''265450''>certainly</span> <span m=''265730''>know</span>
  <span m=''266210''>how to</span> <span m=''266370''>compute</span> <span m=''266860''>Fibonacci</span>
  <span m=''266960''>in</span> <span m=''267310''>linear</span> <span m=''267650''>time</span>
  <span m=''267960''>just</span> <span m=''268200''>by</span> <span m=''268790''>keeping</span>
  <span m=''269070''>track</span> <span m=''269340''>of</span> <span m=''269410''>the</span>
  <span m=''269500''>most</span> <span m=''269750''>recent</span> <span m=''270090''>two.</span>
  <span m=''271340''>1,</span> <span m=''271560''>1,</span> <span m=''271860''>2,</span>
  <span m=''272170''>3,</span> <span m=''272480''>5,</span> <span m=''273310''>you
  just</span> <span m=''273600''>do</span> <span m=''273730''>it.</span> <span m=''274230''>This</span>
  <span m=''274410''>is</span> <span m=''274550''>exponential</span> <span m=''275160''>time</span>
  <span m=''275480''>and</span> <span m=''275580''>there''s</span> <span m=''275800''>an</span>
  <span m=''275880''>algorithm</span> <span m=''276880''>that</span> <span m=''277090''>does
  it</span> <span m=''277450''>in</span> <span m=''277560''>logarithmic</span> <span
  m=''278080''>time.</span> <span m=''278350''>So</span> <span m=''278470''>this</span>
  <span m=''279430''>implementation</span> <span m=''280220''>is</span> <span m=''280520''>doubly,</span>
  <span m=''281060''>exponentially</span> <span m=''282330''>bad.</span> <span m=''284380''>But</span>
  <span m=''284580''>it''s</span> <span m=''284710''>good</span> <span m=''284990''>as</span>
  <span m=''285130''>a</span> <span m=''285180''>didactic</span> <span m=''285640''>example</span>
  <span m=''286230''>because</span> <span m=''286380''>it''s</span> <span m=''286500''>easy</span>
  <span m=''286690''>to</span> <span m=''286760''>understand.</span> <span m=''288020''>So</span>
  <span m=''288160''>to</span> <span m=''288240''>turn</span> <span m=''288710''>this</span>
  <span m=''288900''>into</span> <span m=''288995''>Cilk</span> <span m=''289090''>we</span>
  <span m=''289210''>just</span> <span m=''289400''>add</span> <span m=''289710''>some</span>
  <span m=''289850''>key</span> <span m=''290050''>words</span> <span m=''290420''>and
  I''ll</span> <span m=''290660''>talk</span> <span m=''290910''>about</span> <span
  m=''291110''>what</span> <span m=''291240''>the</span> <span m=''291320''>key</span>
  <span m=''291470''>words</span> <span m=''291740''>are</span> <span m=''291880''>in</span>
  <span m=''291980''>a</span> <span m=''292030''>minute,</span> <span m=''292890''>but</span>
  <span m=''293580''>the</span> <span m=''293730''>key</span> <span m=''294280''>thing</span>
  <span m=''294440''>to</span> <span m=''294600''>understand</span> <span m=''294950''>about</span>
  <span m=''295170''>this</span> <span m=''295370''>is</span> <span m=''295620''>if
  you</span> <span m=''295700''>delete</span> <span m=''296140''>the</span> <span
  m=''296230''>key</span> <span m=''296490''>words</span> <span m=''297020''>you</span>
  <span m=''297170''>have</span> <span m=''297950''>a</span> <span m=''298050''>C</span>
  <span m=''298260''>program</span> <span m=''299160''>and</span> <span m=''299430''>Cilk</span>
  <span m=''300540''>programs</span> <span m=''300780''>have the</span> <span m=''300860''>property</span>
  <span m=''301450''>that</span> <span m=''302040''>one</span> <span m=''302270''>of</span>
  <span m=''302380''>the</span> <span m=''302530''>legal</span> <span m=''303210''>semantics</span>
  <span m=''303890''>for</span> <span m=''304700''>the Cilk</span> <span m=''304960''>program</span>
  <span m=''306070''>is</span> <span m=''306530''>the</span> <span m=''306620''>C</span>
  <span m=''306840''>program</span> <span m=''307570''>that you</span> <span m=''307820''>get</span>
  <span m=''308020''>by</span> <span m=''308150''>deleting</span> <span m=''308460''>the</span>
  <span m=''308540''>key</span> <span m=''308710''>words.</span> <span m=''310210''>Now</span>
  <span m=''310310''>there''s</span> <span m=''310480''>other</span> <span m=''310680''>possible</span>
  <span m=''311080''>semantics</span> <span m=''311490''>you</span> <span m=''311580''>could</span>
  <span m=''311720''>get</span> <span m=''311990''>because--</span> <span m=''313020''>not</span>
  <span m=''313230''>for</span> <span m=''313320''>this</span> <span m=''313520''>function,</span>
  <span m=''313830''>this</span> <span m=''313930''>function</span> <span m=''314260''>always</span>
  <span m=''314510''>produces</span> <span m=''315280''>the</span> <span m=''315390''>same</span>
  <span m=''315620''>answer</span> <span m=''316610''>because</span> <span m=''316770''>there''s</span>
  <span m=''316920''>no</span> <span m=''317040''>race</span> <span m=''317300''>conditions</span>
  <span m=''317780''>in</span> <span m=''317910''>it.</span> <span m=''318450''>But</span>
  <span m=''318790''>for</span> <span m=''318930''>programs</span> <span m=''319390''>that</span>
  <span m=''319500''>have</span> <span m=''319600''>races</span> <span m=''320040''>you</span>
  <span m=''320130''>may</span> <span m=''320240''>have</span> <span m=''320440''>other</span>
  <span m=''320660''>semantics</span> <span m=''321760''>that</span> <span m=''321910''>the</span>
  <span m=''321990''>system</span> <span m=''322570''>could</span> <span m=''322730''>provide.</span>
  <span m=''324150''>And</span> <span m=''324740''>so</span> <span m=''324870''>this</span>
  <span m=''325030''>kind</span> <span m=''325230''>of</span> <span m=''325760''>a</span>
  <span m=''325880''>language</span> <span m=''326250''>extension</span> <span m=''326720''>where</span>
  <span m=''326870''>you</span> <span m=''327010''>can</span> <span m=''327300''>sort</span>
  <span m=''327480''>of</span> <span m=''327580''>delete</span> <span m=''328000''>the</span>
  <span m=''328100''>extensions</span> <span m=''328840''>and</span> <span m=''329000''>get</span>
  <span m=''329670''>a</span> <span m=''330720''>correct</span> <span m=''331330''>implementation</span>
  <span m=''332590''>of the</span> <span m=''332810''>parallel</span> <span m=''333180''>program</span>
  <span m=''334330''>is</span> <span m=''334570''>called</span> <span m=''334850''>a</span>
  <span m=''334890''>faithful</span> <span m=''335410''>extension.</span> <span m=''336150''>A
  lot</span> <span m=''336500''>of</span> <span m=''336580''>languages</span> <span
  m=''337290''>like</span> <span m=''337510''>OpenMP</span> <span m=''338670''>have</span>
  <span m=''338860''>properties</span> <span m=''339420''>that</span> <span m=''339570''>if</span>
  <span m=''339700''>you</span> <span m=''340380''>had</span> <span m=''340560''>these</span>
  <span m=''340730''>directives</span> <span m=''341320''>and</span> <span m=''341410''>if</span>
  <span m=''341510''>you</span> <span m=''341590''>delete</span> <span m=''341910''>them,</span>
  <span m=''342020''>it</span> <span m=''342190''>will</span> <span m=''342360''>change</span>
  <span m=''342740''>the</span> <span m=''342910''>semantics</span> <span m=''343083''>of</span>
  <span m=''343256''>your</span> <span m=''343430''>program</span> <span m=''344220''>and</span>
  <span m=''344380''>so</span> <span m=''344490''>you</span> <span m=''344630''>have</span>
  <span m=''344820''>to</span> <span m=''344910''>be</span> <span m=''344990''>very</span>
  <span m=''345280''>careful.</span> </p><p><span m=''346160''>Now if</span> <span
  m=''346270''>you''re</span> <span m=''346670''>careful</span> <span m=''347190''>about</span>
  <span m=''347500''>programming</span> <span m=''348030''>OpenMP</span> <span m=''348570''>you</span>
  <span m=''348660''>can</span> <span m=''348820''>make</span> <span m=''349070''>it</span>
  <span m=''349190''>so</span> <span m=''349310''>that</span> <span m=''349480''>it''s</span>
  <span m=''349670''>faithful,</span> <span m=''350990''>that</span> <span m=''351120''>has</span>
  <span m=''351320''>this</span> <span m=''351460''>property.</span> <span m=''351990''>But</span>
  <span m=''352240''>that''s</span> <span m=''352410''>not</span> <span m=''352710''>always</span>
  <span m=''353070''>the</span> <span m=''353170''>case</span> <span m=''353510''>that</span>
  <span m=''354450''>it is.</span> <span m=''357600''>Sure.</span> </p><p><span m=''358896''>AUDIENCE:
  Is</span> <span m=''359390''>it</span> <span m=''359720''>built</span> <span m=''360202''>on</span>
  <span m=''360684''>the different..</span> </p><p><span m=''364060''>BRADLEY KUSZMAUL:
  C 77.</span> <span m=''366310''>No,</span> <span m=''366730''>C 89.</span> </p><p><span
  m=''366940''>AUDIENCE: OK,</span> <span m=''367340''>so</span> <span m=''367740''>there''s</span>
  <span m=''367960''>no</span> <span m=''368447''>presumption</span> <span m=''368934''>or</span>
  <span m=''369422''>any</span> <span m=''369909''>alias</span> <span m=''370396''>involved?</span>
  <span m=''372346''>It''s</span> <span m=''372833''>assumed</span> <span m=''373320''>that</span>
  <span m=''373808''>the</span> <span m=''374295''>[OBSCURED].</span> </p><p><span
  m=''375570''>BRADLEY KUSZMAUL: So</span> <span m=''375810''>the</span> <span m=''375970''>issue</span>
  <span m=''376400''>of</span> <span m=''376580''>restricted</span> <span m=''377060''>pointers,</span>
  <span m=''377450''>for</span> <span m=''377550''>example?</span> </p><p><span m=''378095''>AUDIENCE:
  Restricted</span> <span m=''378640''>pointers.</span> </p><p><span m=''380820''>BRADLEY
  KUSZMAUL: So</span> <span m=''381060''>Cilk</span> <span m=''381120''>turns</span>
  <span m=''381350''>out</span> <span m=''381500''>to</span> <span m=''381610''>work</span>
  <span m=''381860''>with</span> <span m=''381980''>C 99</span> <span m=''382740''>as</span>
  <span m=''382890''>well.</span> </p><p><span m=''383535''>AUDIENCE: But</span> <span
  m=''383930''>is</span> <span m=''384200''>the</span> <span m=''384610''>presumption</span>
  <span m=''385310''>though</span> <span m=''385827''>for</span> <span m=''386345''>a</span>
  <span m=''386862''>pointer</span> <span m=''387120''>that</span> <span m=''387380''>it
  could</span> <span m=''387897''>alias?</span> </p><p><span m=''389450''>BRADLEY
  KUSZMAUL: The</span> <span m=''389740''>Cilk</span> <span m=''389910''>compiler</span>
  <span m=''390140''>makes</span> <span m=''390380''>no</span> <span m=''390510''>assumptions</span>
  <span m=''391020''>about</span> <span m=''391270''>that.</span> <span m=''392680''>If
  you</span> <span m=''393080''>write</span> <span m=''393260''>a</span> <span m=''393350''>program</span>
  <span m=''394300''>and</span> <span m=''394750''>the</span> <span m=''394980''>back
  end--</span> <span m=''395310''>Cilk</span> <span m=''397700''>works</span> <span
  m=''398200''>and I''ll</span> <span m=''398470''>talk</span> <span m=''398710''>about</span>
  <span m=''398960''>this</span> <span m=''399370''>in</span> <span m=''399450''>a</span>
  <span m=''399530''>couple</span> <span m=''399750''>minutes.</span> <span m=''400040''>Cilk</span>
  <span m=''400210''>works</span> <span m=''400420''>by</span> <span m=''400590''>transforming</span>
  <span m=''401220''>this</span> <span m=''401410''>into</span> <span m=''401780''>a</span>
  <span m=''401890''>C</span> <span m=''402080''>program</span> <span m=''403520''>that</span>
  <span m=''403940''>has--</span> <span m=''404940''>when</span> <span m=''405680''>you</span>
  <span m=''405810''>run</span> <span m=''406110''>it on</span> <span m=''406250''>one</span>
  <span m=''406450''>processor</span> <span m=''407560''>it''s</span> <span m=''407760''>just</span>
  <span m=''407980''>the</span> <span m=''408060''>original</span> <span m=''408410''>C</span>
  <span m=''408630''>program</span> <span m=''409340''>in</span> <span m=''409470''>effect.</span>
  <span m=''410370''>And</span> <span m=''410570''>so</span> <span m=''411290''>if</span>
  <span m=''411450''>you</span> <span m=''411550''>have</span> <span m=''411750''>a</span>
  <span m=''411790''>dialect</span> <span m=''412120''>of</span> <span m=''412220''>C</span>
  <span m=''412580''>that</span> <span m=''412730''>has</span> <span m=''412980''>restricted</span>
  <span m=''413420''>pointers</span> <span m=''413766''>and</span> <span m=''414113''>a</span>
  <span m=''414460''>compiler</span> <span m=''414970''>that--</span> </p><p><span
  m=''415950''>PROFESSOR: You''re</span> <span m=''416190''>taking</span> <span m=''416490''>the</span>
  <span m=''416760''>assumptions</span> <span m=''417360''>that</span> <span m=''417460''>if</span>
  <span m=''417750''>you</span> <span m=''417980''>make</span> <span m=''418360''>a</span>
  <span m=''418980''>mistake--</span> </p><p><span m=''419110''>BRADLEY KUSZMAUL:
  If</span> <span m=''419380''>you</span> <span m=''419790''>make</span> <span m=''420180''>a</span>
  <span m=''420283''>mistake</span> <span m=''420386''>the</span> <span m=''420490''>language</span>
  <span m=''421090''>doens''t</span> <span m=''422610''>stop</span> <span m=''422960''>you</span>
  <span m=''423310''>from</span> <span m=''423717''>making</span> <span m=''424125''>the</span>
  <span m=''424532''>mistake.</span> </p><p><span m=''424940''>AUDIENCE: Well,</span>
  <span m=''425986''>but in</span> <span m=''426510''>C 89</span> <span m=''426770''>there''s</span>
  <span m=''427256''>not</span> <span m=''427743''>a mistake.</span> <span m=''428230''>There''s
  no</span> <span m=''428580''>assumption</span> <span m=''429076''>about</span> <span
  m=''429572''>aliasing, right?</span> <span m=''430068''>It</span> <span m=''430564''>could
  alias.</span> <span m=''431060''>So</span> <span m=''431830''>if</span> <span m=''432314''>I</span>
  <span m=''432798''>said</span> <span m=''433282''>--</span> </p><p><span m=''434250''>BRADLEY
  KUSZMAUL: Because</span> <span m=''434476''>of</span> <span m=''434703''>the</span>
  <span m=''434930''>aliasing</span> <span m=''435920''>you write</span> <span m=''436080''>a</span>
  <span m=''436232''>program</span> <span m=''436384''>that</span> <span m=''436536''>has</span>
  <span m=''436688''>a</span> <span m=''436840''>race</span> <span m=''437362''>condition</span>
  <span m=''437884''>in</span> <span m=''438406''>it,</span> <span m=''438928''>which</span>
  <span m=''439102''>is</span> <span m=''439276''>erroneous--</span> </p><p><span
  m=''439450''>AUDIENCE: It</span> <span m=''439545''>would</span> <span m=''439640''>be</span>
  <span m=''440800''>valid?</span> </p><p><span m=''442930''>BRADLEY KUSZMAUL: No,</span>
  <span m=''443160''>it''d still be</span> <span m=''443280''>valid.</span> <span
  m=''443360''>It</span> <span m=''443600''>would</span> <span m=''443650''>just</span>
  <span m=''443700''>have</span> <span m=''443750''>a</span> <span m=''444210''>race</span>
  <span m=''444283''>in</span> <span m=''444356''>it</span> <span m=''444430''>and</span>
  <span m=''444590''>you would</span> <span m=''444870''>have a</span> <span m=''445120''>non-determinate</span>
  <span m=''445760''>result.</span> </p><p><span m=''446910''>PROFESSOR:</span> <span
  m=''447010''>It may not do </span> <span m=''447110''> what</span> <span m=''447580''>you
  want.</span> </p><p><span m=''447900''>BRADLEY KUSZMAUL: It</span> <span m=''448090''>may</span>
  <span m=''448130''>not</span> <span m=''448170''>do</span> <span m=''448210''>what</span>
  <span m=''448250''>you</span> <span m=''448390''>want,</span> <span m=''449350''>but</span>
  <span m=''449570''>one</span> <span m=''449740''>of</span> <span m=''449830''>the</span>
  <span m=''449900''>legal</span> <span m=''450240''>executions</span> <span m=''450830''>of</span>
  <span m=''450930''>that</span> <span m=''451340''>parallel</span> <span m=''451620''>program</span>
  <span m=''451990''>is</span> <span m=''452250''>the original</span> <span m=''452370''>C</span>
  <span m=''452843''>program.</span> </p><p><span m=''454060''>AUDIENCE: So</span>
  <span m=''454420''>there''s</span> <span m=''454780''>no</span> <span m=''455140''>extra.</span>
  </p><p><span m=''457300''>BRADLEY KUSZMAUL: At</span> <span m=''457690''>the</span>
  <span m=''457870''>sort</span> <span m=''458030''>of</span> <span m=''458110''>level</span>
  <span m=''458390''>of</span> <span m=''458470''>doing</span> <span m=''458680''>analysis,</span>
  <span m=''459270''>Cilk</span> <span m=''459500''>doesn''t</span> <span m=''460190''>do</span>
  <span m=''460330''>analysis.</span> <span m=''460840''>Cilk</span> <span m=''461070''>is</span>
  <span m=''461280''>a</span> <span m=''461350''>compiler</span> <span m=''461910''>that</span>
  <span m=''462030''>compiles</span> <span m=''464390''>this</span> <span m=''464620''>language</span>
  <span m=''466010''>and the</span> <span m=''466530''>semantics</span> <span m=''467060''>are</span>
  <span m=''467150''>what</span> <span m=''467310''>they</span> <span m=''467430''>are,</span>
  <span m=''467730''>which</span> <span m=''467930''>is</span> <span m=''468170''>you</span>
  <span m=''468380''>the</span> <span m=''468510''>spawn</span> <span m=''469520''>is
  its--</span> <span m=''469700''>and I''ll</span> <span m=''469890''>talk about</span>
  <span m=''470150''>the semantics.</span> <span m=''470450''>The</span> <span m=''470540''>spawn</span>
  <span m=''470870''>means</span> <span m=''471090''>you</span> <span m=''471170''>can</span>
  <span m=''471460''>run</span> <span m=''471680''>the</span> <span m=''471780''>function</span>
  <span m=''472140''>in</span> <span m=''472230''>parallel</span> <span m=''472740''>and</span>
  <span m=''472910''>if</span> <span m=''473130''>that</span> <span m=''473310''>doesn''t</span>
  <span m=''473560''>give</span> <span m=''473720''>you</span> <span m=''473930''>the</span>
  <span m=''474060''>same</span> <span m=''474250''>answer</span> <span m=''474540''>every</span>
  <span m=''474730''>time</span> <span m=''476190''>it''s</span> <span m=''476310''>not</span>
  <span m=''476480''>the</span> <span m=''476550''>compilers</span> <span m=''476920''>fault.</span>
  </p><p><span m=''478350''>AUDIENCE:</span> <span m=''478536''>[OBSCURED]</span>
  </p><p><span m=''480890''>BRADLEY KUSZMAUL: Pardon?</span> </p><p><span m=''481752''>AUDIENCE:
  There</span> <span m=''482224''>has to be</span> <span m=''482696''>some</span>
  <span m=''483168''>guarantee</span> <span m=''483641''>[OBSCURED].</span> </p><p><span
  m=''484585''>[OBSCURED]</span> </p><p><span m=''487990''>PROFESSOR: How</span> <span
  m=''488500''>in a</span> <span m=''489010''>race</span> <span m=''489230''>condition</span>
  <span m=''489450''>you</span> <span m=''489596''>get</span> <span m=''489743''>some</span>
  <span m=''489890''>[OBSCURED].</span> </p><p><span m=''492650''>BRADLEY KUSZMAUL:
  One</span> <span m=''492800''>of</span> <span m=''492890''>the</span> <span m=''492970''>legal</span>
  <span m=''493280''>things</span> <span m=''493620''>the Cilk</span> <span m=''493780''>system</span>
  <span m=''494240''>could</span> <span m=''494410''>do</span> <span m=''494650''>is</span>
  <span m=''494790''>just</span> <span m=''495010''>run</span> <span m=''495310''>this,</span>
  <span m=''495800''>run</span> <span m=''495980''>that</span> <span m=''496190''>program.</span>
  <span m=''497480''>Now</span> <span m=''498250''>if</span> <span m=''498380''>you''re</span>
  <span m=''498470''>running</span> <span m=''498720''>it</span> <span m=''498800''>on</span>
  <span m=''498920''>multiple</span> <span m=''499300''>processors</span> <span m=''499980''>that''s</span>
  <span m=''500200''>not</span> <span m=''500410''>what</span> <span m=''500530''>happens</span>
  <span m=''501090''>because</span> <span m=''501490''>the</span> <span m=''501610''>other</span>
  <span m=''501770''>thing</span> <span m=''502110''>is</span> <span m=''502216''>there''s</span>
  <span m=''502323''>some</span> <span m=''502430''>performance</span> <span m=''502930''>guarantees</span>
  <span m=''503400''>we</span> <span m=''503510''>get.</span> <span m=''503730''>So</span>
  <span m=''503860''>there''s</span> <span m=''504010''>actually</span> <span m=''504340''>parallelism.</span>
  <span m=''504970''>But</span> <span m=''505310''>on</span> <span m=''505540''>one</span>
  <span m=''505760''>processor</span> <span m=''506340''>in</span> <span m=''506450''>fact,</span>
  <span m=''506690''>that''s</span> <span m=''506850''>exactly</span> <span m=''507380''>what</span>
  <span m=''508030''>the</span> <span m=''508130''>execution</span> <span m=''508680''>does.</span>
  <span m=''510860''>So</span> <span m=''511880''>Cilk</span> <span m=''512220''>does</span>
  <span m=''512650''>dynamic</span> <span m=''513240''>multithreading</span> <span
  m=''513800''>and</span> <span m=''513890''>this</span> <span m=''514000''>is</span>
  <span m=''514120''>different</span> <span m=''514490''>from</span> <span m=''515280''>p</span>
  <span m=''515510''>threads</span> <span m=''515870''>for</span> <span m=''516000''>example</span>
  <span m=''516440''>where</span> <span m=''516580''>you</span> <span m=''516680''>have</span>
  <span m=''517350''>this</span> <span m=''517660''>very</span> <span m=''517920''>heavyweight</span>
  <span m=''518490''>thread that</span> <span m=''518910''>costs</span> <span m=''519890''>tens</span>
  <span m=''520200''>of</span> <span m=''520300''>thousands</span> <span m=''521060''>of</span>
  <span m=''521330''>instructions</span> <span m=''521980''>to</span> <span m=''522100''>create.</span>
  <span m=''523010''>Cilk</span> <span m=''523210''>threads</span> <span m=''523550''>are</span>
  <span m=''523600''>really</span> <span m=''523920''>small,</span> <span m=''524340''>so</span>
  <span m=''524750''>in</span> <span m=''525490''>this</span> <span m=''525640''>program</span>
  <span m=''526470''>there''s</span> <span m=''526630''>a</span> <span m=''526720''>Cilk</span>
  <span m=''526960''>thread</span> <span m=''527280''>that</span> <span m=''527380''>runs</span>
  <span m=''527610''>basically</span> <span m=''528140''>from</span> <span m=''528350''>when</span>
  <span m=''528960''>the</span> <span m=''529140''>fib</span> <span m=''529350''>starts</span>
  <span m=''529820''>to</span> <span m=''530090''>here</span> <span m=''530850''>and</span>
  <span m=''531050''>then--</span> <span m=''537480''>I</span> <span m=''537510''>feel</span>
  <span m=''537710''>like</span> <span m=''537850''>there''s a</span> <span m=''538040''>missing</span>
  <span m=''538900''>slide</span> <span m=''539710''>in here.</span> <span m=''539920''>I</span>
  <span m=''539976''>didn''t</span> <span m=''540033''>tell</span> <span m=''540090''>you</span>
  <span m=''540170''>about</span> <span m=''540450''>spawn.</span> </p><p><span m=''544400''>OK,</span>
  <span m=''544740''>well</span> <span m=''544980''>let</span> <span m=''545120''>me</span>
  <span m=''545230''>tell</span> <span m=''545410''>you</span> <span m=''545520''>about</span>
  <span m=''545780''>spawn</span> <span m=''546150''>because</span> <span m=''547070''>what</span>
  <span m=''547250''>the</span> <span m=''547460''>spawn</span> <span m=''547820''>means</span>
  <span m=''548960''>is</span> <span m=''549870''>that</span> <span m=''550070''>this</span>
  <span m=''550200''>function</span> <span m=''550570''>can</span> <span m=''550730''>run</span>
  <span m=''550900''>in</span> <span m=''550990''>parallel.</span> <span m=''552940''>That''s</span>
  <span m=''553130''>very</span> <span m=''553340''>simple.</span> <span m=''553920''>What</span>
  <span m=''554130''>the</span> <span m=''554230''>sync</span> <span m=''554630''>means</span>
  <span m=''555530''>is</span> <span m=''555820''>that</span> <span m=''556470''>all</span>
  <span m=''556710''>the</span> <span m=''556810''>functions</span> <span m=''557400''>that</span>
  <span m=''558270''>were</span> <span m=''558430''>spawned</span> <span m=''558970''>off</span>
  <span m=''559540''>in</span> <span m=''560190''>this</span> <span m=''560470''>function</span>
  <span m=''561680''>all</span> <span m=''561880''>have</span> <span m=''562070''>to</span>
  <span m=''562170''>finish</span> <span m=''562590''>before</span> <span m=''563360''>this</span>
  <span m=''563540''>function</span> <span m=''563880''>can</span> <span m=''564170''>proceed.</span>
  <span m=''565040''>So</span> <span m=''565126''>in</span> <span m=''565213''>a</span>
  <span m=''565300''>normal</span> <span m=''565770''>execution</span> <span m=''566820''>of
  C,</span> <span m=''567360''>when</span> <span m=''567470''>you</span> <span m=''567580''>call</span>
  <span m=''567850''>a</span> <span m=''567920''>function</span> <span m=''569070''>the</span>
  <span m=''569170''>parent</span> <span m=''569510''>stops.</span> <span m=''571060''>In</span>
  <span m=''571230''>Cilk</span> <span m=''571800''>the</span> <span m=''571900''>parent</span>
  <span m=''572200''>can</span> <span m=''572330''>keep</span> <span m=''572550''>running,</span>
  <span m=''573360''>so</span> <span m=''573470''>while</span> <span m=''573670''>that''s</span>
  <span m=''573910''>running</span> <span m=''574250''>the</span> <span m=''574370''>parent--</span>
  <span m=''574710''>this</span> <span m=''574770''>can</span> <span m=''575130''>spawn</span>
  <span m=''575760''>off</span> <span m=''575940''>this</span> <span m=''576250''>and</span>
  <span m=''576360''>then</span> <span m=''576480''>the</span> <span m=''576580''>sync</span>
  <span m=''576840''>happens</span> <span m=''577170''>and now</span> <span m=''577500''>the
  parent</span> <span m=''577770''>has</span> <span m=''577990''>to</span> <span m=''578080''>stop.</span>
  <span m=''579410''>And</span> <span m=''579580''>this</span> <span m=''579780''>key</span>
  <span m=''579960''>word</span> <span m=''580270''>basically</span> <span m=''580740''>just</span>
  <span m=''581050''>says</span> <span m=''581520''>that</span> <span m=''581650''>this</span>
  <span m=''581810''>function</span> <span m=''582140''>can</span> <span m=''582490''>be</span>
  <span m=''582610''>spawned.</span> </p><p><span m=''584590''>AUDIENCE: Is</span>
  <span m=''585070''>the</span> <span m=''585550''>sync</span> <span m=''586030''>in
  that scope or the children scope?</span> </p><p><span m=''589960''>BRADLEY KUSZMAUL:
  The</span> <span m=''591080''>sync</span> <span m=''591300''>is</span> <span m=''591520''>scoped</span>
  <span m=''591880''>within</span> <span m=''592260''>the</span> <span m=''592320''>function.</span>
  <span m=''592710''>So</span> <span m=''592910''>you</span> <span m=''593180''>could</span>
  <span m=''593300''>have</span> <span m=''593530''>a</span> <span m=''593850''>4
  loop</span> <span m=''594270''>that</span> <span m=''594570''>spawned</span> <span
  m=''594790''>off</span> <span m=''594836''>a</span> <span m=''594883''>whole</span>
  <span m=''594930''>bunch</span> <span m=''595080''>of</span> <span m=''595180''>stuff.</span>
  </p><p><span m=''595640''>AUDIENCE: You</span> <span m=''595780''>could</span> <span
  m=''595920''>call</span> <span m=''596060''>the</span> <span m=''596200''>function</span>
  <span m=''596910''>instead</span> <span m=''597530''>of</span> <span m=''597680''>moving</span>
  <span m=''598220''>some</span> <span m=''598760''>spawns,</span> <span m=''599300''>but</span>
  <span m=''599740''>then</span> <span m=''599960''>[OBSCURED]</span> <span m=''600180''>in
  the sync.</span> </p><p><span m=''600620''>BRADLEY KUSZMAUL: There''s</span> <span
  m=''600980''>an</span> <span m=''601160''>explicit</span> <span m=''601210''>sync</span>
  <span m=''601470''>at</span> <span m=''601560''>the</span> <span m=''601650''>end</span>
  <span m=''601750''>of</span> <span m=''601830''>every</span> <span m=''602020''>function.</span>
  <span m=''603640''>So</span> <span m=''603870''>Cilk</span> <span m=''604160''>functions</span>
  <span m=''604570''>are</span> <span m=''604670''>strict.</span> </p><p><span m=''606660''>PROFESSOR:
  [NOISE]</span> </p><p><span m=''612680''>BRADLEY KUSZMAUL: You</span> <span m=''612820''>know,</span>
  <span m=''613300''>there''s</span> <span m=''613510''>children</span> <span m=''613900''>down</span>
  <span m=''614260''>inside</span> <span m=''614940''>here,</span> <span m=''615015''>but</span>
  <span m=''615090''>this</span> <span m=''615350''>function</span> <span m=''615510''>can''t</span>
  <span m=''615730''>return--</span> <span m=''616480''>well,</span> <span m=''616810''>if
  I</span> <span m=''616930''>had</span> <span m=''617420''>omitted</span> <span m=''617990''>the</span>
  <span m=''618470''>sync</span> <span m=''619380''>and</span> <span m=''620070''>down
  in</span> <span m=''620360''>some</span> <span m=''620550''>leaf</span> <span m=''621380''>the</span>
  <span m=''621490''>compiler</span> <span m=''621890''>puts</span> <span m=''622000''>one</span>
  <span m=''622350''>in</span> <span m=''622510''>before</span> <span m=''622830''>the
  function</span> <span m=''623280''>returns.</span> <span m=''625970''>There''s</span>
  <span m=''626450''>some</span> <span m=''626810''>languages</span> <span m=''627340''>that</span>
  <span m=''627460''>are</span> <span m=''627520''>like</span> <span m=''627750''>this</span>
  <span m=''628000''>where</span> <span m=''628180''>somehow</span> <span m=''628620''>the</span>
  <span m=''628760''>intermediate</span> <span m=''629220''>function</span> <span
  m=''629640''>can</span> <span m=''630220''>go</span> <span m=''630390''>away</span>
  <span m=''630770''>and</span> <span m=''630920''>then</span> <span m=''631470''>you</span>
  <span m=''631640''>can</span> <span m=''631770''>sync</span> <span m=''632030''>directly</span>
  <span m=''632380''>with</span> <span m=''632490''>your</span> <span m=''632580''>grandparent.</span>
  </p><p><span m=''635490''>AUDIENCE: Otherwise it would stop.</span> </p><p><span
  m=''638710''>BRADLEY KUSZMAUL: So</span> <span m=''638860''>this</span> <span m=''639020''>gives</span>
  <span m=''639190''>you</span> <span m=''639530''>this</span> <span m=''639940''>dag,</span>
  <span m=''640070''>so</span> <span m=''640240''>you</span> <span m=''640303''>have</span>
  <span m=''640366''>this</span> <span m=''640430''>part</span> <span m=''640640''>of</span>
  <span m=''640710''>the</span> <span m=''640850''>program that</span> <span m=''641300''>runs</span>
  <span m=''641440''>up to the</span> <span m=''641580''>first</span> <span m=''642100''>spawn</span>
  <span m=''642690''>and then</span> <span m=''642900''>part of</span> <span m=''642970''>the</span>
  <span m=''643070''>program</span> <span m=''643490''>that</span> <span m=''643600''>runs</span>
  <span m=''643950''>between</span> <span m=''644270''>the spawns</span> <span m=''645530''>and</span>
  <span m=''645710''>the</span> <span m=''645790''>part of the</span> <span m=''646050''>program</span>
  <span m=''646420''>that</span> <span m=''646520''>runs</span> <span m=''646760''>after--</span>
  <span m=''648460''>well,</span> <span m=''649150''>after</span> <span m=''649400''>the</span>
  <span m=''649480''>last</span> <span m=''649810''>spawn</span> <span m=''650010''>to</span>
  <span m=''650070''>the</span> <span m=''650150''>sync</span> <span m=''650990''>and
  then</span> <span m=''651280''>from</span> <span m=''651450''>there</span> <span
  m=''651760''>to the</span> <span m=''651860''>return.</span> <span m=''653080''>So</span>
  <span m=''653230''>I''ve</span> <span m=''653680''>got</span> <span m=''653860''>this</span>
  <span m=''655070''>drawing</span> <span m=''655550''>that</span> <span m=''655650''>shows</span>
  <span m=''656510''>this</span> <span m=''656690''>function</span> <span m=''657210''>sort</span>
  <span m=''657360''>of</span> <span m=''657770''>running.</span> <span m=''658130''>So</span>
  <span m=''658230''>first</span> <span m=''658470''>the</span> <span m=''658540''>purple</span>
  <span m=''658860''>code</span> <span m=''659130''>runs</span> <span m=''659420''>at
  it</span> <span m=''659630''>gets to the</span> <span m=''659810''>spawn,</span>
  <span m=''660000''>it</span> <span m=''660650''>spawns</span> <span m=''661370''>of</span>
  <span m=''661730''>this</span> <span m=''662130''>guy,</span> <span m=''662265''>but</span>
  <span m=''662400''>now</span> <span m=''662630''>the</span> <span m=''662750''>second</span>
  <span m=''663110''>piece</span> <span m=''663280''>of</span> <span m=''663350''>code</span>
  <span m=''663750''>can</span> <span m=''663850''>start</span> <span m=''664150''>running.</span>
  <span m=''665140''>He</span> <span m=''665370''>does a</span> <span m=''665620''>spawn,</span>
  <span m=''666210''>so these</span> <span m=''666440''>two</span> <span m=''666570''>are</span>
  <span m=''666740''>running in</span> <span m=''667130''>parallel.</span> <span m=''668510''>Meanwhile.</span>
  <span m=''668880''>This</span> <span m=''669060''>guy</span> <span m=''669210''>started</span>
  <span m=''669590''>that</span> <span m=''669810''>pff.</span> <span m=''673460''>This</span>
  <span m=''673620''>is</span> <span m=''673720''>a</span> <span m=''673830''>base</span>
  <span m=''674150''>case,</span> <span m=''674450''>so</span> <span m=''674720''>he''s</span>
  <span m=''675030''>going to</span> <span m=''675310''>not</span> <span m=''675550''>do</span>
  <span m=''675670''>anything.</span> <span m=''678480''>Just</span> <span m=''678760''>feels</span>
  <span m=''679020''>like</span> <span m=''679150''>there''s</span> <span m=''679610''>something</span>
  <span m=''679920''>missing</span> <span m=''680210''>in</span> <span m=''680320''>this</span>
  <span m=''680510''>slide.</span> <span m=''681530''>Oh</span> <span m=''681650''>well.</span>
  </p><p><span m=''683670''>Essentially</span> <span m=''684290''>now</span> <span
  m=''684970''>this</span> <span m=''685420''>guy</span> <span m=''685850''>couldn''t</span>
  <span m=''686170''>run</span> <span m=''686780''>going</span> <span m=''687020''>back</span>
  <span m=''687230''>to</span> <span m=''687330''>here.</span> <span m=''688260''>This</span>
  <span m=''688370''>part of</span> <span m=''688590''>the</span> <span m=''688650''>code</span>
  <span m=''688890''>couldn''t</span> <span m=''689130''>run</span> <span m=''689330''>until</span>
  <span m=''689560''>after</span> <span m=''689780''>sync</span> <span m=''689880''>so</span>
  <span m=''690320''>this</span> <span m=''690500''>thing''s</span> <span m=''690870''>sitting</span>
  <span m=''691130''>here</span> <span m=''691240''>waiting.</span> <span m=''692410''>So</span>
  <span m=''693700''>when</span> <span m=''693880''>these</span> <span m=''694110''>guys</span>
  <span m=''694500''>finally</span> <span m=''694770''>return</span> <span m=''696530''>then</span>
  <span m=''696730''>this</span> <span m=''696930''>can</span> <span m=''697090''>run.</span>
  <span m=''697780''>This</span> <span m=''697930''>guy''s</span> <span m=''698230''>getting</span>
  <span m=''698450''>stuck</span> <span m=''698830''>here.</span> <span m=''699270''>He</span>
  <span m=''699410''>runs</span> <span m=''700200''>and</span> <span m=''701170''>he
  runs.</span> <span m=''701320''>These two</span> <span m=''701530''>return</span>
  <span m=''702280''>and</span> <span m=''702410''>the</span> <span m=''702540''>value</span>
  <span m=''702670''>comes</span> <span m=''702940''>up</span> <span m=''703060''>here.</span>
  <span m=''703970''>And</span> <span m=''705490''>now</span> <span m=''705660''>basically</span>
  <span m=''706180''>the</span> <span m=''706270''>function</span> <span m=''706720''>is
  done.</span> <span m=''709820''>One</span> <span m=''710030''>observation</span>
  <span m=''710620''>here</span> <span m=''710810''>is</span> <span m=''710970''>that</span>
  <span m=''711080''>there''s</span> <span m=''711340''>no</span> <span m=''711520''>mention</span>
  <span m=''712270''>of</span> <span m=''712420''>the</span> <span m=''712500''>number
  of</span> <span m=''712730''>processors</span> <span m=''713390''>in</span> <span
  m=''713490''>this</span> <span m=''713660''>code.</span> <span m=''715470''>You</span>
  <span m=''715820''>haven''t</span> <span m=''716160''>specified</span> <span m=''717310''>how</span>
  <span m=''717410''>to</span> <span m=''717510''>schedule</span> <span m=''718040''>or</span>
  <span m=''718530''>how</span> <span m=''718630''>many</span> <span m=''718760''>processors.</span>
  <span m=''719800''>All</span> <span m=''719930''>you''ve</span> <span m=''720060''>specified</span>
  <span m=''720700''>is</span> <span m=''720910''>this</span> <span m=''721510''>directed</span>
  <span m=''721660''>acyclic</span> <span m=''722000''>graph</span> <span m=''722470''>that</span>
  <span m=''722580''>unfolds</span> <span m=''723060''>dynamically</span> <span m=''724250''>and</span>
  <span m=''724590''>it''s</span> <span m=''724770''>up</span> <span m=''724950''>to</span>
  <span m=''725240''>us</span> <span m=''725580''>to</span> <span m=''725890''>schedule</span>
  <span m=''726340''>those</span> <span m=''726550''>onto</span> <span m=''726660''>the</span>
  <span m=''726790''>processors.</span> <span m=''727830''>So</span> <span m=''727950''>this</span>
  <span m=''728120''>code</span> <span m=''728440''>is</span> <span m=''728630''>processor</span>
  <span m=''729300''>oblivious.</span> <span m=''729850''>It''s</span> <span m=''730140''>oblivious</span>
  <span m=''730770''>to</span> <span m=''730860''>the</span> <span m=''730950''>number</span>
  <span m=''731240''>of</span> <span m=''731615''>processors.</span> </p><p><span
  m=''732481''>PROFESSOR: But</span> <span m=''732973''>because</span> <span m=''733465''>we''re
  using</span> <span m=''733956''>the language</span> <span m=''734448''>we''re</span>
  <span m=''734940''>probably</span> <span m=''735431''>have to</span> <span m=''735923''>create,</span>
  <span m=''736415''>write</span> <span m=''736906''>as many</span> <span m=''737398''>spawns</span>
  <span m=''737561''>depending</span> <span m=''737725''>on--</span> </p><p><span
  m=''737890''>BRADLEY KUSZMAUL: No,</span> <span m=''738190''>what</span> <span m=''738620''>you</span>
  <span m=''738740''>do</span> <span m=''738792''>is</span> <span m=''738845''>you</span>
  <span m=''738897''>write</span> <span m=''738950''>as</span> <span m=''739070''>many</span>
  <span m=''739300''>spawns</span> <span m=''739570''>as</span> <span m=''739840''>you
  can.</span> <span m=''740866''>You</span> <span m=''741380''>expose</span> <span
  m=''741670''>all</span> <span m=''741940''>the</span> <span m=''742780''>parallelism</span>
  <span m=''743290''>in your code.</span> <span m=''743800''>So</span> <span m=''743960''>you</span>
  <span m=''744110''>want</span> <span m=''744350''>this</span> <span m=''744520''>dag</span>
  <span m=''744750''>to have</span> <span m=''745740''>millions</span> <span m=''746330''>of</span>
  <span m=''746520''>threads in</span> <span m=''747240''>it</span> <span m=''747980''>concurrently.</span>
  <span m=''749520''>And</span> <span m=''749660''>then</span> <span m=''749760''>it''s</span>
  <span m=''749910''>up to us</span> <span m=''750470''>to</span> <span m=''751040''>schedule</span>
  <span m=''751320''>that</span> <span m=''751720''>efficiently.</span> <span m=''752120''>So</span>
  <span m=''752390''>it''s</span> <span m=''752510''>a</span> <span m=''752560''>different</span>
  <span m=''752890''>mindset</span> <span m=''754010''>then,</span> <span m=''755080''>I
  have</span> <span m=''755300''>4</span> <span m=''755460''>processors,</span> <span
  m=''756000''>let</span> <span m=''756120''>me</span> <span m=''756220''>create</span>
  <span m=''756580''>4</span> <span m=''756750''>things</span> <span m=''756940''>to
  do.</span> <span m=''757440''>I</span> <span m=''757600''>have</span> <span m=''757840''>4
  processors,</span> <span m=''758360''>let</span> <span m=''758480''>me</span> <span
  m=''758560''>create</span> <span m=''758780''>a</span> <span m=''758820''>million</span>
  <span m=''759160''>things</span> <span m=''759410''>to</span> <span m=''759510''>do.</span>
  <span m=''760250''>And</span> <span m=''760560''>then</span> <span m=''760720''>the</span>
  <span m=''760820''>Cilk</span> <span m=''761440''>scheduler</span> <span m=''761780''>guarantees</span>
  <span m=''762380''>to</span> <span m=''762460''>give</span> <span m=''762630''>you--</span>
  <span m=''763260''>you</span> <span m=''763350''>have</span> <span m=''763460''>4</span>
  <span m=''763670''>processors,</span> <span m=''764250''>I''ll</span> <span m=''764330''>give</span>
  <span m=''764480''>you</span> <span m=''764550''>4</span> <span m=''764790''>fold</span>
  <span m=''765010''>speed</span> <span m=''765260''>up.</span> </p><p><span m=''765480''>PROFESSOR:
  I</span> <span m=''765992''>guess</span> <span m=''766505''>what you''d like to
  avoid is the</span> <span m=''768042''>mindset</span> <span m=''768555''>of</span>
  <span m=''769067''>the programmer</span> <span m=''769580''>has</span> <span m=''770042''>to</span>
  <span m=''770505''>change</span> <span m=''770967''>or</span> <span m=''771082''>find</span>
  <span m=''771198''>the</span> <span m=''771313''>changing</span> <span m=''771430''>tuning
  the parameters for the performance.</span> </p><p><span m=''775260''>BRADLEY KUSZMAUL:
  There''s</span> <span m=''775880''>some</span> <span m=''776380''>tuning</span>
  <span m=''776510''>that</span> <span m=''776840''>you</span> <span m=''777143''>do</span>
  <span m=''777446''>in</span> <span m=''777750''>order</span> <span m=''778060''>to
  make</span> <span m=''778370''>the</span> <span m=''778750''>leaf</span> <span m=''779620''>code.</span>
  <span m=''779890''>There''s</span> <span m=''780015''>some</span> <span m=''780140''>overhead</span>
  <span m=''780360''>for</span> <span m=''781140''>doing</span> <span m=''781246''>function</span>
  <span m=''781353''>calls.</span> <span m=''782120''>So</span> <span m=''783880''>it''s</span>
  <span m=''784090''>small</span> <span m=''784820''>overhead.</span> <span m=''786140''>It</span>
  <span m=''786295''>turns</span> <span m=''786450''>out</span> <span m=''786760''>the</span>
  <span m=''786835''>cost</span> <span m=''786910''>of</span> <span m=''786985''>the</span>
  <span m=''787060''>spawn</span> <span m=''787110''>is</span> <span m=''787160''>like</span>
  <span m=''787210''>three</span> <span m=''787540''>function</span> <span m=''788190''>calls.</span>
  <span m=''790670''>If you</span> <span m=''791020''>were</span> <span m=''791220''>actually</span>
  <span m=''791820''>trying</span> <span m=''792030''>to</span> <span m=''792210''>make
  this</span> <span m=''792420''>code run</span> <span m=''793180''>faster</span>
  <span m=''793690''>you make the</span> <span m=''793900''>base</span> <span m=''794243''>case</span>
  <span m=''794586''>bigger</span> <span m=''794930''>and</span> <span m=''795160''>do</span>
  <span m=''795330''>something,</span> <span m=''796200''>trying</span> <span m=''797160''>to</span>
  <span m=''798490''>speed things</span> <span m=''799140''>up</span> <span m=''799280''>a</span>
  <span m=''799350''>little</span> <span m=''799530''>bit</span> <span m=''799730''>with</span>
  <span m=''799894''>the</span> <span m=''800058''> leaves</span> <span m=''800222''>of</span>
  <span m=''800715''>this</span> <span m=''801207''>call.</span> <span m=''801970''>So</span>
  <span m=''802200''>there''s</span> <span m=''802370''>this</span> <span m=''802620''>call</span>
  <span m=''803130''>tree</span> <span m=''803350''>and</span> <span m=''803680''>inside</span>
  <span m=''803880''>the call</span> <span m=''804140''>tree</span> <span m=''804920''>is</span>
  <span m=''805330''>this dag.</span> <span m=''808140''>So it</span> <span m=''808450''>supports</span>
  <span m=''809820''>C''s</span> <span m=''810310''>rule for</span> <span m=''810580''>pointers.</span>
  <span m=''811740''>For</span> <span m=''811880''>whatever</span> <span m=''812220''>dialect</span>
  <span m=''812640''>you</span> <span m=''812730''>have.</span> <span m=''813770''>If</span>
  <span m=''813970''>you</span> <span m=''814220''>have</span> <span m=''814430''>a</span>
  <span m=''814510''>pointer</span> <span m=''814860''>to</span> <span m=''817440''>a</span>
  <span m=''817550''>stack</span> <span m=''819240''>and</span> <span m=''819420''>then</span>
  <span m=''819510''>you</span> <span m=''819990''>have</span> <span m=''820180''>a</span>
  <span m=''820250''>pointer</span> <span m=''820396''>to</span> <span m=''820543''>the</span>
  <span m=''820690''>stack</span> <span m=''821060''>and then</span> <span m=''821250''>you</span>
  <span m=''821330''>call,</span> <span m=''821950''>you''re</span> <span m=''822120''>allowed</span>
  <span m=''822480''>to</span> <span m=''823090''>use</span> <span m=''823320''>that</span>
  <span m=''823500''>pointer</span> <span m=''823800''>in</span> <span m=''823960''>C.</span>
  <span m=''824530''>So</span> <span m=''824950''>in</span> <span m=''825120''>Cilk</span>
  <span m=''825220''>you</span> <span m=''825320''>are</span> <span m=''825580''>as</span>
  <span m=''825720''>well.</span> <span m=''826760''>If</span> <span m=''826840''>you</span>
  <span m=''826940''>have</span> <span m=''827100''>a</span> <span m=''827190''>parallel</span>
  <span m=''827890''>thing</span> <span m=''828120''>going</span> <span m=''828410''>on</span>
  <span m=''828630''>where</span> <span m=''829240''>normally</span> <span m=''829680''>in
  C</span> <span m=''829820''>you would</span> <span m=''830030''>call</span> <span
  m=''830310''>A,</span> <span m=''830660''>then</span> <span m=''831030''>B</span>
  <span m=''831270''>returns,</span> <span m=''831800''>then</span> <span m=''831970''>C
  and</span> <span m=''832250''>D.</span> <span m=''833180''>So</span> <span m=''833360''>C</span>
  <span m=''833780''>and</span> <span m=''833823''>D</span> <span m=''833866''>can</span>
  <span m=''833910''>refer</span> <span m=''834200''>to</span> <span m=''834280''>anything</span>
  <span m=''834630''>on</span> <span m=''834820''>A,</span> <span m=''835630''>but</span>
  <span m=''836230''>C</span> <span m=''836470''>can''t</span> <span m=''837270''>legally</span>
  <span m=''837700''>refer</span> <span m=''838030''>to</span> <span m=''838130''>something</span>
  <span m=''838520''>on</span> <span m=''838790''>B</span> <span m=''838960''>and</span>
  <span m=''839130''>the</span> <span m=''839230''>same</span> <span m=''839520''>rule</span>
  <span m=''839740''>applies</span> <span m=''840290''>to</span> <span m=''840960''>Cilk.</span>
  <span m=''842000''>So</span> <span m=''842130''>we</span> <span m=''842240''>have</span>
  <span m=''842410''>a</span> <span m=''842450''>data</span> <span m=''842710''>structure</span>
  <span m=''843130''>that</span> <span m=''843230''>implements</span> <span m=''843560''>this</span>
  <span m=''844020''>cactus</span> <span m=''844550''>stack</span> <span m=''844950''>is</span>
  <span m=''845700''>what</span> <span m=''845840''>it''s</span> <span m=''845980''>called,</span>
  <span m=''846330''>after</span> <span m=''846550''>the</span> <span m=''846840''>sugauro</span>
  <span m=''847310''>cactus--</span> <span m=''850062''>the</span> <span m=''850580''>view</span>
  <span m=''850960''>of</span> <span m=''851190''>the</span> <span m=''853040''>imagery</span>
  <span m=''853440''>there</span> <span m=''853730''>and</span> <span m=''854750''>it</span>
  <span m=''855390''>lets</span> <span m=''855680''>you</span> <span m=''857360''>support</span>
  <span m=''857710''>that</span> <span m=''857870''>rule.</span> </p><p><span m=''859690''>There''s</span>
  <span m=''859870''>some</span> <span m=''860400''>advanced</span> <span m=''860870''>features</span>
  <span m=''861250''>in</span> <span m=''861390''>Cilk</span> <span m=''861590''>that</span>
  <span m=''861850''>have</span> <span m=''862060''>to</span> <span m=''862140''>do</span>
  <span m=''862360''>with</span> <span m=''863630''>speculative</span> <span m=''864290''>execution</span>
  <span m=''865290''>and</span> <span m=''867860''>I''m</span> <span m=''868010''>going
  to</span> <span m=''868170''>skip</span> <span m=''868390''>over</span> <span m=''868600''>those</span>
  <span m=''868820''>today</span> <span m=''869150''>because</span> <span m=''869410''>it</span>
  <span m=''869480''>turns</span> <span m=''869780''>out</span> <span m=''870000''>that</span>
  <span m=''870390''>sort</span> <span m=''870550''>of</span> <span m=''870620''>99%</span>
  <span m=''871410''>of</span> <span m=''871470''>the</span> <span m=''871530''>time</span>
  <span m=''871750''>you</span> <span m=''871820''>don''t</span> <span m=''872000''>need</span>
  <span m=''872170''>this</span> <span m=''872260''>stuff.</span> <span m=''875720''>We</span>
  <span m=''875850''>have</span> <span m=''876610''>some</span> <span m=''876820''>debugger</span>
  <span m=''877220''>support,</span> <span m=''877700''>so</span> <span m=''878120''>if</span>
  <span m=''878400''>you''ve</span> <span m=''878530''>written</span> <span m=''878810''>code</span>
  <span m=''879060''>that</span> <span m=''879740''>relied</span> <span m=''880290''>on</span>
  <span m=''881530''>some</span> <span m=''881880''>semantics</span> <span m=''882620''>that</span>
  <span m=''882840''>maybe</span> <span m=''883070''>you</span> <span m=''883130''>didn''t</span>
  <span m=''883400''>like</span> <span m=''885050''>when</span> <span m=''885200''>you</span>
  <span m=''885300''>went</span> <span m=''885500''>to</span> <span m=''885570''>the</span>
  <span m=''885660''>parallel</span> <span m=''886040''>world,</span> <span m=''886330''>you''d</span>
  <span m=''886430''>like</span> <span m=''886600''>to</span> <span m=''886690''>find</span>
  <span m=''887000''>out.</span> <span m=''888460''>This</span> <span m=''888670''>is</span>
  <span m=''889010''>a</span> <span m=''889310''>tool</span> <span m=''889660''>that</span>
  <span m=''889800''>basically</span> <span m=''890270''>takes</span> <span m=''890530''>a</span>
  <span m=''890600''>Cilk</span> <span m=''890840''>program and</span> <span m=''891450''>an</span>
  <span m=''891560''>input</span> <span m=''892070''>data</span> <span m=''892360''>set</span>
  <span m=''894050''>and</span> <span m=''894590''>it</span> <span m=''894720''>runs</span>
  <span m=''895180''>and</span> <span m=''895270''>it</span> <span m=''895340''>tells</span>
  <span m=''895630''>you</span> <span m=''895930''>is</span> <span m=''896160''>there</span>
  <span m=''896340''>any</span> <span m=''896640''>schedule</span> <span m=''897290''>that</span>
  <span m=''897640''>I</span> <span m=''897800''>could</span> <span m=''898010''>have</span>
  <span m=''898110''>chosen--</span> <span m=''898890''>so</span> <span m=''899130''>it''s
  that</span> <span m=''899340''>directed</span> <span m=''899780''>acyclic</span>
  <span m=''900040''>graph.</span> <span m=''900470''>So</span> <span m=''900660''>there''s
  a</span> <span m=''900710''>whole</span> <span m=''900950''>bunch</span> <span m=''901140''>of</span>
  <span m=''901210''>possible</span> <span m=''901600''>schedules</span> <span m=''902020''>I</span>
  <span m=''902090''>could</span> <span m=''902230''>have</span> <span m=''902320''>chosen.</span>
  <span m=''903270''>Is</span> <span m=''903390''>there</span> <span m=''903520''>any</span>
  <span m=''903790''>schedule</span> <span m=''904500''>that</span> <span m=''904700''>changes</span>
  <span m=''905910''>the</span> <span m=''906020''>order</span> <span m=''906550''>of</span>
  <span m=''906720''>two</span> <span m=''907030''>concurrent</span> <span m=''907650''>memory</span>
  <span m=''907990''>operations</span> <span m=''908650''>where</span> <span m=''908800''>one</span>
  <span m=''909060''>of</span> <span m=''909170''>them</span> <span m=''910050''>is</span>
  <span m=''910250''>right?</span> <span m=''912060''>So</span> <span m=''912190''>we</span>
  <span m=''912280''>call</span> <span m=''912460''>this</span> <span m=''912650''>the</span>
  <span m=''912750''>non-determinator</span> <span m=''913580''>because</span> <span
  m=''913900''>it</span> <span m=''914000''>finds</span> <span m=''914340''>all</span>
  <span m=''914530''>the</span> <span m=''914670''>determinacy</span> <span m=''915310''>races</span>
  <span m=''915740''>in</span> <span m=''915850''>your</span> <span m=''915970''>program.</span>
  <span m=''917750''>And</span> <span m=''918520''>Cilk</span> <span m=''918860''>guarantees--</span>
  <span m=''919670''>the</span> <span m=''919770''>Cilk</span> <span m=''919990''>race</span>
  <span m=''920360''>detector</span> <span m=''920880''>is</span> <span m=''921400''>guaranteed</span>
  <span m=''922010''>to</span> <span m=''922080''>find</span> <span m=''922700''>those.</span>
  <span m=''923150''>There''s</span> <span m=''923290''>a</span> <span m=''923340''>lot</span>
  <span m=''923530''>of</span> <span m=''923600''>race</span> <span m=''923820''>detectors</span>
  <span m=''924290''>where</span> <span m=''924980''>if</span> <span m=''925110''>the</span>
  <span m=''925210''>race</span> <span m=''925470''>doesn''t</span> <span m=''925750''>actually</span>
  <span m=''926070''>occur</span> <span m=''926400''>you</span> <span m=''926550''>have</span>
  <span m=''926690''>two</span> <span m=''926840''>things</span> <span m=''927130''>that</span>
  <span m=''927220''>are</span> <span m=''927300''>logically</span> <span m=''927990''>in</span>
  <span m=''928130''>parallel,</span> <span m=''929590''>but</span> <span m=''929730''>if</span>
  <span m=''929890''>they</span> <span m=''929980''>don''t</span> <span m=''930170''>actually</span>
  <span m=''930450''>run</span> <span m=''930680''>on</span> <span m=''930820''>different</span>
  <span m=''931120''>processors</span> <span m=''932830''>a</span> <span m=''932920''>lot</span>
  <span m=''933080''>of</span> <span m=''934150''>race</span> <span m=''934240''>detectors</span>
  <span m=''934500''>out</span> <span m=''934620''>there</span> <span m=''934800''>in</span>
  <span m=''934910''>the</span> <span m=''934990''>world</span> <span m=''935260''>won''t</span>
  <span m=''935470''>report</span> <span m=''935820''>the</span> <span m=''935910''>race.</span>
  <span m=''936190''>So you</span> <span m=''936320''>get</span> <span m=''936480''>false</span>
  <span m=''936930''>negatives</span> <span m=''937810''>and</span> <span m=''937900''>there''s</span>
  <span m=''937990''>a</span> <span m=''938050''>bunch</span> <span m=''938220''>of</span>
  <span m=''938310''>false</span> <span m=''938560''>positives</span> <span m=''939030''>that</span>
  <span m=''939130''>show</span> <span m=''939350''>up.</span> <span m=''939530''>This</span>
  <span m=''939780''>basically</span> <span m=''940260''>only</span> <span m=''940470''>gives</span>
  <span m=''940650''>you</span> <span m=''940720''>the</span> <span m=''940820''>real</span>
  <span m=''941030''>ones.</span> </p><p><span m=''941753''>AUDIENCE: That might be
  indicatiors</span> <span m=''945349''>there</span> <span m=''945833''>might</span>
  <span m=''946316''>be</span> <span m=''946800''>still</span> <span m=''947284''>a</span>
  <span m=''947768''>data</span> <span m=''948252''>to arrays.</span> </p><p><span
  m=''949220''>BRADLEY KUSZMAUL: So</span> <span m=''949420''>this</span> <span m=''949640''>doesn''t</span>
  <span m=''949920''>analyze</span> <span m=''950510''>the</span> <span m=''950610''>program.</span>
  <span m=''951110''>It</span> <span m=''951190''>analyzes</span> <span m=''951810''>the</span>
  <span m=''951920''>execution.</span> <span m=''952890''>So</span> <span m=''953190''>it''s</span>
  <span m=''953470''>not</span> <span m=''953670''>trying</span> <span m=''953990''>to</span>
  <span m=''954070''>solve</span> <span m=''954420''>some</span> <span m=''954540''>MP</span>
  <span m=''955190''>complete</span> <span m=''955410''>problem</span> <span m=''955780''>or</span>
  <span m=''956040''> Turing</span> <span m=''956510''>complete</span> <span m=''956610''>problem.</span>
  <span m=''958560''>And</span> <span m=''958740''>so</span> <span m=''958830''>this</span>
  <span m=''959040''>reduces</span> <span m=''959590''>the</span> <span m=''959690''>problem</span>
  <span m=''960160''>of</span> <span m=''960260''>finding</span> <span m=''960630''>data</span>
  <span m=''960900''>races</span> <span m=''961810''>to</span> <span m=''961980''>the</span>
  <span m=''962070''>situation</span> <span m=''962610''>that''s</span> <span m=''962830''>just</span>
  <span m=''963140''>like</span> <span m=''963340''>when</span> <span m=''963470''>you''re</span>
  <span m=''963600''>trying</span> <span m=''963860''>to</span> <span m=''963950''>do</span>
  <span m=''965770''>code</span> <span m=''966030''>release and</span> <span m=''966810''>quality</span>
  <span m=''967180''>control</span> <span m=''967670''>for</span> <span m=''967780''>serial</span>
  <span m=''968100''>programs.</span> <span m=''968540''>You</span> <span m=''968620''>write</span>
  <span m=''968890''>tests.</span> <span m=''970030''>If</span> <span m=''970180''>you</span>
  <span m=''970300''>don''t</span> <span m=''970740''>test</span> <span m=''971070''>your</span>
  <span m=''971170''>program</span> <span m=''971700''>you</span> <span m=''971810''>don''t</span>
  <span m=''972020''>know</span> <span m=''972120''>what</span> <span m=''972270''>it</span>
  <span m=''972370''>does</span> <span m=''972720''>and</span> <span m=''972830''>that''s</span>
  <span m=''972980''>the</span> <span m=''973070''>same</span> <span m=''973330''>property</span>
  <span m=''973680''>here.</span> <span m=''975280''>If</span> <span m=''975450''>you</span>
  <span m=''975530''>do</span> <span m=''975720''>find</span> <span m=''976070''>some</span>
  <span m=''976220''>race</span> <span m=''976460''>someday</span> <span m=''976930''>later</span>
  <span m=''978020''>then</span> <span m=''978200''>you</span> <span m=''978290''>can</span>
  <span m=''978430''>write</span> <span m=''978630''>a</span> <span m=''978690''>test</span>
  <span m=''978990''>for</span> <span m=''979200''>it</span> <span m=''979330''>and</span>
  <span m=''980060''>know</span> <span m=''980360''>that</span> <span m=''980950''>you''re</span>
  <span m=''981100''>testing</span> <span m=''981450''>to</span> <span m=''981510''>make</span>
  <span m=''981660''>sure</span> <span m=''981790''>that</span> <span m=''981980''>race</span>
  <span m=''982480''>didn''t</span> <span m=''982575''>creep</span> <span m=''982670''>back</span>
  <span m=''982940''>into</span> <span m=''983020''>your</span> <span m=''983220''>code.</span>
  <span m=''983860''>That''s</span> <span m=''984130''>what</span> <span m=''984240''>you</span>
  <span m=''984340''>want</span> <span m=''984770''>out</span> <span m=''984940''>of</span>
  <span m=''985570''>a</span> <span m=''985680''>software</span> <span m=''985815''>release</span>
  <span m=''985950''>strategy.</span> </p><p><span m=''987025''>AUDIENCE: [NOISE]</span>
  </p><p><span m=''996900''>BRADLEY KUSZMAUL: If</span> <span m=''997440''>you</span>
  <span m=''997630''>start</span> <span m=''997920''>putting</span> <span m=''998150''>in</span>
  <span m=''999690''>sync than</span> <span m=''999850''>maybe</span> <span m=''1000070''>the</span>
  <span m=''1000170''>race</span> <span m=''1000390''>goes</span> <span m=''1000560''>away</span>
  <span m=''1000780''>because</span> <span m=''1001010''>of</span> <span m=''1001090''>that.</span>
  <span m=''1001480''>But if</span> <span m=''1001620''>just</span> <span m=''1001850''>put</span>
  <span m=''1002060''>in</span> <span m=''1003860''>instrumentation</span> <span m=''1004640''>to</span>
  <span m=''1004710''>try</span> <span m=''1004890''>to</span> <span m=''1004950''>figure</span>
  <span m=''1005130''>out</span> <span m=''1005230''>what''s</span> <span m=''1005370''>going,</span>
  <span m=''1005570''>it''s</span> <span m=''1005950''>still</span> <span m=''1006130''>there.</span>
  <span m=''1007380''>And</span> <span m=''1007710''>the</span> <span m=''1007823''>race</span>
  <span m=''1007936''>detector</span> <span m=''1008050''>sort</span> <span m=''1008200''>of</span>
  <span m=''1008290''>says,</span> <span m=''1009380''>this</span> <span m=''1009580''>variable</span>
  <span m=''1010360''>in this</span> <span m=''1010650''>function,</span> <span m=''1011590''>this</span>
  <span m=''1011740''>variable</span> <span m=''1012080''>in</span> <span m=''1012150''>this</span>
  <span m=''1012290''>function,</span> <span m=''1012640''>you</span> <span m=''1012750''>look</span>
  <span m=''1012930''>at</span> <span m=''1013260''>it</span> <span m=''1013312''>and</span>
  <span m=''1013365''>say,</span> <span m=''1013417''>how</span> <span m=''1013470''>could</span>
  <span m=''1013600''>that</span> <span m=''1013770''>happen?</span> <span m=''1014330''>And</span>
  <span m=''1014600''>finally you</span> <span m=''1014900''>figured</span> <span
  m=''1015250''>out</span> <span m=''1015460''>and</span> <span m=''1015550''>you</span>
  <span m=''1015670''>fix</span> <span m=''1015990''>it</span> <span m=''1016190''>and</span>
  <span m=''1016280''>then</span> <span m=''1016370''>you</span> <span m=''1016460''>put</span>
  <span m=''1016730''>it--</span> <span m=''1017080''>if</span> <span m=''1017230''>you''re</span>
  <span m=''1017800''>trying</span> <span m=''1018020''>to</span> <span m=''1018110''>do</span>
  <span m=''1018240''>software</span> <span m=''1018660''>release</span> <span m=''1019010''>you</span>
  <span m=''1019100''>build</span> <span m=''1019290''>a</span> <span m=''1019330''>regression</span>
  <span m=''1019820''>test</span> <span m=''1020210''>that</span> <span m=''1020320''>will</span>
  <span m=''1020450''>verify</span> <span m=''1022100''>that</span> <span m=''1022220''>has</span>
  <span m=''1022420''>that</span> <span m=''1022550''>input.</span> </p><p><span m=''1023610''>AUDIENCE:</span>
  <span m=''1023876''>What if</span> <span m=''1024010''>you</span> <span m=''1024420''>have</span>
  <span m=''1024830''>a</span> <span m=''1026240''>situation</span> <span m=''1026720''>where</span>
  <span m=''1027050''>the</span> <span m=''1027535''>spawn</span> <span m=''1028021''>graph</span>
  <span m=''1028507''>falls</span> <span m=''1028992''>into</span> <span m=''1029478''>a
  terminal.</span> <span m=''1029964''>So</span> <span m=''1030450''>it''s</span>
  <span m=''1030900''>not</span> <span m=''1031000''>a</span> <span m=''1031230''>
  radius,</span> <span m=''1031310''>but</span> <span m=''1031920''>monitoring</span>
  <span m=''1033070''>spawn</span> <span m=''1033410''>is</span> <span m=''1034050''>there</span>
  <span m=''1034600''>but it spawns a graph a little bit deeper.</span> </p><p><span
  m=''1041060''>BRADLEY KUSZMAUL: Yes.</span> <span m=''1043580''>For</span> <span
  m=''1043730''>example,</span> <span m=''1044130''>our</span> <span m=''1044283''>race</span>
  <span m=''1044436''>detector</span> <span m=''1044590''>understands</span> <span
  m=''1045005''>locks.</span> <span m=''1045420''>So part</span> <span m=''1045850''>of</span>
  <span m=''1045910''>the</span> <span m=''1045990''>rule</span> <span m=''1046240''>is</span>
  <span m=''1046390''>it</span> <span m=''1046460''>doesn''t</span> <span m=''1046730''>report
  a</span> <span m=''1047140''>race</span> <span m=''1047680''>if</span> <span m=''1048550''>the</span>
  <span m=''1049390''>two</span> <span m=''1049520''>memory</span> <span m=''1049840''>accesses--</span>
  <span m=''1050910''>if</span> <span m=''1051040''>there</span> <span m=''1051150''>was</span>
  <span m=''1051310''>a</span> <span m=''1051410''>lock</span> <span m=''1051800''>that</span>
  <span m=''1051920''>they</span> <span m=''1052020''>both</span> <span m=''1052280''>held</span>
  <span m=''1052680''>in</span> <span m=''1052800''>common.</span> <span m=''1054610''>Now</span>
  <span m=''1054770''>you</span> <span m=''1055010''>now</span> <span m=''1055180''>you</span>
  <span m=''1055290''>can</span> <span m=''1055410''>write</span> <span m=''1055590''>buggy</span>
  <span m=''1055830''>programs</span> <span m=''1056420''>because</span> <span m=''1056710''>you</span>
  <span m=''1056840''>can</span> <span m=''1057010''>essentially</span> <span m=''1057800''>do</span>
  <span m=''1057900''>the</span> <span m=''1057960''>memory</span> <span m=''1058470''>at</span>
  <span m=''1058620''>lock,</span> <span m=''1059220''>you</span> <span m=''1059480''>know,</span>
  <span m=''1059570''>read</span> <span m=''1059820''>the</span> <span m=''1059890''>memory,</span>
  <span m=''1060440''>unlock,</span> <span m=''1061290''>lock,</span> <span m=''1061620''>write</span>
  <span m=''1061870''>the</span> <span m=''1061950''>memory.</span> <span m=''1062390''>Now</span>
  <span m=''1062620''>the</span> <span m=''1062750''>interleave</span> <span m=''1063150''>happens</span>
  <span m=''1063640''>and</span> <span m=''1063760''>there''s</span> <span m=''1063890''>a</span>
  <span m=''1063960''>race.</span> <span m=''1064330''>So</span> <span m=''1065090''>the</span>
  <span m=''1065250''>assumption</span> <span m=''1065740''>of</span> <span m=''1065840''>this</span>
  <span m=''1065970''>race</span> <span m=''1066240''>detector</span> <span m=''1066630''>is</span>
  <span m=''1066810''>that</span> <span m=''1066940''>if</span> <span m=''1067040''>you</span>
  <span m=''1067120''>put</span> <span m=''1067330''>locks</span> <span m=''1067670''>in</span>
  <span m=''1067800''>there</span> <span m=''1068030''>that</span> <span m=''1068180''>you''ve</span>
  <span m=''1068260''>sort of</span> <span m=''1068480''>thought</span> <span m=''1068730''>about.</span>
  <span m=''1069600''>This</span> <span m=''1069750''>is</span> <span m=''1069870''>finding</span>
  <span m=''1070790''>races</span> <span m=''1071200''>that</span> <span m=''1071310''>you</span>
  <span m=''1071390''>forgot</span> <span m=''1071750''>about</span> <span m=''1072410''>rather</span>
  <span m=''1072730''>than</span> <span m=''1073200''>races</span> <span m=''1073560''>that</span>
  <span m=''1073700''>you</span> <span m=''1073860''>ostensibly</span> <span m=''1074320''>thought</span>
  <span m=''1074590''>about.</span> <span m=''1075150''>There</span> <span m=''1075273''>are</span>
  <span m=''1075396''>some</span> <span m=''1075520''>races</span> <span m=''1075920''>that</span>
  <span m=''1076740''>are</span> <span m=''1076800''>actually</span> <span m=''1077110''>correct.</span>
  <span m=''1077530''>For</span> <span m=''1077650''>example,</span> <span m=''1077990''>in</span>
  <span m=''1078060''>the</span> <span m=''1078120''>chess</span> <span m=''1078420''>programs</span>
  <span m=''1079150''>there''s</span> <span m=''1079340''>this</span> <span m=''1079510''>big</span>
  <span m=''1079880''>table</span> <span m=''1080300''>that</span> <span m=''1080430''>remembers</span>
  <span m=''1080960''>all</span> <span m=''1081150''>the</span> <span m=''1081230''>chess</span>
  <span m=''1081440''>positions</span> <span m=''1081910''>that</span> <span m=''1082000''>have</span>
  <span m=''1082100''>been</span> <span m=''1082240''>seen.</span> <span m=''1083290''>And</span>
  <span m=''1083480''>if</span> <span m=''1083580''>you</span> <span m=''1083660''>don''t</span>
  <span m=''1083890''>get</span> <span m=''1084040''>the</span> <span m=''1084130''>right</span>
  <span m=''1084380''>answer</span> <span m=''1084690''>out</span> <span m=''1084820''>of</span>
  <span m=''1084880''>the</span> <span m=''1084940''>table</span> <span m=''1085270''>it</span>
  <span m=''1085360''>doesn''t</span> <span m=''1085630''>matter</span> <span m=''1085920''>because</span>
  <span m=''1086150''>you</span> <span m=''1086250''>search</span> <span m=''1086570''>it</span>
  <span m=''1086640''>again</span> <span m=''1086870''>anyway.</span> <span m=''1087740''>Not</span>
  <span m=''1087950''>getting</span> <span m=''1088110''>the</span> <span m=''1088200''>right</span>
  <span m=''1088360''>answer</span> <span m=''1088640''>means</span> <span m=''1088810''>you</span>
  <span m=''1088880''>don''t</span> <span m=''1089080''>get</span> <span m=''1089210''>any</span>
  <span m=''1089430''>answer.</span> <span m=''1089700''>You</span> <span m=''1089830''>look</span>
  <span m=''1089990''>something</span> <span m=''1090280''>up</span> <span m=''1090440''>and</span>
  <span m=''1090550''>it''s</span> <span m=''1090690''>not</span> <span m=''1090920''>there</span>
  <span m=''1091080''>so you</span> <span m=''1091270''>search</span> <span m=''1091530''>again.</span>
  <span m=''1092420''>If</span> <span m=''1092590''>you</span> <span m=''1092710''>just</span>
  <span m=''1092960''>waited</span> <span m=''1093180''>a</span> <span m=''1093220''>little</span>
  <span m=''1093450''>longer</span> <span m=''1093830''>maybe</span> <span m=''1094220''>somebody</span>
  <span m=''1094560''>else</span> <span m=''1094790''>would</span> <span m=''1094970''>have
  put</span> <span m=''1095140''>the</span> <span m=''1095220''>value in,</span> <span
  m=''1095600''>you</span> <span m=''1095740''>could</span> <span m=''1095850''>have</span>
  <span m=''1095940''>saved</span> <span m=''1096180''>a</span> <span m=''1096220''>little</span>
  <span m=''1096420''>work.</span> <span m=''1097470''>And</span> <span m=''1097620''>so</span>
  <span m=''1097790''>in</span> <span m=''1097870''>that</span> <span m=''1098040''>case,</span>
  <span m=''1098350''>well it</span> <span m=''1098540''>turns</span> <span m=''1098810''>out</span>
  <span m=''1098970''>to</span> <span m=''1099070''>be</span> <span m=''1099990''>there''s</span>
  <span m=''1100140''>no</span> <span m=''1100310''>parallel</span> <span m=''1100860''>way</span>
  <span m=''1101000''>to</span> <span m=''1101110''>do</span> <span m=''1101270''>that.</span>
  <span m=''1101570''>So</span> <span m=''1103020''>I''m</span> <span m=''1103250''>willing</span>
  <span m=''1103500''>to</span> <span m=''1103590''>tolerate</span> <span m=''1104090''>that</span>
  <span m=''1104280''>race</span> <span m=''1104520''>because</span> <span m=''1104790''>that</span>
  <span m=''1105040''>gives</span> <span m=''1105290''>me</span> <span m=''1105420''>performance</span>
  <span m=''1106100''>and</span> <span m=''1106250''>so</span> <span m=''1106360''>you</span>
  <span m=''1106960''>have</span> <span m=''1107220''>what</span> <span m=''1107660''>we</span>
  <span m=''1107740''>call</span> <span m=''1107940''>fake</span> <span m=''1108260''>locks,</span>
  <span m=''1108720''>which</span> <span m=''1108940''>are</span> <span m=''1109020''>basically</span>
  <span m=''1109870''>things</span> <span m=''1110120''>that</span> <span m=''1111950''>look</span>
  <span m=''1112130''>like</span> <span m=''1112330''>lock</span> <span m=''1112660''>calls,</span>
  <span m=''1113080''>but</span> <span m=''1113200''>they</span> <span m=''1113280''>don''t</span>
  <span m=''1113460''>do</span> <span m=''1113590''>anything</span> <span m=''1114020''>except</span>
  <span m=''1114340''>tell</span> <span m=''1114490''>the</span> <span m=''1114580''>race</span>
  <span m=''1114860''>detector,</span> <span m=''1115740''>pretend</span> <span m=''1116200''>there</span>
  <span m=''1116310''>was</span> <span m=''1116430''>a</span> <span m=''1116490''>lock</span>
  <span m=''1116750''>held in</span> <span m=''1117050''>common.</span> <span m=''1117940''>Yeah?</span>
  </p><p><span m=''1118707''>AUDIENCE: [UNINTELLIGIBLE PHRASE]</span> </p><p><span
  m=''1132080''>BRADLEY KUSZMAUL: If</span> <span m=''1132250''>it</span> <span m=''1132350''>says</span>
  <span m=''1132610''>there''s</span> <span m=''1132770''>no</span> <span m=''1132920''>race
  it</span> <span m=''1133390''>means that</span> <span m=''1133780''>for</span> <span
  m=''1133960''>every</span> <span m=''1134290''>possible</span> <span m=''1134770''>scheduling</span>
  <span m=''1137330''>that--</span> </p><p><span m=''1137745''>AUDIENCE: [UNINTELLIGIBLE
  PHRASE].</span> </p><p><span m=''1139290''>BRADLEY KUSZMAUL: Well,</span> <span
  m=''1140090''>you</span> <span m=''1140190''>have</span> <span m=''1140330''>that</span>
  <span m=''1140530''>dag.</span> <span m=''1140880''>And</span> <span m=''1141040''>imagine</span>
  <span m=''1141500''>running</span> <span m=''1141800''>it</span> <span m=''1141880''>on</span>
  <span m=''1142000''>one</span> <span m=''1142260''>processor.</span> <span m=''1142850''>There''s</span>
  <span m=''1143030''>a</span> <span m=''1143100''>lot</span> <span m=''1143290''>of</span>
  <span m=''1143390''>possible</span> <span m=''1143810''>orders</span> <span m=''1144220''>in</span>
  <span m=''1144300''>which</span> <span m=''1144490''>to</span> <span m=''1144580''>run</span>
  <span m=''1144780''>the</span> <span m=''1144860''>dag.</span> <span m=''1145910''>And</span>
  <span m=''1146050''>the</span> <span m=''1146110''>rule</span> <span m=''1146430''>is</span>
  <span m=''1146730''>well,</span> <span m=''1148080''>was</span> <span m=''1148300''>there</span>
  <span m=''1148460''>a</span> <span m=''1148560''>load</span> <span m=''1149580''>in</span>
  <span m=''1149760''>a</span> <span m=''1149830''>store</span> <span m=''1150003''>or</span>
  <span m=''1150176''>a</span> <span m=''1150350''>store</span> <span m=''1150610''>in</span>
  <span m=''1150690''>a</span> <span m=''1150760''>store</span> <span m=''1151030''>that</span>
  <span m=''1151190''>switched</span> <span m=''1151550''>orders</span> <span m=''1153090''>in</span>
  <span m=''1153350''>some</span> <span m=''1153600''>possible</span> <span m=''1154100''>schedule</span>
  <span m=''1154500''>and</span> <span m=''1154600''>that''s</span> <span m=''1154880''>the</span>
  <span m=''1154970''>definition.</span> </p><p><span m=''1156511''>AUDIENCE:</span>
  <span m=''1157513''>So,</span> <span m=''1158013''>in</span> <span m=''1158514''>practice,</span>
  <span m=''1159015''>sorry,</span> <span m=''1162650''>one</span> <span m=''1168430''>of</span>
  <span m=''1168750''>the</span> <span m=''1169510''>[INAUDIBLE]</span> <span m=''1170090''>techniques</span>
  <span m=''1170584''>is</span> <span m=''1171078''>loss.</span> <span m=''1171573''>Assuming,</span>
  <span m=''1172067''>dependent on</span> <span m=''1172562''>the processor,</span>
  <span m=''1173056''>that you</span> <span m=''1173551''>have atomic</span> <span
  m=''1174045''>rights,</span> <span m=''1174540''>we want</span> <span m=''1175034''>to</span>
  <span m=''1175528''>deal with</span> <span m=''1176023''>that</span> <span m=''1176517''>data</span>
  <span m=''1177012''>[UNINTELLIGIBLE]</span> <span m=''1177506''>in</span> <span
  m=''1178001''>the</span> <span m=''1178495''>background --</span> </p><p><span m=''1178990''>BRADLEY
  KUSZMAUL: Those</span> <span m=''1179410''>protocols</span> <span m=''1179640''>are
  really</span> <span m=''1179910''>hard</span> <span m=''1180070''>to</span> <span
  m=''1180140''>get</span> <span m=''1180290''>right,</span> <span m=''1180620''>but
  yes,</span> <span m=''1181110''>it''s</span> <span m=''1181360''>an</span> <span
  m=''1181830''>important</span> <span m=''1181980''>trick.</span> </p><p><span m=''1182755''>AUDIENCE:
  Certainly</span> <span m=''1183200''>[INAUDIBLE].</span> </p><p><span m=''1184430''>BRADLEY
  KUSZMAUL: So</span> <span m=''1184630''>to</span> <span m=''1184730''>convince</span>
  <span m=''1185050''>the</span> <span m=''1185210''>race</span> <span m=''1185260''>detector</span>
  <span m=''1185310''>not to</span> <span m=''1185570''>complain</span> <span m=''1186020''>you
  put</span> <span m=''1186210''>fake</span> <span m=''1186410''>locks</span> <span
  m=''1186710''>around</span> <span m=''1187010''>it.</span> <span m=''1191410''>You''ve</span>
  <span m=''1191540''>programmed</span> <span m=''1192000''>a</span> <span m=''1192240''>sophisticated</span>
  <span m=''1192620''>algorithm</span> <span m=''1193590''>it''s</span> <span m=''1193840''>up</span>
  <span m=''1193960''>to you</span> <span m=''1194090''>to</span> <span m=''1194180''>get</span>
  <span m=''1194360''>the</span> <span m=''1194430''>details</span> <span m=''1195180''>right.</span>
  <span m=''1199150''>The</span> <span m=''1199310''>other</span> <span m=''1199510''>property</span>
  <span m=''1199870''>about</span> <span m=''1200110''>this</span> <span m=''1200260''>race</span>
  <span m=''1200540''>detector</span> <span m=''1200930''>is</span> <span m=''1201020''>that
  it''s</span> <span m=''1201190''>fast.</span> <span m=''1201415''>It</span> <span
  m=''1201640''>runs</span> <span m=''1201910''>almost</span> <span m=''1202330''>in</span>
  <span m=''1202440''>liear</span> <span m=''1202760''>time.</span> <span m=''1203220''>A</span>
  <span m=''1203340''>lot</span> <span m=''1203570''>of</span> <span m=''1203680''>the</span>
  <span m=''1203750''>race</span> <span m=''1204020''>detectors</span> <span m=''1204490''>that</span>
  <span m=''1204600''>you</span> <span m=''1204700''>find</span> <span m=''1205030''>out</span>
  <span m=''1205210''>there</span> <span m=''1205370''>run in</span> <span m=''1205700''>quadratic</span>
  <span m=''1206250''>time.</span> <span m=''1207210''>So</span> <span m=''1207320''>if</span>
  <span m=''1207410''>you</span> <span m=''1207490''>want</span> <span m=''1207660''>to</span>
  <span m=''1207720''>run</span> <span m=''1208025''>a</span> <span m=''1208330''>million</span>
  <span m=''1208700''>instructions</span> <span m=''1209210''>it</span> <span m=''1209310''>has</span>
  <span m=''1209480''>to</span> <span m=''1209550''>compare</span> <span m=''1209870''>every</span>
  <span m=''1210250''>instruction</span> <span m=''1210730''>to every</span> <span
  m=''1211050''>other</span> <span m=''1211250''>instruction.</span> <span m=''1212380''>Turns</span>
  <span m=''1212600''>out</span> <span m=''1212740''>we</span> <span m=''1212850''>don''t</span>
  <span m=''1213010''>have</span> <span m=''1213170''>to</span> <span m=''1213270''>do</span>
  <span m=''1213410''>that.</span> <span m=''1213690''>We</span> <span m=''1214220''>run
  in</span> <span m=''1214510''>time,</span> <span m=''1214810''>which</span> <span
  m=''1214970''>is</span> <span m=''1215110''>n</span> <span m=''1215770''>times</span>
  <span m=''1216090''>alpha</span> <span m=''1216570''>of</span> <span m=''1216830''>n</span>
  <span m=''1216960''>where</span> <span m=''1217090''>alpha''s</span> <span m=''1217220''>the</span>
  <span m=''1217350''>inverse</span> <span m=''1217710''>Ackermann</span> <span m=''1218100''>function.</span>
  <span m=''1218440''>Anybody</span> <span m=''1218700''>remember</span> <span m=''1219000''>that</span>
  <span m=''1219240''>from</span> <span m=''1220045''>the</span> <span m=''1220500''>union-find</span>
  <span m=''1221100''>algorithm.</span> <span m=''1223580''>It''s</span> <span m=''1223770''>got</span>
  <span m=''1223960''>that</span> <span m=''1224140''>graded</span> <span m=''1224420''>So</span>
  <span m=''1224520''>it''s</span> <span m=''1224720''>like</span> <span m=''1224930''>the
  almost</span> <span m=''1225930''>linear</span> <span m=''1226330''>time.</span>
  <span m=''1227210''>We</span> <span m=''1227400''>actually</span> <span m=''1227680''>now</span>
  <span m=''1227880''>have</span> <span m=''1228000''>a</span> <span m=''1228050''>linear</span>
  <span m=''1228360''>timed</span> <span m=''1228650''>one</span> <span m=''1228830''>that</span>
  <span m=''1232200''>has</span> <span m=''1232470''>performance</span> <span m=''1232980''>advantages.</span>
  <span m=''1234990''>So</span> <span m=''1235330''>let</span> <span m=''1235550''>me</span>
  <span m=''1235950''>do</span> <span m=''1236990''>a</span> <span m=''1237100''>little</span>
  <span m=''1237310''>theory</span> <span m=''1237730''>in practice.</span> </p><p><span
  m=''1240130''>In</span> <span m=''1240310''>Cilk</span> <span m=''1240790''>we</span>
  <span m=''1240950''>have</span> <span m=''1241590''>some</span> <span m=''1241910''>fundamental</span>
  <span m=''1242300''>complexity</span> <span m=''1242850''>measures</span> <span
  m=''1243180''>that</span> <span m=''1243290''>we</span> <span m=''1243460''>worry</span>
  <span m=''1243810''>about.</span> <span m=''1244160''>So</span> <span m=''1244320''>we''re</span>
  <span m=''1244450''>interested</span> <span m=''1244930''>in</span> <span m=''1245040''>knowing</span>
  <span m=''1245860''>and being</span> <span m=''1246110''>able</span> <span m=''1246300''>to</span>
  <span m=''1246390''>predict</span> <span m=''1246980''>the</span> <span m=''1247070''>runtime</span>
  <span m=''1247920''>of</span> <span m=''1248040''>a</span> <span m=''1248110''>Cilk</span>
  <span m=''1248310''>program</span> <span m=''1248820''>on</span> <span m=''1248980''>P</span>
  <span m=''1249180''>processors.</span> <span m=''1250440''>So</span> <span m=''1250620''>we</span>
  <span m=''1250770''>want</span> <span m=''1250980''>to</span> <span m=''1251050''>know</span>
  <span m=''1251220''>T</span> <span m=''1251640''>sub p,</span> <span m=''1251950''>which</span>
  <span m=''1252180''>is</span> <span m=''1252400''>the</span> <span m=''1252630''>execution</span>
  <span m=''1253210''>time</span> <span m=''1253460''>on</span> <span m=''1253580''>P</span>
  <span m=''1253870''>processors.</span> <span m=''1254350''>That''s</span> <span
  m=''1254610''>the</span> <span m=''1254710''>goal.</span> <span m=''1255660''>What</span>
  <span m=''1255930''>we''ve</span> <span m=''1256090''>got</span> <span m=''1256320''>to</span>
  <span m=''1256410''>work</span> <span m=''1256710''>with</span> <span m=''1257440''>is</span>
  <span m=''1257930''>some</span> <span m=''1258180''>directed</span> <span m=''1258450''>acyclic</span>
  <span m=''1258920''>graph</span> <span m=''1259430''>that</span> <span m=''1259890''>is</span>
  <span m=''1260260''>for</span> <span m=''1260410''>a</span> <span m=''1260460''>particular</span>
  <span m=''1260890''>input</span> <span m=''1261170''>set</span> <span m=''1261630''>and</span>
  <span m=''1261780''>if the</span> <span m=''1261860''>program</span> <span m=''1262260''>determines</span>
  <span m=''1262690''>it</span> <span m=''1262840''>and</span> <span m=''1262930''>everything</span>
  <span m=''1263220''>else</span> <span m=''1263470''>it''s</span> <span m=''1263920''>a
  well</span> <span m=''1264270''>defined</span> <span m=''1264660''>graph</span>
  <span m=''1265400''>and</span> <span m=''1265940''>we</span> <span m=''1266060''>can</span>
  <span m=''1266530''>come</span> <span m=''1266710''>up</span> <span m=''1266820''>with</span>
  <span m=''1266940''>some</span> <span m=''1267090''>basic</span> <span m=''1267450''>measures</span>
  <span m=''1267890''>of</span> <span m=''1268000''>this</span> <span m=''1268140''>graph.</span>
  <span m=''1268470''>So</span> <span m=''1268560''>T sub</span> <span m=''1268770''>1</span>
  <span m=''1269050''>is</span> <span m=''1269210''>the</span> <span m=''1269300''>work</span>
  <span m=''1270390''>of</span> <span m=''1270530''>the</span> <span m=''1270620''>graph,</span>
  <span m=''1270940''>which</span> <span m=''1271100''>is</span> <span m=''1271230''>the</span>
  <span m=''1271320''>total</span> <span m=''1271670''>time</span> <span m=''1271950''>it</span>
  <span m=''1272010''>would</span> <span m=''1272140''>take</span> <span m=''1272350''>to</span>
  <span m=''1272470''>run</span> <span m=''1272710''>that</span> <span m=''1272920''>graph</span>
  <span m=''1273250''>on</span> <span m=''1273430''>one</span> <span m=''1273680''>processor.</span>
  <span m=''1275080''>Or</span> <span m=''1275250''>if</span> <span m=''1275420''>you</span>
  <span m=''1275570''>assume</span> <span m=''1275880''>that</span> <span m=''1276010''>these</span>
  <span m=''1276210''>things</span> <span m=''1276510''>are</span> <span m=''1276650''>all</span>
  <span m=''1276980''>cost</span> <span m=''1277320''>unit</span> <span m=''1277570''>times,</span>
  <span m=''1277950''>just</span> <span m=''1278130''>the</span> <span m=''1278200''>number</span>
  <span m=''1278480''>of</span> <span m=''1278580''>nodes.</span> <span m=''1279510''>So</span>
  <span m=''1279650''>for</span> <span m=''1279820''>this</span> <span m=''1280080''>graph</span>
  <span m=''1281120''>what''s</span> <span m=''1281430''>the</span> <span m=''1281540''>work?</span>
  </p><p><span m=''1291780''>I</span> <span m=''1292550''>heard</span> <span m=''1292800''>teen,</span>
  <span m=''1293150''>but</span> <span m=''1293570''>something--</span> <span m=''1294070''>18?</span>
  <span m=''1296460''>And</span> <span m=''1297120''>the critical</span> <span m=''1297540''>path</span>
  <span m=''1299190''>is</span> <span m=''1302060''>the</span> <span m=''1302180''>longest</span>
  <span m=''1302680''>path.</span> <span m=''1303590''>And</span> <span m=''1303810''>if</span>
  <span m=''1303920''>these</span> <span m=''1304150''>nodes</span> <span m=''1304380''>weren''t</span>
  <span m=''1304630''>unit</span> <span m=''1304910''>time</span> <span m=''1305200''>you''d</span>
  <span m=''1305290''>have</span> <span m=''1305450''>to</span> <span m=''1305560''>weight</span>
  <span m=''1305920''>the</span> <span m=''1306470''>things</span> <span m=''1306750''>according</span>
  <span m=''1307130''>to</span> <span m=''1307700''>actually</span> <span m=''1308050''>how</span>
  <span m=''1308200''>much</span> <span m=''1308480''>time</span> <span m=''1308720''>they</span>
  <span m=''1308960''>run.</span> <span m=''1309200''>So the</span> <span m=''1309390''>critical</span>
  <span m=''1309710''>path</span> <span m=''1310070''>here</span> <span m=''1310260''>is</span>
  <span m=''1310410''>what?</span> <span m=''1313280''>9.</span> <span m=''1314770''>So</span>
  <span m=''1316680''>I</span> <span m=''1316790''>think</span> <span m=''1316950''>those</span>
  <span m=''1317120''>are</span> <span m=''1317200''>right.</span> <span m=''1317700''>The</span>
  <span m=''1317790''>lower</span> <span m=''1318050''>bounds</span> <span m=''1318440''>then</span>
  <span m=''1319180''>that</span> <span m=''1319320''>you</span> <span m=''1319490''>know</span>
  <span m=''1320130''>is</span> <span m=''1320340''>that</span> <span m=''1320570''>you</span>
  <span m=''1320690''>don''t</span> <span m=''1321110''>expect</span> <span m=''1322500''>the</span>
  <span m=''1322630''>runtime</span> <span m=''1323080''>on</span> <span m=''1323200''>P</span>
  <span m=''1323400''>processes</span> <span m=''1324130''>to</span> <span m=''1324210''>be</span>
  <span m=''1324340''>faster</span> <span m=''1324750''>than</span> <span m=''1324860''>linear</span>
  <span m=''1325180''>speedup.</span> <span m=''1329980''>In</span> <span m=''1330100''>this</span>
  <span m=''1330290''>model</span> <span m=''1332760''>that</span> <span m=''1332900''>doesn''t</span>
  <span m=''1333180''>happen.</span> <span m=''1337430''>It</span> <span m=''1337620''>turns</span>
  <span m=''1337850''>out</span> <span m=''1338040''>cache</span> <span m=''1338390''>does</span>
  <span m=''1338630''>things.</span> <span m=''1338820''>It''s</span> <span m=''1338930''>adding</span>
  <span m=''1339270''>more</span> <span m=''1339500''>than</span> <span m=''1339630''>just</span>
  <span m=''1339830''>processors.</span> <span m=''1341190''>You''re</span> <span
  m=''1341360''>adding</span> <span m=''1341620''>more</span> <span m=''1341840''>cache</span>
  <span m=''1342280''>too.</span> <span m=''1343060''>So</span> <span m=''1343200''>all</span>
  <span m=''1343510''>sorts of</span> <span m=''1343660''>things</span> <span m=''1343930''>or</span>
  <span m=''1344250''>maybe</span> <span m=''1345750''>it</span> <span m=''1345850''>means</span>
  <span m=''1346040''>that</span> <span m=''1346160''>there''s</span> <span m=''1346320''>a</span>
  <span m=''1346380''>better</span> <span m=''1346610''>algorithm</span> <span m=''1347050''>you</span>
  <span m=''1347170''>should have</span> <span m=''1347470''>used.</span> <span m=''1348180''>So</span>
  <span m=''1348460''>there''s</span> <span m=''1348640''>some</span> <span m=''1348740''>funny</span>
  <span m=''1348970''>things</span> <span m=''1349200''>that</span> <span m=''1349290''>happen</span>
  <span m=''1349590''>if</span> <span m=''1349670''>you</span> <span m=''1349770''>have</span>
  <span m=''1349910''>bad</span> <span m=''1350120''>algorithms</span> <span m=''1350720''>and</span>
  <span m=''1350820''>so</span> <span m=''1350960''>forth.</span> <span m=''1351180''>But</span>
  <span m=''1351400''>in this</span> <span m=''1351600''>model</span> <span m=''1351910''>you</span>
  <span m=''1352030''>can''t</span> <span m=''1352260''>have</span> <span m=''1352420''>more</span>
  <span m=''1352590''>than</span> <span m=''1352870''>linear</span> <span m=''1353000''>speedup.</span>
  <span m=''1354020''>You</span> <span m=''1354090''>also</span> <span m=''1354350''>can''t</span>
  <span m=''1354600''>get</span> <span m=''1354760''>things</span> <span m=''1354990''>done</span>
  <span m=''1355270''>faster</span> <span m=''1355700''>than</span> <span m=''1355920''>in</span>
  <span m=''1356080''>linear</span> <span m=''1356260''>time.</span> <span m=''1356880''>This</span>
  <span m=''1357080''>model</span> <span m=''1357490''>assumes</span> <span m=''1357800''>basically</span>
  <span m=''1358430''>that</span> <span m=''1358580''>these</span> <span m=''1358800''>costs</span>
  <span m=''1359330''>of</span> <span m=''1359430''>running</span> <span m=''1359660''>these</span>
  <span m=''1359860''>things</span> <span m=''1360180''>are</span> <span m=''1360980''>fixed</span>
  <span m=''1362150''>and</span> <span m=''1362570''>the</span> <span m=''1363970''>cache</span>
  <span m=''1364290''>has</span> <span m=''1364420''>the</span> <span m=''1364500''>property</span>
  <span m=''1364870''>that</span> <span m=''1365420''>changing</span> <span m=''1365830''>the</span>
  <span m=''1365900''>order of</span> <span m=''1366180''>execution</span> <span m=''1366720''>means</span>
  <span m=''1366940''>that</span> <span m=''1367050''>the</span> <span m=''1367410''>actual</span>
  <span m=''1367650''>costs</span> <span m=''1368040''>of</span> <span m=''1368160''>the</span>
  <span m=''1368300''>nodes</span> <span m=''1368620''>in</span> <span m=''1368710''>the</span>
  <span m=''1368770''>graph</span> <span m=''1369630''>change</span> <span m=''1369990''>costs.</span>
  <span m=''1372600''>So</span> <span m=''1372760''>those</span> <span m=''1372960''>are</span>
  <span m=''1373020''>lower</span> <span m=''1373330''>bounds</span> <span m=''1374330''>and</span>
  <span m=''1374980''>the</span> <span m=''1375760''>things</span> <span m=''1375980''>that</span>
  <span m=''1376070''>we</span> <span m=''1376220''>want</span> <span m=''1376470''>to</span>
  <span m=''1376530''>know</span> <span m=''1376830''>are</span> <span m=''1377070''>speedups,</span>
  <span m=''1377590''>so</span> <span m=''1377720''>that''s</span> <span m=''1378030''>T</span>
  <span m=''1378250''>sub 1</span> <span m=''1378690''>over</span> <span m=''1378930''>T
  sub</span> <span m=''1379230''>p.</span> <span m=''1380410''>And</span> <span m=''1380800''>the</span>
  <span m=''1381010''>parallelism</span> <span m=''1381640''>of</span> <span m=''1381740''>the</span>
  <span m=''1381810''>graph</span> <span m=''1382200''>is</span> <span m=''1382370''>T
  sub</span> <span m=''1382600''>1</span> <span m=''1382840''>over</span> <span m=''1383020''>T
  sub</span> <span m=''1383330''>infinity.</span> <span m=''1384310''>So</span> <span
  m=''1384460''>the</span> <span m=''1384580''>work</span> <span m=''1385350''>over</span>
  <span m=''1385630''>the</span> <span m=''1385710''>critical</span> <span m=''1386070''>path</span>
  <span m=''1386430''>and we''ve</span> <span m=''1386630''>been</span> <span m=''1386740''>calling</span>
  <span m=''1387090''>this</span> <span m=''1387460''>span</span> <span m=''1388100''>sometimes</span>
  <span m=''1388640''>lately.</span> <span m=''1389740''>Some</span> <span m=''1389880''>people</span>
  <span m=''1390080''>call</span> <span m=''1390280''>that</span> <span m=''1390520''>depth.</span>
  <span m=''1392260''>Span</span> <span m=''1392530''>is</span> <span m=''1392630''>easier</span>
  <span m=''1392920''>to</span> <span m=''1393000''>say</span> <span m=''1393220''>than</span>
  <span m=''1393340''>critical</span> <span m=''1393710''>path,</span> <span m=''1394110''>depth</span>
  <span m=''1394400''>has</span> <span m=''1394590''>too</span> <span m=''1394750''>many</span>
  <span m=''1395000''>other</span> <span m=''1395190''>meanings</span> <span m=''1395560''>so</span>
  <span m=''1396440''>I</span> <span m=''1396580''>kind of</span> <span m=''1396770''>like</span>
  <span m=''1396960''>span.</span> </p><p><span m=''1397390''>So</span> <span m=''1397760''>what''s</span>
  <span m=''1398120''>the</span> <span m=''1398260''>parallelism</span> <span m=''1398820''>for</span>
  <span m=''1398930''>this</span> <span m=''1399070''>program?</span> <span m=''1404760''>18/9.</span>
  <span m=''1409880''>We</span> <span m=''1410240''>said</span> <span m=''1410780''>that</span>
  <span m=''1410850''>T sub 1</span> <span m=''1411260''>was</span> <span m=''1411490''>what?</span>
  <span m=''1413920''>18.</span> <span m=''1415120''>The</span> <span m=''1415660''>infinity</span>
  <span m=''1416740''>is</span> <span m=''1416950''>9.</span> <span m=''1417770''>So</span>
  <span m=''1417900''>on</span> <span m=''1418140''>average</span> <span m=''1418860''>and</span>
  <span m=''1419010''>if</span> <span m=''1419190''>you</span> <span m=''1419290''>had</span>
  <span m=''1419530''>an</span> <span m=''1419660''>infinite</span> <span m=''1420030''>number
  of</span> <span m=''1420290''>processors</span> <span m=''1420950''>and</span> <span
  m=''1421080''>you</span> <span m=''1421190''>scheduled</span> <span m=''1421690''>this</span>
  <span m=''1422230''>as</span> <span m=''1422410''>greedy</span> <span m=''1422770''>as</span>
  <span m=''1423000''>you good,</span> <span m=''1424530''>it</span> <span m=''1424730''>would</span>
  <span m=''1425190''>take you</span> <span m=''1425550''>9 steps</span> <span m=''1426270''>to</span>
  <span m=''1426350''>run</span> <span m=''1426430''>and</span> <span m=''1426510''>you</span>
  <span m=''1426590''>would</span> <span m=''1426740''>you</span> <span m=''1426840''>be</span>
  <span m=''1426930''>doing</span> <span m=''1427160''>18</span> <span m=''1427560''>things</span>
  <span m=''1427810''>worth</span> <span m=''1427980''>of</span> <span m=''1428060''>work.</span>
  <span m=''1428350''>So</span> <span m=''1429550''>on</span> <span m=''1429730''>average</span>
  <span m=''1430130''>there''s</span> <span m=''1430330''>two</span> <span m=''1430500''>things</span>
  <span m=''1430820''>to</span> <span m=''1430920''>do.</span> <span m=''1431140''>You</span>
  <span m=''1431200''>know,</span> <span m=''1431310''>1</span> <span m=''1431870''>plus</span>
  <span m=''1432090''>1</span> <span m=''1432440''>plus</span> <span m=''1432680''>1</span>
  <span m=''1433050''>plus</span> <span m=''1433300''>3</span> <span m=''1433730''>plus</span>
  <span m=''1434030''>4</span> <span m=''1434350''>plus</span> <span m=''1434610''>4</span>
  <span m=''1434910''>plus</span> <span m=''1435170''>1</span> <span m=''1435380''>plus</span>
  <span m=''1435680''>1</span> <span m=''1435950''>plus</span> <span m=''1436140''>1</span>
  <span m=''1436920''>divided</span> <span m=''1437340''>by</span> <span m=''1437930''>9</span>
  <span m=''1438820''>turns</span> <span m=''1439070''>out</span> <span m=''1439240''>to</span>
  <span m=''1439340''>be</span> <span m=''1439460''>2.</span> <span m=''1439970''>So</span>
  <span m=''1440110''>the</span> <span m=''1440200''>average</span> <span m=''1440580''>parallelism</span>
  <span m=''1441640''>or</span> <span m=''1441750''>just</span> <span m=''1441960''>the</span>
  <span m=''1442040''>parallelism</span> <span m=''1442510''>of</span> <span m=''1442620''>the</span>
  <span m=''1442950''>program</span> <span m=''1444500''>is</span> <span m=''1444950''>T</span>
  <span m=''1445140''>sub 1</span> <span m=''1445350''>over</span> <span m=''1445500''>T
  sub</span> <span m=''1445670''>infinity.</span> <span m=''1446120''>And</span> <span
  m=''1446230''>this</span> <span m=''1446480''>property</span> <span m=''1446960''>is</span>
  <span m=''1447080''>something</span> <span m=''1447370''>that''s</span> <span m=''1447560''>not</span>
  <span m=''1447940''>dependent</span> <span m=''1448350''>on</span> <span m=''1448490''>the</span>
  <span m=''1448580''>scheduler,</span> <span m=''1449620''>it''s</span> <span m=''1449780''>a</span>
  <span m=''1449860''>property</span> <span m=''1450420''>of</span> <span m=''1450540''>the</span>
  <span m=''1450640''>program.</span> <span m=''1452390''>Doesn''t</span> <span m=''1452630''>depend</span>
  <span m=''1452850''>on</span> <span m=''1452930''>how</span> <span m=''1453030''>many</span>
  <span m=''1453180''>processors</span> <span m=''1453780''>you</span> <span m=''1453900''>have.</span>
  </p><p><span m=''1455490''>AUDIENCE: [OBSCURED]</span> <span m=''1456438''>You''re</span>
  <span m=''1456913''>saying,</span> <span m=''1457387''>you''re</span> <span m=''1457862''>calling</span>
  <span m=''1458336''>that</span> <span m=''1458811''>the</span> <span m=''1459285''>span
  now?</span> <span m=''1461740''>Is that</span> <span m=''1462080''>the</span> <span
  m=''1462573''>one</span> <span m=''1463066''>for</span> <span m=''1463559''>us</span>
  <span m=''1464052''>[OBSCURED]</span> </p><p><span m=''1472070''>BRADLEY KUSZMAUL:
  That''s</span> <span m=''1472300''>too</span> <span m=''1472740''>long</span> <span
  m=''1473160''>to say.</span> <span m=''1474460''>I</span> <span m=''1474590''>might</span>
  <span m=''1474720''>as well</span> <span m=''1474850''>say</span> <span m=''1474980''>critical</span>
  <span m=''1475310''>path</span> <span m=''1475600''>length.</span> <span m=''1477240''>Critical</span>
  <span m=''1477560''>path</span> <span m=''1477910''>length,</span> <span m=''1478160''>longest</span>
  <span m=''1478580''>trace</span> <span m=''1478890''>span</span> <span m=''1479250''>is
  a</span> <span m=''1479610''>mathematical</span> <span m=''1480440''>sounding</span>
  <span m=''1480860''>name.</span> </p><p><span m=''1485956''>AUDIENCE: We</span>
  <span m=''1486472''>just</span> <span m=''1486988''>like</span> <span m=''1487160''>to</span>
  <span m=''1487332''>steal</span> <span m=''1487504''>terminology.</span> </p><p><span
  m=''1488020''>BRADLEY KUSZMAUL: Well,</span> <span m=''1488710''>yeah.</span> <span
  m=''1490510''>So</span> <span m=''1490660''>there''s</span> <span m=''1490850''>a</span>
  <span m=''1490970''>theorem</span> <span m=''1491540''>due to--</span> <span m=''1491660''>Graham
  and</span> <span m=''1492040''>Brent</span> <span m=''1492410''>said</span> <span
  m=''1492830''>that there''s</span> <span m=''1492960''>some</span> <span m=''1493330''>schedule</span>
  <span m=''1494140''>that</span> <span m=''1494340''>can</span> <span m=''1494500''>actually</span>
  <span m=''1495020''>achieve</span> <span m=''1496040''>the</span> <span m=''1496290''>sum
  of</span> <span m=''1496600''>those</span> <span m=''1496900''>two lower</span>
  <span m=''1497320''>bounds.</span> <span m=''1498040''>This</span> <span m=''1498170''>linear</span>
  <span m=''1498450''>speedup</span> <span m=''1498860''>is</span> <span m=''1499380''>one</span>
  <span m=''1499590''>lower</span> <span m=''1499840''>bound</span> <span m=''1500160''>of
  the</span> <span m=''1500260''>runtime</span> <span m=''1501340''>and</span> <span
  m=''1501740''>the</span> <span m=''1501980''>critical</span> <span m=''1502340''>path</span>
  <span m=''1502780''>is the</span> <span m=''1502910''>other.</span> <span m=''1504470''>So</span>
  <span m=''1504610''>there''s</span> <span m=''1504790''>some</span> <span m=''1505080''>schedule</span>
  <span m=''1505230''>that</span> <span m=''1505460''>basically</span> <span m=''1505970''>achieves</span>
  <span m=''1506270''>the</span> <span m=''1506313''>sum</span> <span m=''1506356''>of</span>
  <span m=''1506400''>those</span> <span m=''1507790''>and</span> <span m=''1508180''>how</span>
  <span m=''1508370''>does</span> <span m=''1508530''>that</span> <span m=''1508890''>theorem</span>
  <span m=''1509150''>work?</span> <span m=''1509360''>Well,</span> <span m=''1510310''>at</span>
  <span m=''1510440''>each</span> <span m=''1510700''>time</span> <span m=''1511160''>step</span>
  <span m=''1511570''>either--</span> <span m=''1512350''>suppose</span> <span m=''1512730''>we
  had</span> <span m=''1512960''>3</span> <span m=''1513180''>processors.</span> <span
  m=''1514400''>Either</span> <span m=''1514580''>there''s</span> <span m=''1514870''>at</span>
  <span m=''1514970''>least</span> <span m=''1515720''>3</span> <span m=''1516050''>things</span>
  <span m=''1516350''>ready</span> <span m=''1516580''>to</span> <span m=''1516680''>run</span>
  <span m=''1519080''>and</span> <span m=''1519300''>so</span> <span m=''1520090''>what</span>
  <span m=''1520240''>you</span> <span m=''1520370''>do</span> <span m=''1520740''>is</span>
  <span m=''1520940''>you</span> <span m=''1521030''>do a</span> <span m=''1521190''>greedy</span>
  <span m=''1521490''>schedule.</span> <span m=''1522460''>You grab</span> <span m=''1522950''>any</span>
  <span m=''1523190''>3</span> <span m=''1523480''>of</span> <span m=''1523580''>them.</span>
  <span m=''1527790''>If</span> <span m=''1528010''>there''s</span> <span m=''1528190''>fewer</span>
  <span m=''1528350''>than</span> <span m=''1528630''>p</span> <span m=''1528840''>things</span>
  <span m=''1529140''>to run,</span> <span m=''1529470''>like</span> <span m=''1529630''>here</span>
  <span m=''1529840''>we</span> <span m=''1529940''>have</span> <span m=''1530070''>a</span>
  <span m=''1530120''>situation</span> <span m=''1530920''>where</span> <span m=''1533550''>these</span>
  <span m=''1533820''>have</span> <span m=''1533930''>all</span> <span m=''1534130''>run.</span>
  <span m=''1534680''>The</span> <span m=''1534780''>green</span> <span m=''1535030''>ones</span>
  <span m=''1535210''>are</span> <span m=''1535290''>ready</span> <span m=''1535580''>to</span>
  <span m=''1535680''>go.</span> <span m=''1536270''>Those</span> <span m=''1536540''>are</span>
  <span m=''1536610''>the</span> <span m=''1536700''>only</span> <span m=''1536910''>2</span>
  <span m=''1537070''>that</span> <span m=''1537240''>are</span> <span m=''1537320''>ready</span>
  <span m=''1537560''>to</span> <span m=''1537660''>go.</span> <span m=''1538600''>So</span>
  <span m=''1538800''>what</span> <span m=''1538920''>do</span> <span m=''1538990''>you</span>
  <span m=''1539100''>do</span> <span m=''1539250''>then in</span> <span m=''1539750''>a
  greedy</span> <span m=''1540160''>schedule?</span> <span m=''1540640''>You</span>
  <span m=''1541440''>run</span> <span m=''1541710''>them</span> <span m=''1541790''>all.</span>
  <span m=''1544880''>And</span> <span m=''1545060''>the</span> <span m=''1545130''>argument</span>
  <span m=''1545670''>goes,</span> <span m=''1548910''>well,</span> <span m=''1549200''>how</span>
  <span m=''1549540''>many</span> <span m=''1549830''>times</span> <span m=''1550130''>steps</span>
  <span m=''1550420''>could</span> <span m=''1550590''>you</span> <span m=''1550730''>execute</span>
  <span m=''1551170''>3</span> <span m=''1551510''>things?</span> <span m=''1555800''>At</span>
  <span m=''1556070''>most</span> <span m=''1556420''>you</span> <span m=''1556520''>could</span>
  <span m=''1556680''>do</span> <span m=''1556810''>it</span> <span m=''1556930''>the</span>
  <span m=''1557030''>work</span> <span m=''1557320''>divided</span> <span m=''1557640''>by</span>
  <span m=''1557730''>the</span> <span m=''1557830''>number of</span> <span m=''1558090''>processors</span>
  <span m=''1558680''>times</span> <span m=''1559430''>because</span> <span m=''1559640''>then</span>
  <span m=''1560000''>after</span> <span m=''1560280''>that</span> <span m=''1560450''>you''ve
  used</span> <span m=''1560800''>up</span> <span m=''1560920''>all</span> <span m=''1561060''>the</span>
  <span m=''1561140''>work.</span> <span m=''1562860''>Well</span> <span m=''1563010''>how</span>
  <span m=''1563150''>many</span> <span m=''1563330''>times</span> <span m=''1563690''>could</span>
  <span m=''1563860''>you</span> <span m=''1563990''>execute</span> <span m=''1564270''>less</span>
  <span m=''1564570''>than</span> <span m=''1565460''>p</span> <span m=''1565740''>things?</span>
  <span m=''1567910''>Well,</span> <span m=''1568090''>every</span> <span m=''1568260''>time</span>
  <span m=''1568480''>you</span> <span m=''1568660''>execute</span> <span m=''1568970''>less
  than</span> <span m=''1569360''>p</span> <span m=''1569530''>things</span> <span
  m=''1569810''>you''re</span> <span m=''1569940''>reducing</span> <span m=''1570470''>the</span>
  <span m=''1570570''>length</span> <span m=''1570910''>of</span> <span m=''1570990''>the</span>
  <span m=''1571070''>remaining</span> <span m=''1571490''>critical</span> <span m=''1571840''>path.</span>
  <span m=''1573090''>You</span> <span m=''1573230''>can''t</span> <span m=''1573500''>do</span>
  <span m=''1573600''>that</span> <span m=''1573890''>more</span> <span m=''1574100''>than</span>
  <span m=''1574820''>the</span> <span m=''1575680''>span times.</span> <span m=''1577130''>And</span>
  <span m=''1577360''>so</span> <span m=''1577870''>a greedy</span> <span m=''1578310''>scheduler</span>
  <span m=''1579250''>will</span> <span m=''1579480''>achieve</span> <span m=''1580020''>some</span>
  <span m=''1580290''>runtime</span> <span m=''1580730''>which</span> <span m=''1580910''>is</span>
  <span m=''1581040''>within</span> <span m=''1581470''>the</span> <span m=''1581560''>sum</span>
  <span m=''1581880''>of</span> <span m=''1581980''>these</span> <span m=''1582220''>2.</span>
  <span m=''1582520''>It''s</span> <span m=''1583220''>actually</span> <span m=''1584000''>the
  sum</span> <span m=''1584340''>of</span> <span m=''1584430''>these</span> <span
  m=''1584660''>2</span> <span m=''1584840''>minus</span> <span m=''1585240''>1.</span>
  <span m=''1585990''>It</span> <span m=''1586110''>turns</span> <span m=''1586390''>out</span>
  <span m=''1586620''>that</span> <span m=''1587340''>there</span> <span m=''1587485''>has</span>
  <span m=''1587630''>to</span> <span m=''1587690''>be</span> <span m=''1587770''>at</span>
  <span m=''1587840''>least</span> <span m=''1588100''>one</span> <span m=''1588350''>node</span>
  <span m=''1588520''>that''s</span> <span m=''1588750''>on</span> <span m=''1588940''>both</span>
  <span m=''1589600''>work</span> <span m=''1589920''>and</span> <span m=''1590100''>critical</span>
  <span m=''1590520''>path.</span> <span m=''1592430''>And</span> <span m=''1592750''>so</span>
  <span m=''1592880''>that</span> <span m=''1593030''>means</span> <span m=''1593240''>that</span>
  <span m=''1593420''>you''re</span> <span m=''1593540''>guaranteed</span> <span m=''1593950''>to</span>
  <span m=''1594020''>be</span> <span m=''1594110''>within</span> <span m=''1594360''>a</span>
  <span m=''1594400''>factor</span> <span m=''1594750''>of</span> <span m=''1594840''>2</span>
  <span m=''1595840''>of</span> <span m=''1596110''>optimal</span> <span m=''1597320''>with</span>
  <span m=''1597550''>a</span> <span m=''1597640''>greedy</span> <span m=''1597920''>schedule.</span>
  </p><p><span m=''1599720''>And</span> <span m=''1599870''>it</span> <span m=''1599960''>turns</span>
  <span m=''1600250''>out</span> <span m=''1600470''>that</span> <span m=''1600640''>if
  you</span> <span m=''1600790''>have</span> <span m=''1601760''>a</span> <span m=''1601880''>lot
  of</span> <span m=''1602320''>parallelism</span> <span m=''1603030''>compared</span>
  <span m=''1603430''>to</span> <span m=''1603490''>the</span> <span m=''1603570''>number</span>
  <span m=''1603830''>processors,</span> <span m=''1605410''>so if</span> <span m=''1605550''>you</span>
  <span m=''1605630''>have</span> <span m=''1605740''>a</span> <span m=''1605810''>graph</span>
  <span m=''1606190''>that</span> <span m=''1606280''>has</span> <span m=''1606440''>a</span>
  <span m=''1606490''>million</span> <span m=''1606920''>fold</span> <span m=''1607150''>parallelism</span>
  <span m=''1608620''>and</span> <span m=''1608790''>a</span> <span m=''1608820''>thousand</span>
  <span m=''1609330''>fold</span> <span m=''1609590''>processors</span> <span m=''1610280''>Well,</span>
  <span m=''1611850''>if</span> <span m=''1612690''>this</span> <span m=''1612930''>is</span>
  <span m=''1613190''>really</span> <span m=''1613660''>small</span> <span m=''1614250''>compared</span>
  <span m=''1614730''>to</span> <span m=''1614890''>the</span> <span m=''1615020''>work,</span>
  <span m=''1616110''>if</span> <span m=''1616210''>you</span> <span m=''1616273''>have</span>
  <span m=''1616336''>a</span> <span m=''1616400''>graph</span> <span m=''1616680''>with</span>
  <span m=''1616820''>a</span> <span m=''1616880''>million</span> <span m=''1617190''>fold</span>
  <span m=''1617440''>parallelism</span> <span m=''1617980''>that</span> <span m=''1618180''>means</span>
  <span m=''1618290''>the</span> <span m=''1618380''>critical</span> <span m=''1618700''>path</span>
  <span m=''1619030''>is</span> <span m=''1619120''>small.</span> <span m=''1620410''>If
  you</span> <span m=''1620550''>only</span> <span m=''1620830''>had 1000</span> <span
  m=''1621120''>processors</span> <span m=''1621690''>that</span> <span m=''1621830''>means</span>
  <span m=''1622010''>this</span> <span m=''1622190''>term''s</span> <span m=''1622490''>big.</span>
  <span m=''1625220''>And</span> <span m=''1625350''>that</span> <span m=''1625590''>means</span>
  <span m=''1625790''>that</span> <span m=''1625890''>this</span> <span m=''1626110''>term</span>
  <span m=''1626470''>is</span> <span m=''1626630''>very</span> <span m=''1626960''>close</span>
  <span m=''1627260''>to</span> <span m=''1627360''>this</span> <span m=''1627560''>term,</span>
  <span m=''1628300''>so</span> <span m=''1628420''>essentially</span> <span m=''1628920''>the</span>
  <span m=''1629010''>corollary</span> <span m=''1629600''>to</span> <span m=''1629690''>this</span>
  <span m=''1629910''>is</span> <span m=''1630030''>that</span> <span m=''1630140''>you</span>
  <span m=''1630260''>get</span> <span m=''1631540''>linear</span> <span m=''1631730''>speedup,</span>
  <span m=''1633510''>perfect</span> <span m=''1633860''>linear</span> <span m=''1634130''>speed</span>
  <span m=''1634420''>asymptotically</span> <span m=''1636350''>if</span> <span m=''1636570''>you</span>
  <span m=''1636710''>have</span> <span m=''1637770''>fewer</span> <span m=''1637950''>processors</span>
  <span m=''1638660''>then</span> <span m=''1638840''>you</span> <span m=''1638950''>have</span>
  <span m=''1640560''>parallelism</span> <span m=''1641120''>in</span> <span m=''1641210''>your</span>
  <span m=''1641330''>program.</span> <span m=''1642060''>So</span> <span m=''1642190''>the</span>
  <span m=''1642290''>game</span> <span m=''1642640''>here</span> <span m=''1643790''>at</span>
  <span m=''1644030''>this</span> <span m=''1644280''>level</span> <span m=''1644620''>of</span>
  <span m=''1645410''>understanding,</span> <span m=''1645930''>I</span> <span m=''1646090''>haven''t</span>
  <span m=''1646280''>told</span> <span m=''1646313''>you</span> <span m=''1646346''>how</span>
  <span m=''1646380''>the</span> <span m=''1646530''>scheduler</span> <span m=''1647040''>actually</span>
  <span m=''1647370''>works--</span> <span m=''1647860''>is</span> <span m=''1648120''>to</span>
  <span m=''1648240''>write</span> <span m=''1648450''>a</span> <span m=''1648500''>program</span>
  <span m=''1648910''>that''s</span> <span m=''1649050''>got</span> <span m=''1649180''>a</span>
  <span m=''1649220''>lot</span> <span m=''1649440''>of</span> <span m=''1649510''>parallelism</span>
  <span m=''1650190''>that</span> <span m=''1650340''>you</span> <span m=''1650460''>can</span>
  <span m=''1650580''>get</span> <span m=''1650720''>linear</span> <span m=''1650990''>speedup.</span>
  <span m=''1658070''>Well,</span> <span m=''1658520''>the</span> <span m=''1658660''>work-stealing</span>
  <span m=''1659220''>scheduler</span> <span m=''1659610''>we</span> <span m=''1659730''>actually</span>
  <span m=''1660230''>use.</span> <span m=''1660390''>The</span> <span m=''1660460''>problem</span>
  <span m=''1660720''>is</span> <span m=''1660870''>the</span> <span m=''1661110''>greedy</span>
  <span m=''1661480''>schedulers</span> <span m=''1661680''>can be</span> <span m=''1661830''>hard</span>
  <span m=''1662190''>to compute--</span> <span m=''1662570''>especially</span> <span
  m=''1663440''>if you</span> <span m=''1663550''>imagine</span> <span m=''1663950''>having</span>
  <span m=''1664250''>a</span> <span m=''1664280''>million</span> <span m=''1664670''>processors</span>
  <span m=''1665370''>in</span> <span m=''1665460''>a</span> <span m=''1665510''>program</span>
  <span m=''1665910''>with</span> <span m=''1666030''>a</span> <span m=''1666080''>billion</span>
  <span m=''1666460''>fold</span> <span m=''1666690''>parallelism.</span> <span m=''1668090''>Finding</span>
  <span m=''1668600''>on</span> <span m=''1668750''>every</span> <span m=''1668980''>clock</span>
  <span m=''1669300''>cycle,</span> <span m=''1669680''>finding</span> <span m=''1670190''>something</span>
  <span m=''1670560''>for</span> <span m=''1670690''>each</span> <span m=''1670860''>of</span>
  <span m=''1670940''>the</span> <span m=''1671020''>million</span> <span m=''1671370''>guys</span>
  <span m=''1671680''>to</span> <span m=''1671790''>do</span> <span m=''1672060''>is</span>
  <span m=''1673470''>conceptually</span> <span m=''1673980''>difficult,</span> <span
  m=''1674470''>so</span> <span m=''1674580''>instead</span> <span m=''1674980''>we</span>
  <span m=''1675380''>have</span> <span m=''1675570''>a</span> <span m=''1676130''>work-stealing</span>
  <span m=''1676810''>scheduler.</span> <span m=''1677520''>I''ll</span> <span m=''1677710''>talk</span>
  <span m=''1677940''>about</span> <span m=''1678110''>that</span> <span m=''1678230''>in</span>
  <span m=''1678290''>a</span> <span m=''1678370''>second.</span> <span m=''1679140''>It</span>
  <span m=''1679450''>achieves</span> <span m=''1680010''>bounds</span> <span m=''1680510''>which</span>
  <span m=''1680680''>are</span> <span m=''1680750''>not</span> <span m=''1681000''>quite</span>
  <span m=''1681350''>as</span> <span m=''1681480''>good</span> <span m=''1681670''>as</span>
  <span m=''1682110''>those.</span> <span m=''1682970''>This</span> <span m=''1683190''>bound</span>
  <span m=''1683490''>is</span> <span m=''1683630''>the</span> <span m=''1683720''>same.</span>
  <span m=''1684140''>It''s</span> <span m=''1684260''>the</span> <span m=''1684360''>sum</span>
  <span m=''1684550''>of</span> <span m=''1684660''>two</span> <span m=''1684840''>terms.</span>
  <span m=''1685240''>One</span> <span m=''1685450''>is</span> <span m=''1685610''>the</span>
  <span m=''1685710''>linear</span> <span m=''1686010''>speedup</span> <span m=''1686470''>term,</span>
  <span m=''1687130''>but</span> <span m=''1687330''>instead</span> <span m=''1687610''>of</span>
  <span m=''1687690''>it</span> <span m=''1687790''>being</span> <span m=''1688020''>T
  sub</span> <span m=''1688210''>infinity</span> <span m=''1688770''>it''s</span>
  <span m=''1688940''>big</span> <span m=''1689230''>O</span> <span m=''1689400''>of</span>
  <span m=''1689570''>T sub</span> <span m=''1689740''>infinity</span> <span m=''1691260''>because</span>
  <span m=''1691570''>you</span> <span m=''1691680''>actually</span> <span m=''1691950''>have</span>
  <span m=''1692040''>to</span> <span m=''1692130''>do</span> <span m=''1692250''>communication</span>
  <span m=''1694010''>sometimes</span> <span m=''1694850''>if</span> <span m=''1694980''>the</span>
  <span m=''1695070''>critical</span> <span m=''1695420''>path</span> <span m=''1695720''>length</span>
  <span m=''1695930''>is</span> <span m=''1696210''>long.</span> </p><p><span m=''1697530''>Basically,</span>
  <span m=''1698120''>you</span> <span m=''1698245''>can</span> <span m=''1698370''>sort</span>
  <span m=''1698410''>of</span> <span m=''1698450''>imagine.</span> <span m=''1698860''>If</span>
  <span m=''1698940''>you</span> <span m=''1699030''>have</span> <span m=''1699130''>a</span>
  <span m=''1699210''>lot</span> <span m=''1699410''>of</span> <span m=''1699510''>things</span>
  <span m=''1699770''>to</span> <span m=''1699870''>do,</span> <span m=''1700680''>a
  lot</span> <span m=''1700930''>of</span> <span m=''1701010''>tasks</span> <span
  m=''1701550''>and</span> <span m=''1701680''>people</span> <span m=''1701930''>to</span>
  <span m=''1702030''>do</span> <span m=''1702210''>it,</span> <span m=''1702940''>it''s</span>
  <span m=''1703140''>easy</span> <span m=''1704000''>to</span> <span m=''1704420''>do</span>
  <span m=''1704580''>that</span> <span m=''1704830''>in</span> <span m=''1704930''>parallel</span>
  <span m=''1705400''>if</span> <span m=''1705520''>there''s</span> <span m=''1705700''>no</span>
  <span m=''1705840''>interdependencies</span> <span m=''1706570''>among</span> <span
  m=''1706780''>the</span> <span m=''1706870''>tasks.</span> <span m=''1707810''>But</span>
  <span m=''1708050''>as</span> <span m=''1708140''>soon</span> <span m=''1708340''>as</span>
  <span m=''1708560''>there''s</span> <span m=''1708740''>dependencies</span> <span
  m=''1709340''>you</span> <span m=''1709510''>end</span> <span m=''1709610''>up</span>
  <span m=''1709680''>having</span> <span m=''1709930''>to</span> <span m=''1710020''>coordinate</span>
  <span m=''1710560''>a</span> <span m=''1710640''>lot</span> <span m=''1711000''>and</span>
  <span m=''1711250''>that</span> <span m=''1711650''>communication</span> <span m=''1712290''>costs--</span>
  <span m=''1713530''>there''s</span> <span m=''1714020''>lots</span> <span m=''1714730''>of</span>
  <span m=''1715080''>lore</span> <span m=''1715690''>about</span> <span m=''1716140''>adding</span>
  <span m=''1716420''>programmers</span> <span m=''1716980''>to</span> <span m=''1717130''>a</span>
  <span m=''1717200''>task</span> <span m=''1717620''>and</span> <span m=''1717760''>it</span>
  <span m=''1717840''>slowing</span> <span m=''1718210''>you</span> <span m=''1718340''>down.</span>
  <span m=''1721590''>Because</span> <span m=''1721920''>basically</span> <span m=''1722430''>communication</span>
  <span m=''1723030''>gets</span> <span m=''1723240''>you.</span> <span m=''1725380''>What</span>
  <span m=''1725640''>we</span> <span m=''1725750''>found</span> <span m=''1726050''>empirically--</span>
  <span m=''1727170''>there''s</span> <span m=''1727410''>a</span> <span m=''1727760''>theorem</span>
  <span m=''1728180''>for</span> <span m=''1728310''>this--</span> <span m=''1728680''>empirically</span>
  <span m=''1729790''>the</span> <span m=''1730420''>runtime</span> <span m=''1731000''>is</span>
  <span m=''1731120''>actually</span> <span m=''1731500''>still</span> <span m=''1732160''>very</span>
  <span m=''1732460''>close</span> <span m=''1732900''>to</span> <span m=''1733130''>the</span>
  <span m=''1733250''>sum</span> <span m=''1733660''>of</span> <span m=''1733820''>those</span>
  <span m=''1734060''>terms.</span> <span m=''1734980''>Or</span> <span m=''1735180''>maybe</span>
  <span m=''1735400''>it''s</span> <span m=''1735610''>those</span> <span m=''1735910''>terms</span>
  <span m=''1736320''>plus</span> <span m=''1736700''>2</span> <span m=''1736960''>times</span>
  <span m=''1737330''>T sub</span> <span m=''1737470''>infinity</span> <span m=''1738010''>or</span>
  <span m=''1738150''>something</span> <span m=''1738510''>like</span> <span m=''1738690''>that.</span>
  <span m=''1740610''>And</span> <span m=''1740790''>again,</span> <span m=''1741040''>we</span>
  <span m=''1741150''>basically</span> <span m=''1741580''>get</span> <span m=''1741770''>near-perfect</span>
  <span m=''1742380''>speedup</span> <span m=''1742770''>as</span> <span m=''1742880''>long</span>
  <span m=''1743190''>as</span> <span m=''1743670''>the</span> <span m=''1743773''>number</span>
  <span m=''1743876''>of</span> <span m=''1743980''>processors</span> <span m=''1744620''>is</span>
  <span m=''1744750''>a</span> <span m=''1744830''>lot</span> <span m=''1745050''>less</span>
  <span m=''1745260''>than</span> <span m=''1745370''>the</span> <span m=''1745450''>parallelism.</span>
  <span m=''1746250''>Should</span> <span m=''1746460''>be</span> <span m=''1746530''>sort</span>
  <span m=''1746715''>of</span> <span m=''1746900''>a less</span> <span m=''1747240''>than</span>
  <span m=''1747765''>less</span> <span m=''1748290''>than.</span> </p><p><span m=''1752320''>The</span>
  <span m=''1752880''>compiler</span> <span m=''1753310''>has</span> <span m=''1753470''>the</span>
  <span m=''1753540''>mode</span> <span m=''1753760''>where</span> <span m=''1753870''>you</span>
  <span m=''1753950''>basically</span> <span m=''1754380''>can</span> <span m=''1754530''>insert</span>
  <span m=''1754950''>instrumentations.</span> <span m=''1755310''>So</span> <span
  m=''1755750''>you</span> <span m=''1755860''>can</span> <span m=''1756000''>run</span>
  <span m=''1756160''>your</span> <span m=''1756270''>program,</span> <span m=''1756700''>it''ll</span>
  <span m=''1756900''>tell</span> <span m=''1757130''>you</span> <span m=''1757250''>the</span>
  <span m=''1757340''>critical</span> <span m=''1757700''>path</span> <span m=''1757980''>length.</span>
  <span m=''1758200''>You</span> <span m=''1758290''>can</span> <span m=''1758430''>compute</span>
  <span m=''1758790''>these</span> <span m=''1758980''>numbers.</span> <span m=''1760530''>Clear</span>
  <span m=''1760730''>how</span> <span m=''1760850''>to</span> <span m=''1760930''>compute</span>
  <span m=''1761210''>work,</span> <span m=''1761550''>you</span> <span m=''1761640''>just</span>
  <span m=''1761870''>sum</span> <span m=''1762090''>up</span> <span m=''1762280''>the</span>
  <span m=''1762610''>runtime</span> <span m=''1762980''>of</span> <span m=''1763090''>all</span>
  <span m=''1763220''>the</span> <span m=''1763310''>threads.</span> <span m=''1764590''>To</span>
  <span m=''1764710''>compute</span> <span m=''1765110''>the</span> <span m=''1765920''>critical</span>
  <span m=''1766240''>path</span> <span m=''1766530''>length,</span> <span m=''1766790''>well</span>
  <span m=''1766930''>you</span> <span m=''1767060''>have</span> <span m=''1767170''>to</span>
  <span m=''1767260''>do</span> <span m=''1767360''>some</span> <span m=''1767560''>max''s</span>
  <span m=''1768030''>and</span> <span m=''1768190''>stuff</span> <span m=''1768790''>as</span>
  <span m=''1768970''>you</span> <span m=''1769050''>go</span> <span m=''1769180''>through</span>
  <span m=''1769330''>the</span> <span m=''1769420''>graph.</span> <span m=''1771540''>And</span>
  <span m=''1771880''>the</span> <span m=''1771980''>average</span> <span m=''1772350''>cost</span>
  <span m=''1772770''>of</span> <span m=''1772860''>a</span> <span m=''1772920''>spawn</span>
  <span m=''1773400''>these</span> <span m=''1773650''>days</span> <span m=''1774030''>is</span>
  <span m=''1774140''>about</span> <span m=''1774540''>3</span> <span m=''1775230''>on</span>
  <span m=''1776000''>like</span> <span m=''1776200''>a</span> <span m=''1777130''>dual</span>
  <span m=''1777400''>core</span> <span m=''1778310''>pentium.</span> <span m=''1779580''>Three</span>
  <span m=''1780020''>times</span> <span m=''1780590''>the</span> <span m=''1780690''>cost</span>
  <span m=''1780960''>of</span> <span m=''1781040''>a</span> <span m=''1781110''>function</span>
  <span m=''1781460''>call.</span> <span m=''1782270''>And</span> <span m=''1782560''>most</span>
  <span m=''1782860''>of</span> <span m=''1782940''>that</span> <span m=''1783150''>cost</span>
  <span m=''1783590''>actually</span> <span m=''1784090''>has</span> <span m=''1784300''>to</span>
  <span m=''1784390''>do</span> <span m=''1784520''>with</span> <span m=''1784680''>the</span>
  <span m=''1784750''>memory</span> <span m=''1785080''>barrier</span> <span m=''1786120''>that</span>
  <span m=''1786290''>we</span> <span m=''1786450''>do</span> <span m=''1786610''>at</span>
  <span m=''1786820''>the</span> <span m=''1786980''>spawn</span> <span m=''1787390''>because</span>
  <span m=''1788200''>that</span> <span m=''1788390''>machine</span> <span m=''1788700''>doesn''t</span>
  <span m=''1788960''>have</span> <span m=''1789110''>strong</span> <span m=''1789430''>consistencies.</span>
  <span m=''1790080''>So</span> <span m=''1790210''>you</span> <span m=''1790300''>have</span>
  <span m=''1790430''>to</span> <span m=''1790520''>put</span> <span m=''1790650''>this</span>
  <span m=''1790780''>memory</span> <span m=''1791120''>barrier</span> <span m=''1791580''>in</span>
  <span m=''1791770''>and</span> <span m=''1791900''>that</span> <span m=''1792040''>just</span>
  <span m=''1792360''>empties</span> <span m=''1792670''>all</span> <span m=''1792810''>the</span>
  <span m=''1792910''>pipelines.</span> <span m=''1796480''>It</span> <span m=''1796990''>does</span>
  <span m=''1797320''>better</span> <span m=''1797590''>on</span> <span m=''1797800''>like</span>
  <span m=''1797930''>an</span> <span m=''1798020''>SGI</span> <span m=''1798610''>machine,</span>
  <span m=''1798960''>which</span> <span m=''1799140''>has</span> <span m=''1799260''>strong--</span>
  <span m=''1800100''>well,</span> <span m=''1800500''>traditional.</span> <span m=''1801480''>A</span>
  <span m=''1801630''>MIPS</span> <span m=''1801820''>machine</span> <span m=''1802130''>that</span>
  <span m=''1802230''>has</span> <span m=''1802420''>strong</span> <span m=''1802740''>consistency</span>
  <span m=''1803380''>actually</span> <span m=''1804270''>does</span> <span m=''1804520''>better</span>
  <span m=''1805610''>for</span> <span m=''1805790''>the</span> <span m=''1806210''>cost</span>
  <span m=''1806520''>of</span> <span m=''1806580''>that</span> <span m=''1806700''>overhead.</span>
  </p><p><span m=''1808440''>Let</span> <span m=''1808590''>me</span> <span m=''1808650''>talk</span>
  <span m=''1808900''>a</span> <span m=''1808940''>little</span> <span m=''1809130''>bit</span>
  <span m=''1809270''>about</span> <span m=''1809430''>chess.</span> <span m=''1810490''>And</span>
  <span m=''1811820''>we</span> <span m=''1811990''>had</span> <span m=''1812170''>a</span>
  <span m=''1812200''>bunch</span> <span m=''1812410''>of</span> <span m=''1812470''>chess</span>
  <span m=''1812740''>programs.</span> <span m=''1813420''>I</span> <span m=''1813600''>wrote</span>
  <span m=''1813900''>one</span> <span m=''1814880''>in</span> <span m=''1815260''>1994,</span>
  <span m=''1816410''>which</span> <span m=''1816680''>placed</span> <span m=''1817130''>third</span>
  <span m=''1818080''>at</span> <span m=''1818350''>the</span> <span m=''1818580''>International</span>
  <span m=''1819130''>Computer</span> <span m=''1819450''>Chess</span> <span m=''1819650''>Championship</span>
  <span m=''1820230''>and</span> <span m=''1820330''>that</span> <span m=''1820440''>was</span>
  <span m=''1820570''>running</span> <span m=''1820870''>on</span> <span m=''1821110''>a</span>
  <span m=''1821240''>big</span> <span m=''1821540''>connection</span> <span m=''1821940''>machine</span>
  <span m=''1822210''>CM5.</span> <span m=''1823960''>I</span> <span m=''1824060''>was</span>
  <span m=''1824210''>one</span> <span m=''1824330''>of</span> <span m=''1824390''>the</span>
  <span m=''1824450''>architects</span> <span m=''1824860''>of</span> <span m=''1824930''>that</span>
  <span m=''1825090''>machine,</span> <span m=''1825440''>so</span> <span m=''1825663''>it</span>
  <span m=''1825886''>was</span> <span m=''1826110''>double</span> <span m=''1826340''>fun.</span>
  <span m=''1827770''>We</span> <span m=''1827930''>wrote</span> <span m=''1828150''>another</span>
  <span m=''1828450''>program</span> <span m=''1829210''>that</span> <span m=''1829480''>placed</span>
  <span m=''1829800''>second</span> <span m=''1830340''>in</span> <span m=''1830480''>''95</span>
  <span m=''1831870''>and</span> <span m=''1831990''>that</span> <span m=''1832110''>was</span>
  <span m=''1832230''>running</span> <span m=''1832510''>on</span> <span m=''1832700''>an</span>
  <span m=''1833110''>1800</span> <span m=''1833440''>node</span> <span m=''1833710''>Paragon</span>
  <span m=''1834250''>and</span> <span m=''1834340''>that</span> <span m=''1834490''>was</span>
  <span m=''1834600''>a</span> <span m=''1834660''>big</span> <span m=''1834860''>computer</span>
  <span m=''1835220''>back</span> <span m=''1835480''>then.</span> <span m=''1837020''>We</span>
  <span m=''1837220''>built</span> <span m=''1837590''>another</span> <span m=''1837960''>program</span>
  <span m=''1838440''>called</span> <span m=''1838690''>Cilk</span> <span m=''1838960''>chess,</span>
  <span m=''1839600''>which</span> <span m=''1840520''>placed</span> <span m=''1840940''>first</span>
  <span m=''1842150''>in</span> <span m=''1842320''>''96</span> <span m=''1842890''>running</span>
  <span m=''1843130''>on</span> <span m=''1843290''>a</span> <span m=''1844130''>relatively</span>
  <span m=''1844800''>smaller</span> <span m=''1845520''>machine.</span> <span m=''1846440''>And</span>
  <span m=''1846820''>then</span> <span m=''1846980''>on</span> <span m=''1847140''>a</span>
  <span m=''1847970''>larger</span> <span m=''1848360''>SGI</span> <span m=''1850290''>origin</span>
  <span m=''1851150''>we</span> <span m=''1851790''>ran</span> <span m=''1852010''>some</span>
  <span m=''1852160''>more</span> <span m=''1852570''>and</span> <span m=''1852810''>then</span>
  <span m=''1852950''>at</span> <span m=''1853030''>the</span> <span m=''1853110''>World</span>
  <span m=''1853370''>Computer</span> <span m=''1853670''>Chess</span> <span m=''1853930''>Championship</span>
  <span m=''1854560''>in</span> <span m=''1854650''>1999</span> <span m=''1856210''>we</span>
  <span m=''1856520''>beat</span> <span m=''1856920''>Deep</span> <span m=''1857810''>Blue</span>
  <span m=''1859930''>and</span> <span m=''1860230''>lost</span> <span m=''1860770''>to</span>
  <span m=''1861010''>a</span> <span m=''1861070''>PC.</span> <span m=''1864420''>And</span>
  <span m=''1865230''>people</span> <span m=''1865610''>don''t</span> <span m=''1865750''>realize</span>
  <span m=''1866120''>this,</span> <span m=''1866410''>but</span> <span m=''1866560''>at</span>
  <span m=''1866720''>the</span> <span m=''1866800''>time</span> <span m=''1867050''>that</span>
  <span m=''1867150''>Deep</span> <span m=''1867340''>Blue</span> <span m=''1867570''>beat</span>
  <span m=''1867740''>Kasparov</span> <span m=''1868360''>it</span> <span m=''1868470''>was</span>
  <span m=''1868650''>not</span> <span m=''1868880''>the</span> <span m=''1868960''>World</span>
  <span m=''1869160''>Computer</span> <span m=''1869470''>Chess</span> <span m=''1869740''>Champion,</span>
  <span m=''1870450''>a</span> <span m=''1870570''>PC</span> <span m=''1870920''>was.</span>
  <span m=''1873290''>So</span> <span m=''1874760''>what?</span> <span m=''1876150''>It''s</span>
  <span m=''1876240''>running</span> <span m=''1876470''>a</span> <span m=''1876520''>program.</span>
  <span m=''1880930''>You</span> <span m=''1881100''>know,</span> <span m=''1881260''>there''s</span>
  <span m=''1881490''>this</span> <span m=''1881800''>head</span> <span m=''1882140''>and</span>
  <span m=''1882300''>a</span> <span m=''1882390''>tape.</span> <span m=''1886830''>I</span>
  <span m=''1887130''>don''t</span> <span m=''1887280''>know</span> <span m=''1887350''>what</span>
  <span m=''1887520''>it</span> <span m=''1887630''>did.</span> </p><p><span m=''1889360''>So</span>
  <span m=''1889530''>this</span> <span m=''1889690''>was</span> <span m=''1889760''>a</span>
  <span m=''1889830''>program</span> <span m=''1890160''>called</span> <span m=''1890380''>Fritz,</span>
  <span m=''1891180''>which</span> <span m=''1891400''>is</span> <span m=''1891480''>a</span>
  <span m=''1891540''>commercially</span> <span m=''1891980''>available</span> <span
  m=''1892320''>program.</span> <span m=''1892860''>And</span> <span m=''1893080''>those</span>
  <span m=''1893290''>guys</span> <span m=''1894160''>were</span> <span m=''1894350''>very</span>
  <span m=''1894720''>good,</span> <span m=''1896170''>the</span> <span m=''1896320''>PC</span>
  <span m=''1896720''>guys</span> <span m=''1897270''>playing</span> <span m=''1897740''>were</span>
  <span m=''1897940''>very</span> <span m=''1898450''>good</span> <span m=''1898710''>at</span>
  <span m=''1898850''>getting</span> <span m=''1899620''>on</span> <span m=''1899830''>sort
  of</span> <span m=''1900040''>the</span> <span m=''1900150''>algorithm</span> <span
  m=''1900810''>side.</span> <span m=''1902290''>We</span> <span m=''1902450''>got</span>
  <span m=''1902660''>advantage</span> <span m=''1903060''>by</span> <span m=''1903190''>brute</span>
  <span m=''1903460''>force.</span> <span m=''1904680''>And</span> <span m=''1905260''>we</span>
  <span m=''1905370''>also</span> <span m=''1905500''>had</span> <span m=''1905700''>some</span>
  <span m=''1905840''>real</span> <span m=''1906040''>chess</span> <span m=''1906340''>expertise</span>
  <span m=''1906850''>on</span> <span m=''1906970''>our</span> <span m=''1907080''>team,</span>
  <span m=''1907630''>but</span> <span m=''1907900''>those</span> <span m=''1908120''>guys</span>
  <span m=''1908410''>were</span> <span m=''1908500''>spending</span> <span m=''1908810''>full</span>
  <span m=''1909110''>time</span> <span m=''1909510''>on</span> <span m=''1910590''>things</span>
  <span m=''1910880''>like</span> <span m=''1911060''>pruning</span> <span m=''1911430''>away</span>
  <span m=''1912610''>sub-searches</span> <span m=''1914160''>that</span> <span m=''1914330''>they</span>
  <span m=''1914460''>were</span> <span m=''1914620''>convinced</span> <span m=''1915100''>weren''t</span>
  <span m=''1915290''>going to</span> <span m=''1915470''>pan</span> <span m=''1915740''>out.</span>
  <span m=''1915930''>Computer</span> <span m=''1916230''>chess</span> <span m=''1916500''>programs</span>
  <span m=''1916950''>spend</span> <span m=''1917200''>most</span> <span m=''1917460''>of</span>
  <span m=''1917520''>their</span> <span m=''1917620''>time</span> <span m=''1917900''>looking</span>
  <span m=''1918180''>at</span> <span m=''1918340''>situations</span> <span m=''1918890''>that</span>
  <span m=''1919000''>any</span> <span m=''1919180''>person</span> <span m=''1919480''>would</span>
  <span m=''1919600''>look</span> <span m=''1919750''>at</span> <span m=''1919860''>and</span>
  <span m=''1919990''>say,</span> <span m=''1920470''>ah,</span> <span m=''1920720''>blacks</span>
  <span m=''1921130''>won.</span> <span m=''1921420''>Why are</span> <span m=''1921650''>you
  even</span> <span m=''1921880''>looking</span> <span m=''1922230''>at</span> <span
  m=''1922350''>this?</span> <span m=''1922560''>And</span> <span m=''1922970''>it</span>
  <span m=''1923100''>keeps</span> <span m=''1923290''>searching.</span> <span m=''1923820''>It''s</span>
  <span m=''1923930''>like,</span> <span m=''1924130''>well</span> <span m=''1924380''>maybe</span>
  <span m=''1924630''>there''s</span> <span m=''1924810''>a</span> <span m=''1924870''>way</span>
  <span m=''1925000''>to</span> <span m=''1925090''>get</span> <span m=''1925230''>the</span>
  <span m=''1925310''>queen.</span> <span m=''1930480''>So</span> <span m=''1930910''>computers</span>
  <span m=''1931350''>are</span> <span m=''1931430''>pretty</span> <span m=''1931680''>dumb</span>
  <span m=''1932000''>at</span> <span m=''1932080''>that.</span> <span m=''1932310''>So</span>
  <span m=''1932410''>basically</span> <span m=''1932880''>these</span> <span m=''1933080''>guys</span>
  <span m=''1933480''>put</span> <span m=''1933630''>a</span> <span m=''1933680''>lot</span>
  <span m=''1934030''>more</span> <span m=''1934240''>chess</span> <span m=''1934570''>intelligence</span>
  <span m=''1935170''>in</span> <span m=''1935380''>and</span> <span m=''1936150''>we</span>
  <span m=''1936440''>also</span> <span m=''1936740''>lost</span> <span m=''1937240''>due</span>
  <span m=''1937380''>to</span> <span m=''1937560''>what--</span> <span m=''1937700''>in</span>
  <span m=''1937840''>this</span> <span m=''1938160''>particular</span> <span m=''1938610''>game,</span>
  <span m=''1938900''>we</span> <span m=''1939270''>were</span> <span m=''1939470''>tied</span>
  <span m=''1939920''>for</span> <span m=''1940070''>first</span> <span m=''1940420''>place</span>
  <span m=''1941020''>and</span> <span m=''1941240''>we</span> <span m=''1941310''>decided</span>
  <span m=''1941760''>to</span> <span m=''1942340''>do</span> <span m=''1943190''>a</span>
  <span m=''1943390''>runoff</span> <span m=''1944260''>game</span> <span m=''1944570''>to</span>
  <span m=''1944650''>find</span> <span m=''1944870''>out</span> <span m=''1944940''>who</span>
  <span m=''1945080''>would</span> <span m=''1945200''>win</span> <span m=''1945450''>and</span>
  <span m=''1945580''>we</span> <span m=''1945700''>lost</span> <span m=''1946390''>due</span>
  <span m=''1946800''>to a</span> <span m=''1946880''>classic</span> <span m=''1947770''>horizon</span>
  <span m=''1948350''>effect.</span> <span m=''1949960''>So</span> <span m=''1950120''>it</span>
  <span m=''1950200''>turns</span> <span m=''1950480''>out</span> <span m=''1950690''>that</span>
  <span m=''1950820''>we</span> <span m=''1950980''>were</span> <span m=''1951120''>searching</span>
  <span m=''1951450''>to</span> <span m=''1951540''>depth</span> <span m=''1951860''>12</span>
  <span m=''1952420''>in</span> <span m=''1952850''>the</span> <span m=''1952910''>tree</span>
  <span m=''1953300''>and</span> <span m=''1953740''>Fritz</span> <span m=''1954060''>was</span>
  <span m=''1954160''>searching</span> <span m=''1954480''>to</span> <span m=''1954580''>depth</span>
  <span m=''1954840''>11.</span> <span m=''1955280''>Even</span> <span m=''1955560''>with</span>
  <span m=''1955670''>all</span> <span m=''1955930''>these</span> <span m=''1956700''>heuristics</span>
  <span m=''1957830''>and</span> <span m=''1957940''>stuff</span> <span m=''1958160''>they</span>
  <span m=''1958260''>had</span> <span m=''1958480''>in it,</span> <span m=''1958650''>they</span>
  <span m=''1958730''>were</span> <span m=''1958880''>still</span> <span m=''1959110''>not</span>
  <span m=''1959320''>searching</span> <span m=''1959680''>as</span> <span m=''1959810''>deeply</span>
  <span m=''1960170''>as</span> <span m=''1960290''>we</span> <span m=''1960460''>were.</span>
  <span m=''1961280''>But</span> <span m=''1961560''>there</span> <span m=''1961670''>was</span>
  <span m=''1962140''>a move</span> <span m=''1962620''>that</span> <span m=''1962860''>was</span>
  <span m=''1963180''>a</span> <span m=''1963630''>good</span> <span m=''1963940''>move</span>
  <span m=''1964240''>that</span> <span m=''1964330''>looked</span> <span m=''1964520''>OK</span>
  <span m=''1964870''>at</span> <span m=''1965050''>depth</span> <span m=''1965260''>11</span>
  <span m=''1965650''>and</span> <span m=''1965990''>looked</span> <span m=''1966170''>bad</span>
  <span m=''1966570''>at</span> <span m=''1966680''>depth</span> <span m=''1967000''>11</span>
  <span m=''1967430''>and</span> <span m=''1967530''>at depth</span> <span m=''1967860''>13</span>
  <span m=''1969120''>it</span> <span m=''1969290''>looked</span> <span m=''1969460''>really</span>
  <span m=''1969740''>good</span> <span m=''1969960''>again.</span> <span m=''1973000''>So</span>
  <span m=''1973200''>they</span> <span m=''1973380''>saw</span> <span m=''1973810''>the</span>
  <span m=''1973910''>move and</span> <span m=''1974330''>made</span> <span m=''1974510''>it</span>
  <span m=''1974620''>for</span> <span m=''1974730''>the</span> <span m=''1974800''>wrong</span>
  <span m=''1975080''>reason,</span> <span m=''1976240''>we</span> <span m=''1976460''>saw</span>
  <span m=''1976710''>the</span> <span m=''1976800''>move and</span> <span m=''1977160''>didn''t</span>
  <span m=''1977510''>make</span> <span m=''1977740''>it</span> <span m=''1978210''>for</span>
  <span m=''1978340''>the</span> <span m=''1978420''>right</span> <span m=''1978670''>reason,</span>
  <span m=''1979030''>but</span> <span m=''1979130''>it</span> <span m=''1979190''>was</span>
  <span m=''1979310''>wrong</span> <span m=''1980290''>and</span> <span m=''1980560''>the</span>
  <span m=''1980640''>right</span> <span m=''1980910''>move--</span> <span m=''1981140''>if</span>
  <span m=''1981360''>we''d</span> <span m=''1981690''>been</span> <span m=''1981800''>able</span>
  <span m=''1982020''>to</span> <span m=''1982120''>search</span> <span m=''1982760''>a</span>
  <span m=''1982860''>little</span> <span m=''1983080''>deeper,</span> <span m=''1983660''>we</span>
  <span m=''1983880''>would</span> <span m=''1984020''>have</span> <span m=''1984110''>seen</span>
  <span m=''1984620''>that</span> <span m=''1984790''>it</span> <span m=''1984880''>was</span>
  <span m=''1985320''>really</span> <span m=''1985560''>the</span> <span m=''1985640''>wrong</span>
  <span m=''1985970''>thing</span> <span m=''1986220''>to</span> <span m=''1986310''>do.</span>
  <span m=''1988070''>This</span> <span m=''1988250''>happens</span> <span m=''1988570''>all</span>
  <span m=''1988690''>the</span> <span m=''1988790''>time</span> <span m=''1989010''>in</span>
  <span m=''1989090''>chess.</span> <span m=''1989550''>There''s</span> <span m=''1989610''>a</span>
  <span m=''1989670''>little</span> <span m=''1989730''>randomness</span> <span m=''1990490''>in</span>
  <span m=''1990600''>there.</span> <span m=''1990760''>This</span> <span m=''1990950''>horizon</span>
  <span m=''1991400''>effect</span> <span m=''1991660''>shows</span> <span m=''1991980''>up</span>
  <span m=''1992290''>and</span> <span m=''1992660''>again,</span> <span m=''1992980''>it</span>
  <span m=''1993120''>boils</span> <span m=''1993510''>down</span> <span m=''1993760''>to</span>
  <span m=''1993820''>the</span> <span m=''1993890''>programs</span> <span m=''1994460''>are</span>
  <span m=''1994580''>not</span> <span m=''1994860''>intelligent.</span> <span m=''1995820''>A
  human</span> <span m=''1996150''>would</span> <span m=''1996280''>look</span> <span
  m=''1996440''>at</span> <span m=''1996600''>it and</span> <span m=''1996740''>say,</span>
  <span m=''1997050''>eventually</span> <span m=''1997600''>that</span> <span m=''1998210''>knight''s</span>
  <span m=''1998550''>going to</span> <span m=''1998720''>fall.</span> <span m=''1999730''>But</span>
  <span m=''1999960''>if</span> <span m=''2000050''>the</span> <span m=''2000140''>computer</span>
  <span m=''2000430''>can''t</span> <span m=''2000720''>see</span> <span m=''2000920''>it</span>
  <span m=''2001030''>with</span> <span m=''2001150''>a</span> <span m=''2001230''>search,</span>
  <span m=''2003510''>you</span> <span m=''2003700''>know?</span> </p><p><span m=''2007190''>We</span>
  <span m=''2007510''>plotted</span> <span m=''2007970''>the</span> <span m=''2008070''>speedup</span>
  <span m=''2008740''>of</span> <span m=''2009590''>star</span> <span m=''2010300''>Socrates,</span>
  <span m=''2010530''>which</span> <span m=''2010690''>was</span> <span m=''2010870''>the</span>
  <span m=''2010950''>first</span> <span m=''2011280''>one</span> <span m=''2012100''>on</span>
  <span m=''2012430''>this</span> <span m=''2012630''>funny</span> <span m=''2012900''>graph.</span>
  <span m=''2013330''>So this</span> <span m=''2013550''>looks</span> <span m=''2013810''>sort</span>
  <span m=''2013990''>of</span> <span m=''2014080''>like</span> <span m=''2014290''>a</span>
  <span m=''2014370''>typical</span> <span m=''2014860''>linear</span> <span m=''2015230''>speedup</span>
  <span m=''2015650''>graph.</span> <span m=''2015980''>Sort</span> <span m=''2016120''>of</span>
  <span m=''2016180''>when</span> <span m=''2016300''>you''re</span> <span m=''2016410''>down</span>
  <span m=''2016630''>here</span> <span m=''2016810''>with</span> <span m=''2017010''>few</span>
  <span m=''2017130''>numbers</span> <span m=''2017490''>processors</span> <span m=''2018200''>you</span>
  <span m=''2018310''>get</span> <span m=''2018490''>good</span> <span m=''2018640''>linear</span>
  <span m=''2018930''>speedup</span> <span m=''2019570''>and</span> <span m=''2019890''>eventually</span>
  <span m=''2020280''>you stop</span> <span m=''2020660''>getting</span> <span m=''2020850''>linear</span>
  <span m=''2021150''>speedup.</span> <span m=''2021730''>That''s</span> <span m=''2021805''>sort</span>
  <span m=''2021880''>of</span> <span m=''2022100''>in</span> <span m=''2022500''>broad</span>
  <span m=''2022940''>strokes</span> <span m=''2023260''>what</span> <span m=''2023410''>this</span>
  <span m=''2023550''>graph</span> <span m=''2023910''>looks</span> <span m=''2024140''>like.</span>
  <span m=''2024960''>But</span> <span m=''2025200''>the</span> <span m=''2025300''>axes</span>
  <span m=''2025570''>are</span> <span m=''2025850''>kind</span> <span m=''2026110''>of</span>
  <span m=''2026190''>funny.</span> <span m=''2026510''>The</span> <span m=''2026740''>axes</span>
  <span m=''2027000''>aren''t</span> <span m=''2027210''>the</span> <span m=''2027280''>number</span>
  <span m=''2027530''>of</span> <span m=''2027640''>processors</span> <span m=''2029160''>and</span>
  <span m=''2029520''>the</span> <span m=''2029610''>speedup--</span> <span m=''2030210''>it''s</span>
  <span m=''2030550''>the</span> <span m=''2030660''>number</span> <span m=''2030940''>processors</span>
  <span m=''2031660''>divided</span> <span m=''2032180''>by</span> <span m=''2033490''>the</span>
  <span m=''2033590''>parallelism</span> <span m=''2034070''>of</span> <span m=''2034250''>the</span>
  <span m=''2034550''>program.</span> <span m=''2035440''>And</span> <span m=''2035760''>here</span>
  <span m=''2036020''>is</span> <span m=''2036170''>the</span> <span m=''2036300''>speedup</span>
  <span m=''2036970''>divided</span> <span m=''2037390''>by</span> <span m=''2037540''>the</span>
  <span m=''2037650''>parallelism</span> <span m=''2038280''>of</span> <span m=''2038360''>the</span>
  <span m=''2038450''>program.</span> <span m=''2039400''>And</span> <span m=''2039530''>the</span>
  <span m=''2039620''>reason</span> <span m=''2039950''>we</span> <span m=''2040080''>did</span>
  <span m=''2040290''>that</span> <span m=''2040500''>is</span> <span m=''2040610''>the</span>
  <span m=''2040720''>each</span> <span m=''2040970''>of</span> <span m=''2041060''>these</span>
  <span m=''2041240''>data</span> <span m=''2041490''>points</span> <span m=''2041750''>is</span>
  <span m=''2041830''>a</span> <span m=''2041950''>different</span> <span m=''2042310''>program</span>
  <span m=''2043540''>with</span> <span m=''2043870''>different</span> <span m=''2044390''>work</span>
  <span m=''2044820''>in</span> <span m=''2044940''>span.</span> <span m=''2048640''>If</span>
  <span m=''2048770''>I''m</span> <span m=''2048850''>trying</span> <span m=''2049020''>to</span>
  <span m=''2049080''>run</span> <span m=''2049230''>a</span> <span m=''2049280''>particular</span>
  <span m=''2049670''>problem</span> <span m=''2050100''>on</span> <span m=''2050490''>a</span>
  <span m=''2050540''>bunch</span> <span m=''2050720''>of</span> <span m=''2050790''>different</span>
  <span m=''2051020''>processors</span> <span m=''2051540''>I</span> <span m=''2051610''>can</span>
  <span m=''2051750''>just</span> <span m=''2051920''>draw</span> <span m=''2052180''>that</span>
  <span m=''2052400''>curve</span> <span m=''2052710''>and</span> <span m=''2053160''>see</span>
  <span m=''2053350''>what</span> <span m=''2053510''>happens</span> <span m=''2053900''>as</span>
  <span m=''2054430''>get</span> <span m=''2054610''>more</span> <span m=''2054790''>processors.</span>
  <span m=''2059250''>I''m</span> <span m=''2059370''>not</span> <span m=''2059540''>getting</span>
  <span m=''2059750''>any</span> <span m=''2059930''>advantage</span> <span m=''2060340''>because</span>
  <span m=''2060510''>I''ve</span> <span m=''2060700''>got too</span> <span m=''2060800''>many</span>
  <span m=''2060960''>processors.</span> <span m=''2061600''>I''ve</span> <span m=''2061830''>exceeded</span>
  <span m=''2062120''>the</span> <span m=''2062340''>parallelism</span> <span m=''2062750''>of</span>
  <span m=''2062880''>the</span> <span m=''2062960''>program.</span> <span m=''2063320''>But</span>
  <span m=''2063420''>if</span> <span m=''2063480''>I''m</span> <span m=''2063670''>running,</span>
  <span m=''2064010''>trying</span> <span m=''2064220''>to</span> <span m=''2064280''>compare</span>
  <span m=''2064600''>two</span> <span m=''2064840''>different</span> <span m=''2065240''>programs,</span>
  <span m=''2066390''>how</span> <span m=''2066530''>do</span> <span m=''2066640''>I</span>
  <span m=''2066730''>do</span> <span m=''2066930''>that?</span> </p><p><span m=''2067170''>Well,</span>
  <span m=''2067460''>you</span> <span m=''2067590''>can</span> <span m=''2067710''>do</span>
  <span m=''2067850''>that</span> <span m=''2068070''>by</span> <span m=''2068190''>normalizing</span>
  <span m=''2069040''>by</span> <span m=''2069420''>the</span> <span m=''2069560''>parallelism.</span>
  <span m=''2070760''>So</span> <span m=''2070890''>down</span> <span m=''2071150''>in</span>
  <span m=''2071270''>this</span> <span m=''2071500''>domain</span> <span m=''2073070''>the</span>
  <span m=''2073180''>number of</span> <span m=''2073440''>processors</span> <span
  m=''2074190''>is</span> <span m=''2075210''>small</span> <span m=''2075890''>compared</span>
  <span m=''2076340''>to</span> <span m=''2076410''>the</span> <span m=''2076500''>average</span>
  <span m=''2076840''>parallelism</span> <span m=''2078020''>and</span> <span m=''2078240''>we</span>
  <span m=''2078340''>get</span> <span m=''2078500''>good</span> <span m=''2078800''>linear</span>
  <span m=''2078940''>speedups.</span> <span m=''2079610''>And</span> <span m=''2079760''>up</span>
  <span m=''2079910''>in</span> <span m=''2080080''>this the</span> <span m=''2080380''>domain</span>
  <span m=''2080813''>the</span> <span m=''2081680''>number</span> <span m=''2081825''>of</span>
  <span m=''2081970''>processors</span> <span m=''2082570''>is</span> <span m=''2082690''>large</span>
  <span m=''2083210''>and</span> <span m=''2083350''>it</span> <span m=''2083460''>starts</span>
  <span m=''2083760''>asymptoting</span> <span m=''2084530''>to</span> <span m=''2084660''>the</span>
  <span m=''2084750''>point</span> <span m=''2085070''>where</span> <span m=''2085620''>the</span>
  <span m=''2085750''>speedup</span> <span m=''2086310''>approaches</span> <span m=''2088120''>the</span>
  <span m=''2088490''>parallelism</span> <span m=''2090280''>and</span> <span m=''2090470''>that''s</span>
  <span m=''2090630''>sort</span> <span m=''2090950''>of</span> <span m=''2091010''>what</span>
  <span m=''2091160''>happened.</span> <span m=''2091650''>You</span> <span m=''2091970''>get</span>
  <span m=''2092110''>some</span> <span m=''2092240''>noise</span> <span m=''2092590''>out</span>
  <span m=''2092750''>here</span> <span m=''2092920''>so</span> <span m=''2093040''>one</span>
  <span m=''2093190''>of</span> <span m=''2093270''>the</span> <span m=''2093340''>things</span>
  <span m=''2093510''>down</span> <span m=''2093700''>here,</span> <span m=''2093830''>it''s</span>
  <span m=''2093950''>nice</span> <span m=''2094280''>and</span> <span m=''2094410''>tight.</span>
  <span m=''2096520''>And</span> <span m=''2096740''>that''s</span> <span m=''2097010''>because</span>
  <span m=''2097430''>we''re</span> <span m=''2097580''>in</span> <span m=''2097660''>that</span>
  <span m=''2097860''>domain</span> <span m=''2098310''>where</span> <span m=''2098540''>the</span>
  <span m=''2098660''>communication</span> <span m=''2099290''>costs</span> <span
  m=''2100150''>are</span> <span m=''2100450''>infrequently</span> <span m=''2101120''>paid</span>
  <span m=''2101510''>because</span> <span m=''2101790''>there''s</span> <span m=''2101950''>lots</span>
  <span m=''2102320''>of</span> <span m=''2102420''>work</span> <span m=''2102650''>to</span>
  <span m=''2102780''>do.</span> <span m=''2103200''>You</span> <span m=''2103300''>don''t</span>
  <span m=''2103520''>have</span> <span m=''2103800''>to</span> <span m=''2104260''>communicate</span>
  <span m=''2104790''>very</span> <span m=''2104920''>much.</span> <span m=''2105120''>Up</span>
  <span m=''2105230''>here</span> <span m=''2105490''>there''s</span> <span m=''2105660''>a</span>
  <span m=''2105730''>lot</span> <span m=''2105910''>of</span> <span m=''2105970''>communication</span>
  <span m=''2106530''>that</span> <span m=''2106640''>happens</span> <span m=''2107260''>and</span>
  <span m=''2107510''>so</span> <span m=''2107640''>the</span> <span m=''2107750''>noise</span>
  <span m=''2109040''>is</span> <span m=''2109170''>showing</span> <span m=''2109540''>up</span>
  <span m=''2109750''>more</span> <span m=''2109920''>in</span> <span m=''2110000''>the</span>
  <span m=''2110070''>data.</span> <span m=''2112170''>This</span> <span m=''2112500''>curve</span>
  <span m=''2112800''>here</span> <span m=''2113090''>is</span> <span m=''2113300''>the</span>
  <span m=''2113410''>T sub</span> <span m=''2113590''>1</span> <span m=''2113840''>over</span>
  <span m=''2114020''>P plus</span> <span m=''2114460''>T sub</span> <span m=''2114600''>infinity</span>
  <span m=''2115120''>curve.</span> <span m=''2119200''>The</span> <span m=''2119370''>T
  sub</span> <span m=''2119710''>P</span> <span m=''2120080''>equals</span> <span
  m=''2120350''>T sub</span> <span m=''2120550''>infinity</span> <span m=''2121000''>curve</span>
  <span m=''2121410''>and</span> <span m=''2121530''>that''s</span> <span m=''2121800''>the</span>
  <span m=''2122700''>linear</span> <span m=''2122890''>speedup</span> <span m=''2123140''>curve</span>
  <span m=''2123820''>on</span> <span m=''2123950''>this</span> <span m=''2124080''>graph.</span>
  <span m=''2125430''>So</span> <span m=''2125600''>I</span> <span m=''2125680''>think</span>
  <span m=''2125950''>there''s</span> <span m=''2126220''>an</span> <span m=''2126330''>important</span>
  <span m=''2126730''>lesson</span> <span m=''2127080''>in</span> <span m=''2127160''>this</span>
  <span m=''2127300''>graph</span> <span m=''2128380''>besides</span> <span m=''2128890''>the</span>
  <span m=''2129510''>data</span> <span m=''2129730''>itself,</span> <span m=''2130170''>which</span>
  <span m=''2130370''>is</span> <span m=''2131170''>if</span> <span m=''2131320''>you''re</span>
  <span m=''2131460''>careful</span> <span m=''2131880''>about</span> <span m=''2132120''>choosing</span>
  <span m=''2133750''>the</span> <span m=''2134600''>axes,</span> <span m=''2135450''>you</span>
  <span m=''2135580''>can</span> <span m=''2136400''>take</span> <span m=''2136980''>a</span>
  <span m=''2137190''>whole</span> <span m=''2137420''>bunch</span> <span m=''2137600''>of</span>
  <span m=''2137660''>data</span> <span m=''2137920''>that</span> <span m=''2138060''>you</span>
  <span m=''2138160''>couldn''t</span> <span m=''2138460''>see</span> <span m=''2138630''>how</span>
  <span m=''2138830''>to</span> <span m=''2139300''>plot</span> <span m=''2139780''>it</span>
  <span m=''2139870''>together</span> <span m=''2140280''>and</span> <span m=''2140400''>you</span>
  <span m=''2140460''>can</span> <span m=''2140580''>plot</span> <span m=''2140810''>it</span>
  <span m=''2140900''>together</span> <span m=''2141240''>and</span> <span m=''2141340''>get</span>
  <span m=''2141470''>something</span> <span m=''2141740''>meaningful.</span> <span
  m=''2142690''>So in</span> <span m=''2142770''>my</span> <span m=''2142870''>Ph.D.</span>
  <span m=''2143360''>thesis</span> <span m=''2144000''>I</span> <span m=''2144150''>had</span>
  <span m=''2144430''>hundreds</span> <span m=''2144810''>of</span> <span m=''2144920''>little</span>
  <span m=''2145160''>plots</span> <span m=''2145520''>for each</span> <span m=''2146740''>chess</span>
  <span m=''2147050''>position</span> <span m=''2147480''>and</span> <span m=''2147600''>I</span>
  <span m=''2147660''>didn''t</span> <span m=''2148060''>figure</span> <span m=''2148310''>out</span>
  <span m=''2148420''>how--</span> <span m=''2148710''>it''s</span> <span m=''2148980''>like</span>
  <span m=''2149060''>they</span> <span m=''2149210''>all</span> <span m=''2149295''>look</span>
  <span m=''2149380''>the</span> <span m=''2149490''>same,</span> <span m=''2149850''>right?</span>
  <span m=''2150030''>But</span> <span m=''2150150''>I</span> <span m=''2150260''>didn''t</span>
  <span m=''2150370''>sort</span> <span m=''2150500''>of</span> <span m=''2150570''>figure</span>
  <span m=''2150890''>out</span> <span m=''2151110''>that</span> <span m=''2151740''>if</span>
  <span m=''2151970''>I was</span> <span m=''2152490''>careful</span> <span m=''2152960''>I</span>
  <span m=''2153050''>could</span> <span m=''2153180''>actually</span> <span m=''2153440''>make</span>
  <span m=''2153630''>them</span> <span m=''2153790''>be</span> <span m=''2153940''>the</span>
  <span m=''2154070''>same.</span> <span m=''2155110''>That</span> <span m=''2155270''>happened</span>
  <span m=''2155580''>after</span> <span m=''2156430''>I</span> <span m=''2156530''>published</span>
  <span m=''2156850''>my</span> <span m=''2156960''>thesis.</span> <span m=''2157290''>Oh,</span>
  <span m=''2157570''>we</span> <span m=''2157710''>could</span> <span m=''2157840''>just</span>
  <span m=''2158240''>overlay</span> <span m=''2158710''>them.</span> <span m=''2159030''>Well,</span>
  <span m=''2159350''>what''s</span> <span m=''2159770''>the</span> <span m=''2159850''>normalization</span>
  <span m=''2160510''>that</span> <span m=''2160620''>makes</span> <span m=''2160830''>that</span>
  <span m=''2161040''>work?</span> </p><p><span m=''2163340''>So</span> <span m=''2163480''>there''s</span>
  <span m=''2163640''>a</span> <span m=''2163800''>speedup</span> <span m=''2164260''>paradox</span>
  <span m=''2164810''>that</span> <span m=''2164890''>happened.</span> <span m=''2169220''>Pardon?</span>
  </p><p><span m=''2170025''>AUDIENCE: [OBSCURED]</span> </p><p><span m=''2171480''>BRADLEY
  KUSZMAUL: Yeah,</span> <span m=''2172100''>OK.</span> <span m=''2172940''>There</span>
  <span m=''2173050''>was</span> <span m=''2173160''>a</span> <span m=''2173210''>speedup</span>
  <span m=''2173840''>paradox</span> <span m=''2174390''>that</span> <span m=''2174500''>happened</span>
  <span m=''2175090''>while</span> <span m=''2175260''>we</span> <span m=''2175370''>were</span>
  <span m=''2175460''>developing</span> <span m=''2175900''>star</span> <span m=''2176240''>Socrates.</span>
  <span m=''2176650''>We</span> <span m=''2176760''>were</span> <span m=''2176920''>developing</span>
  <span m=''2177410''>this</span> <span m=''2177570''>for</span> <span m=''2177790''>512</span>
  <span m=''2179080''>processor</span> <span m=''2179610''>connection</span> <span
  m=''2180040''>machine</span> <span m=''2180320''>that</span> <span m=''2180420''>was</span>
  <span m=''2180630''>at</span> <span m=''2181930''>University</span> <span m=''2182410''>of</span>
  <span m=''2182490''>Illinois,</span> <span m=''2183060''>but</span> <span m=''2183190''>we</span>
  <span m=''2183610''>only</span> <span m=''2183920''>had</span> <span m=''2184340''>a</span>
  <span m=''2184520''>smaller</span> <span m=''2185040''>machine</span> <span m=''2185430''>on</span>
  <span m=''2185530''>which</span> <span m=''2185720''>to do</span> <span m=''2185930''>our</span>
  <span m=''2186170''>development.</span> <span m=''2186790''>We</span> <span m=''2186890''>had</span>
  <span m=''2187030''>a</span> <span m=''2187060''>128</span> <span m=''2187850''>processor</span>
  <span m=''2188310''>machine</span> <span m=''2188630''>at</span> <span m=''2188740''>MIT</span>
  <span m=''2189780''>and</span> <span m=''2190100''>most</span> <span m=''2190400''>days</span>
  <span m=''2190690''>I</span> <span m=''2190770''>could</span> <span m=''2190910''>only</span>
  <span m=''2191070''>get</span> <span m=''2191220''>32</span> <span m=''2191580''>processors</span>
  <span m=''2192680''>because</span> <span m=''2193090''>the</span> <span m=''2193680''>machine</span>
  <span m=''2194040''>was</span> <span m=''2194160''>in</span> <span m=''2194250''>heavy</span>
  <span m=''2194460''>demand.</span> <span m=''2195340''>So</span> <span m=''2195480''>we</span>
  <span m=''2195630''>had</span> <span m=''2195890''>this</span> <span m=''2196180''>program</span>
  <span m=''2196750''>and</span> <span m=''2196840''>it</span> <span m=''2196930''>ran</span>
  <span m=''2197660''>on</span> <span m=''2197860''>32</span> <span m=''2198240''>processors</span>
  <span m=''2198900''>in</span> <span m=''2199390''>65</span> <span m=''2200130''>seconds.</span>
  <span m=''2201000''>And</span> <span m=''2201440''>one</span> <span m=''2201590''>of</span>
  <span m=''2201710''>the</span> <span m=''2202370''>developers</span> <span m=''2202970''>said,</span>
  <span m=''2203250''>here''s</span> <span m=''2203380''>a</span> <span m=''2203520''>variation</span>
  <span m=''2204110''>on</span> <span m=''2204260''>the</span> <span m=''2204340''>algorithm,</span>
  <span m=''2204960''>it changes</span> <span m=''2205460''>the</span> <span m=''2205940''>dag.</span>
  <span m=''2206390''>It''s</span> <span m=''2206610''>a</span> <span m=''2207120''>heuristic.</span>
  <span m=''2207720''>It</span> <span m=''2208190''>makes</span> <span m=''2208510''>the</span>
  <span m=''2209250''>program</span> <span m=''2209710''>run</span> <span m=''2209900''>more</span>
  <span m=''2210130''>efficient.</span> <span m=''2210510''>Look,</span> <span m=''2210750''>it</span>
  <span m=''2210840''>runs</span> <span m=''2211020''>in</span> <span m=''2211140''>only</span>
  <span m=''2211340''>40</span> <span m=''2211660''>seconds</span> <span m=''2212070''>on</span>
  <span m=''2212220''>32</span> <span m=''2212590''>processors.</span> <span m=''2213910''>And</span>
  <span m=''2214140''>so</span> <span m=''2214250''>is</span> <span m=''2214520''>that</span>
  <span m=''2214690''>a</span> <span m=''2214740''>good</span> <span m=''2214960''>idea?</span>
  <span m=''2215850''>It sure</span> <span m=''2216470''>seemed</span> <span m=''2216550''>like</span>
  <span m=''2216630''>a</span> <span m=''2216710''>good</span> <span m=''2216880''>idea,</span>
  <span m=''2218020''>but</span> <span m=''2218300''>we</span> <span m=''2218410''>were</span>
  <span m=''2218610''>worried</span> <span m=''2219050''>that</span> <span m=''2219770''>we</span>
  <span m=''2220030''>knew</span> <span m=''2220340''>that</span> <span m=''2220500''>the</span>
  <span m=''2220570''>transformation</span> <span m=''2221260''>increased</span> <span
  m=''2221790''>the</span> <span m=''2221890''>critical</span> <span m=''2222260''>path</span>
  <span m=''2222560''>length</span> <span m=''2222740''>of</span> <span m=''2222840''>the</span>
  <span m=''2222940''>program,</span> <span m=''2223220''>so</span> <span m=''2223500''>we</span>
  <span m=''2223640''>weren''t</span> <span m=''2223890''>sure</span> <span m=''2224160''>it</span>
  <span m=''2224260''>was</span> <span m=''2224380''>a</span> <span m=''2224420''>good</span>
  <span m=''2224590''>idea.</span> </p><p><span m=''2225280''>So we did</span> <span
  m=''2225670''>some</span> <span m=''2226150''>calculation.</span> <span m=''2227660''>We</span>
  <span m=''2227800''>measured</span> <span m=''2229400''>the</span> <span m=''2229540''>work</span>
  <span m=''2230190''>and</span> <span m=''2230500''>the</span> <span m=''2230570''>speedup.</span>
  <span m=''2231550''>And</span> <span m=''2231820''>so</span> <span m=''2231910''>the</span>
  <span m=''2231990''>work</span> <span m=''2232240''>here--</span> <span m=''2232510''>these</span>
  <span m=''2232690''>numbers</span> <span m=''2232950''>have</span> <span m=''2233045''>been</span>
  <span m=''2233140''>cooked</span> <span m=''2233380''>a</span> <span m=''2233420''>little</span>
  <span m=''2233620''>bit</span> <span m=''2233770''>to</span> <span m=''2233850''>make</span>
  <span m=''2234000''>the</span> <span m=''2234080''>math</span> <span m=''2234340''>easy,</span>
  <span m=''2237960''>but</span> <span m=''2238250''>the</span> <span m=''2238860''>numbers--</span>
  <span m=''2239950''>this</span> <span m=''2240500''>really</span> <span m=''2240750''>did</span>
  <span m=''2240880''>happen,</span> <span m=''2242490''>but</span> <span m=''2242590''>not</span>
  <span m=''2242800''>with</span> <span m=''2242920''>these</span> <span m=''2243100''>exact</span>
  <span m=''2243490''>numbers.</span> <span m=''2244980''>So</span> <span m=''2245140''>we</span>
  <span m=''2245260''>had</span> <span m=''2245390''>a</span> <span m=''2245440''>work</span>
  <span m=''2245800''>which</span> <span m=''2245980''>was</span> <span m=''2246120''>2048</span>
  <span m=''2247190''>seconds</span> <span m=''2247640''>and</span> <span m=''2247900''>only</span>
  <span m=''2248500''>1</span> <span m=''2248780''>second</span> <span m=''2249100''>of</span>
  <span m=''2249170''>critical</span> <span m=''2249550''>path.</span> <span m=''2249910''>And</span>
  <span m=''2250040''>over</span> <span m=''2250610''>this</span> <span m=''2250790''>new</span>
  <span m=''2250930''>program</span> <span m=''2251370''>had</span> <span m=''2251570''>only</span>
  <span m=''2251780''>1/2</span> <span m=''2252030''>as</span> <span m=''2252180''>much</span>
  <span m=''2252340''>work</span> <span m=''2252610''>to</span> <span m=''2252710''>do,</span>
  <span m=''2253430''>but</span> <span m=''2253540''>the</span> <span m=''2253630''>critical</span>
  <span m=''2253980''>path</span> <span m=''2254270''>length</span> <span m=''2254475''>was</span>
  <span m=''2254680''>longer.</span> <span m=''2255120''>It was</span> <span m=''2255270''>8</span>
  <span m=''2255550''>seconds</span> <span m=''2255970''>long.</span> <span m=''2260190''>If</span>
  <span m=''2260310''>you</span> <span m=''2260390''>predict</span> <span m=''2261020''>on</span>
  <span m=''2261180''>32</span> <span m=''2261550''>processors</span> <span m=''2262280''>what</span>
  <span m=''2262490''>the</span> <span m=''2262580''>runtime''s</span> <span m=''2263140''>going
  to</span> <span m=''2263380''>be</span> <span m=''2264460''>that</span> <span m=''2264690''>formula</span>
  <span m=''2265120''>says</span> <span m=''2265400''>well,</span> <span m=''2265600''>65</span>
  <span m=''2266180''>seconds.</span> <span m=''2266740''>If</span> <span m=''2266830''>you</span>
  <span m=''2266920''>predict it</span> <span m=''2267520''>on</span> <span m=''2268370''>32</span>
  <span m=''2268700''>processors</span> <span m=''2269270''>this--</span> <span m=''2269640''>well,</span>
  <span m=''2269900''>it''s</span> <span m=''2270050''>40</span> <span m=''2270350''>seconds</span>
  <span m=''2270790''>and</span> <span m=''2271210''>that</span> <span m=''2271390''>looks</span>
  <span m=''2271620''>good,</span> <span m=''2271960''>but</span> <span m=''2272110''>we</span>
  <span m=''2272240''>were</span> <span m=''2272340''>going to</span> <span m=''2273410''>be</span>
  <span m=''2273540''>running</span> <span m=''2273770''>the</span> <span m=''2273850''>tournament</span>
  <span m=''2274360''>on</span> <span m=''2274510''>512</span> <span m=''2275360''>processors</span>
  <span m=''2276300''>where</span> <span m=''2277130''>this</span> <span m=''2277680''>term</span>
  <span m=''2277990''>would</span> <span m=''2278280''>start</span> <span m=''2278650''>being</span>
  <span m=''2278940''>less</span> <span m=''2279180''>important</span> <span m=''2280110''>than</span>
  <span m=''2280370''>this</span> <span m=''2280580''>term.</span> <span m=''2282030''>So</span>
  <span m=''2282190''>this</span> <span m=''2282770''>really</span> <span m=''2283050''>did</span>
  <span m=''2283200''>happen</span> <span m=''2283540''>and we</span> <span m=''2283730''>actually</span>
  <span m=''2284000''>went</span> <span m=''2284210''>back</span> <span m=''2284430''>and</span>
  <span m=''2284570''>validated</span> <span m=''2285200''>that</span> <span m=''2285340''>these</span>
  <span m=''2285530''>numbers</span> <span m=''2285850''>were</span> <span m=''2285980''>right</span>
  <span m=''2286650''>after</span> <span m=''2286900''>we</span> <span m=''2286970''>did</span>
  <span m=''2287120''>the</span> <span m=''2287200''>calculation</span> <span m=''2288000''>and
  it</span> <span m=''2288650''>allowed</span> <span m=''2289150''>us</span> <span
  m=''2289310''>to</span> <span m=''2289440''>do</span> <span m=''2289560''>the</span>
  <span m=''2289650''>engineering</span> <span m=''2290780''>to</span> <span m=''2290910''>make</span>
  <span m=''2291120''>the</span> <span m=''2291210''>right</span> <span m=''2291440''>decision</span>
  <span m=''2291910''>and</span> <span m=''2292060''>not</span> <span m=''2292280''>be</span>
  <span m=''2292400''>misled</span> <span m=''2293530''>by</span> <span m=''2293700''>something</span>
  <span m=''2294160''>that</span> <span m=''2294310''>looked</span> <span m=''2294580''>good</span>
  <span m=''2295700''>in</span> <span m=''2296230''>the</span> <span m=''2296550''>test</span>
  <span m=''2296880''>environment.</span> <span m=''2299120''>We</span> <span m=''2299260''>were</span>
  <span m=''2299350''>able</span> <span m=''2299480''>to</span> <span m=''2299560''>predict</span>
  <span m=''2299980''>what</span> <span m=''2300090''>was</span> <span m=''2300200''>going</span>
  <span m=''2300330''>to</span> <span m=''2300390''>happen</span> <span m=''2300670''>on</span>
  <span m=''2300770''>the</span> <span m=''2300870''>big</span> <span m=''2301090''>machine</span>
  <span m=''2301580''>without</span> <span m=''2301950''>actually</span> <span m=''2302250''>having</span>
  <span m=''2302550''>access</span> <span m=''2302910''>to</span> <span m=''2303030''>the</span>
  <span m=''2303120''>big</span> <span m=''2303310''>machine</span> <span m=''2303620''>and</span>
  <span m=''2303710''>that</span> <span m=''2303850''>was</span> <span m=''2303990''>very</span>
  <span m=''2304210''>important.</span> </p><p><span m=''2307660''>Let</span> <span
  m=''2307720''>me</span> <span m=''2307960''>do some</span> <span m=''2308270''>algorithms.</span>
  <span m=''2310210''>You</span> <span m=''2310380''>guys</span> <span m=''2310590''>probably</span>
  <span m=''2310880''>have done</span> <span m=''2311100''>some</span> <span m=''2311230''>matrix</span>
  <span m=''2311490''>multipliers</span> <span m=''2312140''>over</span> <span m=''2312300''>the</span>
  <span m=''2312380''>past</span> <span m=''2312630''>3</span> <span m=''2312810''>weeks,</span>
  <span m=''2313060''>right?</span> <span m=''2314000''>That''s probably</span> <span
  m=''2314280''>the</span> <span m=''2314350''>only</span> <span m=''2314540''>thing</span>
  <span m=''2314680''>you''ve</span> <span m=''2314770''>been</span> <span m=''2314950''>able</span>
  <span m=''2315130''>to</span> <span m=''2315645''>do</span> <span m=''2316160''>would
  be my</span> <span m=''2316350''>guess.</span> <span m=''2318210''>So</span> <span
  m=''2318480''>matrix</span> <span m=''2318850''>multiplication</span> <span m=''2319640''>is</span>
  <span m=''2319780''>this</span> <span m=''2319920''>operation.</span> <span m=''2320680''>I
  won''t</span> <span m=''2320850''>talk</span> <span m=''2321070''>about</span> <span
  m=''2321320''>it,</span> <span m=''2321420''>but</span> <span m=''2321580''>you</span>
  <span m=''2321670''>know</span> <span m=''2321780''>what</span> <span m=''2321920''>it</span>
  <span m=''2322040''>is.</span> <span m=''2322780''>In</span> <span m=''2322920''>Cilk</span>
  <span m=''2323290''>instead</span> <span m=''2323590''>of</span> <span m=''2323690''>doing</span>
  <span m=''2324340''>the</span> <span m=''2324520''>standard</span> <span m=''2325200''>triply</span>
  <span m=''2326080''>nested</span> <span m=''2326620''>loops</span> <span m=''2327240''>you</span>
  <span m=''2327550''>do</span> <span m=''2327810''>divide</span> <span m=''2328190''>and</span>
  <span m=''2328310''>conquer.</span> <span m=''2329740''>We</span> <span m=''2329970''>don''t</span>
  <span m=''2330170''>parallelize</span> <span m=''2330860''>loops</span> <span m=''2331220''>we</span>
  <span m=''2331480''>parallelize</span> <span m=''2332010''>function</span> <span
  m=''2332430''>calls,</span> <span m=''2332770''>so you</span> <span m=''2332880''>want</span>
  <span m=''2333140''>to</span> <span m=''2333690''>express</span> <span m=''2334710''>a</span>
  <span m=''2334920''>loops</span> <span m=''2335170''>as</span> <span m=''2335460''>recursion.</span>
  <span m=''2336830''>So</span> <span m=''2336970''>to</span> <span m=''2337260''>multipliy</span>
  <span m=''2337740''>two</span> <span m=''2338380''>big</span> <span m=''2338650''>matrices</span>
  <span m=''2339240''>you</span> <span m=''2339420''>do</span> <span m=''2340000''>a</span>
  <span m=''2340090''>whole</span> <span m=''2340260''>bunch</span> <span m=''2340460''>of</span>
  <span m=''2340520''>little</span> <span m=''2340730''>matrix</span> <span m=''2341070''>multiplications</span>
  <span m=''2341790''>of the</span> <span m=''2341990''>sub-blocks</span> <span m=''2342680''>and</span>
  <span m=''2342840''>then</span> <span m=''2342930''>you</span> <span m=''2343050''>express</span>
  <span m=''2343520''>those</span> <span m=''2343820''>little</span> <span m=''2344060''>matrix</span>
  <span m=''2344450''>multiplications</span> <span m=''2345660''>themselves</span>
  <span m=''2346230''>and go</span> <span m=''2346360''>off and</span> <span m=''2346660''>recursively</span>
  <span m=''2347270''>do</span> <span m=''2347870''>smaller</span> <span m=''2348320''>matrix</span>
  <span m=''2348690''>multiplications.</span> <span m=''2350490''>So</span> <span
  m=''2350690''>this</span> <span m=''2350930''>requires</span> <span m=''2351430''>8</span>
  <span m=''2351700''>multiplications</span> <span m=''2352520''>of</span> <span m=''2352630''>matrices</span>
  <span m=''2352980''>these</span> <span m=''2353490''>of</span> <span m=''2353770''>1/2</span>
  <span m=''2354150''>the</span> <span m=''2354450''>number</span> <span m=''2354810''>of</span>
  <span m=''2354956''>rows</span> <span m=''2355103''>and</span> <span m=''2355250''>1/2</span>
  <span m=''2355470''>the</span> <span m=''2355530''>number</span> <span m=''2355780''>columns</span>
  <span m=''2356590''>an</span> <span m=''2357150''>one</span> <span m=''2357490''>edition</span>
  <span m=''2357990''>at</span> <span m=''2358100''>the</span> <span m=''2358260''>end</span>
  <span m=''2358440''>where</span> <span m=''2358560''>you</span> <span m=''2358670''>add</span>
  <span m=''2358930''>these</span> <span m=''2359140''>two</span> <span m=''2359280''>matrices</span>
  <span m=''2359840''>together.</span> <span m=''2360430''>That''s</span> <span m=''2360720''>the</span>
  <span m=''2360820''>algorithm</span> <span m=''2362020''>that</span> <span m=''2362120''>we</span>
  <span m=''2362250''>do,</span> <span m=''2362550''>it''s</span> <span m=''2362690''>the</span>
  <span m=''2362780''>same</span> <span m=''2363320''>total</span> <span m=''2363670''>work</span>
  <span m=''2365600''>as</span> <span m=''2365990''>the</span> <span m=''2366050''>standard</span>
  <span m=''2366460''>one,</span> <span m=''2367060''>but</span> <span m=''2367260''>it''s</span>
  <span m=''2367490''>just</span> <span m=''2367730''>expressed</span> <span m=''2368560''>recursively.</span>
  <span m=''2368700''>So</span> <span m=''2369030''>a</span> <span m=''2369250''>matrix</span>
  <span m=''2369710''>multiply</span> <span m=''2370460''>is</span> <span m=''2371500''>you</span>
  <span m=''2371650''>do</span> <span m=''2371810''>these</span> <span m=''2371960''>8</span>
  <span m=''2372200''>multiplies.</span> <span m=''2372850''>I</span> <span m=''2372900''>had</span>
  <span m=''2373050''>to</span> <span m=''2373140''>create</span> <span m=''2373410''>a</span>
  <span m=''2373460''>temporary</span> <span m=''2373970''>variable,</span> <span
  m=''2374510''>so</span> <span m=''2375040''>the</span> <span m=''2375160''>first</span>
  <span m=''2375470''>four</span> <span m=''2375660''>multiplies</span> <span m=''2377350''>the</span>
  <span m=''2377660''>A''s</span> <span m=''2378330''>and</span> <span m=''2378430''>B''s</span>
  <span m=''2378540''>into</span> <span m=''2378630''>C.</span> <span m=''2379800''>The</span>
  <span m=''2379910''>second</span> <span m=''2380280''>four</span> <span m=''2380540''>multiply</span>
  <span m=''2381790''>the</span> <span m=''2382370''>A''s and</span> <span m=''2382560''>B''s</span>
  <span m=''2382850''>into</span> <span m=''2383060''>T</span> <span m=''2383540''>and</span>
  <span m=''2383670''>then</span> <span m=''2383780''>I</span> <span m=''2383880''>have</span>
  <span m=''2384170''>to</span> <span m=''2384260''>add</span> <span m=''2384820''>T</span>
  <span m=''2385030''>into</span> <span m=''2385260''>C.</span> <span m=''2386180''>So</span>
  <span m=''2386330''>I</span> <span m=''2386400''>do</span> <span m=''2386570''>all</span>
  <span m=''2386780''>those</span> <span m=''2387090''>spawns,</span> <span m=''2387560''>do</span>
  <span m=''2387710''>all</span> <span m=''2387870''>the</span> <span m=''2387970''>multiplies.</span>
  <span m=''2388880''>I</span> <span m=''2388990''>do</span> <span m=''2389140''>a</span>
  <span m=''2389210''>sync</span> <span m=''2389700''>because</span> <span m=''2389940''>I</span>
  <span m=''2390000''>better</span> <span m=''2390260''>not</span> <span m=''2390530''>start</span>
  <span m=''2390830''>using</span> <span m=''2391150''>the</span> <span m=''2391230''>results</span>
  <span m=''2391373''>on</span> <span m=''2391516''>the</span> <span m=''2391660''>multiplies</span>
  <span m=''2392260''>and</span> <span m=''2392350''>adding</span> <span m=''2392640''>them</span>
  <span m=''2392730''>until the</span> <span m=''2393120''>multiplies</span> <span
  m=''2393570''>are</span> <span m=''2393650''>done.</span> </p><p><span m=''2395030''>AUDIENCE:
  Which</span> <span m=''2395340''>four</span> <span m=''2395850''>do</span> <span
  m=''2396020''>you</span> <span m=''2396190''>add?</span> </p><p><span m=''2396360''>BRADLEY
  KUSZMAUL: What?</span> <span m=''2397960''>There''s</span> <span m=''2398070''>parallelism</span>
  <span m=''2398670''>in add.</span> <span m=''2401620''>Matrix</span> <span m=''2401950''>addition.</span>
  </p><p><span m=''2402930''>AUDIENCE: Yeah,</span> <span m=''2403420''>but it</span>
  <span m=''2403910''>doesn''t</span> <span m=''2404240''>add</span> <span m=''2404743''>spawn</span>
  <span m=''2405246''>extent</span> </p><p><span m=''2405750''>BRADLEY KUSZMAUL: Well,</span>
  <span m=''2406200''>we</span> <span m=''2406390''>spawn</span> <span m=''2406880''>off</span>
  <span m=''2407105''>add.</span> <span m=''2408330''>I don''t</span> <span m=''2408360''>understand--</span>
  </p><p><span m=''2410610''>[INTERPOSING VOICES]</span> </p><p><span m=''2412770''>BRADLEY
  KUSZMAUL: So</span> <span m=''2413250''>you</span> <span m=''2413450''>have</span>
  <span m=''2413950''>to spawn</span> <span m=''2414520''>Cilk functions</span> <span
  m=''2415250''>even</span> <span m=''2415550''>if</span> <span m=''2415710''>you''re</span>
  <span m=''2416160''>only</span> <span m=''2416610''>executing</span> <span m=''2416810''>one</span>
  <span m=''2417310''>of</span> <span m=''2417620''>them</span> <span m=''2417687''>at</span>
  <span m=''2417755''>a</span> <span m=''2417822''>time.</span> <span m=''2420760''>Cilk</span>
  <span m=''2421040''>functions</span> <span m=''2421380''>are</span> <span m=''2421560''>spawned,</span>
  <span m=''2421970''>C</span> <span m=''2422110''>functions</span> <span m=''2422500''>are</span>
  <span m=''2422570''>called.</span> <span m=''2424290''>It''s</span> <span m=''2424490''>a</span>
  <span m=''2424970''>decision</span> <span m=''2425540''>that''s</span> <span m=''2425800''>built</span>
  <span m=''2426120''>into the</span> <span m=''2426340''>language.</span> <span m=''2426810''>It''s</span>
  <span m=''2426950''>not</span> <span m=''2427160''>really</span> <span m=''2427340''>a</span>
  <span m=''2427400''>fundamental</span> <span m=''2427910''>decision.</span> <span
  m=''2428760''>It''s</span> <span m=''2428930''>just</span> <span m=''2429480''>that''s</span>
  <span m=''2429750''>the</span> <span m=''2429830''>way</span> <span m=''2429970''>we</span>
  <span m=''2430100''>did</span> <span m=''2430260''>it.</span> <span m=''2430748''>AUDIENCE:
  Why''d</span> <span m=''2431237''>you choose</span> <span m=''2431726''>to</span>
  <span m=''2431888''>have</span> <span m=''2432051''>the</span> <span m=''2432215''>key</span>
  <span m=''2432377''>word</span> <span m=''2432540''>then?</span> <span m=''2432703''>That''s</span>
  <span m=''2432865''>just</span> <span m=''2433028''>documentation</span> <span m=''2433192''>from
  the</span> <span m=''2433681''>caller side?</span> </p><p><span m=''2434170''>BRADLEY
  KUSZMAUL: Yeah,</span> <span m=''2434630''>we</span> <span m=''2434980''>found</span>
  <span m=''2436630''>we</span> <span m=''2436780''>were</span> <span m=''2436920''>less</span>
  <span m=''2437160''>likely</span> <span m=''2437490''>to</span> <span m=''2437600''>make</span>
  <span m=''2437830''>a</span> <span m=''2437890''>mistake</span> <span m=''2438560''>if</span>
  <span m=''2439600''>we</span> <span m=''2439890''>sort</span> <span m=''2440140''>of</span>
  <span m=''2440210''>built</span> <span m=''2440560''>it into</span> <span m=''2440710''>the</span>
  <span m=''2440800''>type</span> <span m=''2441060''>system</span> <span m=''2441420''>in</span>
  <span m=''2441530''>this</span> <span m=''2441720''>way.</span> <span m=''2442370''>But</span>
  <span m=''2442520''>I''m</span> <span m=''2442620''>not</span> <span m=''2442840''>convinced</span>
  <span m=''2443240''>that</span> <span m=''2443340''>this</span> <span m=''2443510''>is</span>
  <span m=''2443660''>the</span> <span m=''2443750''>best</span> <span m=''2444140''>way</span>
  <span m=''2444270''>to</span> <span m=''2444390''>do</span> <span m=''2445110''>this</span>
  <span m=''2445800''>type</span> <span m=''2447690''>system.</span> </p><p><span
  m=''2447990''>AUDIENCE:</span> <span m=''2448222''>Can</span> <span m=''2448455''>the</span>
  <span m=''2448687''>C</span> <span m=''2448803''>functions</span> <span m=''2448832''>spawn</span>
  <span m=''2448861''>a</span> <span m=''2448890''>Cilk function.</span> </p><p><span
  m=''2448920''>BRADLEY KUSZMAUL: No.</span> <span m=''2449240''>You can</span> <span
  m=''2449660''>only</span> <span m=''2450020''>call</span> <span m=''2450940''>spawn,</span>
  <span m=''2451310''>spawn,</span> <span m=''2451630''>spawn,</span> <span m=''2451920''>spawn</span>
  <span m=''2452160''>then</span> <span m=''2452270''>you</span> <span m=''2452330''>can</span>
  <span m=''2452470''>call</span> <span m=''2452740''>C</span> <span m=''2452900''>functions</span>
  <span m=''2453310''>at</span> <span m=''2453440''>the</span> <span m=''2453930''>leaves.</span>
  <span m=''2455390''>It</span> <span m=''2455480''>turns</span> <span m=''2455740''>out</span>
  <span m=''2455910''>you</span> <span m=''2455980''>can</span> <span m=''2456130''>actually</span>
  <span m=''2456810''>spawn Cilk</span> <span m=''2457400''>functions</span> <span
  m=''2457830''>if</span> <span m=''2457990''>you''re</span> <span m=''2458160''>a</span>
  <span m=''2458200''>little</span> <span m=''2458380''>clever</span> <span m=''2458770''>about--</span>
  <span m=''2459060''>there''s a</span> <span m=''2459300''>mechanism</span> <span
  m=''2459870''>for</span> <span m=''2460680''>a</span> <span m=''2461040''>Cilk</span>
  <span m=''2461310''>system</span> <span m=''2461640''>running</span> <span m=''2461880''>in</span>
  <span m=''2461950''>the</span> <span m=''2462030''>background</span> <span m=''2462570''>and</span>
  <span m=''2462660''>if</span> <span m=''2462770''>you''re</span> <span m=''2462850''>running</span>
  <span m=''2463170''>C</span> <span m=''2464240''>you</span> <span m=''2464410''>can</span>
  <span m=''2464980''>say</span> <span m=''2465170''>OK,</span> <span m=''2465450''>do</span>
  <span m=''2465630''>this</span> <span m=''2465800''>Cilk</span> <span m=''2466390''>function</span>
  <span m=''2466820''>in</span> <span m=''2466940''>parallel.</span> <span m=''2467570''>So</span>
  <span m=''2467660''>we</span> <span m=''2467770''>have</span> <span m=''2468010''>that,</span>
  <span m=''2468370''>but</span> <span m=''2468540''>that''s</span> <span m=''2468710''>not</span>
  <span m=''2470050''>didactic.</span> </p><p><span m=''2473805''>AUDIENCE: Sorry,</span>
  <span m=''2474290''>I</span> <span m=''2474775''>have a</span> <span m=''2475260''>question</span>
  <span m=''2475745''>about the</span> <span m=''2476230''>sync</span> <span m=''2477200''>spawning.</span>
  <span m=''2478655''>Is</span> <span m=''2479140''>the</span> <span m=''2479666''>sync</span>
  <span m=''2480192''>actually</span> <span m=''2480455''>doing</span> <span m=''2480718''>a</span>
  <span m=''2481244''>whole</span> <span m=''2481507''>wave</span> <span m=''2481770''>or
  --</span> <span m=''2482180''>like,</span> <span m=''2482282''>in</span> <span m=''2482385''>the</span>
  <span m=''2482487''>case</span> <span m=''2482590''>of--</span> <span m=''2482810''>maybe</span>
  <span m=''2483326''>not</span> <span m=''2483498''>in</span> <span m=''2483670''>the</span>
  <span m=''2483843''>case</span> <span m=''2484877''>of</span> <span m=''2485394''>the</span>
  <span m=''2485911''> add </span> <span m=''2486428''>here,</span> <span m=''2486945''>but</span>
  <span m=''2487462''>in plenty</span> <span m=''2487979''>of other</span> <span m=''2488496''>practical</span>
  <span m=''2489013''>functions</span> <span m=''2489530''>you</span> <span m=''2490940''>get</span>
  <span m=''2491220''>inside</span> <span m=''2491687''>the</span> <span m=''2492155''>spawn</span>
  <span m=''2492622''>function</span> <span m=''2493090''>looking</span> <span m=''2493470''>at</span>
  <span m=''2493960''>the</span> <span m=''2494451''>tendencies</span> <span m=''2494942''>of
  the</span> <span m=''2495433''>parameters,</span> <span m=''2495924''>right?</span>
  <span m=''2496415''>Based</span> <span m=''2496906''>on</span> <span m=''2497397''>how</span>
  <span m=''2497888''>those</span> <span m=''2498379''>were</span> <span m=''2498870''>built</span>
  <span m=''2499003''>from</span> <span m=''2499136''>previous</span> <span m=''2499270''>spawned</span>
  <span m=''2499820''>funcitons.</span> <span m=''2500960''>You</span> <span m=''2501116''>can</span>
  <span m=''2501273''>actually</span> <span m=''2501430''>just</span> <span m=''2502000''>start</span>
  <span m=''2502570''>processing</span> <span m=''2503140''>so</span> <span m=''2503300''>long</span>
  <span m=''2503850''>as</span> <span m=''2504336''>it''s</span> <span m=''2504822''>guaranteed</span>
  <span m=''2505308''>that the</span> <span m=''2505794''>results</span> <span m=''2506280''>are
  available</span> <span m=''2506860''>before</span> <span m=''2506933''>you</span>
  <span m=''2507006''>actually read them.</span> </p><p><span m=''2507080''>BRADLEY
  KUSZMAUL: So</span> <span m=''2507250''>there''s</span> <span m=''2507790''>this
  other</span> <span m=''2507990''>style</span> <span m=''2508500''>of</span> <span
  m=''2508580''>expressing</span> <span m=''2509080''>parallelism</span> <span m=''2509500''>which</span>
  <span m=''2509710''>you</span> <span m=''2509850''>see in</span> <span m=''2510120''>some</span>
  <span m=''2510310''>of</span> <span m=''2510380''>the</span> <span m=''2510450''>data</span>
  <span m=''2510650''>flow</span> <span m=''2510890''>languages</span> <span m=''2511500''>where</span>
  <span m=''2511640''>you</span> <span m=''2511730''>say</span> <span m=''2511900''>well,</span>
  <span m=''2512180''>I''ve</span> <span m=''2512790''>computed</span> <span m=''2513950''>this</span>
  <span m=''2514150''>first</span> <span m=''2514480''>multiply,</span> <span m=''2515010''>why</span>
  <span m=''2515250''>can''t</span> <span m=''2515420''>I</span> <span m=''2515500''>get</span>
  <span m=''2515680''>started</span> <span m=''2516010''>on</span> <span m=''2516160''>the</span>
  <span m=''2516580''>corresponding</span> <span m=''2517160''>part</span> <span m=''2517830''>of</span>
  <span m=''2517970''>the</span> <span m=''2518070''>addition.</span> <span m=''2520030''>And</span>
  <span m=''2520180''>it</span> <span m=''2520280''>turns</span> <span m=''2520630''>out</span>
  <span m=''2521250''>that</span> <span m=''2521520''>in</span> <span m=''2521660''>those</span>
  <span m=''2521900''>models</span> <span m=''2522390''>there''s</span> <span m=''2522670''>no</span>
  <span m=''2522920''>performance</span> <span m=''2523440''>guarantees.</span> <span
  m=''2527110''>The</span> <span m=''2527210''>real</span> <span m=''2527420''>issue
  is</span> <span m=''2527660''>you</span> <span m=''2527740''>run</span> <span m=''2527890''>out</span>
  <span m=''2527990''>of</span> <span m=''2528100''>memory.</span> <span m=''2532220''>It''s</span>
  <span m=''2532670''>a</span> <span m=''2532790''>long</span> <span m=''2533120''>topic,</span>
  <span m=''2533430''>let''s</span> <span m=''2533570''>not</span> <span m=''2533750''>go</span>
  <span m=''2533860''>into</span> <span m=''2534080''>it,</span> <span m=''2534190''>but</span>
  <span m=''2534290''>there''s</span> <span m=''2534710''>a</span> <span m=''2535060''>serious</span>
  <span m=''2535580''>technical</span> <span m=''2535930''>issue</span> <span m=''2536050''>with</span>
  <span m=''2536490''>those</span> <span m=''2536680''>programming</span> <span m=''2537140''>models.</span>
  <span m=''2540610''>We</span> <span m=''2540770''>have</span> <span m=''2540890''>very</span>
  <span m=''2541110''>tight</span> <span m=''2541360''>memory</span> <span m=''2541660''>bounds</span>
  <span m=''2541960''>as</span> <span m=''2542100''>well,</span> <span m=''2542253''>so</span>
  <span m=''2542406''>we</span> <span m=''2542560''>simultaneously</span> <span m=''2543610''>get</span>
  <span m=''2543670''>these</span> <span m=''2543730''>good</span> <span m=''2543790''>scheduling</span>
  <span m=''2544200''>bounds</span> <span m=''2544930''>and</span> <span m=''2545150''>good</span>
  <span m=''2545310''>memory</span> <span m=''2545600''>bounds</span> <span m=''2545960''>and</span>
  <span m=''2546130''>if</span> <span m=''2546240''>you</span> <span m=''2546800''>are</span>
  <span m=''2547140''>doing that</span> <span m=''2547480''>you</span> <span m=''2547620''>could</span>
  <span m=''2547760''>have</span> <span m=''2547900''>sort</span> <span m=''2548060''>of</span>
  <span m=''2548150''>a</span> <span m=''2548240''>really</span> <span m=''2548640''>large</span>
  <span m=''2549000''>number</span> <span m=''2549350''>of</span> <span m=''2549460''>temporaries</span>
  <span m=''2550010''>required</span> <span m=''2550630''>and</span> <span m=''2550880''>run
  out</span> <span m=''2550940''>of</span> <span m=''2551090''>memory.</span> <span
  m=''2551300''>The</span> <span m=''2552250''>data</span> <span m=''2552580''>flow</span>
  <span m=''2552740''>machine</span> <span m=''2553740''>used</span> <span m=''2553940''>to</span>
  <span m=''2554020''>have</span> <span m=''2554200''>this</span> <span m=''2554360''>number--</span>
  <span m=''2554680''>there</span> <span m=''2554820''>was</span> <span m=''2554960''>a</span>
  <span m=''2555030''>student,</span> <span m=''2555490''>Ken</span> <span m=''2555730''>Traub,</span>
  <span m=''2556630''>who</span> <span m=''2556735''>was</span> <span m=''2556840''>working</span>
  <span m=''2557090''>on</span> <span m=''2557240''>Monsoon</span> <span m=''2557820''>when</span>
  <span m=''2558190''>Greg Papadapolous</span> <span m=''2558550''>was</span> <span
  m=''2559010''>here</span> <span m=''2559540''>and</span> <span m=''2561340''>he</span>
  <span m=''2561450''>came</span> <span m=''2561650''>up</span> <span m=''2561760''>with</span>
  <span m=''2561870''>this</span> <span m=''2562050''>term</span> <span m=''2562640''>which</span>
  <span m=''2562780''>we</span> <span m=''2562890''>called</span> <span m=''2563090''>Traub''s</span>
  <span m=''2563550''>constant,</span> <span m=''2564070''>which</span> <span m=''2564230''>was</span>
  <span m=''2564410''>how</span> <span m=''2564660''>long</span> <span m=''2564930''>the</span>
  <span m=''2565030''>machine</span> <span m=''2565390''>could</span> <span m=''2565520''>be</span>
  <span m=''2565940''>guaranteed</span> <span m=''2566360''>to</span> <span m=''2566420''>run</span>
  <span m=''2566650''>before</span> <span m=''2566790''>it</span> <span m=''2566930''>crashed
  from</span> <span m=''2567570''>being</span> <span m=''2567740''>out</span> <span
  m=''2567870''>of</span> <span m=''2567960''>memory.</span> <span m=''2568870''>And</span>
  <span m=''2568990''>that</span> <span m=''2569170''>was--</span> <span m=''2569740''>well,</span>
  <span m=''2569880''>he</span> <span m=''2569980''>took</span> <span m=''2570160''>the</span>
  <span m=''2570280''>rate at</span> <span m=''2570640''>which</span> <span m=''2570760''>it</span>
  <span m=''2571060''>Kahn''s</span> <span m=''2571910''>divided</span> <span m=''2572380''>by</span>
  <span m=''2572920''>the</span> <span m=''2573280''>amount</span> <span m=''2573480''>of</span>
  <span m=''2573550''>memory</span> <span m=''2574020''>and</span> <span m=''2574494''>that</span>
  <span m=''2574968''>was</span> <span m=''2575442''>it.</span> <span m=''2576960''>And</span>
  <span m=''2577370''>many</span> <span m=''2577600''>data</span> <span m=''2577850''>flow</span>
  <span m=''2578010''>programs</span> <span m=''2578660''>had</span> <span m=''2578910''>that</span>
  <span m=''2579100''>property</span> <span m=''2579790''>that</span> <span m=''2579920''>Monsoon</span>
  <span m=''2580390''>could</span> <span m=''2580570''>run</span> <span m=''2580770''>for</span>
  <span m=''2580890''>40</span> <span m=''2581280''>seconds</span> <span m=''2581710''>and</span>
  <span m=''2581860''>then</span> <span m=''2582170''>after</span> <span m=''2582460''>that</span>
  <span m=''2583660''>you</span> <span m=''2583780''>never</span> <span m=''2583990''>knew.</span>
  <span m=''2584150''>It</span> <span m=''2584240''>might</span> <span m=''2584430''>start</span>
  <span m=''2584640''>crashing</span> <span m=''2584850''>at</span> <span m=''2585060''>any</span>
  <span m=''2585240''>moment,</span> <span m=''2585730''>so</span> <span m=''2585880''>everybody</span>
  <span m=''2586230''>wrote</span> <span m=''2586420''>short</span> <span m=''2586710''>data</span>
  <span m=''2586920''>flow</span> <span m=''2587100''>programs.</span> </p><p><span
  m=''2591770''>So</span> <span m=''2591940''>one</span> <span m=''2592090''>of</span>
  <span m=''2592150''>the</span> <span m=''2592220''>things</span> <span m=''2592430''>you</span>
  <span m=''2592530''>actually</span> <span m=''2592850''>do</span> <span m=''2593000''>when</span>
  <span m=''2593110''>you''re</span> <span m=''2593280''>implementing,</span> <span
  m=''2593800''>when</span> <span m=''2593940''>you''re</span> <span m=''2594030''>trying</span>
  <span m=''2594200''>to</span> <span m=''2594260''>engineer</span> <span m=''2594560''>this</span>
  <span m=''2594720''>to</span> <span m=''2594800''>go</span> <span m=''2594900''>fast,</span>
  <span m=''2595280''>is</span> <span m=''2596690''>you</span> <span m=''2596800''>course
  in</span> <span m=''2597290''>the</span> <span m=''2597370''>base</span> <span m=''2597680''>case,</span>
  <span m=''2598010''>which</span> <span m=''2598210''>I</span> <span m=''2598260''>didn''t</span>
  <span m=''2598540''>describe</span> <span m=''2599050''>up</span> <span m=''2599180''>there.</span>
  <span m=''2599350''>You</span> <span m=''2599470''>don''t</span> <span m=''2599690''>just</span>
  <span m=''2599950''>do</span> <span m=''2600090''>a</span> <span m=''2600170''>1</span>
  <span m=''2600500''>by</span> <span m=''2600660''>1</span> <span m=''2600960''>matrix</span>
  <span m=''2601400''>multiplied</span> <span m=''2601870''>down</span> <span m=''2602130''>there</span>
  <span m=''2602310''>at the</span> <span m=''2602420''>leaves</span> <span m=''2602720''>of
  this</span> <span m=''2602990''>recursion.</span> <span m=''2604970''>Because</span>
  <span m=''2605240''>then</span> <span m=''2605380''>you''re</span> <span m=''2605490''>not</span>
  <span m=''2605670''>using</span> <span m=''2605890''>the</span> <span m=''2605960''>processor</span>
  <span m=''2606460''>pipeline</span> <span m=''2606900''>efficiently.</span> <span
  m=''2608580''>You</span> <span m=''2608740''>call</span> <span m=''2608970''>the</span>
  <span m=''2609110''>Intel</span> <span m=''2609410''>Math</span> <span m=''2609760''>Kernel</span>
  <span m=''2609960''>Library</span> <span m=''2610410''>or</span> <span m=''2610480''>something</span>
  <span m=''2611090''>on</span> <span m=''2611320''>an</span> <span m=''2611720''>8</span>
  <span m=''2611980''>by 8</span> <span m=''2612310''>matrix</span> <span m=''2612790''>so
  that</span> <span m=''2612940''>it</span> <span m=''2613030''>really</span> <span
  m=''2613200''>gets</span> <span m=''2613400''>the</span> <span m=''2613490''>pipeline</span>
  <span m=''2614190''>a</span> <span m=''2614290''>chance</span> <span m=''2614670''>to</span>
  <span m=''2615010''>chug</span> <span m=''2615430''>away.</span> </p><p><span m=''2618740''>So</span>
  <span m=''2618930''>analysis.</span> <span m=''2619250''>This</span> <span m=''2620220''>matrix</span>
  <span m=''2620550''>addition</span> <span m=''2620960''>operation--</span> <span
  m=''2621560''>well,</span> <span m=''2622500''>what''s</span> <span m=''2622750''>the</span>
  <span m=''2622850''>work</span> <span m=''2623560''>for</span> <span m=''2624010''>matrix</span>
  <span m=''2624420''>addition?</span> <span m=''2625390''>Well</span> <span m=''2625650''>the</span>
  <span m=''2625760''>work</span> <span m=''2626030''>to</span> <span m=''2626140''>do</span>
  <span m=''2626540''>a</span> <span m=''2626650''>matrix</span> <span m=''2627690''>operation</span>
  <span m=''2628260''>on</span> <span m=''2628940''>n</span> <span m=''2629330''>rows</span>
  <span m=''2629840''>is</span> <span m=''2630680''>well,</span> <span m=''2630820''>you</span>
  <span m=''2630920''>have</span> <span m=''2631030''>to</span> <span m=''2631100''>do</span>
  <span m=''2631190''>4</span> <span m=''2632760''>additions</span> <span m=''2633440''>of</span>
  <span m=''2633590''>size</span> <span m=''2633950''>n</span> <span m=''2634070''>over</span>
  <span m=''2634250''>2.</span> <span m=''2635120''>Plus there''s</span> <span m=''2635540''>order</span>
  <span m=''2635840''>1</span> <span m=''2636100''>work</span> <span m=''2636380''>here</span>
  <span m=''2636610''>for</span> <span m=''2636750''>the</span> <span m=''2636880''>sync.</span>
  <span m=''2638370''>And</span> <span m=''2638580''>that</span> <span m=''2639030''>recurrence</span>
  <span m=''2639670''>has</span> <span m=''2640150''>solution</span> <span m=''2641440''>order</span>
  <span m=''2641720''>n</span> <span m=''2641930''>squared.</span> <span m=''2644080''>Well,</span>
  <span m=''2644330''>that''s</span> <span m=''2644510''>not</span> <span m=''2644690''>surprising.</span>
  <span m=''2645200''>You</span> <span m=''2645300''>have</span> <span m=''2645470''>to</span>
  <span m=''2645580''>add</span> <span m=''2645780''>up</span> <span m=''2645900''>2</span>
  <span m=''2646020''>matrices</span> <span m=''2646540''>which</span> <span m=''2646720''>are
  n</span> <span m=''2646930''>by</span> <span m=''2647140''>n.</span> <span m=''2647980''>That''s</span>
  <span m=''2648250''>going</span> <span m=''2648297''>to</span> <span m=''2648345''>be</span>
  <span m=''2648392''>n</span> <span m=''2648440''>squared</span> <span m=''2648830''>so</span>
  <span m=''2649470''>that''s</span> <span m=''2649630''>a</span> <span m=''2649700''>good</span>
  <span m=''2650140''>result.</span> <span m=''2650900''>The</span> <span m=''2651030''>critical</span>
  <span m=''2651350''>path</span> <span m=''2651720''>for</span> <span m=''2651850''>this</span>
  <span m=''2652640''>is</span> <span m=''2653000''>well,</span> <span m=''2653230''>you</span>
  <span m=''2653380''>have</span> <span m=''2653630''>to</span> <span m=''2653740''>do</span>
  <span m=''2655110''>all</span> <span m=''2655340''>of</span> <span m=''2655450''>these</span>
  <span m=''2655680''>in</span> <span m=''2655790''>parallel.</span> <span m=''2656350''>So</span>
  <span m=''2656960''>whatever</span> <span m=''2657280''>the</span> <span m=''2657380''>critical</span>
  <span m=''2657720''>path</span> <span m=''2658110''>of</span> <span m=''2658230''>the</span>
  <span m=''2658330''>longest</span> <span m=''2658830''>one</span> <span m=''2659070''>is,</span>
  <span m=''2660680''>they''re</span> <span m=''2660840''>all</span> <span m=''2660950''>the</span>
  <span m=''2661040''>same</span> <span m=''2661450''>so</span> <span m=''2661600''>it''s</span>
  <span m=''2661760''>just</span> <span m=''2662090''>the</span> <span m=''2662180''>critical</span>
  <span m=''2662500''>path</span> <span m=''2662800''>of the</span> <span m=''2663270''>size
  n</span> <span m=''2663350''>over</span> <span m=''2663530''>2</span> <span m=''2663740''>plus</span>
  <span m=''2664060''>quarter</span> <span m=''2664290''>1,</span> <span m=''2665140''>so</span>
  <span m=''2665260''>the</span> <span m=''2665330''>critical</span> <span m=''2665650''>path</span>
  <span m=''2666090''>is order</span> <span m=''2666350''>log</span> <span m=''2666660''>n.</span>
  </p><p><span m=''2669350''>For</span> <span m=''2669470''>matrix</span> <span m=''2669830''>multiplication,</span>
  <span m=''2673490''>sort</span> <span m=''2673720''>of</span> <span m=''2673810''>the</span>
  <span m=''2673920''>reason</span> <span m=''2674190''>I</span> <span m=''2674270''>do</span>
  <span m=''2674470''>this</span> <span m=''2674690''>is</span> <span m=''2675030''>I</span>
  <span m=''2675150''>can.</span> <span m=''2676840''>This</span> <span m=''2677000''>is</span>
  <span m=''2677080''>a</span> <span m=''2677150''>model</span> <span m=''2677450''>which</span>
  <span m=''2677700''>I</span> <span m=''2677740''>can</span> <span m=''2677890''>do</span>
  <span m=''2678010''>this</span> <span m=''2678190''>analysis,</span> <span m=''2678350''>so</span>
  <span m=''2678820''>I</span> <span m=''2678880''>have</span> <span m=''2679140''>to</span>
  <span m=''2679250''>do</span> <span m=''2679410''>it.</span> <span m=''2680010''>But</span>
  <span m=''2680610''>really,</span> <span m=''2681840''>being</span> <span m=''2682050''>able</span>
  <span m=''2682220''>to</span> <span m=''2682310''>do</span> <span m=''2682420''>this</span>
  <span m=''2682600''>analysis</span> <span m=''2683180''>is</span> <span m=''2683310''>important</span>
  <span m=''2683740''>when</span> <span m=''2683840''>you''re</span> <span m=''2683940''>trying</span>
  <span m=''2684130''>to</span> <span m=''2684190''>make</span> <span m=''2684350''>things</span>
  <span m=''2684550''>run</span> <span m=''2684750''>faster.</span> <span m=''2686550''>Matrix</span>
  <span m=''2686870''>multiplication,</span> <span m=''2687540''>well,</span> <span
  m=''2687660''>the</span> <span m=''2687740''>work</span> <span m=''2688030''>is</span>
  <span m=''2688160''>I</span> <span m=''2688243''>have</span> <span m=''2688326''>to</span>
  <span m=''2688410''>do</span> <span m=''2688540''>8</span> <span m=''2688800''>little</span>
  <span m=''2688980''>matrix</span> <span m=''2689390''>multiplies</span> <span m=''2690840''>plus</span>
  <span m=''2691150''>I</span> <span m=''2691260''>have</span> <span m=''2691480''>to</span>
  <span m=''2691580''>do</span> <span m=''2691890''>the</span> <span m=''2692050''>matrix</span>
  <span m=''2692440''>add.</span> <span m=''2696350''>The</span> <span m=''2696500''>work</span>
  <span m=''2696760''>has</span> <span m=''2696980''>solution</span> <span m=''2697390''>order</span>
  <span m=''2697660''>n</span> <span m=''2697900''>cubed</span> <span m=''2698250''>and</span>
  <span m=''2698370''>everybody</span> <span m=''2698740''>knows</span> <span m=''2699020''>that</span>
  <span m=''2699110''>there''s</span> <span m=''2699270''>order</span> <span m=''2699480''>n</span>
  <span m=''2699710''>cubed</span> <span m=''2700520''>multiply</span> <span m=''2700990''>adds</span>
  <span m=''2701260''>in</span> <span m=''2701330''>a</span> <span m=''2701390''>matrix</span>
  <span m=''2701740''>multiplier,</span> <span m=''2701990''>so</span> <span m=''2702240''>that''s</span>
  <span m=''2702470''>not</span> <span m=''2702660''>very</span> <span m=''2702840''>surprising.</span>
  <span m=''2704420''>The</span> <span m=''2704530''>critical</span> <span m=''2704900''>path</span>
  <span m=''2705310''>is--</span> <span m=''2705580''>well,</span> <span m=''2705830''>I</span>
  <span m=''2705910''>have</span> <span m=''2706130''>to</span> <span m=''2706240''>do</span>
  <span m=''2707520''>a</span> <span m=''2708190''>add</span> <span m=''2709190''>so</span>
  <span m=''2709360''>that</span> <span m=''2709510''>takes</span> <span m=''2709700''>log
  n,</span> <span m=''2710570''>plus</span> <span m=''2710870''>I</span> <span m=''2710940''>have</span>
  <span m=''2711040''>to</span> <span m=''2711130''>do</span> <span m=''2711240''>a</span>
  <span m=''2711320''>multiply</span> <span m=''2711870''>on a</span> <span m=''2712300''>matrix</span>
  <span m=''2712730''>that''s</span> <span m=''2712910''>1/2</span> <span m=''2713200''>the</span>
  <span m=''2713290''>size.</span> <span m=''2714210''>So</span> <span m=''2714350''>the</span>
  <span m=''2714440''>critical</span> <span m=''2714790''>path</span> <span m=''2715140''>length</span>
  <span m=''2715390''>of</span> <span m=''2715480''>the</span> <span m=''2715570''>whole</span>
  <span m=''2715840''>thing</span> <span m=''2716340''>has</span> <span m=''2716590''>solution</span>
  <span m=''2716990''>order</span> <span m=''2717240''>log</span> <span m=''2717750''>squared</span>
  <span m=''2718220''>n.</span> <span m=''2719190''>So</span> <span m=''2719480''>the</span>
  <span m=''2719780''>total</span> <span m=''2721820''>parallelism</span> <span m=''2722700''>of</span>
  <span m=''2723630''>matrix</span> <span m=''2724070''>multiplication</span> <span
  m=''2725010''>is</span> <span m=''2725410''>the</span> <span m=''2725670''>work</span>
  <span m=''2726050''>over</span> <span m=''2726270''>the</span> <span m=''2726390''>span,</span>
  <span m=''2727340''>which</span> <span m=''2727520''>is</span> <span m=''2727650''>n</span>
  <span m=''2727910''>cubed</span> <span m=''2728820''>over</span> <span m=''2729060''>log</span>
  <span m=''2729360''>squared</span> <span m=''2729680''>n.</span> <span m=''2730900''>So</span>
  <span m=''2731090''>if</span> <span m=''2731180''>you</span> <span m=''2731240''>have</span>
  <span m=''2731370''>a</span> <span m=''2731420''>1000</span> <span m=''2731880''>by</span>
  <span m=''2732000''>1000</span> <span m=''2732470''>matrix</span> <span m=''2733580''>that</span>
  <span m=''2733750''>means</span> <span m=''2733890''>your</span> <span m=''2734030''>parallelism</span>
  <span m=''2734770''>is</span> <span m=''2734920''>close</span> <span m=''2735280''>to</span>
  <span m=''2735950''>10</span> <span m=''2736170''>million.</span> <span m=''2737860''>There''s</span>
  <span m=''2738030''>a</span> <span m=''2738100''>lot</span> <span m=''2738380''>of</span>
  <span m=''2738450''>parallelism</span> <span m=''2738930''>and</span> <span m=''2739440''>in</span>
  <span m=''2739610''>fact,</span> <span m=''2739950''>we</span> <span m=''2740070''>see</span>
  <span m=''2740540''>perfect</span> <span m=''2740930''>linear</span> <span m=''2741200''>speedup</span>
  <span m=''2741750''>on</span> <span m=''2741960''>matrix</span> <span m=''2742360''>multiply</span>
  <span m=''2742880''>because</span> <span m=''2743390''>there''s</span> <span m=''2743590''>so</span>
  <span m=''2743760''>much</span> <span m=''2743960''>parallelism</span> <span m=''2744360''>in</span>
  <span m=''2744570''>it.</span> </p><p><span m=''2747710''>It</span> <span m=''2747870''>turns</span>
  <span m=''2748210''>out</span> <span m=''2748440''>that</span> <span m=''2748570''>this</span>
  <span m=''2748720''>stack</span> <span m=''2749240''>temporary</span> <span m=''2749760''>that</span>
  <span m=''2749910''>I</span> <span m=''2749990''>created</span> <span m=''2751160''>so</span>
  <span m=''2751270''>that</span> <span m=''2751360''>I</span> <span m=''2751410''>could</span>
  <span m=''2751570''>do</span> <span m=''2751730''>these</span> <span m=''2751930''>multiplies</span>
  <span m=''2752510''>all</span> <span m=''2752660''>in</span> <span m=''2752770''>parallel</span>
  <span m=''2753390''>is</span> <span m=''2753550''>actually</span> <span m=''2753870''>costing</span>
  <span m=''2754400''>me</span> <span m=''2754820''>work</span> <span m=''2756120''>because</span>
  <span m=''2757090''>I''m</span> <span m=''2757270''>on</span> <span m=''2757390''>a</span>
  <span m=''2757440''>machine</span> <span m=''2757770''>that</span> <span m=''2757870''>has</span>
  <span m=''2758130''>cache</span> <span m=''2758590''>and</span> <span m=''2758700''>I</span>
  <span m=''2758740''>want</span> <span m=''2758940''>to</span> <span m=''2759000''>use</span>
  <span m=''2759220''>the</span> <span m=''2759310''>cache</span> <span m=''2759620''>effectively.</span>
  <span m=''2760110''>So</span> <span m=''2760230''>I</span> <span m=''2760260''>really</span>
  <span m=''2760570''>don''t</span> <span m=''2760800''>want</span> <span m=''2760990''>to</span>
  <span m=''2761060''>create</span> <span m=''2761350''>a</span> <span m=''2761400''>whole</span>
  <span m=''2761620''>big</span> <span m=''2762180''>temporary</span> <span m=''2762630''>matrix</span>
  <span m=''2763150''>and blow</span> <span m=''2763440''>my</span> <span m=''2763600''>cache</span>
  <span m=''2763970''>out</span> <span m=''2764120''>if</span> <span m=''2764200''>I</span>
  <span m=''2764280''>can</span> <span m=''2764440''>avoid</span> <span m=''2764760''>it.</span>
  <span m=''2766780''>So</span> <span m=''2767220''>I</span> <span m=''2767330''>proposed</span>
  <span m=''2767720''>the</span> <span m=''2767810''>following</span> <span m=''2769490''>matrix</span>
  <span m=''2769860''>multiply,</span> <span m=''2770380''>which</span> <span m=''2770590''>is</span>
  <span m=''2770730''>I</span> <span m=''2770860''>first</span> <span m=''2771200''>do</span>
  <span m=''2771340''>4</span> <span m=''2771680''>of the</span> <span m=''2771800''>matrix</span>
  <span m=''2772140''>multiplies</span> <span m=''2772730''>into</span> <span m=''2773020''>C1</span>
  <span m=''2773780''>then</span> <span m=''2774550''>I</span> <span m=''2774720''>do</span>
  <span m=''2774880''>a</span> <span m=''2774950''>sync</span> <span m=''2775360''>and</span>
  <span m=''2775490''>then</span> <span m=''2775620''>I</span> <span m=''2775690''>do</span>
  <span m=''2775820''>the</span> <span m=''2775950''>other</span> <span m=''2776160''>4</span>
  <span m=''2776440''>into</span> <span m=''2776600''>C1</span> <span m=''2777130''>and</span>
  <span m=''2778260''>another</span> <span m=''2778640''>sync.</span> <span m=''2780830''>And</span>
  <span m=''2780920''>I</span> <span m=''2780980''>forgot</span> <span m=''2781400''>to</span>
  <span m=''2781530''>do</span> <span m=''2782500''>the</span> <span m=''2782950''>add--</span>
  <span m=''2783080''>oh, no</span> <span m=''2783180''>those</span> <span m=''2783330''>are</span>
  <span m=''2783390''>multiply</span> <span m=''2783860''>adds</span> <span m=''2784560''>so</span>
  <span m=''2784840''>they''re</span> <span m=''2785030''>multiplying</span> <span
  m=''2785520''>and</span> <span m=''2785640''>adding</span> <span m=''2785980''>in.</span>
  <span m=''2786850''>And</span> <span m=''2787120''>this</span> <span m=''2787230''>saves</span>
  <span m=''2787650''>space</span> <span m=''2788140''>because</span> <span m=''2788440''>it</span>
  <span m=''2788560''>doesn''t</span> <span m=''2789050''>need</span> <span m=''2789280''>a</span>
  <span m=''2789330''>temporary,</span> <span m=''2790300''>but</span> <span m=''2790530''>it</span>
  <span m=''2790650''>increases</span> <span m=''2791210''>the</span> <span m=''2791300''>critical</span>
  <span m=''2791670''>path.</span> <span m=''2792960''>So</span> <span m=''2793110''>is</span>
  <span m=''2793200''>that</span> <span m=''2793330''>a</span> <span m=''2793380''>good</span>
  <span m=''2793590''>idea</span> <span m=''2794040''>about</span> <span m=''2794320''>or
  a</span> <span m=''2794580''>bad</span> <span m=''2795185''>idea?</span> </p><p><span
  m=''2795790''>Well,</span> <span m=''2796370''>we</span> <span m=''2796480''>can</span>
  <span m=''2796670''>answer</span> <span m=''2797070''>part</span> <span m=''2797340''>of</span>
  <span m=''2797400''>that</span> <span m=''2797570''>question</span> <span m=''2797940''>with</span>
  <span m=''2798090''>analysis.</span> <span m=''2799410''>Saving</span> <span m=''2799720''>space</span>
  <span m=''2800090''>we</span> <span m=''2800210''>know</span> <span m=''2800420''>is</span>
  <span m=''2800640''>going</span> <span m=''2800703''>to</span> <span m=''2800766''>save</span>
  <span m=''2800830''>something.</span> <span m=''2802290''>What</span> <span m=''2802590''>does</span>
  <span m=''2802720''>it</span> <span m=''2802830''>do</span> <span m=''2803000''>to</span>
  <span m=''2803120''>the</span> <span m=''2803200''>work in</span> <span m=''2803500''>critical</span>
  <span m=''2803810''>path?</span> <span m=''2804080''>Well,</span> <span m=''2804180''>the</span>
  <span m=''2804250''>work</span> <span m=''2804520''>is</span> <span m=''2804630''>still</span>
  <span m=''2804850''>the</span> <span m=''2804950''>same,</span> <span m=''2805900''>it''s</span>
  <span m=''2806410''>n</span> <span m=''2806640''>cubed</span> <span m=''2806870''>because</span>
  <span m=''2807140''>we</span> <span m=''2807220''>didn''t</span> <span m=''2807440''>change</span>
  <span m=''2807860''>the</span> <span m=''2808000''>number of</span> <span m=''2808630''>flops</span>
  <span m=''2808835''>that</span> <span m=''2809040''>we''re</span> <span m=''2809270''>doing.</span>
  <span m=''2810370''>But</span> <span m=''2810530''>the</span> <span m=''2810600''>critical</span>
  <span m=''2810980''>path has</span> <span m=''2811540''>grown.</span> <span m=''2811900''>Instead</span>
  <span m=''2812220''>of</span> <span m=''2812310''>doing</span> <span m=''2813010''>1</span>
  <span m=''2813550''>times</span> <span m=''2814520''>a</span> <span m=''2814800''>matrix</span>
  <span m=''2815040''>multiply,</span> <span m=''2816100''>we</span> <span m=''2816280''>have</span>
  <span m=''2816370''>to</span> <span m=''2816450''>do</span> <span m=''2816530''>one</span>
  <span m=''2816900''>and</span> <span m=''2817080''>then</span> <span m=''2817390''>sync</span>
  <span m=''2817750''>and</span> <span m=''2817880''>then</span> <span m=''2817990''>do</span>
  <span m=''2818110''>another</span> <span m=''2818440''>one.</span> <span m=''2818690''>So</span>
  <span m=''2818830''>it''s</span> <span m=''2818980''>2</span> <span m=''2819390''>matrix</span>
  <span m=''2819800''>multiplies</span> <span m=''2820320''>of</span> <span m=''2820430''>1/2</span>
  <span m=''2820660''>the</span> <span m=''2820750''>size</span> <span m=''2821380''>plus</span>
  <span m=''2821690''>the</span> <span m=''2821790''>order</span> <span m=''2821950''>1</span>
  <span m=''2822140''>and</span> <span m=''2822260''>that</span> <span m=''2822560''>recurrence</span>
  <span m=''2823050''>has</span> <span m=''2824970''>solution</span> <span m=''2825370''>order</span>
  <span m=''2825740''>n</span> <span m=''2826320''>instead</span> <span m=''2826600''>of</span>
  <span m=''2826700''>order</span> <span m=''2827820''>log</span> <span m=''2828110''>squared</span>
  <span m=''2828500''>n.</span> <span m=''2829300''>So</span> <span m=''2829450''>that</span>
  <span m=''2829590''>sounds</span> <span m=''2829810''>bad,</span> <span m=''2830080''>we''ve</span>
  <span m=''2830200''>made</span> <span m=''2830320''>the</span> <span m=''2830410''>critical</span>
  <span m=''2830720''>path</span> <span m=''2831050''>longer.</span> </p><p><span
  m=''2832590''>AUDIENCE: [OBSCURED]</span> </p><p><span m=''2833610''>BRADLEY KUSZMAUL:
  What?</span> <span m=''2833870''>Yeah.</span> <span m=''2835010''>So</span> <span
  m=''2835560''>parallelism</span> <span m=''2836230''>is</span> <span m=''2836410''>now</span>
  <span m=''2836790''>order</span> <span m=''2837070''>n</span> <span m=''2837340''>squared</span>
  <span m=''2837850''>instead</span> <span m=''2838150''>of</span> <span m=''2838230''>n</span>
  <span m=''2838470''>cubed</span> <span m=''2838790''>over</span> <span m=''2838980''>log</span>
  <span m=''2839280''>squared</span> <span m=''2839650''>n</span> <span m=''2840440''>and</span>
  <span m=''2840660''>for a</span> <span m=''2840760''>1000</span> <span m=''2841180''>by</span>
  <span m=''2841300''>1000</span> <span m=''2841650''>matrix</span> <span m=''2842090''>that
  means</span> <span m=''2842240''>you</span> <span m=''2842450''>still</span> <span
  m=''2842670''>have</span> <span m=''2842790''>a</span> <span m=''2842840''>million</span>
  <span m=''2843210''>fold</span> <span m=''2843420''>parallelism.</span> <span m=''2844740''>So</span>
  <span m=''2844910''>for</span> <span m=''2845080''>relatively</span> <span m=''2845550''>modest</span>
  <span m=''2846020''>sized</span> <span m=''2846410''>matrices</span> <span m=''2846970''>you</span>
  <span m=''2847080''>still</span> <span m=''2847330''>have</span> <span m=''2847610''>plenty</span>
  <span m=''2847900''>of</span> <span m=''2848000''>work</span> <span m=''2848270''>to</span>
  <span m=''2848370''>do</span> <span m=''2848470''>this</span> <span m=''2848640''>optimization.</span>
  <span m=''2849260''>So</span> <span m=''2849360''>this</span> <span m=''2849530''>is</span>
  <span m=''2849620''>a</span> <span m=''2849690''>good</span> <span m=''2850770''>transformation</span>
  <span m=''2851470''>to</span> <span m=''2851560''>do</span> <span m=''2851730''>it.</span>
  <span m=''2851830''>One</span> <span m=''2851990''>of</span> <span m=''2852050''>the</span>
  <span m=''2852130''>advantages</span> <span m=''2852660''>of</span> <span m=''2852770''>Cilk</span>
  <span m=''2853640''>is</span> <span m=''2853820''>that</span> <span m=''2853960''>you</span>
  <span m=''2854070''>can</span> <span m=''2854210''>do</span> <span m=''2854350''>this</span>
  <span m=''2854520''>kind</span> <span m=''2854680''>of</span> <span m=''2854740''>You</span>
  <span m=''2855860''>could</span> <span m=''2855980''>say,</span> <span m=''2856100''>let</span>
  <span m=''2856270''>me</span> <span m=''2856350''>do</span> <span m=''2856450''>an</span>
  <span m=''2856540''>optimization.</span> <span m=''2857770''>I</span> <span m=''2857990''>can</span>
  <span m=''2858120''>do an</span> <span m=''2858260''>optimization</span> <span m=''2858910''>in</span>
  <span m=''2858990''>my</span> <span m=''2859130''>C</span> <span m=''2859420''>code</span>
  <span m=''2859780''>and</span> <span m=''2859880''>I</span> <span m=''2859940''>get</span>
  <span m=''2860080''>to</span> <span m=''2860150''>take</span> <span m=''2860340''>advantage</span>
  <span m=''2860720''>of</span> <span m=''2860810''>it</span> <span m=''2860910''>in</span>
  <span m=''2861030''>the</span> <span m=''2861680''>Cilk</span> <span m=''2862010''>code.</span>
  <span m=''2862460''>I</span> <span m=''2862530''>could</span> <span m=''2862670''>do</span>
  <span m=''2862770''>this</span> <span m=''2862900''>kind</span> <span m=''2863120''>of</span>
  <span m=''2864260''>optimization</span> <span m=''2864720''>of</span> <span m=''2864990''>trading</span>
  <span m=''2865360''>work</span> <span m=''2865580''>for</span> <span m=''2865690''>parallelism.</span>
  <span m=''2866290''>If</span> <span m=''2866400''>I</span> <span m=''2866460''>have</span>
  <span m=''2866650''>a</span> <span m=''2866710''>lot</span> <span m=''2866890''>of</span>
  <span m=''2867000''>work</span> <span m=''2867730''>that</span> <span m=''2867900''>sometimes</span>
  <span m=''2868290''>is</span> <span m=''2868380''>a</span> <span m=''2868430''>good</span>
  <span m=''2868590''>idea.</span> <span m=''2869730''>Ordinary</span> <span m=''2870340''>matrix</span>
  <span m=''2870750''>multiplication</span> <span m=''2871430''>just is</span> <span
  m=''2871750''>really</span> <span m=''2872160''>bad.</span> <span m=''2873810''>Basically</span>
  <span m=''2874270''>you</span> <span m=''2874350''>can</span> <span m=''2874500''>imagine</span>
  <span m=''2875090''>spawning</span> <span m=''2875660''>off</span> <span m=''2876010''>the</span>
  <span m=''2876180''>n</span> <span m=''2876720''>squared</span> <span m=''2877170''>inner</span>
  <span m=''2878130''>dot</span> <span m=''2878380''>products</span> <span m=''2878790''>here</span>
  <span m=''2879030''>and</span> <span m=''2880180''>computing</span> <span m=''2880660''>them</span>
  <span m=''2880800''>all</span> <span m=''2880970''>in</span> <span m=''2881060''>parallel.</span>
  <span m=''2881790''>It</span> <span m=''2881920''>has</span> <span m=''2883330''>work</span>
  <span m=''2883690''>n</span> <span m=''2883920''>cubed</span> <span m=''2884440''>parallelism</span>
  <span m=''2885140''>log</span> <span m=''2885500''>n.</span> <span m=''2886560''>I</span>
  <span m=''2886640''>mean,</span> <span m=''2887100''>critical</span> <span m=''2887410''>path</span>
  <span m=''2887780''>log</span> <span m=''2887920''>n so</span> <span m=''2888020''>the</span>
  <span m=''2888100''>parallelism''s</span> <span m=''2888710''>even</span> <span
  m=''2888920''>better.</span> <span m=''2890210''>It''s</span> <span m=''2890380''>n</span>
  <span m=''2890620''>cubed</span> <span m=''2890940''>over</span> <span m=''2891130''>log</span>
  <span m=''2891480''>n</span> <span m=''2891930''>instead</span> <span m=''2892080''>of</span>
  <span m=''2892420''>n</span> <span m=''2892600''>squared.</span> <span m=''2893480''>That</span>
  <span m=''2893660''>looks</span> <span m=''2893900''>better</span> <span m=''2894220''>theoretically,</span>
  <span m=''2895420''>but</span> <span m=''2895540''>it''s</span> <span m=''2895640''>really</span>
  <span m=''2896000''>bad</span> <span m=''2896280''>in</span> <span m=''2896380''>practice</span>
  <span m=''2896810''>because</span> <span m=''2897080''>it</span> <span m=''2897150''>has</span>
  <span m=''2897350''>such</span> <span m=''2897590''>poor</span> <span m=''2897810''>cache</span>
  <span m=''2898130''>behavior.</span> <span m=''2899430''>So</span> <span m=''2900750''>we</span>
  <span m=''2900890''>don''t</span> <span m=''2901050''>do</span> <span m=''2901160''>that.</span>
  </p><p><span m=''2903390''>I''ll</span> <span m=''2903560''>just</span> <span m=''2903830''>briefly</span>
  <span m=''2904220''>talk</span> <span m=''2904440''>about</span> <span m=''2904700''>how</span>
  <span m=''2904890''>it</span> <span m=''2904990''>works.</span> <span m=''2905360''>So</span>
  <span m=''2905470''>Cilk</span> <span m=''2905790''>does</span> <span m=''2905990''>work-stealing.</span>
  <span m=''2907000''>We</span> <span m=''2907150''>had</span> <span m=''2907380''>did</span>
  <span m=''2907740''>double</span> <span m=''2908180''>ended</span> <span m=''2908560''>queue-like</span>
  <span m=''2908850''>decque.</span> <span m=''2909740''>So</span> <span m=''2909980''>at
  the</span> <span m=''2910110''>bottom</span> <span m=''2910500''>of</span> <span
  m=''2910570''>the</span> <span m=''2910720''>queue</span> <span m=''2910950''>is</span>
  <span m=''2911130''>the</span> <span m=''2911230''>stack</span> <span m=''2911630''>where</span>
  <span m=''2911715''>you</span> <span m=''2911800''>push and</span> <span m=''2912190''>pop</span>
  <span m=''2912510''>things</span> <span m=''2912890''>and</span> <span m=''2912990''>the</span>
  <span m=''2913070''>top</span> <span m=''2913420''>is</span> <span m=''2913670''>something</span>
  <span m=''2914040''>where</span> <span m=''2914150''>you</span> <span m=''2914230''>can</span>
  <span m=''2914420''>pop</span> <span m=''2914680''>things</span> <span m=''2914950''>off</span>
  <span m=''2915200''>if</span> <span m=''2915300''>you</span> <span m=''2915390''>want</span>
  <span m=''2915650''>to.</span> <span m=''2916500''>And</span> <span m=''2916800''>so</span>
  <span m=''2916890''>what''s</span> <span m=''2917120''>running</span> <span m=''2917420''>is</span>
  <span m=''2917540''>all</span> <span m=''2917670''>these</span> <span m=''2917820''>processors</span>
  <span m=''2918390''>are</span> <span m=''2918480''>running</span> <span m=''2918790''>each</span>
  <span m=''2919000''>on</span> <span m=''2919110''>their</span> <span m=''2919240''>own</span>
  <span m=''2919410''>stack.</span> <span m=''2920170''>They''re</span> <span m=''2920310''>all</span>
  <span m=''2920600''>running</span> <span m=''2921090''>the</span> <span m=''2921190''>ordinary</span>
  <span m=''2921770''>serial</span> <span m=''2922180''>code.</span> <span m=''2922690''>That''s</span>
  <span m=''2922930''>sort</span> <span m=''2923120''>of</span> <span m=''2923480''>the</span>
  <span m=''2923660''>basic</span> <span m=''2924080''>situation.</span> <span m=''2924700''>They''re</span>
  <span m=''2924800''>pretty</span> <span m=''2925110''>much</span> <span m=''2925360''>running</span>
  <span m=''2925670''>the</span> <span m=''2925780''>serial</span> <span m=''2926190''>code</span>
  <span m=''2927200''>most</span> <span m=''2927540''>of</span> <span m=''2927600''>the</span>
  <span m=''2927690''>time.</span> <span m=''2928470''>So</span> <span m=''2928670''>some</span>
  <span m=''2928880''>processor</span> <span m=''2929400''>runs.</span> <span m=''2930170''>It</span>
  <span m=''2930350''>pushes.</span> <span m=''2931490''>Well,</span> <span m=''2931790''>it</span>
  <span m=''2931860''>doesn''t</span> <span m=''2932100''>spawn,</span> <span m=''2932610''>so</span>
  <span m=''2932700''>what</span> <span m=''2932810''>does</span> <span m=''2932910''>it</span>
  <span m=''2933010''>do?</span> <span m=''2933130''>It</span> <span m=''2933230''>pushes</span>
  <span m=''2933590''>something</span> <span m=''2933920''>onto</span> <span m=''2934180''>its</span>
  <span m=''2934330''>stack</span> <span m=''2934580''>because</span> <span m=''2934710''>it''s</span>
  <span m=''2934820''>just</span> <span m=''2935030''>a</span> <span m=''2935080''>function</span>
  <span m=''2935480''>call.</span> <span m=''2937080''>And</span> <span m=''2937340''>it
  does</span> <span m=''2937510''>another</span> <span m=''2938980''>couple</span>
  <span m=''2939280''>more</span> <span m=''2939470''>spawns</span> <span m=''2940050''>so
  things</span> <span m=''2940320''>pop</span> <span m=''2940620''>off.</span> <span
  m=''2941760''>Somebody</span> <span m=''2942100''>returns</span> <span m=''2942670''>so</span>
  <span m=''2942770''>he</span> <span m=''2942900''>pops</span> <span m=''2943250''>his</span>
  <span m=''2943430''>stack.</span> <span m=''2944180''>So</span> <span m=''2944380''>far</span>
  <span m=''2944640''>everything''s</span> <span m=''2945080''>going</span> <span
  m=''2945360''>on,</span> <span m=''2945600''>they''re</span> <span m=''2945890''>not</span>
  <span m=''2946220''>communicating,</span> <span m=''2946890''>they''re</span> <span
  m=''2947020''>completely</span> <span m=''2947530''>independent</span> <span m=''2948000''>computations.</span>
  <span m=''2950640''>This</span> <span m=''2950830''>guy</span> <span m=''2951170''>spawns</span>
  <span m=''2951620''>and</span> <span m=''2951750''>now</span> <span m=''2951940''>he''s</span>
  <span m=''2952120''>out</span> <span m=''2952250''>of</span> <span m=''2952340''>work.</span>
  <span m=''2952840''>Now</span> <span m=''2953050''>he</span> <span m=''2953120''>has</span>
  <span m=''2953240''>to</span> <span m=''2953350''>do</span> <span m=''2953500''>something.</span>
  <span m=''2954220''>What</span> <span m=''2954510''>he</span> <span m=''2954620''>does</span>
  <span m=''2955420''>is he</span> <span m=''2955510''>goes</span> <span m=''2955800''>and</span>
  <span m=''2955900''>picks</span> <span m=''2956120''>another</span> <span m=''2956420''>processor</span>
  <span m=''2957020''>at</span> <span m=''2957090''>random</span> <span m=''2959060''>and</span>
  <span m=''2959400''>he</span> <span m=''2959650''>steals</span> <span m=''2960890''>the</span>
  <span m=''2961020''>thing</span> <span m=''2961840''>from</span> <span m=''2962170''>the</span>
  <span m=''2962270''>other</span> <span m=''2962500''>end</span> <span m=''2962630''>of</span>
  <span m=''2962710''>the</span> <span m=''2962780''>stack.</span> <span m=''2963920''>So</span>
  <span m=''2964030''>he''s</span> <span m=''2964230''>unlikely</span> <span m=''2964790''>to</span>
  <span m=''2964890''>conflict</span> <span m=''2965430''>because</span> <span m=''2965560''>this</span>
  <span m=''2965690''>guy''s</span> <span m=''2965810''>pushing</span> <span m=''2966035''>and</span>
  <span m=''2966260''>popping</span> <span m=''2966630''>down</span> <span m=''2966840''>here,</span>
  <span m=''2967360''>but</span> <span m=''2967570''>there''s</span> <span m=''2967780''>a</span>
  <span m=''2967850''>lock</span> <span m=''2968200''>in</span> <span m=''2968320''>there,</span>
  <span m=''2968480''>thers''s</span> <span m=''2968660''>a little</span> <span m=''2969140''>algorithm.</span>
  <span m=''2970290''>A</span> <span m=''2970640''>non-blocking</span> <span m=''2971890''>algorithm</span>
  <span m=''2972030''>actually,</span> <span m=''2972350''>it''s</span> <span m=''2972480''>not</span>
  <span m=''2973040''>lock.</span> <span m=''2974680''>And</span> <span m=''2975480''>so</span>
  <span m=''2975600''>he</span> <span m=''2975700''>goes</span> <span m=''2975930''>and
  he</span> <span m=''2976060''>steals</span> <span m=''2976460''>something</span>
  <span m=''2976920''>and</span> <span m=''2977590''>come</span> <span m=''2977790''>on,</span>
  <span m=''2978370''>slide</span> <span m=''2978870''>over</span> <span m=''2979080''>there.</span>
  <span m=''2979690''>Whoa.</span> <span m=''2980460''>Yes,</span> <span m=''2980520''>that''s</span>
  <span m=''2981520''>animation,</span> <span m=''2982080''>right?</span> <span m=''2983900''>That''s</span>
  <span m=''2984330''>the</span> <span m=''2984600''>extent of</span> <span m=''2985030''>my</span>
  <span m=''2985150''>animation.</span> <span m=''2987340''>And</span> <span m=''2987540''>then</span>
  <span m=''2987630''>he</span> <span m=''2987700''>starts</span> <span m=''2988040''>working</span>
  <span m=''2988370''>away.</span> </p><p><span m=''2989600''>And</span> <span m=''2989840''>the</span>
  <span m=''2989920''>theorem</span> <span m=''2990710''>is</span> <span m=''2991020''>that</span>
  <span m=''2991310''>a</span> <span m=''2991440''>work-stealing</span> <span m=''2992020''>scheduler</span>
  <span m=''2992520''>like</span> <span m=''2992800''>this</span> <span m=''2993050''>gives</span>
  <span m=''2993280''>expected</span> <span m=''2993820''>running</span> <span m=''2994130''>time</span>
  <span m=''2994810''>with</span> <span m=''2995070''>high</span> <span m=''2995230''>probability</span>
  <span m=''2996330''>actually</span> <span m=''2996970''>of</span> <span m=''2997190''>T
  sub</span> <span m=''2997350''>1</span> <span m=''2997540''>over</span> <span m=''2997690''>P</span>
  <span m=''2998240''>plus</span> <span m=''2998300''>T</span> <span m=''2998360''>sub</span>
  <span m=''2998420''>infinity</span> <span m=''2998960''>on</span> <span m=''2999100''>P</span>
  <span m=''2999280''>processors.</span> <span m=''3000690''>And</span> <span m=''3001050''>the</span>
  <span m=''3001120''>pseudoproof</span> <span m=''3002370''>is</span> <span m=''3002570''>a</span>
  <span m=''3002650''>little</span> <span m=''3002910''>bit</span> <span m=''3003060''>like</span>
  <span m=''3003430''>the</span> <span m=''3003700''>proof</span> <span m=''3004020''>for</span>
  <span m=''3004190''>Brent''s</span> <span m=''3004650''>Theorem,</span> <span m=''3004770''>which</span>
  <span m=''3004920''>is</span> <span m=''3005030''>either</span> <span m=''3005270''>you''re</span>
  <span m=''3005440''>working</span> <span m=''3005930''>or</span> <span m=''3006020''>stealing.</span>
  <span m=''3007020''>If</span> <span m=''3007300''>you''re</span> <span m=''3007420''>working</span>
  <span m=''3008060''>well,</span> <span m=''3008280''>that</span> <span m=''3008610''>goes</span>
  <span m=''3008850''>against</span> <span m=''3009180''>T</span> <span m=''3009290''>sub
  1</span> <span m=''3009460''>over</span> <span m=''3010180''>P.</span> <span m=''3011050''>You
  can''t</span> <span m=''3011370''>do</span> <span m=''3011470''>that</span> <span
  m=''3011990''>very</span> <span m=''3012250''>much</span> <span m=''3012440''>or</span>
  <span m=''3012850''>you</span> <span m=''3012990''>run</span> <span m=''3013150''>out</span>
  <span m=''3013250''>of</span> <span m=''3013340''>work.</span> <span m=''3014410''>If</span>
  <span m=''3014590''>you''re</span> <span m=''3014720''>stealing</span> <span m=''3015300''>well,</span>
  <span m=''3016490''>each</span> <span m=''3016860''>steal</span> <span m=''3017200''>has</span>
  <span m=''3017510''>a</span> <span m=''3017940''>chance</span> <span m=''3018790''>that</span>
  <span m=''3019020''>it</span> <span m=''3019210''>steals</span> <span m=''3019590''>the</span>
  <span m=''3019710''>thing</span> <span m=''3019950''>that''s</span> <span m=''3020160''>on</span>
  <span m=''3020320''>the</span> <span m=''3020390''>critical</span> <span m=''3020740''>path.</span>
  <span m=''3022040''>You</span> <span m=''3022140''>may</span> <span m=''3022250''>actually</span>
  <span m=''3022540''>steal</span> <span m=''3022840''>the</span> <span m=''3022930''>wrong</span>
  <span m=''3023240''>thing,</span> <span m=''3023440''>but</span> <span m=''3023560''>you</span>
  <span m=''3023690''>actually</span> <span m=''3023960''>have</span> <span m=''3024150''>a</span>
  <span m=''3024280''>1</span> <span m=''3024510''>in</span> <span m=''3024620''>P</span>
  <span m=''3024830''>chance</span> <span m=''3025290''>that</span> <span m=''3025420''>you''re</span>
  <span m=''3025580''>the</span> <span m=''3025670''>one</span> <span m=''3025840''>who</span>
  <span m=''3025940''>steals</span> <span m=''3026780''>the</span> <span m=''3026910''>thing</span>
  <span m=''3027640''>that</span> <span m=''3027820''>it''s</span> <span m=''3027980''>on</span>
  <span m=''3028130''>the</span> <span m=''3028200''>critical</span> <span m=''3028570''>path</span>
  <span m=''3029470''>and</span> <span m=''3029770''>then</span> <span m=''3029920''>in
  which</span> <span m=''3030140''>case the</span> <span m=''3030530''>expected</span>
  <span m=''3031020''>number--</span> <span m=''3031910''>so</span> <span m=''3032070''>you</span>
  <span m=''3032200''>had</span> <span m=''3032350''>this</span> <span m=''3032550''>chance</span>
  <span m=''3032900''>of</span> <span m=''3032980''>1</span> <span m=''3033180''>over</span>
  <span m=''3033310''>P</span> <span m=''3033440''>of</span> <span m=''3033570''>reducing</span>
  <span m=''3033980''>the</span> <span m=''3034060''>critical</span> <span m=''3034400''>path</span>
  <span m=''3034730''>length</span> <span m=''3034920''>by</span> <span m=''3035080''>1,</span>
  <span m=''3035470''>so</span> <span m=''3035660''>after</span> <span m=''3036430''>this</span>
  <span m=''3036730''>many</span> <span m=''3037030''>steals</span> <span m=''3038120''>the</span>
  <span m=''3038210''>critical</span> <span m=''3038530''>path is</span> <span m=''3038930''>all</span>
  <span m=''3039090''>gone.</span> <span m=''3039750''>So</span> <span m=''3039900''>you</span>
  <span m=''3039960''>can</span> <span m=''3040080''>only</span> <span m=''3040270''>do</span>
  <span m=''3041360''>P</span> <span m=''3041590''>times</span> <span m=''3041850''>T
  infinity</span> <span m=''3043020''>steals.</span> <span m=''3044260''>This</span>
  <span m=''3044460''>high</span> <span m=''3044580''>probability</span> <span m=''3045180''>it</span>
  <span m=''3045280''>comes</span> <span m=''3045570''>out.</span> <span m=''3046750''>And</span>
  <span m=''3046950''>that</span> <span m=''3047100''>gives</span> <span m=''3047280''>you</span>
  <span m=''3047370''>these</span> <span m=''3047570''>bounds.</span> </p><p><span
  m=''3050440''>OK,</span> <span m=''3051040''>I''m</span> <span m=''3051160''>not</span>
  <span m=''3051310''>going</span> <span m=''3051450''>to</span> <span m=''3051550''>give</span>
  <span m=''3051720''>you</span> <span m=''3051850''>all</span> <span m=''3052000''>this</span>
  <span m=''3052180''>stuff.</span> <span m=''3054110''>Message</span> <span m=''3054540''>passing</span>
  <span m=''3054920''>sucks,</span> <span m=''3055490''>you</span> <span m=''3055650''>know.</span>
  <span m=''3058040''>You</span> <span m=''3058280''>guys</span> <span m=''3058560''>know.</span>
  <span m=''3059170''>There''s</span> <span m=''3061100''>probably</span> <span m=''3061380''>nothing</span>
  <span m=''3061650''>else</span> <span m=''3061840''>in</span> <span m=''3061960''>here.</span>
  <span m=''3065270''>So</span> <span m=''3065460''>basically</span> <span m=''3067640''>the</span>
  <span m=''3067770''>pitch</span> <span m=''3068070''>here</span> <span m=''3068350''>is</span>
  <span m=''3068520''>that</span> <span m=''3068810''>you</span> <span m=''3069000''>get</span>
  <span m=''3069180''>some</span> <span m=''3069340''>high</span> <span m=''3069520''>level</span>
  <span m=''3069790''>linguistics</span> <span m=''3070320''>support</span> <span
  m=''3070820''>for</span> <span m=''3071740''>these</span> <span m=''3071930''>very</span>
  <span m=''3072240''>fine-grained</span> <span m=''3073000''>parallelism.</span>
  <span m=''3073620''>It''s</span> <span m=''3074910''>an</span> <span m=''3075160''>algorithmic</span>
  <span m=''3075510''>programming</span> <span m=''3076020''>model</span> <span m=''3076450''>so
  that</span> <span m=''3076620''>means</span> <span m=''3076880''>that</span> <span
  m=''3076980''>you</span> <span m=''3077100''>can</span> <span m=''3077240''>do</span>
  <span m=''3077390''>engineering</span> <span m=''3077990''>for</span> <span m=''3078120''>performance.</span>
  <span m=''3079640''>There''s</span> <span m=''3080620''>fairly</span> <span m=''3081010''>easy</span>
  <span m=''3081340''>conversion</span> <span m=''3081880''>of</span> <span m=''3081970''>existing</span>
  <span m=''3082460''>code,</span> <span m=''3082940''>especially</span> <span m=''3083310''>when</span>
  <span m=''3083410''>you</span> <span m=''3083500''>combine</span> <span m=''3083870''>it</span>
  <span m=''3083950''>with</span> <span m=''3084050''>the</span> <span m=''3084130''>race</span>
  <span m=''3084390''>detector.</span> <span m=''3084770''>You''ve</span> <span m=''3084960''>got</span>
  <span m=''3085150''>this</span> <span m=''3085240''>factorization</span> <span m=''3086220''>of</span>
  <span m=''3086320''>the</span> <span m=''3086420''>debugging</span> <span m=''3086850''>problem</span>
  <span m=''3087230''>and</span> <span m=''3087335''>to</span> <span m=''3087440''>debugging</span>
  <span m=''3087880''>your</span> <span m=''3088010''>serial</span> <span m=''3088360''>code</span>
  <span m=''3089180''>is</span> <span m=''3089290''>you</span> <span m=''3089390''>run</span>
  <span m=''3089630''>it</span> <span m=''3090320''>with</span> <span m=''3090470''>all</span>
  <span m=''3090630''>the</span> <span m=''3090930''>Cilk</span> <span m=''3091240''>stuff</span>
  <span m=''3091470''>turned</span> <span m=''3091730''>off.</span> <span m=''3092060''>You</span>
  <span m=''3092330''>allied</span> <span m=''3092730''>the</span> <span m=''3092820''>program</span>
  <span m=''3093240''>and</span> <span m=''3093390''>make</span> <span m=''3093510''>sure</span>
  <span m=''3093680''>your</span> <span m=''3093800''>program</span> <span m=''3094200''>works.</span>
  <span m=''3095010''>Then</span> <span m=''3095140''>you</span> <span m=''3095210''>run</span>
  <span m=''3095340''>it</span> <span m=''3095400''>with</span> <span m=''3095510''>the</span>
  <span m=''3095590''>rate</span> <span m=''3095820''>detector</span> <span m=''3096230''>to
  make</span> <span m=''3096420''>sure you</span> <span m=''3096570''>get</span> <span
  m=''3096700''>the</span> <span m=''3096770''>same</span> <span m=''3096990''>answer</span>
  <span m=''3097310''>in</span> <span m=''3097430''>parallel</span> <span m=''3097860''>and</span>
  <span m=''3098330''>then</span> <span m=''3098480''>you''re</span> <span m=''3098600''>done.</span>
  </p><p><span m=''3101290''>Applications</span> <span m=''3102050''>in</span> <span
  m=''3102180''>Cilk</span> <span m=''3102770''>don''t</span> <span m=''3103000''>just</span>
  <span m=''3103220''>scale</span> <span m=''3103610''>to</span> <span m=''3103730''>large</span>
  <span m=''3104060''>number of</span> <span m=''3104310''>processors,</span> <span
  m=''3104960''>they</span> <span m=''3105080''>scale</span> <span m=''3105450''>down</span>
  <span m=''3105800''>to</span> <span m=''3106150''>small</span> <span m=''3106570''>numbers,</span>
  <span m=''3106960''>which</span> <span m=''3107140''>is</span> <span m=''3107240''>important</span>
  <span m=''3107710''>if</span> <span m=''3107790''>you</span> <span m=''3107880''>only</span>
  <span m=''3108060''>have</span> <span m=''3108640''>two</span> <span m=''3108820''>processors</span>
  <span m=''3109450''>or</span> <span m=''3109540''>one.</span> <span m=''3109890''>You</span>
  <span m=''3110010''>don''t</span> <span m=''3110320''>suddenly</span> <span m=''3110730''>want
  to</span> <span m=''3111390''>pay</span> <span m=''3111650''>a</span> <span m=''3111710''>factor</span>
  <span m=''3112100''>of</span> <span m=''3112220''>10</span> <span m=''3113100''>to</span>
  <span m=''3113240''>get</span> <span m=''3113400''>off</span> <span m=''3113670''>the</span>
  <span m=''3113750''>ground,</span> <span m=''3114150''>which</span> <span m=''3114340''>happens</span>
  <span m=''3115100''>sometimes</span> <span m=''3115640''>on</span> <span m=''3115820''>clusters</span>
  <span m=''3116360''>running</span> <span m=''3116630''>MPI.</span> <span m=''3117110''>You</span>
  <span m=''3117270''>have</span> <span m=''3117390''>to</span> <span m=''3117530''>pay</span>
  <span m=''3117850''>a</span> <span m=''3117890''>big</span> <span m=''3118110''>overhead</span>
  <span m=''3118530''>before</span> <span m=''3118760''>you''ve</span> <span m=''3118900''>made</span>
  <span m=''3119100''>any</span> <span m=''3119270''>progress.</span> <span m=''3121700''>And</span>
  <span m=''3122480''>one</span> <span m=''3122620''>of</span> <span m=''3122690''>the</span>
  <span m=''3122890''>advantages</span> <span m=''3123410''>for</span> <span m=''3123520''>example</span>
  <span m=''3123735''>is</span> <span m=''3123950''>that</span> <span m=''3124030''>the</span>
  <span m=''3124090''>number of</span> <span m=''3124320''>processors</span> <span
  m=''3125030''>might</span> <span m=''3125250''>change</span> <span m=''3125850''>dynamically.</span>
  <span m=''3126420''>In</span> <span m=''3126950''>this</span> <span m=''3127210''>model</span>
  <span m=''3127780''>that''s</span> <span m=''3128000''>OK</span> <span m=''3129010''>because</span>
  <span m=''3129380''>it''s</span> <span m=''3129520''>not</span> <span m=''3129740''>part</span>
  <span m=''3129910''>of</span> <span m=''3129970''>the</span> <span m=''3130040''>program.</span>
  <span m=''3130650''>So</span> <span m=''3130780''>you</span> <span m=''3130920''>may</span>
  <span m=''3131050''>have</span> <span m=''3131270''>the</span> <span m=''3131400''>operating</span>
  <span m=''3131830''>system</span> <span m=''3133060''>reduce</span> <span m=''3133530''>the</span>
  <span m=''3133640''>number</span> <span m=''3133950''>of</span> <span m=''3134050''>actual</span>
  <span m=''3135330''>worker</span> <span m=''3135730''>threads</span> <span m=''3136100''>that</span>
  <span m=''3136230''>you</span> <span m=''3136330''>have</span> <span m=''3136840''>doing</span>
  <span m=''3137080''>that</span> <span m=''3137250''>work-stealing</span> <span m=''3138230''>and</span>
  <span m=''3138600''>that</span> <span m=''3138780''>can</span> <span m=''3138900''>work.</span>
  <span m=''3139560''>One</span> <span m=''3139740''>of</span> <span m=''3139820''>the</span>
  <span m=''3139930''>bad</span> <span m=''3140230''>things</span> <span m=''3140540''>about</span>
  <span m=''3141180''>Cilk</span> <span m=''3141600''>is</span> <span m=''3141760''>that</span>
  <span m=''3141910''>it</span> <span m=''3142010''>doesn''t</span> <span m=''3142420''>support</span>
  <span m=''3143800''>sort</span> <span m=''3144100''>of</span> <span m=''3145520''>data</span>
  <span m=''3145830''>parallel</span> <span m=''3146410''>or</span> <span m=''3146510''>program</span>
  <span m=''3147020''>model</span> <span m=''3147550''>kind</span> <span m=''3147750''>of</span>
  <span m=''3149450''>parallelism.</span> <span m=''3150420''>You</span> <span m=''3150690''>really</span>
  <span m=''3150960''>have</span> <span m=''3151170''>to</span> <span m=''3151790''>think</span>
  <span m=''3152020''>of</span> <span m=''3152140''>things</span> <span m=''3152650''>as</span>
  <span m=''3153150''>this</span> <span m=''3153490''>divide</span> <span m=''3153880''>and</span>
  <span m=''3154010''>conquer</span> <span m=''3154670''>kind</span> <span m=''3154880''>of</span>
  <span m=''3154960''>the</span> <span m=''3155060''>world.</span> <span m=''3155930''>And</span>
  <span m=''3156100''>if</span> <span m=''3156180''>you</span> <span m=''3156380''>have</span>
  <span m=''3156660''>trouble</span> <span m=''3157070''>expressing</span> <span m=''3157630''>that--</span>
  <span m=''3160730''>situations</span> <span m=''3161270''>where</span> <span m=''3161390''>you''re</span>
  <span m=''3161960''>doing</span> <span m=''3162070''>Jacobi</span> <span m=''3162720''>update</span>
  <span m=''3163300''>and you</span> <span m=''3163640''>very</span> <span m=''3163900''>carefully</span>
  <span m=''3164400''>put</span> <span m=''3164680''>things</span> <span m=''3165240''>on,</span>
  <span m=''3166540''>had</span> <span m=''3166780''>each</span> <span m=''3166980''>processor</span>
  <span m=''3167500''>work</span> <span m=''3167750''>on</span> <span m=''3167880''>its</span>
  <span m=''3168010''>local</span> <span m=''3168360''>memory</span> <span m=''3168780''>and</span>
  <span m=''3168900''>then</span> <span m=''3168970''>they</span> <span m=''3169060''>only</span>
  <span m=''3169210''>have</span> <span m=''3169350''>to</span> <span m=''3169430''>communicate</span>
  <span m=''3169680''>at</span> <span m=''3169930''>the</span> <span m=''3170180''>boundaries.</span>
  <span m=''3171250''>That''s</span> <span m=''3171660''>difficult</span> <span m=''3172200''>to</span>
  <span m=''3172320''>do</span> <span m=''3172440''>right</span> <span m=''3172710''>in
  Cilk</span> <span m=''3173190''>because</span> <span m=''3174290''>essentially</span>
  <span m=''3174660''>every</span> <span m=''3174840''>time</span> <span m=''3175070''>you</span>
  <span m=''3175190''>go</span> <span m=''3175320''>around</span> <span m=''3175570''>the</span>
  <span m=''3175630''>loop</span> <span m=''3175880''>of</span> <span m=''3176380''>I</span>
  <span m=''3176515''>have</span> <span m=''3176650''>all</span> <span m=''3176810''>these</span>
  <span m=''3176960''>things</span> <span m=''3177190''>to</span> <span m=''3177290''>do.</span>
  <span m=''3177420''>All</span> <span m=''3177580''>the</span> <span m=''3177670''>work-stealing</span>
  <span m=''3178220''>happens</span> <span m=''3178560''>randomly</span> <span m=''3179070''>and</span>
  <span m=''3179190''>it</span> <span m=''3179250''>happens</span> <span m=''3179540''>on</span>
  <span m=''3179640''>a</span> <span m=''3179700''>different</span> <span m=''3179970''>processor.</span>
  <span m=''3180520''>So</span> <span m=''3180690''>it''s</span> <span m=''3180850''>not</span>
  <span m=''3181250''>very</span> <span m=''3181460''>good</span> <span m=''3181650''>at</span>
  <span m=''3181740''>that</span> <span m=''3181990''>sort</span> <span m=''3182210''>of</span>
  <span m=''3182770''>thing,</span> <span m=''3183030''>although</span> <span m=''3183250''>it</span>
  <span m=''3183350''>turns</span> <span m=''3183610''>out</span> <span m=''3183780''>Jacobi</span>
  <span m=''3184170''>update''s</span> <span m=''3184520''>not</span> <span m=''3184690''>a</span>
  <span m=''3184720''>very</span> <span m=''3184870''>good</span> <span m=''3185020''>example</span>
  <span m=''3185460''>for</span> <span m=''3185700''>that</span> <span m=''3185920''>because</span>
  <span m=''3186630''>there</span> <span m=''3186860''>are</span> <span m=''3187180''>more</span>
  <span m=''3187460''>sophisticated</span> <span m=''3188160''>algorithms</span> <span
  m=''3188700''>that</span> <span m=''3188790''>use</span> <span m=''3188990''>cache</span>
  <span m=''3189360''>effectively</span> <span m=''3190580''>that</span> <span m=''3190750''>you</span>
  <span m=''3190860''>can</span> <span m=''3191020''>express</span> <span m=''3191420''>in
  Cilk</span> <span m=''3191860''>and</span> <span m=''3191960''>I</span> <span m=''3192230''>would</span>
  <span m=''3192440''>have</span> <span m=''3192540''>no</span> <span m=''3192670''>idea</span>
  <span m=''3192990''>how</span> <span m=''3193110''>to</span> <span m=''3193800''>no</span>
  <span m=''3194050''>say</span> <span m=''3194290''>those</span> <span m=''3194630''>in
  some</span> <span m=''3194810''>of</span> <span m=''3194880''>these</span> <span
  m=''3195020''>sort</span> <span m=''3195210''>of</span> <span m=''3195300''>data</span>
  <span m=''3195570''>parallel</span> <span m=''3196000''>languages.</span> <span
  m=''3196870''>Using</span> <span m=''3197210''>the</span> <span m=''3197290''>cache</span>
  <span m=''3197640''>efficiently</span> <span m=''3198190''>is</span> <span m=''3198330''>really</span>
  <span m=''3199220''>important</span> <span m=''3200160''>on</span> <span m=''3200760''>modern</span>
  <span m=''3201010''>processors.</span> </p><p><span m=''3203481''>PROFESSOR: Thank</span>
  <span m=''3203989''>you.</span> <span m=''3207543''>Questions?</span> </p><p><span
  m=''3213130''>BRADLEY KUSZMAUL: You</span> <span m=''3213240''>can</span> <span
  m=''3213370''>download</span> <span m=''3213800''>Cilk,</span> <span m=''3214400''>there''s</span>
  <span m=''3214520''>a</span> <span m=''3214640''>bunch of</span> <span m=''3214760''>contributors.</span>
  <span m=''3215360''>Those</span> <span m=''3215540''>are</span> <span m=''3215610''>the</span>
  <span m=''3215700''>Cilk</span> <span m=''3216120''>worms</span> <span m=''3217340''>and</span>
  <span m=''3217800''>you</span> <span m=''3217950''>can</span> <span m=''3218060''>download</span>
  <span m=''3218490''>Cilk</span> <span m=''3218740''>off</span> <span m=''3218890''>our</span>
  <span m=''3218990''>webpage.</span> <span m=''3219620''>Just</span> <span m=''3219810''>Google</span>
  <span m=''3220100''>for</span> <span m=''3220220''>Cilk</span> <span m=''3220430''>and</span>
  <span m=''3221050''>you''ll</span> <span m=''3221276''>find</span> <span m=''3221503''>it.</span>
  <span m=''3221730''>It''s</span> <span m=''3221880''>a</span> <span m=''3221940''>great</span>
  <span m=''3222240''>language,</span> <span m=''3222700''>you''ll</span> <span m=''3223160''>love</span>
  <span m=''3223620''>it.</span> <span m=''3224540''>You''ll</span> <span m=''3224670''>love</span>
  <span m=''3224800''>it</span> <span m=''3224930''>much</span> <span m=''3225150''>more</span>
  <span m=''3225350''>than</span> <span m=''3226050''>what</span> <span m=''3226300''>you''ve</span>
  <span m=''3226430''>been</span> <span m=''3226560''>doing.</span> </p><p><span m=''3227115''>AUDIENCE:
  How</span> <span m=''3227253''>does</span> <span m=''3227392''>the</span> <span
  m=''3227531''>Cilk</span> <span m=''3227670''>play</span> <span m=''3227860''>with</span>
  <span m=''3228050''>processor</span> <span m=''3228534''>[OBSCURED]?</span> </p><p><span
  m=''3234350''>BRADLEY KUSZMAUL: Well,</span> <span m=''3235040''>you</span> <span
  m=''3235380''>have</span> <span m=''3235600''>to</span> <span m=''3235670''>have</span>
  <span m=''3235810''>a</span> <span m=''3235860''>language,</span> <span m=''3236440''>a</span>
  <span m=''3237420''>compiler</span> <span m=''3237980''>that can</span> <span m=''3238070''>generate</span>
  <span m=''3238570''>those.</span> <span m=''3238820''>If</span> <span m=''3239060''>you</span>
  <span m=''3239170''>have</span> <span m=''3239370''>an</span> <span m=''3239830''>assembly</span>
  <span m=''3241010''>command</span> <span m=''3241600''>or you</span> <span m=''3241690''>have</span>
  <span m=''3242020''>some</span> <span m=''3242350''>other</span> <span m=''3242482''>complier</span>
  <span m=''3242615''>that</span> <span m=''3242747''>can</span> <span m=''3242880''>generate</span>
  <span m=''3243485''>those.</span> <span m=''3244090''>So</span> <span m=''3244830''>I</span>
  <span m=''3244950''>just</span> <span m=''3245500''>won</span> <span m=''3246230''>the</span>
  <span m=''3247620''>HPC</span> <span m=''3248380''>challenge,</span> <span m=''3248890''>which</span>
  <span m=''3249070''>is</span> <span m=''3249980''>this</span> <span m=''3250130''>challenge</span>
  <span m=''3250580''>where</span> <span m=''3250730''>everybody</span> <span m=''3251810''>tries</span>
  <span m=''3252110''>to</span> <span m=''3252210''>run</span> <span m=''3254750''>parallel</span>
  <span m=''3255120''>programs</span> <span m=''3256070''>and</span> <span m=''3256220''>argue</span>
  <span m=''3256370''>that</span> <span m=''3256530''>they get</span> <span m=''3256760''>productivity.</span>
  <span m=''3258620''>For</span> <span m=''3258840''>that</span> <span m=''3259260''>there</span>
  <span m=''3259400''>were</span> <span m=''3259490''>some</span> <span m=''3259790''>codes</span>
  <span m=''3260120''>like</span> <span m=''3260310''>matrix</span> <span m=''3260690''>multiply
  and</span> <span m=''3261400''>LUD</span> <span m=''3261870''>composition</span>
  <span m=''3262530''>with</span> <span m=''3263080''>pivoting.</span> <span m=''3264020''>Basically</span>
  <span m=''3264570''>at</span> <span m=''3264615''>the</span> <span m=''3264660''>leads</span>
  <span m=''3265230''>of the</span> <span m=''3265910''>computation</span> <span m=''3265980''>I</span>
  <span m=''3266050''>call</span> <span m=''3266590''>the</span> <span m=''3266740''>Intel</span>
  <span m=''3266910''>Math</span> <span m=''3267010''>Kernel</span> <span m=''3267440''>Library.</span>
  <span m=''3267960''>Which</span> <span m=''3268180''>in</span> <span m=''3268300''>turn</span>
  <span m=''3268800''>uses</span> <span m=''3269270''>the</span> <span m=''3269560''>SSE</span>
  <span m=''3269830''>instructions.</span> <span m=''3272190''>You</span> <span m=''3272310''>could</span>
  <span m=''3272420''>do</span> <span m=''3272520''>anything</span> <span m=''3272830''>you</span>
  <span m=''3272940''>can</span> <span m=''3273090''>do</span> <span m=''3273240''>in</span>
  <span m=''3273420''>C</span> <span m=''3275000''>in</span> <span m=''3275160''>the</span>
  <span m=''3275260''>C</span> <span m=''3275510''>parts</span> <span m=''3275626''>of</span>
  <span m=''3275743''>the</span> <span m=''3275860''>code</span> <span m=''3276300''>because</span>
  <span m=''3277070''>Cilk</span> <span m=''3277520''>compiler</span> <span m=''3277830''>just</span>
  <span m=''3278010''>passes those</span> <span m=''3278640''>through.</span> <span
  m=''3279940''>So</span> <span m=''3280120''>if</span> <span m=''3280260''>you</span>
  <span m=''3280370''>have</span> <span m=''3280620''>some</span> <span m=''3280910''>really</span>
  <span m=''3281200''>efficient</span> <span m=''3281730''>pipeline</span> <span m=''3282120''>code</span>
  <span m=''3283020''>for</span> <span m=''3283140''>doing</span> <span m=''3283460''>something,</span>
  <span m=''3285690''>up</span> <span m=''3285850''>to</span> <span m=''3285960''>some</span>
  <span m=''3286170''>point</span> <span m=''3286470''>it</span> <span m=''3286540''>made</span>
  <span m=''3287530''>sense</span> <span m=''3287740''>to</span> <span m=''3287830''>use</span>
  <span m=''3288070''>that.</span> </p><p><span m=''3288680''>AUDIENCE: [OBSCURED]</span>
  </p><p><span m=''3292620''>BRADLEY KUSZMAUL: So</span> <span m=''3292880''>I</span>
  <span m=''3293050''>ran</span> <span m=''3293670''>it</span> <span m=''3293950''>on</span>
  <span m=''3294590''>NASIS</span> <span m=''3295250''>Columbia.</span> <span m=''3298460''>So</span>
  <span m=''3298640''>the</span> <span m=''3298790''>benchmark</span> <span m=''3299270''>consists</span>
  <span m=''3299810''>of--</span> <span m=''3300680''>well,</span> <span m=''3300880''>there''s</span>
  <span m=''3301270''>7</span> <span m=''3301690''>applications</span> <span m=''3302420''>they</span>
  <span m=''3302560''>have.</span> <span m=''3302880''>6</span> <span m=''3303260''>of</span>
  <span m=''3303370''>which are</span> <span m=''3303490''>actually</span> <span m=''3303960''>well-defined.</span>
  <span m=''3304560''>One</span> <span m=''3304710''>of</span> <span m=''3304915''>them</span>
  <span m=''3305120''>is</span> <span m=''3305496''>this</span> <span m=''3305873''>thing</span>
  <span m=''3306250''>that</span> <span m=''3306520''>just</span> <span m=''3306790''>measures</span>
  <span m=''3307010''>network</span> <span m=''3307065''>performance</span> <span
  m=''3307120''>or</span> <span m=''3307175''>something,</span> <span m=''3307230''>so
  it</span> <span m=''3307310''>doesn''t</span> <span m=''3307540''>have</span> <span
  m=''3307660''>any</span> <span m=''3307800''>real</span> <span m=''3308990''>semantics.</span>
  <span m=''3309190''>There''s 6</span> <span m=''3309470''>benchmarks.</span> <span
  m=''3310020''>One</span> <span m=''3310160''>of</span> <span m=''3310250''>them</span>
  <span m=''3310370''>is</span> <span m=''3310510''>LUD</span> <span m=''3310800''>composition,</span>
  <span m=''3312170''>one</span> <span m=''3312330''>of</span> <span m=''3312420''>them</span>
  <span m=''3313010''>is</span> <span m=''3313220''>DJEM</span> <span m=''3313720''>matrix</span>
  <span m=''3314060''>multiplication</span> <span m=''3315520''>and</span> <span m=''3316190''>this</span>
  <span m=''3316550''>FFT</span> <span m=''3316820''>and</span> <span m=''3317170''>3</span>
  <span m=''3317380''>others.</span> <span m=''3318110''>So</span> <span m=''3318450''>I</span>
  <span m=''3318600''>implemented</span> <span m=''3319040''>all</span> <span m=''3319290''>6,</span>
  <span m=''3319620''>nobody</span> <span m=''3319950''>else</span> <span m=''3320140''>implemented</span>
  <span m=''3320540''>all</span> <span m=''3320730''>6.</span> <span m=''3321030''>It</span>
  <span m=''3321110''>turns</span> <span m=''3321370''>out</span> <span m=''3321620''>that</span>
  <span m=''3321740''>you had</span> <span m=''3321940''>to</span> <span m=''3322250''>implement</span>
  <span m=''3322360''>3</span> <span m=''3322770''>in</span> <span m=''3322840''>order</span>
  <span m=''3323050''>to</span> <span m=''3323160''>enter.</span> <span m=''3324310''>Almost</span>
  <span m=''3324670''>everybody</span> <span m=''3325680''>implemented</span> <span
  m=''3326130''>3</span> <span m=''3326390''>or</span> <span m=''3326480''>4,</span>
  <span m=''3326740''>but</span> <span m=''3327000''>I</span> <span m=''3327170''>did</span>
  <span m=''3327340''>all</span> <span m=''3327530''>6</span> <span m=''3327840''>which</span>
  <span m=''3327915''>is</span> <span m=''3327990''>part</span> <span m=''3328270''>of</span>
  <span m=''3328340''>why</span> <span m=''3328540''>I</span> <span m=''3328600''>won.</span>
  <span m=''3329540''>So</span> <span m=''3329630''>I</span> <span m=''3329680''>could</span>
  <span m=''3329830''>argue</span> <span m=''3330200''>that</span> <span m=''3330820''>in</span>
  <span m=''3331740''>a</span> <span m=''3332530''>weeks</span> <span m=''3332850''>work</span>
  <span m=''3333130''>I</span> <span m=''3333190''>just</span> <span m=''3333390''>implemented--</span>
  </p><p><span m=''3333820''>AUDIENCE: What is</span> <span m=''3334365''>[OBSCURED]?</span>
  </p><p><span m=''3337510''>BRADLEY KUSZMAUL: So</span> <span m=''3338070''>the</span>
  <span m=''3338310''>prize</span> <span m=''3338660''>has</span> <span m=''3339040''>two</span>
  <span m=''3339230''>components.</span> <span m=''3340280''>Performance</span> <span
  m=''3340940''>and</span> <span m=''3341100''>productivity</span> <span m=''3341940''>or</span>
  <span m=''3342410''>elegance</span> <span m=''3342880''>or</span> <span m=''3342990''>something</span>
  <span m=''3343450''>and</span> <span m=''3343860''>it''s</span> <span m=''3344310''>completely</span>
  <span m=''3344760''>whatever</span> <span m=''3344985''>the</span> <span m=''3345210''>judges</span>
  <span m=''3345620''>want</span> <span m=''3346070''>that</span> <span m=''3346230''>to
  be.</span> <span m=''3347370''>So</span> <span m=''3348040''>it was</span> <span
  m=''3348270''>up</span> <span m=''3348480''>to</span> <span m=''3348580''>me</span>
  <span m=''3348870''>as</span> <span m=''3348935''>a</span> <span m=''3349000''>presenter</span>
  <span m=''3349890''>to</span> <span m=''3350020''>make</span> <span m=''3350250''>the</span>
  <span m=''3350330''>case</span> <span m=''3350800''>that</span> <span m=''3351080''>I</span>
  <span m=''3351210''>was</span> <span m=''3351390''>elegant.</span> <span m=''3351780''>Because</span>
  <span m=''3352180''>I</span> <span m=''3352210''>had</span> <span m=''3352370''>my</span>
  <span m=''3352470''>performance</span> <span m=''3353050''>numbers,</span> <span
  m=''3353950''>which</span> <span m=''3354150''>were</span> <span m=''3354290''>pretty</span>
  <span m=''3354550''>good</span> <span m=''3355420''>and</span> <span m=''3355800''>it</span>
  <span m=''3355860''>turned</span> <span m=''3356030''>out</span> <span m=''3356160''>that</span>
  <span m=''3356280''>the</span> <span m=''3356390''>IBM</span> <span m=''3356620''>entry</span>
  <span m=''3356990''>for</span> <span m=''3357270''>x10</span> <span m=''3357980''>did</span>
  <span m=''3358130''>me more</span> <span m=''3358360''>good</span> <span m=''3358460''>than</span>
  <span m=''3358720''>I</span> <span m=''3358860''>did,</span> <span m=''3359050''>I</span>
  <span m=''3359140''>think.</span> <span m=''3359360''>Because</span> <span m=''3359590''>they</span>
  <span m=''3359750''>got</span> <span m=''3359970''>up</span> <span m=''3360110''>there</span>
  <span m=''3360600''>and</span> <span m=''3360770''>they</span> <span m=''3360960''>compared</span>
  <span m=''3361440''>the</span> <span m=''3361890''>performance</span> <span m=''3361960''>of</span>
  <span m=''3362240''>x10</span> <span m=''3362820''>to</span> <span m=''3362970''>their</span>
  <span m=''3363230''>Cilk</span> <span m=''3363460''>implementation</span> <span
  m=''3364480''>and</span> <span m=''3364650''>their</span> <span m=''3364770''>x10</span>
  <span m=''3365330''>thing was</span> <span m=''3365500''>almost</span> <span m=''3365850''>as</span>
  <span m=''3365930''>good</span> <span m=''3366070''>as</span> <span m=''3366210''>Cilk.</span>
  <span m=''3367650''>So</span> <span m=''3368610''>after</span> <span m=''3368820''>that</span>
  <span m=''3369050''>I</span> <span m=''3369100''>think</span> <span m=''3369300''>the</span>
  <span m=''3369370''>judges</span> <span m=''3369720''>said</span> <span m=''3369870''>they</span>
  <span m=''3369960''>had</span> <span m=''3370120''>to</span> <span m=''3370210''>give</span>
  <span m=''3370380''>me</span> <span m=''3370550''>the</span> <span m=''3370660''>prize.</span>
  <span m=''3372310''>So</span> <span m=''3372660''>basically,</span> <span m=''3373280''>it
  went</span> <span m=''3373490''>down</span> <span m=''3373700''>to</span> <span
  m=''3373790''>supercomputing</span> <span m=''3374550''>and</span> <span m=''3374810''>each</span>
  <span m=''3374990''>of</span> <span m=''3375110''>us</span> <span m=''3375230''>got</span>
  <span m=''3375410''>5</span> <span m=''3375690''>minutes</span> <span m=''3375860''>to</span>
  <span m=''3376030''>present</span> <span m=''3376700''>and</span> <span m=''3377220''>there</span>
  <span m=''3377310''>were</span> <span m=''3377390''>5</span> <span m=''3378220''>finalists.</span>
  <span m=''3380680''>We</span> <span m=''3380770''>did</span> <span m=''3380910''>our</span>
  <span m=''3381000''>presentation</span> <span m=''3381730''>and</span> <span m=''3381860''>then</span>
  <span m=''3381960''>they</span> <span m=''3382050''>gave</span> <span m=''3382260''>out</span>
  <span m=''3382520''>the --</span> <span m=''3382840''>So</span> <span m=''3383200''>they</span>
  <span m=''3387240''>divided</span> <span m=''3387560''>the</span> <span m=''3387640''>prize</span>
  <span m=''3387990''>three</span> <span m=''3388160''>ways:</span> <span m=''3388470''>the</span>
  <span m=''3388560''>people</span> <span m=''3388810''>who got</span> <span m=''3388970''>the</span>
  <span m=''3389050''>absolute</span> <span m=''3389540''>best</span> <span m=''3389820''>performance,</span>
  <span m=''3390800''>which</span> <span m=''3390940''>were</span> <span m=''3391060''>some</span>
  <span m=''3391220''>people</span> <span m=''3391450''>running</span> <span m=''3391650''>UPC</span>
  <span m=''3393120''>and</span> <span m=''3393260''>the</span> <span m=''3393330''>people</span>
  <span m=''3393660''>who</span> <span m=''3393810''>had</span> <span m=''3394520''>the</span>
  <span m=''3394620''>most</span> <span m=''3394970''>elegance</span> <span m=''3395930''>based</span>
  <span m=''3396310''>on</span> <span m=''3396550''>minimal</span> <span m=''3396950''>number</span>
  <span m=''3397230''>of</span> <span m=''3397340''>lines</span> <span m=''3397530''>of</span>
  <span m=''3397670''>codes</span> <span m=''3398100''>and</span> <span m=''3398200''>that</span>
  <span m=''3398330''>was</span> <span m=''3398470''>Cleve</span> <span m=''3400030''>at
  --</span> <span m=''3400630''>what''s</span> <span m=''3400800''>his</span> <span
  m=''3400950''>name?</span> <span m=''3401140''>The</span> <span m=''3401230''>Mathworks</span>
  <span m=''3401740''>guy,</span> <span m=''3402120''>MATLAB</span> <span m=''3402660''>guy.</span>
  <span m=''3403100''>Who said,</span> <span m=''3403360''>look,</span> <span m=''3403780''>matrix,</span>
  <span m=''3404480''>LUD</span> <span m=''3404910''>composition.</span> <span m=''3405880''>LU</span>
  <span m=''3406070''>of P.</span> <span m=''3408100''>It''s</span> <span m=''3408630''>very</span>
  <span m=''3408920''>elegant,</span> <span m=''3409380''>but</span> <span m=''3409490''>I</span>
  <span m=''3409550''>don''t</span> <span m=''3409740''>think</span> <span m=''3409920''>that</span>
  <span m=''3410030''>it</span> <span m=''3410110''>really</span> <span m=''3411650''>sort</span>
  <span m=''3411940''>of</span> <span m=''3412320''>explains</span> <span m=''3412780''>what</span>
  <span m=''3412920''>you</span> <span m=''3413000''>have</span> <span m=''3413090''>to</span>
  <span m=''3413180''>do</span> <span m=''3413280''>to</span> <span m=''3413380''>solve</span>
  <span m=''3413650''>the</span> <span m=''3413720''>problems.</span> <span m=''3415540''>So</span>
  <span m=''3415660''>he</span> <span m=''3415790''>won</span> <span m=''3415980''>the</span>
  <span m=''3416070''>prize</span> <span m=''3416450''>for</span> <span m=''3416730''>most</span>
  <span m=''3417120''>elegant</span> <span m=''3417560''>and</span> <span m=''3417650''>I</span>
  <span m=''3417720''>got</span> <span m=''3417980''>the</span> <span m=''3418250''>prize</span>
  <span m=''3418720''>for</span> <span m=''3418950''>best</span> <span m=''3419310''>combination,</span>
  <span m=''3420130''>which</span> <span m=''3420330''>they</span> <span m=''3420490''>then</span>
  <span m=''3420730''>changed--</span> <span m=''3422040''>in</span> <span m=''3422180''>the</span>
  <span m=''3422750''>final</span> <span m=''3423090''>citation</span> <span m=''3424060''>for</span>
  <span m=''3424190''>the</span> <span m=''3424280''>prize</span> <span m=''3424630''>they</span>
  <span m=''3424740''>said,</span> <span m=''3425430''>most</span> <span m=''3426560''>productivity.</span>
  <span m=''3427410''>That</span> <span m=''3427570''>was</span> <span m=''3428000''>the</span>
  <span m=''3428100''>prize.</span> <span m=''3428390''>So</span> <span m=''3428490''>I</span>
  <span m=''3428560''>actually</span> <span m=''3428820''>won</span> <span m=''3429070''>the</span>
  <span m=''3429150''>contest</span> <span m=''3429700''>because</span> <span m=''3429910''>that</span>
  <span m=''3430080''>was</span> <span m=''3430220''>what</span> <span m=''3430370''>the</span>
  <span m=''3430450''>contest</span> <span m=''3430860''>was</span> <span m=''3430970''>supposed</span>
  <span m=''3431320''>to</span> <span m=''3431390''>be</span> <span m=''3431570''>was</span>
  <span m=''3431750''>most</span> <span m=''3431980''>productivity.</span> <span m=''3433040''>But</span>
  <span m=''3433210''>I</span> <span m=''3433240''>only</span> <span m=''3433420''>won</span>
  <span m=''3433570''>1/3</span> <span m=''3433860''>of</span> <span m=''3433930''>the</span>
  <span m=''3434000''>prize</span> <span m=''3434310''>money</span> <span m=''3434500''>because</span>
  <span m=''3434690''>they</span> <span m=''3434880''>divided</span> <span m=''3435390''>it</span>
  <span m=''3435450''>three ways.</span> </p><p><span m=''3439236''>PROFESSOR: Any</span>
  <span m=''3439728''>other</span> <span m=''3440220''>question?</span> <span m=''3442682''>Thank</span>
  <span m=''3443174''>you.</span> </p><p><span m=''3444651''>BRADLEY KUSZMAUL: Thank</span>
  <span m=''3445143''>you.</span> </p><p><span m=''3446620''>PROFESSOR: We''ll</span>
  <span m=''3447113''>take a</span> <span m=''3447605''>5 minute</span> <span m=''3448097''>break</span>
  <span m=''3448590''>and</span> <span m=''3449580''>since</span> <span m=''3450084''>you
  had</span> <span m=''3450589''>guest</span> <span m=''3451094''>lecturer</span>
  <span m=''3451598''>I</span> <span m=''3452103''>do</span> <span m=''3452608''>have</span>
  <span m=''3453112''>[OBSCURED]</span> </p>'
type: course
uid: 2edc2cbc9083e459e08f8478bb72036d

---
None