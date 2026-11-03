# refine_vectors

These test vectors are generated from jampy, using the test service contained in
this repository and are meant to test the `Xi` work report compute function (0.8.0 eq. 14.13).

Every vector follow this json format, where service, package and report format is inherited 
from jamtestvectors:

```json
{
  "name": "refine-echo",
  "core_idx": 0,
  "services": { "1000": { "...": "service json" } },
  "work_package": { "...": "work package json" },
  "bundle": "0x...", 
  "expected": {
    "work_report": { "...": "work report json" },
    "exported_segments": ["0x..."]
  }
}
```

