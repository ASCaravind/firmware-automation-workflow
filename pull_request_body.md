### Firmware Update (FW_PRN_2026_02_26_001)

**Description**: Firmware update targeting DRAM initialization timing, boot-sequence robustness, and improved error telemetry.

**FW_ID**: `FW_PRN_2026_02_26_001`  
**Related TestRail Run**: TR-RUN-2026-02-26-01  
**Expected Impact**: Faster cold boot, fewer memory init faults.

**Validation**:
- Unit tests ✅
- Integration tests ✅
- System tests ▶️ (see TestRail)

**Artifacts**:
- S3 error logs: s3://firmwareerrorlogs1/FW_PRN_2026_02_26_001/
- GitHub Actions run: auto-linked

**Notes for Triage Agent**:
- Parse PR title/body to capture `FW_ID`.
- Use `FW_ID` to query TestRail and locate results.
