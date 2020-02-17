#Ranking criteria(랭크 기준)

*모드별 랭크 기준을 보고 싶으시다면 : [osu!](/wiki/rc_osu!), [osu!taiko](/wiki/rc_osu!taiko), [osu!catch](/wiki/rc_osu!catch), [osu!mania](/wiki/rc_osu!mania) 를 참조해주십시오.*

현재 논의중에 있는 규칙은 [토론 포럼(Discussion forum)](https://osu.ppy.sh/community/forums/87)에서 논의되고 있으며, 해당 토론이 합의에 도달한 경우에 변경사항이 이곳에 갱신됩니다.

**[Code of Conduct(행동강령)](/wiki/Code_of_Conduct), [Timing Songs With #/8th-Signatures(#8박자 용법을 활용하여 노래의 타이밍을 잡는법)](/wiki/Ranking_Criteria/Timing_Songs_With_8-Signatures), [Song Content Rules(노래 컨텐츠 규칙)](/wiki/Ranking_Criteria/Song_Content_Rules) 또한 osu!의 모든 게임모드에 적용된다는것을 명심하십시오.**

##Glossary(용어 사전)

###General terms(일반 용어)

- **Rules(규칙):** 모든 규칙들은 문자 그대로 **규칙입니다**. 이것들은 가이드라인이 **아니며**, **어떠한** 상황에서도 어기실 수 **없습니다**.
- **Guidelines(가이드라인):** 가이드라인은 특별히 **예외적인** 상황에서라면 어기실 수 있습니다. 이러한 예외적인 상황은, 왜 가이드 라인을 무시하는것이 퀄리티에 더 좋은 영향을 주는지 자세히 설명되어야 합니다.

## General(일반적인 것)

### Rules(규칙)

- **어떠한 히트 오브젝트도 같은 틱에 2개 이상 놓일수 없습니다.** 이것은 히트 서클, 슬라이더의 시작지점과 끝나는 지점, 스피너가 시작하는 지점과 끝나는 지점에도 포함되는 규칙입니다. osu!mania 모드의 비트맵은 예외입니다.
- **배경/스토리보드/비디오 컨텐츠에는 음란한 이미지가 없어야 합니다.** 여기에는 나체, 준-나체, 성적 언급, 폭력, 약물 남용등이 포함됩니다. 이에 관해서 더 자세한 규칙을 알고 싶으시다면 [Visual Content Considerations(시각적 콘텐츠 고려 사항)](/wiki/Rules/Visual_Content_Considerations) 을 참조하십시오.
- **스토리보드 또는 비디오에 반복적인 반짝임, 요동치는 이미지, 대비/밝기/색상의 급격한 변화가 있을 경우, 해당 비트맵에는 (Epilepsy warning)간질경고를 사용해야 합니다.** 해당 경고가 게임플레이를 방해할 경우, Audio lead-in(오디오 리드-인)을 더 길게 만들어야 합니다. 3Hz 이하의 스트로빙 효과는 문제를 일으킬 가능성이 없습니다. 확실하지 않은 경우에는 간질경고를 추가하고 모딩중에 해당 경고가 필요한지 확인해 주십시오.
- **비트맵에 사용되지 않은 파일이나 0 바이트 용량인 파일이 있어서는 안됩니다..** 0 바이트 파일은 비트 맵 폴더의 다른 파일이 제대로 업로드되지 못하게하기 때문입니다. 자동적으로 생성된 `thumbs.db` 파일만이 유일한 예외입니다.
- **각 게임 모드에 의도하지 않은 방식으로 난이도 설정을 수정하거나 브레이크 타임을 삽입하기 위해 `osu` 파일을 편집하지 마십시오.** Stack leniency(스택 리니언시), 슬라이더 속도 및 스킨 설정과 같은 다른 `osu`파일 편집은 허용됩니다.
- `Letterbox during breaks(브레이크 타임간 레터박스)` **는 브레이크 타임과 스토리보드와 게임 모드가 같은 다른 난이도들 사이에서 일관성있게 사용되어야 합니다.**

### Guidelines(가이드라인)

- **다른 랭크맵에 자신의 랭크맵을 직접 재사용하는 것은 권장하지 않습니다.** 이것은 이미 랭크된 컨텐츠의 불필요한 확산을 방지하기 위함입니다.
- **Slider tick rate(슬라이더 틱 레이트)는 `.osu` 파일을 통해 수정하실수 없습니다.** 사용자가 직접 수정하는 경우 대부분의 사용자 정의 값은 스냅되지 않은 슬라이더 틱을 초래하지만, 슬라이더 틱 속도 0.5, 1.333 및 1.5는 실용적으로 사용되며 표준 슬라이더 틱보다 더 적절하게 곡을 표현할 수 있는 경우에만 적용하실수 있습니다.
- **Kiai(키아이)는 노래소리가 들리는곳에서 시작되어야 합니다.** 이렇게 하지 않으면 kiai의 플래시가 노래와 무관하다고 여겨질수 있기 때문입니다.
- `카운트 다운 활성화` **설정은 같은 모드의 다른 난이도들 사이에서 일관성있게 사용되어야 합니다.** 난이도가 카운트다운이 들어갈정도로 충분한 길이의 인트로를 가지고 있지 않은경우, 이 설정은 일관성이 지켜질 필요가 없게 됩니다.

## Beatmapset(비트맵 셋)

### Glossary(용어 해설)

- **Drain time(드레인 타임):** 체력바가 작동된 시간을 말합니다. 브레이크 타임의 시간은 드레인 타임에서 제외됩니다. osu!taiko'모드의 드레인 타임은 슬라이더와 스피너의 최대 길이 또한 포함합니다.
- **Song compilation(음악 모음집):** 음악의 특정 부분만을 모아두었거나 여러 곡의 구간을 하나의 오디오 파일로 모아둔것입니다.
- **Play time(플레이 타임)**: 브레이크 타임의 시간과 체력바가 작동된 시간을 합친 길이입니다.
- **Reasonable spread(합리적 스프레드):** Difficulty-specific rules and guidelines(난이도별 규칙과 가이드라인)에 따라 난이도 레벨을 건너 뛰지 않고 난이도간에 크게 큰 차이가없는 비트맵 셋을 말합니다. 여기에는 난이도가 하나만 존재하는 단일 난이도 비트맵 셋 또한 포함됩니다. 
- **Game mode(게임 모드):** osu!, osu!taiko, osu!catch, osu!mania 의 키 카운트는 각각 다른 게임 모드로 간주합니다.
- **Beatmapset host(비트맵 셋 호스트):** 비트맵 셋을 업로드하고 관리하는 유저를 말합니다.
- **Guest difficulty(게스트 난이도):** 비트맵 셋 주인이 만들지 않고 다른 유저가 참여해 만든 난이도를 말합니다.
- **Collaborative difficulty(콜라보 난이도):** 하나의 난이도에 여러명의 제작자가 참여한 난이도. "collab"(콜랍)이라고도 부릅니다.

### Rules(규칙)

- **비트맵 셋 내의 모든 게임 모드는 노래의 길이에 따라 필요한 가장 낮은 난이도 레벨에서 시작하여 합리적인 스프레드를 형성해야합니다. ** 각 스프레드는 해당 게임 모드의 난이도 별 랭크 기준을 준수해야합니다.
- **비트맵 세트의 모든 난이도는 최소한 30초의 드레인 타임을 가져야 합니다.**
- **만약 각 난이도의 드레인 타임이...**
  - **...3분 30초 미만인 경우, 각 게임 모드의 가장 낮은 난이도는 Normal보다 어려워서는 안됩니다.**
  - **...3분 30초 이상 ~ 4분 15초 미만인 경우, 각 게임 모드의 가장 낮은 난이도는 Hard보다 어려워서는 안됩니다.**
  - **...4분 15초 이상 ~ 5분 00초 미만인 경우, 각 게임 모드의 가장 낮은 난이도는 Insane보다 어려워서는 안됩니다.**
  - **...그 이상의 드레인 타임을 가진 경우, 해당 비트맵 셋은 합리적 스프레드 규칙에 영향을 받지 않습니다.**
  - **가장 높은 난이도보다 낮은 난이도들은 드레인 타임 대신에 플레이 타임을 측정 기준으로 사용할수 있습니다.** 단, 이것은 드레인타임이 30초보다 적은 난이도에는 적용되지 않습니다. 가장 낮은 난이도부터 가장 높은 난이도까지 사용되는 게임 플레이 요소의 적합성에 대한 판단은 해당 게임 모드의 Beatmap Nominators와 Nomination Assessment Team 구성원이 판단합니다.
- **비트맵 셋의 난이도는 다음을 제외하고 각각의 난이도를 명확하고 정확하게 표시되어야 합니다. :**
  - 가장 높은 난이도
  - 가장 높은 난이도와 비슷한 난이도의 경우, Insane 및 Extra 난이도에만 적용됩니다. (예시: ENHIIII 세트의 Insane 난이도 또는 ENHIIXXX 세트의 Extra 난이도)
- **비트맵셋의 사용자 지정 난이도는 노래나 난이도에 관련된 일반적인 주제나 패턴을 따라야 하며, 잘못 해석되어서는 안됩니다.** (예시: "Expert" 수준의 어려움을 가진 난이도를 "Normal" 난이도로 명명함.)
**난이도명은 유저 이름으로 명명될수 없습니다.** 우연히 유저 이름이 노래와 관련되어 있다면 예외로 받아들여질수 있습니다. 
- **비트맵 셋의 호스트의 이름은 난이도명에 포함될 수 없습니다. (예시: 비트맵 셋 호스트 이름's Insane).** 다수의 곡을 닉네임과 동일한 메타데이터로 비트맵화하여 생기거나 콜라보 난이도만이 유일한 예외가 될 수 있습니다. 그러나, 게스트 난이도는 해당 창작자의 사용자 이름이나 유저명으로 난이도 명을 지을수 있습니다.

- **비트맵셋의 주인은 게스트 난이도보다 동일하거나 더 많은 수량의 난이도를 만들어야 합니다.** 이것은 신용이 있어야 할 곳에 신용을 제공하기 위함입니다. 콜라보 난이도는 부분적인것으로 간주되며, 게스트 매퍼가 비트맵셋 호스트보다 더 많은 양을 매핑한경우, 드레인 타임이 비트맵 공헌도를 계산하는데 사용됩니다.
- **A beatmapset host and guest beatmap creators can make changes to their respective difficulties as they wish.** If there is a disagreement between both, the beatmapset host must delete the guest contribution upon request. If a guest beatmap creator cannot be contacted for a month, they will be assumed to agree with any changes.

### Guidelines

- **The highest difficulty of a beatmapset should correspond to the general feel of the song.** Easy/Normal difficulties can be used as a lone difficulty of a beatmapset if their rhythms are not oversimplified. A Hard difficulty or beyond should be included otherwise.
- **Avoid incomprehensible username combinations to indicate possession of a collaborative guest difficulty.** If it's unclear whose usernames are combined, simplification is recommended.
- **Avoid difficulty names with descriptive elements not clearly related to a guest difficulty creator or a level of difficulty.** (e.g. Beatmap Creator's Tragic Love Extra)
- **Usernames indicating possession of a guest difficulty should be consistent between multiple beatmapsets.** Varying nicknames for one user makes interpreting who created a difficulty ambiguous or misleading.
- **Avoid non-alphanumeric unicode characters in a difficulty's name.** These can cause errors with the beatmap submission system and problems for certain users when appearing in chat.

## Metadata

### Glossary

- **Official sources**: Media that the artist or their label provides, such as official websites, CD Scans, or official uploads to websites like Bandcamp, YouTube, or SoundCloud. Third party websites such as wikis, databases (vndb, vgmdb, etc.), or music services (Spotify, iTunes, Amazon, etc.) do not count as official sources.
- **vs.**: versus
- **feat.**: featuring
- **CV**: character voice, usually used to refer to the voice actor of a fictional character.
- **Asterisk**: `*`
- **Umlauts**: `ü`, `ö`, `ä` and `ß`
- **Whitespace**: A visual spacing between characters, not always a literal space. Full-width characters do not require whitespaces.
- **TV Size**: A song where the particular version is used in a television program, web series, or direct-to-video series, such as an opening, ending, or insert song. Fan-made works are not included in this.
- **Modified Hepburn romanisation**: Refer to [this page](https://en.wikipedia.org/wiki/Hepburn_romanization#Features) for information.
- **Character-by-character romanisation**: Each Chinese character must be romanised as a capitalised word and separated with a space.

### Rules

#### Technical

- **Metadata must be consistent across all difficulties of a beatmapset.**
- **Guest mappers, storyboarders, skinners and hitsounders must be added to the tags of a beatmapset.** This is to give credit where credit is due and help others identify the main contributors of any given beatmapset. Usernames containing single characters separated by whitespaces must have the whitespaces replaced with underscores.
- **Official Sources must be used as references for metadata unless none are available.** In that case use what is most common and recognizable.
- **Do not modify the metadata an artist provides on official sources unless said modification is done in order to comply with formatting and standardisation rules on this Ranking Criteria.**
- **The artists of a song must be traceable to existing people.** If there is no existing person recorded to be the artist, then `Unknown Artist` is to be used. Fictional characters or programs like Vocaloids cannot be used as the sole artist of any given song.
- **You must use the Source field if the song comes from or is directly tied to another media such as a video game, movie, series, etc.** Website names, album names, or BMS are not acceptable sources. If the song was featured or tied to a media after it was released, the source field is optional. `osu!` may be used as a source for osu!'s Featured Artist content. If a song has multiple potential sources, any options are valid. For remixes, arrangements, or covers based upon the original song, the source(s) of the original song would apply in the same way.
  - In cases where a Song Compilation/Remix/Medley/etc. has songs without a common source, the sources must be put in the tags instead of the source field.
- **Metadata that exceeds the field's limits (81 characters) must be shortened.** Start by dropping additional markers and if this still is not sufficient, indicate that the title has been shortened using `...` in a sensible place.
- **If the artist or title fields were shortened to fit in field limits, the omitted information must be added to the tags.**
- **If the song mapped is a licensed one in the featured artist library, `featured artist` must be added to tags.**
- **Tags must be related to the beatmap and not misleading for search results.** Tags describing the beatmap's style, song, storyboard, video, or background content are considered to be related to the beatmap.

#### Standardisation

All forms of Artist/Title standardisation apply to both the `Romanised` and `Unicode` fields, excluding standardised whitespaces for full-width characters.

- **Commas, `vs.`, `feat.`, `CV:` and any other symbols linking or designating artists must include a trailing whitespace.** If the marker is preceded by a word, a leading whitespace is also required, unless the marker is a comma.
- **Any form of `vs.`, `Vs.`, `VS`, etc. must be written as `vs.` when it is used as a marker signifying a collaboration between two or more artists.**
- **Any form of `feat.`, `ft.`, `Ft.`, etc. must be written as `feat.` when it is used as a marker signifying an artist featured in the song.**
- **When a fictional character is credited as the singer of a song, the artist field is to be formatted in a `Character (CV: Voice Actor)` format.** For live action, credit the voice actor only.
- **If the song is `TV size`, use a `(TV Size)` marker at the end of the current title string.** If there is an existing `TV size` marker in the title, the `(TV Size)` marker would replace it. Additionally, songs with existing `Short Ver` or `Game Ver` markers in their titles must use `(Short Ver.)` or `(Game Ver.)` markers.
  - Note: If a mapset's song contains matching sections to the `TV size`/`Short Ver`/`Game Ver` song, in the same order, and is roughly the same length as the official cut song, the mapset's edit will also count as a `TV Size`/`Short Ver`/`Game Ver` respectively. Covers and remixes do not count.
- **If a song has been edited to have a higher tempo, use a `(Sped Up Ver.)` marker at the end of the current title string.** If there is an existing `Sped Up Ver` marker in the title, the `(Sped Up Ver.)` marker would replace it. Sped up songs in Techno, Trance, Dance, or other similar genres should use a `(Nightcore Mix)` marker instead.
- **Special unicode characters must be filtered to their nearest standard equivalent or removed from the romanised fields within a `.osu` file.** `★ ☆ ⚝ ✪` and the likes are substituted to an asterisk. Other special characters are to be romanised or dropped on case-by-case basis.
- **If a mapset track is composed of two or more songs, list the song titles clearly with a dividing symbol inbetween or use a title descriptive of its contents.** If the title becomes too long as a result, a descriptive title must be used instead.
- **If a symbol is used to group parts of a title, a whitespace must be used before and after the group, but not directly before or after the symbols within the groups.**
- **If a series applicable as a source contains sub-series, the most precise label must be used as the source.** If a song has multiple applicable sub-series, the main series/franchise may be used instead.

#### Romanisation

- **Artist names are to be romanised in the order they are printed in the unicode fields.**
- **Loan words from other languages have to use the original words in their stead when attempting to romanise them.**
- **When a song uses repeat words in the title or in the artist where one is in unicode, and the other as a basic romanisation, the romanised field must use the provided romanisation only and remove the duplicate word.**
- **Songs with German metadata must romanise umlauts into two-letter equivalents (`ue`, `oe`, `ae` and `ss`).**
- **Songs with Russian/Cyrillic metadata are to be romanised using the BGN/PCGN system method in romanised fields.** The same applies to the Source field if a romanised Source is preferred by the mapper. Е and е should be romanised as `ye` if it stands alone or after `a`, `e`, `ё`, `и`, `о`, `у`, `ы`, `э`, `ю`, `я`, `й`, `ъ`, `ь`. In other cases, it should be romanised as `e`. `ё` should be romanised to `yo`, however, use `o` if the character comes after `ж`, `ч`, `ш`, or `щ`. Ignore any other rules in the file provided, these are either irrelevant or would not help in the game. For most of the other characters, refer to the [first page of this document](https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/807920/ROMANIZATION_OF_RUSSIAN.pdf).
- **Songs with Japanese metadata must use the Modified Hepburn romanisation method in romanised fields.** The same applies to the Source field if a romanised Source is preferred by the mapper. As a non-unicode field, long vowels such as `おう` and `うう` should be romanised into `ou` and `uu` to avoid macrons.
- **Songs with Chinese metadata are to be handled with respect to the tones and dialects of Chinese they belong to using character-by-character romanisation method with the exception of artist names.** In any case, all diacritical tone marks must be omitted:
  - Mandarin metadata must be romanised using the Hanyu Pinyin system.
  - Cantonese metadata must be romanised by using the Jyutping system.
  - If the song falls into neither category, this choice is left up to the mapper's discretion and contacting a native speaker is recommended.

### Guidelines

- **When a song is covered or remixed and has metadata varying from the original song, use common sense to determine whether the variation was a mistake or an intentional artist choice.**

#### Technical

- **If the creator of the mapset has remixed or covered the song, they are free to name it appropriately to signal that this song is a special version.** In this case the original songs should still be clearly indicated in the title or tags in order for players to be able to search for the original songs.
- **In the case of compilations or remixes, the original song title(s) and artist(s) should be included in tags.** This is to ensure that players can find all beatmaps of one song by searching the same thing without getting vastly different results.
- **Songs with metadata that contains ambiguous or hard to write unicode characters should add easily searchable variations or romanisations of these words to the beatmapset's tags.**
- **If the source of the song is available in both unicode and romanised formats, the option not used in the source field should be added to tags**
- **Song genre and language should be added to the tags of a beatmap.** This is to enable users to search using these terms in-game like they do on the website. For instrumental tracks, "instrumental" is considered the language tag. Exceptions would be when language and/or genre are not clear, or multiple apply. In case of the latter, one fitting tag for each may be applied.
- **Additional Tags: It is recommended to include tags such related artists, alternate titles for the song, alternate spellings of an artist name, simplified contractions for words in metadata fields, and whatever may aid a player to find the map.**

#### Standardisation

All forms of Artist/Title standardisation apply to both the `Romanised` and `Unicode` fields, excluding standardised whitespaces for full-width characters.

- **Logos should not be used as references for capitalisation of titles or artists.** Because logos are often stylised, apply standard capitalisation unless other textual metadata supports it.
- **Tracks created by artists belonging to doujin circles should list the circle's name as the main artist.** The exception to this is when the artist(s) of a given track is well-known enough by their own name. In this case, the specific artist name(s) may be used instead.
- **If the same song exists in the Ranked or Loved sections already, the metadata should be followed unless it breaks other rules in the Ranking Criteria or the official sources state something completely different.**
- **Artist names should be consistent between different songs from the same person or group in the Ranked or Loved sections.** This does not apply if the person or group intentionally uses a different alias for different song or album releases.
- **Single symbols should be romanised so that they have leading and trailing whitespaces, unless the symbol itself is not commonly requiring whitespaces in English.** This may be ignored if the artist purposefully uses special characters that ignore their common usages.

### Allowances

This category contains explicit allowance statements of concepts and rules that are not commonly straightforward even after reading this whole section of the Ranking Criteria.

- **For songs where the composer(s) and singer(s) are different people, the singer(s) may be listed after the composer(s) or circle/group name following a `feat.` indicator.**
- **If an artist has provided an official translation for their name, this may be used in the romanised artist field.** Official romanisation may be used for the spelling of an artist's name, but the name order must follow the related rule.
- **If a Unicode Song title has either an official translation or romanisation provided by the artist, either or may be used in the romanised title field.**
- **If a mapset track was contributed to by multiple artists, they may be listed with commas inbetween.** If there are 3 or more contributing artists and they are not part of one officially labelled group, `Various Artists` or other descriptive artist labels may be used instead.
- **For Remixes/Covers, the original artist may be used in the artist field, as long as the title field is modified to clearly show that the song is remixed.** This marker should all be in parentheses and contain the Remix/Cover artist followed by descriptor.

## Timing

### Glossary

- **BPM:** An acronym for `beats per minute` used to determine the tempo of a song.
- **Offset:** The millisecond position when a timing point's BPM correlates to a song.
- **Uninherited timing point:** A point used to change a beatmap's BPM, offset, or time signature. Indicated by a red line in the editor and informally called a `red line`.
- **Inherited timing point:** A point that inherits elements from the previous timing point, and is not used to modify a beatmap's timing. Indicated by a green line in the editor and informally called a `green line`.
- **Single-BPM timing:** Timing which only requires one BPM.
- **Multi-BPM timing:** Timing which changes BPM according to a song's composition without irregularity due to a song's fluctuation.
- **Variable-BPM timing:** Timing which changes BPM irregularly due to a song's fluctuations.

### Rules

- **Uninherited timing points must be used to accurately beatmap the song's time signatures.** If an incorrect time signature lasts for more than one bar, a uninherited timing point must be added on the next downbeat to reset the time signature. For #/4-signatures unsupported by the editor, metronome resets or editing of the `.osu` file are acceptable. For other unsupported time signatures, refer to this [exemplary chart](/wiki/shared/timing/Timing_signature_reference_chart.png), and see [this guide](/wiki/Ranking_Criteria/Timing_Songs_With_8-Signatures) for further information.
- **Beatmaps with Single-BPM and Multi-BPM timing must be perfectly timed.** This means BPM and offset are exactly synchronized with the song.
- **Uninherited timing points must be the same in every difficulty of a beatmapset.** Each point must have the same BPM and offset in each difficulty.
- **There must not be extra uninherited timing points in any difficulty.** These may accidentally affect main-menu pulsing, add unwanted sounds to the Nightcore mod, or cause timing to shift. Acceptable uses include:
  - Aligning beats of the Nightcore mod with the start of musical sections.
  - Accomodating for objects in musical sections requiring unsupported beat snap divisors (e.g. 1/5, 1/7).
- **No two uninherited or two inherited timing points can be placed at the same point.** Having two uninherited or two inherited timing points on top of each other will cause unintended behavior for slider velocity and volume settings.
- **An inherited timing point cannot be placed before the first uninherited timing point.** Without having any settings to inherit, an inherited timing point does not function properly. If you wish to alter hitsounds or slider velocities before the first uninherited timing point, it must be moved back one full measure so that inherited timing points may be used.
- **A beatmap's first uninherited point cannot be used to toggle kiai.** Doing this will cause the kiai to flash before objects appear. An inherited point in the same position as the first uninherited point must be used to toggle kiai instead.
- **Objects must be snapped to timeline ticks according to AiMod.** Objects in a musical section requiring unsupported beat snap divisors (e.g. 1/5, 1/7) can either:
  - Remain unsnapped, as long as they align with the intended beat snap divisor.
  - Be snapped through a temporary change in BPM.
- **An object which is wrongly snapped due to passing through or ending slightly before a new uninherited timing point must have its end snapped within the new timing section.** For spinners and osu!mania long notes, this can be achieved through dragging an object's tail in the timeline. For sliders, this can be achieved through slider velocity manipulation or editing of the .osu file.

### Guidelines

- **Beatmaps with Variable-BPM timing should be timed as accurately as possible without negatively affecting gameplay.** This means that your BPM and offset are mostly synchronized with the song, but can include minor changes to aid intuitive gameplay when necessary. Complex timing during breaks or spinners is optional.

## Audio

### Glossary

- **Active hitsounds:** Hitsounds that reach their peak impact exactly when they are clicked.
- **Passive hitsounds:** Hitsounds that are not designed to match a player's exact clicking, such as ambient sounds.
- **Storyboarded hitsounds:** Hitsounds played through storyboard coding.
- **Cut:** A song file that has had a portion of audio removed to shorten the beatmapset's play time.

### Rules

- **A beatmapset's audio file must use the `.mp3` file format and have an average bit rate no greater than 192kbps.**
- **Acceptable songs with mature lyrics/themes must be marked with an 18+ in the beatmap's description.** This game is for all ages, and so a warning is needed for younger audiences. Some songs, however, are unacceptable for ranking regardless of an 18+ warning. See [song content rules](/wiki/Ranking_Criteria/Song_Content_Rules) for more details.
- **A beatmapset may only contain one song file used by all difficulties.** Multiple song files within a single beatmap set is unsupported and results in unexpected behaviour with preview times, metadata, etc.
- **A song's audio file and hitsound files must be of reasonable quality.** Try to find the highest quality source file available rather than ripping a file from a streaming video website. Songs should be normalized to their original release volumes and should not be encoded to a bit rate higher than their original files.
- **If you do not beatmap the last 20% of your beatmapset's audio file, it must be cut.** The intro time is not included. This does not apply if more than 20% of the outro is occupied by a storyboard/video.
- **Beatmaps must be hitsounded.** Hitnormals give feedback to the player, and additions (whistles, claps, and finishes) accent the most important parts of the music.
  - **For osu!mania beatmapsets containing only difficulties Insane or above, additions are not required.**
- **All clicked objects must have audible active hitsounds or active hitnormal samples.** osu!mania beatmaps are exempt from this because of the mode's rhythm construction.
- **Active hitsounds must use the `.wav` or `.ogg` file formats.** `.mp3` files have slight delays, and therefore are reserved only for longer passive hitsounds, such as ambient noises.
- **Applause files and other passive hitsounds must use the `.mp3` or `.ogg` file formats.** These files usually have long durations and `.wav` files are unnecessarily large in comparison.
- **Active hitsounds cannot have a delay more than 5 milliseconds.** "Delay" accounts for the peak of a sound rather than its introduction. This ensures hitsound feedback is synchronized to a song effectively. The default skin's `normal-hitfinish.wav` has a slight delay, but still can be used as a custom hitsound.
- **Hitsounds must be audible.** Their purpose is to provide feedback, so hitsounds with extremely low volume or samples that blend with a song's samples are unacceptable. Specific game modes list exceptions to this rule on their respective ranking criterias.
- **Preview points must be set and consistent between all difficulties of a beatmapset.** This is used for both the song selection menu and the online thumbnail preview.
- **Every hitsound file must be at least 25ms long.** Shorter files can result in no sound being played in-game.
- **Completely silent hitsounds must use [this 44-byte file](https://up.ppy.sh/files/blank.wav).** Other files have unnecessarily high file sizes and 0-byte files do not function.
- **Storyboarded hitsounds cannot be used as replacements for active hitsounds.** These give an inaccurate form of player feedback. Storyboarded hitsounds in other situations are acceptable, but discouraged. osu!mania is exempt from this rule.

### Guidelines

- **The audio file of a song should not be artificially extended in order to meet a time limitation in the beatmapset section of this criteria.** This can include (but is not limited to) looping sections of the audio file, lowering the BPM of the song or section of the song, or adding small amounts of music to the song without incorporating it throughout the entire song. This does not apply to song compilations or audio files less than the minimum rankable beatmapset length.
- **Song compilations should incorporate 3 or more songs.** Using only 2 songs in a compilation is a lackluster experience for players, and should be broken up into separate beatmapsets. Exceptions can be made for songs that were exclusively released together.
- **Song compilations should be mixed properly and should not include abrupt breaks or long fades between different songs.** The songs used for the compilation should be similar in audio quality, volume and length. This is to ensure compilations achieve the same cohesive gameplay experience as other beatmaps.
- **Cuts should maintain the general impression and intensity of the full song.** Cuts that change the structure of the full song (such as excluding or rearranging a song's intro/verse/chorus/outro) can lead to mispresentation of it and often cause unsatisfying playing experiences. This does not apply to official cuts or recreations of official cuts.

## Video and background

### Rules

- **You must have a background image on every difficulty of your beatmap.** Different background files for different difficulties is acceptable.
- **The following are requirements for background images:**
  - **Minimum width:** 160px
  - **Minimum height:** 120px
  - **Maximum width:** 2560px
  - **Maximum height:** 1440px
  - **Maximum file size:** 2.5MB
- **A video's dimensions must not exceed a width of 1280 and a height of 720 pixels.** Additionally, upscaling lower resolution video to a higher resolution should be avoided. This ensures video files do not become excessively large or resource intensive.
- **A video's offset must be correct if it synchronizes with the song.** An incorrect offset can result in a misleading visual representation of the song. If the same video appears in multiple difficulties, it must always have the same offset(s).
- **A video's audio track must be removed from the video file.** The audio track in video is not used in osu!, so removing it reduces that file size of the beatmap. This includes videos with muted audio tracks.

### Guidelines

- **A beatmap's background image should be of reasonable quality.** Try to find the original source of any image and avoid unnecessary upscaling or file size bloating.

## Skinning

### Glossary

- **Gameplay elements:** Skinning elements which the user interacts with on the playfield or receives feedback from during gameplay, as such elements that show up in breaks are excluded. Gameplay relevant elements are declared as such in the [table listing](/wiki/Ranking_Criteria/Skin_Set_List).
- **Hit burst:** Element that appears after hitting an object, informing the player of how accurately timed their hit is in relation to the song (300/100/50).
- **Complete set:** Complete sets of elements as listed in the overview. A set is complete when all required elements in it are skinned. If an optional element is included, all required elements need to be present, but not other optional elements of the set.
- **User-specific:** A user's personal skin which they set in their options menu.
- **Beatmap-specific:** Consists of skin elements located in the beatmap folder.

### Rules

- **If you are using any elements created by another community member, ask permission beforehand.** Respecting the work of others is paramount and most people will be delighted to have their work featured in your projects! Thus, if you do not know who made the elements you plan on using, you must not use them.
- **Gameplay elements must be visible.** You cannot make any element that will impair the playability of the beatmap invisible as it will make the beatmap unintuitive or even impossible to play (``cursormiddle.png`` is an exception as it affects the behaviour of cursor trail). Elements that are not relevant for gameplay may only be transparent if there is a valid reason for this and the action itself does not impair the usage of interface elements negatively.
- **Skinned elements must be cropped cleanly so they do not have pixelated artifacts around them or half-cropped shadows.**
- **Skinned elements cannot exceed dimensions to the point where they overlap other skin elements which they would not normally overlap in the default skin.** This applies only to the visible parts of an image, which could distort the gameplay experience by visually obstructing normally visible elements.
- **When skinning gameplay elements, complete sets of elements need to be skinned in order to avoid conflicts between user-specific and beatmap-specific skins.** A reference for this can be found on the [Skin Set List](/wiki/Ranking_Criteria/Skin_Set_List). When skinning an element that is marked as optional, you need to include all the required elements of the respective set, but you are free to skip other optional elements unless they are grouped with the element you are skinning. However, if a required skin element in a set would be unused or the default skin is forced, the element is not necessary to include.

### Guidelines

- **Skinned elements should be kept in `.png` format if they utilize transparency.** If they do not use any transparency, they can use whichever format uses the least space and is supported for skinning in osu!.

## Storyboarding

### Glossary

- **Storyboard image:** This refers to the image in the song folder that the storyboard uses.
- **Sprite:** An object in a storyboard representing an image, or a series of images.
- **Time:** A millisecond representation of a timeline position. This representation is seen within the design section of the editor.
- **Command:** These affect a sprite in various ways. Some examples of commands are `Move`, `Scale`, `Fade` and `Rotate`. Each of these have a starttime and endtime.
- **Axis-specific command:** A command which only applies to one specified spatial axis, for example `MoveX` and `MoveY`.
- **Active:** From the first start time to the last end time of commands in the object.
- **Rendered:** Often referring to an on-screen sprite that is not completely faded out.
- **osu!pixel:** The smallest dimension of the design tab. Seen in the top right corner of the editor screen, e.g. `x: 104; y: 88`.

### Rules

- **Storyboarded images must not exceed an area of 17,000,000 pixels to keep loading times of large images within reasonable ranges for most computers to handle.** Additionally you may need to rescale your images accordingly to the internal maximum dimensions of the storyboard editor of 854 x 480 osu!pixels when using them.
- **The beatmap must not throw parsing errors upon loading.** This means the parser cannot read part of the storyboard instructions.
- **The `Widescreen support` setting must be consistent between storyboarded difficulties in a beatmapset,** unless difficulty-specific storyboards are designed for different aspect ratios.

### Guidelines

- **There should be no active sprites and commands after the end of the song.** This is flexible up to a few extra seconds depending on the storyboard effect, but more than that should not be necessary.
- **Consider leaving a one pixel border of transparency around storyboard images of rotated sprites for interpolation to work properly.** osu! does not utilize anti-aliasing around images, and as such this becomes very noticeable if the edges are visible and the sprite is rotated.
- **Avoid any noticeable performance issues as much as possible. Even being optimized, having consistent frame rates is crucial for the playing experience of the beatmap.** Test play the beatmap during the modding process to confirm this.
- **Refrain from usage of storyboard sound samples in ways that are easily confused with hitsounds during gameplay.** This goes against the concept of audible feedback, as the sound samples will play independently of any input from the player.
- **Avoid illogical, conflicting and obsolete commands.** Commands of the same type whose intervals overlap, have their ending time before their start time or are bound to impossible to reach triggers, are either not working as intended or obsolete, and should either be removed or adjusted to work as intended.
- **The `Widescreen support` setting should be turned on if the beatmapset contains a widescreen storyboard.** Alternatively, if the storyboard is designed for 4:3 resolutions, widescreen support should be turned off. This setting will not affect anything within the beatmap without a storyboard being present.
- **Make sure the storyboard is optimized as much as possible,** within practical means.
  - **Avoid having sprites, or the background of the beatmap, completely visually obstructed while rendered.** Fading these out when otherwise not visible is preferable for the sake of performance. To fade out the background of the beatmap, turn the same background image into a sprite, with `Background` or `0` as second parameter, and fade accordingly.
  - **Avoid sprites being partially off-screen or visually obstructed for the entire time they are used.** In these cases the respective parts of the images should be cut unless this is necessary for an effect within the storyboard.
  - **Avoid unnecessary transparency around storyboard images.** For the sake of performance, images should be cropped as much as possible for their desired effects.
  - **Use loops for commands that repeat themselves many times, unless this goes against what is visually intended.** Using the loop command will often reduce the line count considerably, which in turn reduces file size.
  - **Avoid using two axis-specific commands when the same effect can be achieved with one regular command instead.** Using one command instead of two will mean less overall file size.
  - **Use whichever image file format takes up the least file size whilst maintaining reasonable quality.** `.png` format often takes up more file size for larger images due to the lossless compression method, unlike `.jpg`.
  - **Avoid any duplicate image files.** Having two instances of the exact same image adds unnecessary file size.
  - **Refrain from having multiple sprites active while not rendered.** Active sprites will still process commands regardless of whether they are visible or not. Should this be the case for longer periods of time, instantiate new sprites instead, for when visibility is regained.
  - **When using many commands of the same type on a sprite, try leaving at least 16 ms between their start times.** 60 commands per second is often more than enough for any sprite to make smooth transitions on an average setup. This is for the sake of reducing file size and loading times.
  - **Fade out sprites activated from triggers after usage.** Triggers will activate from their first possible command and stay active until the end of the beatmap, which is why fading these out when done is preferable.
