# vibe

'''mermail
gantt
    title AI 챔피언 대회 WBS
    dateFormat  YYYY-MM-DD

    section 기획
    대회 목표 및 콘셉트 정의      :a1, 2026-04-08, 3d
    종목/문제 유형 선정 (CV/NLP 등):a2, after a1, 4d
    일정 및 예산 수립             :a3, after a2, 3d

    section 준비 - 운영
    운영팀 구성                  :b1, after a3, 3d
    규정/평가 기준 설계          :b2, after b1, 4d
    심사위원 섭외               :b3, after b2, 5d

    section 준비 - 기술
    플랫폼 선정 (Kaggle/자체)    :c1, after a3, 3d
    서버/인프라 구축            :c2, after c1, 5d
    제출/채점 시스템 개발       :c3, after c2, 6d
    테스트 데이터셋 준비        :c4, after c2, 5d

    section 홍보 및 모집
    홍보 전략 수립              :d1, after b1, 3d
    홍보 콘텐츠 제작            :d2, after d1, 4d
    참가자 모집                 :d3, after d2, 10d

    section 대회 운영
    예선 진행                   :e1, after c3 d3, 7d
    중간 리더보드 관리          :e2, after e1, 5d
    본선 진행                   :e3, after e2, 5d

    section 평가 및 시상
    최종 평가                   :f1, after e3, 4d
    수상자 선정                 :f2, after f1, 2d
    시상식 준비 및 진행         :f3, after f2, 3d

    section 사후 관리
    결과 발표                   :g1, after f3, 2d
    데이터/코드 공개            :g2, after g1, 3d
    회고 및 개선안 도출         :g3, after g2, 3d
    ```
