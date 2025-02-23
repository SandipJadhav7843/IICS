# IICS

### To Cretae dynamic filename in IICS.
'DEPARTMENT_ID_' || TO_CHAR(SYSDATE, 'YYYYMMDD') || '.csv'
