# 해커스토익 실전 1000제 2 — LC 단어 학습

조해나 선생님 · TEST 01~10 · SECTION A~D 각 50개 · 총 2,000개 항목

원본 단어 순서를 유지하면서 토익에서 자주 쓰이는 핵심 뜻, 품사, 짧은 회사·일상생활 예문과 한국어 해석을 추가했습니다. 예문은 학습을 위해 새로 작성했으며 교재 원문 인용이 아닙니다. 다의어는 구분되는 뜻 2~3개를 표시하고, 단일 의미·고정 표현은 뜻을 억지로 늘리지 않았습니다.

## 사용법

index.html에서 TEST를 선택합니다. 전체 200개 또는 A~D를 선택할 수 있습니다. 뜻 오른쪽의 ‘예문·청크’ 열에서 실제 용법을 확인합니다. 예문 앞 숫자는 뜻 번호입니다. 검색, 뜻·해석 가리기, 인쇄를 제공합니다.
랜덤 4지선다 40문항과 주관식 40문항은 제출 후 뜻과 예문을 공개합니다. 같은 표제어가 원본에 반복된 경우 단어장에는 유지하고 퀴즈에서는 한 번만 출제합니다. 주관식은 모범답안과 직접 비교합니다.

## 기존 GitHub 단어장 업데이트 — 아이패드

1. ZIP을 다운로드하고 파일 앱에서 압축을 풉니다.
2. Safari에서 GitHub에 로그인합니다.
3. 기존 `toeic-vocab-test-1000-2` 저장소를 엽니다. 다른 교재 저장소는 선택하지 않습니다.
4. Add file → Upload files → choose your files를 누릅니다.
5. 압축을 푼 폴더 안의 `index.html` + `Test01.html`~`Test10.html`, 총11개 HTML을 선택합니다. ZIP 자체를 올리지 않습니다.
6. 파일 이름을 유지해 같은 이름의 기존 파일을 덮어쓰고 Commit changes로 main에 저장합니다. 새 branch로 올렸다면 main으로 병합합니다.
7. 기존 Pages 설정이 main / (root)이면 자동으로 다시 게시됩니다. 처음 설정하는 경우 Settings → Pages → Source: Deploy from a branch → main → /(root) → Save를 선택합니다.
8. Pages 화면에서 Visit site를 눌러 확인합니다. 주소는 기존 `https://hannahcho0724-tech.github.io/toeic-vocab-test-1000-2/`을 유지합니다.
9. TEST 03·07을 포함해 전체 메뉴와 오른쪽 예문 열을 확인합니다. 예전 화면이 남으면 새로고침하세요.

모든 TEST HTML은 자체적으로 실행되므로 JS 파일을 별도로 업로드하지 않습니다. README.md는 선택적으로 올릴 수 있습니다. `.nojekyll`은 빌드 생략용 빈 파일입니다.

이 패키지를 만드는 과정에서는 기존 온라인 GitHub 사이트를 직접 수정하지 않았습니다. 직접 업로드하면 기존 1000제 2 단어장이 업데이트됩니다.

공식 안내:
https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository
https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## 교재 구분 확인

이 ZIP은 1000제 2 전용입니다. 업로드 대상은 반드시 toeic-vocab-test-1000-2입니다. 1000제 1 저장소에는 올리지 않습니다. 모든 화면의 제목과 상단 표시가 1000제 2인지 확인하세요.
파일 이름은 index.html과 Test01.html~Test10.html입니다. 다운로드 원본에 붙어 있던 (1)은 최종 업로드 파일 이름에서 제거했습니다.
