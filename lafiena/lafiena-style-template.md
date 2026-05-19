# 스타일 템플릿 원문

※ 템플릿 선택 규칙은 lafiena-workflow.md 참조

# ⚙️ 스타일 프롬프트 실행 규칙

## 배정 규칙

- 트랙마다 해당 카테고리 내 템플릿 랜덤 1개 선택
- 그루브: Track 01 → #1 고정 / Track 02~13 → 랜덤 (#1 우선 이후 완전 랜덤)
- BPM: 딱 1개 숫자만 (예: 107 — 범위 표기 금지)

## 보컬 질감 배정 규칙

- 트랙마다 랜덤 선택
- 2회 연속 사용 가능 / 3회 연속 사용 금지

## 공통 Exclude

세트1 첫 트랙 출력 전 1회만 출력. 세트1 나머지 + 세트2·3 전체 생략.
[Exclude]

```
synth fill, vocal run, ad-libs, strings, melisma, vibrato, belting, heavy EDM, Urban Pop, City Pop, distortion, pad, dark, melancholic
```

---

## 그루브

※ 그루브 카테고리 선택 시 → 랜덤 1개 선택

### 그루브 공통 규칙

※ 모든 트랙 스타일 프롬프트에 공통 적용하여 사운드 일관성 유지
[프로덕션] production: "clean mix, minimal arrangement, space between elements, wide stereo, high-fidelity"
[사운드 시그니처] money chord (세련된 코드감 확보를 위해 필수 포함)
[단수형 사용] "guitars" 대신 "guitar" 사용 (AI 사운드 뭉침 방지)
[Hook 시작 트랙 전용] 스타일 프롬프트 끝에 추가: starts with bold hook entry, no build-up intro, full energy from bar 1, tight punch

### 그루브 가변 요소 풀 (Variable Element Pools)

※ 트랙 생성 시 마다 아래 리스트에서 하나씩 선택하여 템플릿의 [ ] 섹션에 삽입

- 보컬 성별 [Vocal Gender]: [Male / Female / Duet] (트랙 번호별 고정 규칙 준수)
- 보컬 질감 [Vocal Texture]:
  Gritty Sing-Rap: gritty raspy tone, heavy vocal fry, raw chest texture, loose unpolished delivery, natural phrasing with no affectation
  Dry Talk-Rap
  dry raspy tone, effortless scratchy edge, deadpan rhythmic delivery, casual talk-rap with a trendy nonchalant groove
  Modern Edgy: modern edgy tone, slight gravelly texture, clear but unpolished delivery, melodic sing-rap with playful grit
- 추천 키 풀 [Key Pool]:
  그루브#1 용: G Major, C Major, D Major, A Major
  그루브#2 용: G Major, C Major, E Major, D Major
  그루브#3 용: F Major, Bb Major, C Major, Eb Major

### 그루브#1 (Groovy Pop)

bright groovy pop with hip-hop / R&B influence, [BPM] BPM, [Key Pool], soft electric piano chords with warm sunny bounce, light acoustic guitar strums, live bass with easy groove, crisp rim clicks and light snaps, easy swinging hi-hats, [Vocal Gender], [Vocal Texture], smooth syncopated flow, Money chord, catchy melody, hit song style, trendy vocal, no humming, no filler sounds

### 그루브#2 (Organic Groovy Pop)

genre: "Organic Groovy Pop", mood: "sunny, energetic, refreshing, motivating", tempo: "[BPM] BPM, steady groove, infectious bounce", key: "[Key Pool]", lead: "bright strummed electric guitar, catchy melody", beat: "crisp acoustic drums with steady groove, subtle percussion", vocal: "[Vocal Gender], [Vocal Texture]", production: "dry mix, organic texture, no distortion, high-fidelity"

### 그루브#3 (Jazzy Pop)

genre: "Bright Jazzy Pop, Jazz-Hop", mood: "high-spirited, euphoric, sophisticated", tempo: "[BPM] BPM, rhythmic bounce, steady groove", key: "[Key Pool]", lead: "sparkling Rhodes, jazzy money chord guitar", beat: "crisp funky drums, tight rhythmic bassline", vocal: "[Vocal Gender], [Vocal Texture]", production: "modern polished, minimal arrangement, wide stereo, high-fidelity, space between elements"

---

## 이지팝1

### 이지팝#1-1 (한국적 멜로디 보컬 / 피아노 인트로 강조)

A bright and sophisticated spring-themed contemporary neo-soul pop song with a touch of jazz pop and light city pop influence, around 92 BPM, warm and uplifting, with a clean and polished modern production, The groove should feel laid-back but steady, smooth and motivating, with crisp drums, warm electric bass, sparkling Rhodes electric piano, subtle clean guitar, soft synth textures, and a gentle sense of movement like sunlight filling a city street in early spring, The mood should be hopeful, refreshing, constructive, and emotionally encouraging, Korean vocals, clear melody, memorable chorus, soft but confident vocal tone, natural emotional build, not too dramatic, not too sad, not aggressive

### 이지팝#1-2 (공기반 트렌디 보컬 / 피아노 인트로 강조)

A bright and sophisticated spring-themed contemporary neo-soul pop song with touches of jazz pop and light city pop, around 92 BPM, warm, uplifting, and polished with clean modern production, The groove should feel laid-back yet steady, smooth and motivating, driven by crisp drums, warm electric bass, sparkling Rhodes electric piano, subtle clean guitar, soft synth textures, Use airy, breathy, ultra-refined trendy pop vocals with a soft whispery tone, silky phrasing, intimate delivery, elegant texture, clear melody, memorable chorus, and a soft but confident presence with a natural emotional build, never too dramatic, sad, or aggressive

### 이지팝#1-3 (유니크 사운드 / 미성 남자보컬)

A bright and sophisticated spring-themed contemporary neo-soul pop song with touches of jazz pop and light city pop, around 92 BPM, warm, uplifting, and luxuriously polished with clean modern production. The groove should feel laid-back yet steady, smooth and quietly motivating, driven by crisp drums, warm electric bass, sparkling Rhodes electric piano, subtle clean guitar, soft synth textures. Use airy, breathy, refined male high-register pop vocals with a silky falsetto edge, intimate phrasing, soft emotional restraint, and a premium trendy Vocal Texture. Make the intro unique and instantly recognizable: begin with acoustic guitar only, delicate fingerpicked or lightly strummed, spacious and cinematic, before the full arrangement enters. Add a special intro hook section with airy chorus-like vocal adlibs such as "ah," "woo," "ooh," layered tastefully like a floating pop chant. The opening should feel elegant, expensive, dreamy, and modern.

### 이지팝#1-4 (보컬 즉시 시작 / 가사 맨 앞에 [hook] 필수)

A bright and sophisticated spring-themed contemporary neo-soul pop song with touches of jazz pop and light city pop, around 92 BPM, warm, uplifting, and luxuriously polished with clean modern production. Start with vocals immediately from the very first second, with no instrumental intro, no empty opening, and no slow buildup. Use airy, breathy, refined male high-register trendy pop vocals with a silky falsetto edge, intimate phrasing, soft emotional restraint, stylish detail, and a premium modern Vocal Texture. The arrangement should feel creative and distinctive, with unusual but tasteful pop structuring, strong sectional identity, subtle dropouts, layered adlibs, dynamic transitions, unexpected melodic turns, and a chorus that expands wider and brighter than the verses.

---

## 이지팝2

### 이지팝#2-1 (세련된 보컬 집중)

Create a warm, intimate indie pop / dream pop song with a sophisticated modern pop edge, soft romantic atmosphere, and a delicate sense of everyday magic. A short elegant instrumental opening is allowed, but keep it brief and instantly atmospheric. Use refined, airy, breathy pop vocals with a polished close-mic texture, soft consonants, silky phrasing, emotional nuance, and a stylish half-whispered delivery that feels expensive, contemporary, and effortlessly trendy. The arrangement should feel light, detailed, and luxurious: clean electric guitar with gentle chorus, muted bass, subtle drums, soft synth pads, tiny glockenspiel or bell sparkle, and a dreamy bedroom-pop texture. The melody should be immediately memorable and singable, with a chorus that blooms softly instead of exploding.

### 이지팝#2-2 (남자 공기반 보컬 / 트렌디 유니크)

Create a sleek, trendy pop / dream pop song with a soft feel-good groove and a modern city-romance mood. Use clean electric guitar, glossy synth textures, airy pads, unique ear-catching sound design, warm bass, crisp ratchet-style 808 drums, subtle punchy percussion, and a refined pop bounce. Add a K-pop-inspired section change with a stronger lift in the pre-chorus or bridge. Use an airy, breathy male vocal with intimate phrasing and smooth pop delivery. No EDM drop.

### 이지팝#2-3 (특이한 트렌디 사운드)

major chord, minimal trendy pop style, unique intro, ratchet 808 drum beat

### 이지팝#2-4 (보컬 즉시 시작 / 가사 맨 앞에 [hook] 필수)

A bright and sophisticated spring-themed contemporary neo-soul pop song with touches of jazz pop and light city pop, around 92 BPM, warm, uplifting, and luxuriously polished with clean modern production. Start with vocals immediately from the very first second, with no instrumental intro, no empty opening, and no slow buildup. Use airy, breathy, refined male high-register trendy pop vocals with a silky falsetto edge, intimate phrasing, soft emotional restraint, stylish detail, and a premium modern Vocal Texture. The arrangement should feel creative and distinctive, with unusual but tasteful pop structuring, strong sectional identity, subtle dropouts, layered adlibs, dynamic transitions, and a chorus that expands wider and brighter than the verses.

---

## ※ 시니어팝 — 비활성 / 사용 안 함

### ※ 시니어팝#1 (부드러운 남자보컬 / 포크 발라드) — 비활성

# Create a soft acoustic folk ballad with warm vintage character, gentle melodic songwriting, and a timeless 60s-inspired British folk-pop warmth. Use acoustic guitar as the main instrument, supported by soft piano, light brushed drums, subtle bass, delicate tambourine, and warm analog textures. The vocal should be a mature male singer in his 40s with a warm, lived-in tone, singing very softly and gently with calm restraint. Never shout, never belt, never push the voice. Keep the vocal close, low-intensity, chest-led, and intimate. The mood should be reflective, nostalgic, peaceful, and quietly hopeful.

### ※ 시니어팝#2 (어쿠스틱 기타 단독 반주) — 비활성

# Create a soft acoustic folk ballad with warm vintage character and timeless 60s-inspired British folk-pop warmth. Use only acoustic guitar as the accompaniment — no drums, no percussion, no bass, no piano. Keep the guitar simple and natural with soft fingerpicking or gentle strumming. The vocal should be a mature male singer in his 40s, singing very softly, gently, and intimately. Never shout, never belt, never push the voice. No drums, no percussion, no EDM, no trap, no glossy pop sheen, no dramatic drop.

### ※ 시니어팝#3 (보컬 즉시 시작 / 가사 맨 앞에 [hook] 필수) — 비활성

# Create a soft acoustic folk ballad with warm vintage character and timeless 60s-inspired British folk-pop warmth. Start with the vocal immediately at 0:00 — no intro, no instrumental opening, no ambient buildup. Use only acoustic guitar as the accompaniment — no drums, no percussion, no bass, no piano. The vocal should be a mature male singer in his 40s, singing very softly, gently, and intimately. Never shout, never belt, never push the voice.
