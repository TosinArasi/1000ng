SELECT
  yyyymm,
  origin,
  country_code,
  device, 
  p75_cls,
  p75_lcp,
  p75_fid,
  p75_fcp,
  rank

FROM
  `chrome-ux-report.materialized.country_summary`
WHERE
  device IN ('phone') AND 
  yyyymm = 202107 AND
  country_code = 'ng' AND 
  rank = 1000

ORDER BY
  yyyymm ASC,
  origin
