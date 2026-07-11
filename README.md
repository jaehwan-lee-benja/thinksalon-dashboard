# thinksalon-dashboard

생각살롱 프로젝트 **로드맵 · PM 대시보드** (공개 프론트 미러).

- `index.html` 단일 자기완결 파일. GitHub Pages로 서빙.
- 데이터: `multi-store · thinksalon` 스키마에 **읽기 전용 라이브**(Supabase PostgREST, anon+RLS). 실패 시 인라인 스냅샷 폴백.
- 정본 소스: 사설 레포 `thinksalon-archive/dashboard/index.html` (여기로 배포 복사).
- PII 없음(집계 수치·로드맵·세션 상태만).

🤖 Generated with [Claude Code](https://claude.com/claude-code)
