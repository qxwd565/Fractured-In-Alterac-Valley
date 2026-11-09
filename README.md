# Fractured-In-Alterac-Valley

HSdeck 카드 API 스키마 1. 최초 추가일과 이후 카드 패치를 한국 날짜로 기록합니다.

- `data/<cardID>.json`: `card`는 최초 추가 당시 스펙, `card.patches`는 변경일과 실제 변경된 필드만 기록
- `cards.json`: 현재 스펙 (기존 데이터 및 원화 경로 보존)
- `render.json`: 현재 스펙 + 날짜별 과거 값
- `history.json`: 이전 HScard 호환 인덱스
- `release-policy.json`: 확장팩/미니 세트/선행 카드 출시일 (Asia/Seoul)

카드 265건, 확인된 패치 이벤트 14건. **제공된 ZIP은 현재 스펙이므로 공식 변경 기록으로 역산하지 못한 최초 수치에는 검증이 필요합니다.** 각 파일의 `card.initialSpecStatus`로 구분합니다.

기존 원화, 황금 이미지/애니메이션 및 경로는 수정하거나 삭제하지 않았습니다.
