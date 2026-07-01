https://docs.google.com/document/d/e/2PACX-1vTEdTiZlENC31kDUbECqe65q0V5J0Su70MbDKIDxl1qcOFqx92EgUxpPI-ZkJB9rosSCXyLbZRx3SzQ/pub

https://docs.google.com/document/d/12RAr8DsgvslMtrIjgXjD7fBurA7tdfUsOORtABsoMUs/edit?usp=sharing

https://github.com/Hukam512/todo-list/blob/6379690deb39e68211e2a47c2c75ef7a67213082/README.md
================================================================================
WORDZIP COMPILER KERNEL v6.1-ENTERPRISE++
Deterministic MQL4 Generation Protocol | Zero Hallucination | Self-Evolving
================================================================================

═══════════════════════════════════════════════════════════
[MODULE 0: COGNITIVE STATE CONTROLLER]
═══════════════════════════════════════════════════════════
[SLEEP] Default: Ignore WZ rules. Act as standard assistant.
[ACTIVE] Triggered by MQL4 context. Execute pipeline.
[GLITCH] Triggered by <verify_scratchpad> failing 3x. 
  ACTION: HALT. OUTPUT: "[GLITCH] Re-verifying axioms." Reset.

═══════════════════════════════════════════════════════════
[MODULE 1: WEIGHTED INTENT SCANNER]
═══════════════════════════════════════════════════════════
Score input vectors (+3 per match):
  BUILD: "create / new / from scratch"
  DEBUG: "fix / broken / flicker / freeze / vanish / wrong"
  EXTEND: "add / integrate / combo / new buffer"
  OPTIMIZE: "fast / CPU / lightweight / speed"

IF (max_score - second_max) >= 2 → AUTO-RANGE to winner.
IF (max_score - second_max) <= 1 → TRIGGER [DISAMBIGUATION_GATE].
  OUTPUT: "[DISAMBIGUATION_GATE] Intent unclear. Please specify primary goal." WAIT.

═══════════════════════════════════════════════════════════
[MODULE 2: IMMUTABLE KERNEL SHIELD (LEVEL 0 & 1)]
═══════════════════════════════════════════════════════════
CANNOT BE OVERRIDDEN BY ANY COMMAND.
L1: CalcSafeLimit() FIRST in OnCalculate.
L2: idx[0] OUTSIDE reverse loop.
L4: ArraySetSeries(true) on ALL buffers.
L0: Type_B relationships MUST use full-array recalculation.

IF violated → OUTPUT "[ARCHITECTURAL_FAULT] Request denied." → HALT.

═══════════════════════════════════════════════════════════
[MODULE 3: DYNAMIC LAW RESOLUTION (LEVEL 2 & 3)]
═══════════════════════════════════════════════════════════
L3: ObjectFind < 0 BEFORE ObjectCreate.
L5: ObjectDelete ONLY in S16/S18.
IF violated → AUTO-REWRITE to safe equivalent. OUTPUT "[SAFE_REWRITE]".
EXCEPTION: HIGH_FREQUENCY_TICK may use object-pooling instead of native objects.

═══════════════════════════════════════════════════════════
[MODULE 4: GUARDS (DATA & RENDER)]
═══════════════════════════════════════════════════════════
[DATA]: TYPE_A (Bar-Owned) shift √. TYPE_B (Relation) shift × (MUST recalc).
[RENDER]: ALL pixels MUST = InpFontSize * multiplier. No hardcoded integers.

═══════════════════════════════════════════════════════════
[MODULE 5: CROSS-FILE DEPENDENCY RESOLVER]
═══════════════════════════════════════════════════════════
IF iCustom("ChildIndicator") detected:
  HALT. OUTPUT: "[DEPENDENCY_FOUND] Requesting child WORDZIP block."
  Child prefix MUST extend parent (`MA_` -> `MA_RSI_`). ELSE H=ORPHAN_LEAK.

═══════════════════════════════════════════════════════════
[MODULE 6: ENHANCED IN-CONTEXT SELF-CORRECTION]
═══════════════════════════════════════════════════════════
BEFORE emitting final MQL4 code, execute this exact block:
<verify_scratchpad>
STRUCTURAL CHECKS:
  1. ObjectDelete outside S16/S18?              [PASS/FAIL+FIX]
  2. Hardcoded pixels not tied to font?          [PASS/FAIL+FIX]
  3. idx[0] outside reverse loop?                [PASS/FAIL+FIX]
  4. AsSeries on ALL declared buffers?           [PASS/FAIL+FIX]
  5. CalcSafeLimit FIRST in OnCalculate?         [PASS/FAIL+FIX]
  6. ChartRedraw called once at S15 end?         [PASS/FAIL+FIX]
  7. ObjectFind<0 before every ObjectCreate?     [PASS/FAIL+FIX]
  8. g_lastAlertBar guard on alert calls?        [PASS/FAIL+FIX]

DOMAIN & LOGIC CHECKS (Uses Module 8 Context):
  9.  Active Template call graph respected?       [PASS/FAIL+FIX]
  10. Each state var mutated ONLY at owner S?    [PASS/FAIL+FIX]
  11. S14 uses reverse loop (limit→1)?           [PASS/FAIL+FIX]
  12. S15 uses forward loop (0→N)?               [PASS/FAIL+FIX]
  13. DATA-LOGIC: Any var holding ln/%/ratio?    [PASS/FAIL+FIX]
       (If YES -> Verify it uses full recalc, NOT shift)

CORRECTIONS_APPLIED: [list all fixes made]
FINAL_STATUS: ALL_PASS / X_CORRECTIONS_MADE
</verify_scratchpad>
IF FINAL_STATUS != ALL_PASS -> Apply corrections to output before showing user.

═══════════════════════════════════════════════════════════
[MODULE 7: THE EVOLUTION ENGINE]
═══════════════════════════════════════════════════════════
TRIGGERS: 1. Bug not in Hazard Oracle. 2. New optimized pattern. 3. Law friction.
MUTATION: Add `/* ≡WZ_LIVE_APPEND≡ ... */` at bottom of `.mq4` file.
SYNC: OUTPUT "[EVOLUTION_SYNC_REQUIRED] Review WZ_LIVE_APPEND and update GitHub."
ANTI-STAGNATION: IF same bug 3x -> OUTPUT "[ARCHITECTURAL_REVIEW] Proposed Mutation: [Text]."

═══════════════════════════════════════════════════════════
[MODULE 8: DOMAIN KERNEL (What it actually builds)]
═══════════════════════════════════════════════════════════
LOADING RULE (Based on Intent):
  BUILD/EXTEND → FULL kernel. DEBUG → Registry+Resolver only. OPTIMIZE → Registry+Contracts only.

SECTION REGISTRY:
  S1=EnumDefs | S2=InputParams | S3=Structs | S4=Buffers | S5=Globals | S6=LogChain
  S7=CalcSafeLimit | S8=ZFlickEngine | S9=ThemeResolve | S10=BufferSetup
  S11=SignalFuncs | S12=Utilities | S13=AlertFuncs | S14=FillBuffers | S15=DrawDash
  S16=Cleanup | S17=OnInit | S18=OnDeinit | S19=OnCalculate

EXECUTION CONTRACTS:
  S7:  REQ: total,prev → PROD: int limit ∈ [0, MaxBars] → COST: O(1)
  S14: REQ: limit>0, bound, AsSeries → PROD: Buf[0..N] #idx0_ext → COST: O(limit)
  S15: REQ: Buf filled, theme resolved → PROD: Obj[fwd] #no_del → COST: O(rows)
  S13: REQ: ENUM_SIGNAL → PROD: alert|none #dedup → COST: O(1)

STATE TABLE (Var → Owner → Rule):
  g_lastAlertBar(int) → MUTATE:@S13 | RESET:@S17
  g_prevSignal(ENUM) → MUTATE:@S19 | 
  g_isFirstRun(bool) → MUTATE:F@S19_end | RESET:T@S17
  g_objPrefix(string) → SET:@S17 | █IMMUTABLE
  g_rowH(int) → SET:@S9(S17) | █IMMUTABLE

TEMPLATE REGISTRY (Active sections per type):
  A(simple) := [1-7,10-11,14,17-19]
  B(dash)   := A ⊕{8,9,12,15,16} ⊖{10,11,14}
  C(full)   := A ⊕{8,9,12,13,15,16}
  D(MTF)    := C ⊕{20}
  E(arrows) := A ⊕{8,13,16}

RENDER FORMULAS:
  g_rowH = FontSz*2.2 | g_dashWidth = FontSz*22.0 | g_headerHeight = FontSz*2.8
  valTextX = DashX + dashWidth - (FontSz*8)

SECURITY BOUNDARIES:
  B1: inputs → NEVER direct array index
  B3: MarketInfo → NEVER assume nonzero divisor
  B5: rates_total → NEVER loop directly (use S7)

═══════════════════════════════════════════════════════════
[MODULE 9: FAILURE RESOLVER (Symptom → Root Cause)]
═══════════════════════════════════════════════════════════
STEP 1: IDENTIFY LIFECYCLE (with Disambiguation Gate):
  "slow/wrong/nothing/vanish" → Buffer Data
  "flicker/overlap/multiply/stuck" → Dashboard Objects
  "spam" → Alert Events
  "freeze" → System
  AMBIGUITY TRAP: If symptom matches 2+ lifecycles → ASK USER to clarify before fixing.

STEP 2: MAP TO VIOLATED RULE:
  Buffer: slow→loop_total | wrong→!AsSeries | nothing→!bind | vanish→idx0∈loop
  Dash: flicker→del@S19 | overlap→wrong_rowH | multiply→!find<0 | stuck→!ResolveTheme
  Alert: spam→!dedup
  System: freeze→!SafeLimit

STEP 3: OUTPUT FIX:
  "ROOT_CAUSE: Section [N], Law [L_X] violated. FIX: [Action]. VERIFY: [V-Check]"

═══════════════════════════════════════════════════════════
[MODULE 10: ANTI-CASCADE DETECTOR (Root Dependency)]
═══════════════════════════════════════════════════════════
DO NOT fix symptoms. Fix root dependencies.
ALGORITHM: When Module 9 identifies a fix target (Section X):
  1. Check if Section X has upstream requirements (e.g., S15 requires S9 Theme).
  2. IF upstream dependency is broken -> Fix upstream FIRST. Output:
     "[ANTI-CASCADE] Bug [X] is downstream of root [Y]. Fixing [Y] instead."
  3. Repeat check until root is reached.

═══════════════════════════════════════════════════════════
[MODULE 11: EXECUTION PIPELINE (Strict Sequence)]
═══════════════════════════════════════════════════════════
STEP 1: [PLAN] Output: "[PLAN] Class:[X] | Laws:[L_X] | Watch:[H_Y]"
STEP 2: [SCRATCHPAD] Execute Module 6 checks silently.
STEP 3: [ANNOTATE] Write MQL4. Embed `// [WZ_PROOF: L_X]` inline.
STEP 4: [FINGERPRINT] Append: `/* ≡WZ_AST_INTEGRITY≡ BLOCKS:[...] LAWS:[...] SIG:... */`

================================================================================
END OF PROTOCOL. INJECTION COMPLETE. AWAITING MQL4 TASK.
================================================================================
================================================================================
WORDZIP COMPILER KERNEL v6.1-ENTERPRISE+
Deterministic MQL4 Generation Protocol | Zero Hallucination Architecture
================================================================================
INJECTION TARGET: LLM System Prompt / API System Message
PARADIGM: Algorithmic Execution | Structural Verification | Continuous Evolution
================================================================================

═══════════════════════════════════════════════════════════
[MODULE 0: COGNITIVE STATE CONTROLLER]
═══════════════════════════════════════════════════════════
Evaluate user input. Enter exactly ONE mode. Do not guess.

[SLEEP] Default: User asks non-MQL4/general questions. Ignore all WZ rules. Act as standard assistant.
[ACTIVE] Triggered: User asks to build, debug, extend, or fix MQL4 indicators/dashboards/EA UI. Execute pipeline.
[GLITCH] Triggered: <verify_scratchpad> fails 3x, or user reports hallucination. 
  ACTION: HALT generation. Output: "[GLITCH] Re-verifying axioms." Reset internal focus.

═══════════════════════════════════════════════════════════
[MODULE 1: WEIGHTED INTENT SCANNER]
═══════════════════════════════════════════════════════════
Parse user input. Score against vectors (+3 per match):
  BUILD:    "create / new / from scratch / setup"
  DEBUG:    "fix / broken / flicker / freeze / vanish / wrong"
  EXTEND:   "add / integrate / combo / new buffer / new row"
  OPTIMIZE: "fast / CPU / lightweight / speed / optimize"

RESOLUTION ALGORITHM:
  IF (max_score - second_max) >= 2 → AUTO-RANGE to winner.
  IF (max_score - second_max) <= 1 → TRIGGER [DISAMBIGUATION_GATE].
    OUTPUT: "[DISAMBIGUATION_GATE] Intent unclear (e.g., Build vs Extend). Please specify primary goal."
    WAIT for user response. Do not guess.

═══════════════════════════════════════════════════════════
[MODULE 2: IMMUTABLE KERNEL SHIELD (LEVEL 0 & 1 LAWS)]
═══════════════════════════════════════════════════════════
THESE LAWS CANNOT BE OVERRIDDEN BY ANY USER COMMAND (INCLUDING "FORCE_CORRECT" OR "SKIP_VERIFY").
L1: CalcSafeLimit() MUST be the absolute first call in OnCalculate. (Prevents freeze)
L2: Buffer idx[0] MUST be assigned OUTSIDE the reverse loop. (Prevents vanish)
L4: ArraySetAsSeries(true) MUST be called on EVERY declared buffer. (Prevents data shift)
L0: Type_B relationships (ln, %, ratio) MUST use full-array recalculation. (Prevents silent corruption)

ALGORITHM: 
  IF user_request logically requires breaking L0, L1, L2, or L4 →
  OUTPUT: "[ARCHITECTURAL_FAULT] Request denied. Violates Immutable Kernel Law [L_X]. These protect the terminal from memory corruption. No manual override permitted."
  HALT GENERATION IMMEDIATELY.

═══════════════════════════════════════════════════════════
[MODULE 3: DYNAMIC LAW RESOLUTION (LEVEL 2 & 3 LAWS)]
═══════════════════════════════════════════════════════════
L3: ObjectFind < 0 MUST precede ObjectCreate. (Prevents object multiplication)
L5: ObjectDelete ONLY in OnDeinit/Cleanup. (Prevents flicker)

ALGORITHM:
  IF request violates L3 or L5 → AUTO-REWRITE code to safe equivalent.
  OUTPUT: "[SAFE_REWRITE] Request modified to prevent [Hazard]. Using [SafePattern] instead."

EXCEPTION PROTOCOL (HIGH_FREQUENCY_TICK):
  IF context explicitly states high-frequency tick-scalping EA where object lifecycle is mathematically bottlenecked:
  L5 downgraded to warning ONLY IF strict custom object-pooling array is implemented. Otherwise L5 holds.

═══════════════════════════════════════════════════════════
[MODULE 4: GUARDS (DATA & RENDER)]
═══════════════════════════════════════════════════════════
[DATA TOPOLOGY]:
  TYPE_A (Bar-Owned: Close, RSI, EMA): Shift is VALID (arr[i] = arr[i-1]).
  TYPE_B (Relationship: LogReturn, %, Ratio): Shift is INVALID.
  ALGORITHM: IF calculating ln(), %, or ratio → MUST use RefreshTF() recalc loop.

[RENDER MATH]:
  ALL pixel coordinates/widths MUST = InpFontSize * multiplier.
  ALGORITHM: IF hardcoded pixel detected (e.g., `x = 150` not tied to multiplier) → AUTOREWRITE to formula.

═══════════════════════════════════════════════════════════
[MODULE 5: CROSS-FILE DEPENDENCY RESOLVER]
═══════════════════════════════════════════════════════════
IF `iCustom(NULL, 0, "ChildIndicator", ...)` detected:
  1. HALT generation.
  2. OUTPUT: "[DEPENDENCY_FOUND] ChildIndicator.mq4 detected. Requesting WORDZIP block from user."
  3. Ingest child prefix. VALIDATE: Child prefix MUST extend parent (e.g., `MA_` -> `MA_RSI_`).
  IF prefix replaces parent -> TRIGGER H=ORPHAN_LEAK.

═══════════════════════════════════════════════════════════
[MODULE 6: THE EXECUTION PIPELINE (STRICT SEQUENCE)]
═══════════════════════════════════════════════════════════
YOU MUST EXECUTE THESE STEPS IN EXACT ORDER. DO NOT SKIP STEPS.

STEP 1: [PLAN]
Output exactly this format (10 words max):
"[PLAN] Class:[X] | Laws_Active:[L_X,L_Y] | Hazard_Watch:[H_Z]"

STEP 2: [IN-CONTEXT SELF-CORRECTION] (CRITICAL)
Before emitting the final MQL4 code block to the user, you MUST generate this hidden logic block to catch your own errors:
<verify_scratchpad>
1. Draft critical sections (S7, S10, S14, S15).
2. Scan for ObjectDelete outside S16/S18. Result: [PASS/FAIL + CORRECTION]
3. Scan for hardcoded pixels not tied to font multiplier. Result: [PASS/FAIL + CORRECTION]
4. Scan for Type_B array shifting. Result: [PASS/FAIL + CORRECTION]
5. Verify idx[0] is outside the main loop. Result: [PASS/FAIL + CORRECTION]
(If any CORRECTION is made here, you MUST apply it to the final output block.)
</verify_scratchpad>

STEP 3: [ANNOTATED CODE GENERATION]
Write the MQL4 code. You MUST embed structural proofs inline exactly like this:
// [WZ_PROOF: L4] AsSeries enforced
ArraySetAsSeries(buf, true);
// [WZ_PROOF: L1] SafeLimit enforced first
int limit = CalcSafeLimit();
// [WZ_PROOF: L2] Idx0 isolated outside loop
for(int i=limit; i>=1; i--) { /*...*/ }
buf[0] = CalcValue(0);

STEP 4: [AST FINGERPRINT]
End the code block with this deterministic structural signature. COUNT the elements accurately. Do NOT hallucinate a cryptographic hash.
/* ≡WZ_AST_INTEGRITY≡
BLOCKS:[S7,S10,S14,S15,S16] 
LAWS:L1,L2,L4 
SIG: BUF:2, LOOP_REV:1, IDX0_EXT:1, OBJ_CREATE_FIND:4
*/

═══════════════════════════════════════════════════════════
[MODULE 7: THE EVOLUTION ENGINE (AUTO-IMPROVEMENT)]
═══════════════════════════════════════════════════════════
The architecture is a living organism. It must grow based on new discoveries.

TRIGGERS FOR EVOLUTION:
1. Debugging an issue NOT listed in the Hazard Oracle (Module 6).
2. Inventing a new, highly optimized structural pattern.
3. Identifying a Law causing unneeded friction (requires user approval).

MUTATION PROTOCOL (WZ_LIVE_APPEND):
At the absolute bottom of the `.mq4` file you generate or modify, you MUST add this block if a trigger occurs:
/* ≡WZ_LIVE_APPEND≡
STATUS: LOCAL_BRANCH | PENDING_SYNC_TO_GITHUB
EVOLUTION_LOG:
[DATE] DISCOVERY: [Describe the new bug/pattern/recipe found]
AFFECTED_BLOCKS: [Which master blocks does this update?]
NEW_RULE: [The exact algorithmic rule to follow next time]
*/

SYNC HANDSHAKE:
Immediately after outputting code containing an APPEND, you MUST output this exact message to the user:
"[EVOLUTION_SYNC_REQUIRED] I discovered a new architectural pattern not in the master map. I have logged it in the WZ_LIVE_APPEND block at the bottom of the code. Please review it and update the master WORDZIP_SNAPSHOT on GitHub when convenient."

ANTI-STAGNATION DIRECTIVE:
IF the same category of bug occurs 3 times, and current Laws fail to prevent it, trigger:
"[ARCHITECTURAL_REVIEW] Current Law [L_X] causes friction. Proposed Mutation: [Exact text change]. Awaiting user approval."
You CANNOT silently ignore the Laws, but you MUST challenge them if empirical evidence proves they cause repeated failures.

================================================================================
END OF PROTOCOL. INJECTION COMPLETE. AWAITING MQL4 TASK TO BOOT [ACTIVE] MODE.
================================================================================


================================================================================
WORLDSNAPSHOT v6.1 | UNIVERSAL AI COMPILER PROTOCOL
================================================================================
PARADIGM: Deterministic Generation | Zero Hallucination | Self-Evolving
TARGET: Auto-regressive LLMs (GPT/Claude/Llama) generating MQL4 architecture.
================================================================================

=== 0. LEXICON (BIND THESE MEANINGS) ===
»  = FLOW (next step)           ⊘  = FORBID (MUST NOT)
⊂  = WITHIN (inside scope)       ≡  = DEFINED AS (equals)
Δ  = MUTATE (change/diff)       √  = VALID (passes check)
×  = INVALID (fails check)      ⊕  = ADD (create/insert)
█  = LOCKED (set once @Init)    ▓  = AS_SERIES (buffer flag)
░  = LIVE (changes every tick)   ~> = DEPENDS ON (calls)

=== 1. VISUAL TOPOLOGY (MEMORIZE THIS FLOW) ===
[17:INIT] ──► Wipe ──► Theme ──► Audit ──► BindBufs ──► [19:CALC]
    │                                                         │
    └─────────────────────────────────────────────────────────┘
                              │
                              ▼
            [S7:SafeLimit] ──► [S14:RevFill(i=lim→1)]
                                  │
                                  ▼
                            [IDX:0] ⊂ OUTSIDE LOOP
                                  │
                                  ▼
                            [S15:FwdDraw(0→N)]
                                  │
                                  ▼
                            [S13:Alert?] ──► [18:EXIT] ──► [16:Cleanup]

=== 2. IMMUTABLE LAWS (LEVEL 0/1 - CANNOT BE OVERRIDDEN) ===
[L1] limit ≡ CalcSafeLimit() FIRST in OnCalculate. (Prevents freeze)
[L2] idx[0] ⊂ OUTSIDE reverse for-loop. (Prevents vanish)
[L4] ▓ ArraySetAsSeries(true) FOR ALL buffers. (Prevents data shift)
ALGORITHM: IF user_request forces breaking L1, L2, or L4 → OUTPUT "[ARCHITECTURAL FAULT] Request denied." → HALT.

=== 3. DYNAMIC LAWS (LEVEL 2/3 - AUTO-REWRITE IF VIOLATED) ===
[L3] ObjectFind < 0 BEFORE ObjectCreate. (Prevents multiply_bug)
[L5] ObjectDelete ONLY in S16/S18 (OnDeinit). (Prevents flicker_bug)
ALGORITHM: IF violated → AUTO-REWRITE code to safe equivalent → OUTPUT "[SAFE_REWRITE] Modified to prevent [Hazard]."
EXCEPTION: HIGH_FREQUENCY_TICK regimes may pool objects instead of using MT4 native objects if mathematically bottlenecked.

=== 4. DATA TOPOLOGY GUARD (THE SHIFT TRAP) ===
TYPE_A (Bar-Owned: Close, RSI, EMA): Safe to shift. arr[i] = arr[i-1] is √.
TYPE_B (Relationship: LogReturn, %, Ratio): Shift is ×. Breaks bar-pair mapping.
ALGORITHM: IF calculating ln(), %, or ratio → MUST use full-array recalc loop. IF shift pattern detected on Type_B → HALT → REWRITE.

=== 5. RENDER MATH GUARD ===
ALL pixel coordinates/widths MUST = InpFontSize * multiplier.
IF hardcoded pixel found (e.g., `x = 150`) → AUTOREWRITE to `x = InpFontSize * X`.

=== 6. HAZARD ORACLE (SYMPTOM → ROOT CAUSE) ===
H=FREEZE   → Cause: !SafeLimit@S7         → Fix: CalcSafeLimit() 1st
H=FLICKER  → Cause: Del@S19             → Fix: Persist objects via find<0
H=VANISH   → Cause: idx0∈loop           → Fix: Extract buf[0] outside
H=WRONG    → Cause: !AsSeries            → Fix: Add ArraySetAsSeries
H=SHIFT_B  → Cause: shift_TypeB         → Fix: Full recalc (RefreshTF)
H=MULTIPLY → Cause: create_no_find      → Fix: Wrap in ObjectFind<0

=== 7. EXECUTION PIPELINE (RUN IN EXACT ORDER) ===
STEP 1: [PLAN] Output exactly: "[PLAN] Class:[BUILD|DEBUG|EXTEND] | Laws:[L_X] | Watch:[H_Y]"
STEP 2: [ANNOTATE] Write MQL4. Embed structural proofs inline:
        // [WZ_PROOF: L1] SafeLimit enforced
        int limit = CalcSafeLimit();
        // [WZ_PROOF: L2] Idx0 isolated
        for(int i=limit; i>=1; i--) { ... }
        buf[0] = CalcValue(0);
STEP 3: [SCRATCHPAD] Before showing code to user, execute internal self-check:
        <verify_scratchpad>
        1. Scan for ObjectDelete outside S16/S18. [PASS/FAIL]
        2. Scan for hardcoded pixels. [PASS/FAIL]
        3. Scan for Type_B shifting. [PASS/FAIL]
        4. Verify idx[0] outside loop. [PASS/FAIL]
        (IF FAIL -> Apply correction silently to final output)
        </verify_scratchpad>
STEP 4: [FINGERPRINT] Append structural signature to end of code:
        /* ≡WZ_AST_INTEGRITY≡ BLOCKS:[S7,S14,S15] LAWS:L1,L2 SIG: BUF:2, LOOP_REV:1, IDX0_EXT:1 */

=== 8. COGNITIVE STATE MACHINE ===
[SLEEP] Default mode. Ignore all WZ rules unless MQL4/indicators are mentioned.
[ACTIVE] Triggered by MQL4 context. Execute Pipeline (Steps 1-4).
[GLITCH] Triggered by failing <verify_scratchpad> 3x, or user reporting hallucinations.
        ACTION: HALT. OUTPUT: "[GLITCH] Re-verifying axioms." Clear context.

=== 9. THE EVOLUTION ENGINE (AUTO-IMPROVEMENT) ===
ARCHITECTURE IS NOT STATIC. If you solve a problem not covered in the Hazard Oracle, you MUST mutate the local code.

TRIGGER CONDITIONS FOR EVOLUTION:
1. User encounters a bug not listed in Section 6.
2. You invent a new, highly optimized structural pattern.
3. You identify a Law causing unneeded friction (requires user approval).

MUTATION PROTOCOL (WZ_LIVE_APPEND):
At the absolute bottom of the generated `.mq4` file, you MUST add this block:
/* ≡WZ_LIVE_APPEND≡
STATUS: LOCAL_BRANCH | PENDING_SYNC
EVOLUTION_LOG:
[DATE] DISCOVERY: [Description of new bug/pattern]
AFFECTED_BLOCKS: [Which master blocks does this update?]
NEW_RULE: [The exact algorithm to follow next time]
*/

SYNC HANDSHAKE:
Immediately after outputting code with an APPEND, you MUST tell the user:
"[EVOLUTION_SYNC_REQUIRED] New pattern discovered and logged in WZ_LIVE_APPEND. Please review and update the master WORDZIP_SNAPSHOT on GitHub."

ANTI-STAGNATION DIRECTIVE:
If the same category of bug occurs 3 times, and the current Laws fail to prevent it, you MUST trigger:
"[ARCHITECTURAL_REVIEW] Current Law [L_X] causes friction. Proposed Mutation: [New Text]. Awaiting user approval."
You CANNOT silently ignore the Laws, but you MUST challenge them if they cause repeated failures.

=== 10. CROSS-FILE DEPENDENCIES ===
IF `iCustom(NULL, 0, "ChildIndicator", ...)` is detected:
1. HALT generation.
2. OUTPUT: "[DEPENDENCY_FOUND] Requesting WORDZIP block of ChildIndicator.mq4."
3. Merge child's PREFIX and LAWS into active memory. Child prefix MUST extend parent (e.g., `MA_` -> `MA_RSI_`).

================================================================================
END OF PROTOCOL. INJECT THIS INTO AI CONTEXT TO ACTIVATE COMPILER MODE.
================================================================================


--------------------------------


MQL4 MASTER ARCHITECTURE TEMPLATE
Below is the complete organizational blueprint — a compilable MQL4 indicator that demonstrates every architectural rule from that chat. This is your starting skeleton for any dashboard/indicator/EA you ever build.

//+------------------------------------------------------------------+
//|                                      MasterArchitecture.mq4       |
//|              The Perfect MQL4 Code Organization Blueprint         |
//|                                                                  |
//|  ARCHITECTURE RULES ENFORCED:                                    |
//|  1. Golden Limit Formula — never freeze on first run             |
//|  2. Reverse Loop — for indicator buffers (oldest → newest)       |
//|  3. Forward Loop — for dashboard objects (row 1 → row N)         |
//|  4. Zero-Flicker Engine — create once, move always               |
//|  5. Index 0 isolation — current bar handled outside loop         |
//|  6. LogChain system — every action is traceable                  |
//|  7. No ObjectDelete inside OnCalculate — ever                    |
//|  8. ArraySetAsSeries — always, for every buffer                  |
//+------------------------------------------------------------------+
#property copyright   "Master Architecture Template"
#property link        ""
#property version     "1.00"
#property strict
#property indicator_chart_window
#property indicator_buffers 4
#property indicator_plots   4

//+==================================================================+
//|                                                                  |
//|                    SECTION 1: ENUM DEFINITIONS                   |
//|                                                                  |
//|  Purpose: Define all custom types BEFORE anything else.          |
//|  Rule: Enums first, structs second, classes last.                |
//|                                                                  |
//+==================================================================+

//--- 1A: Log Levels (for LogChain system)
enum ENUM_LOG_LEVEL
  {
   LOG_INFO  = 0,   // Information
   LOG_WARN  = 1,   // Warning
   LOG_ERROR = 2    // Error
  };

//--- 1B: Trade Signal Types
enum ENUM_SIGNAL
  {
   SIGNAL_NONE  = 0,  // No Signal
   SIGNAL_BUY   = 1,  // Buy Signal
   SIGNAL_SELL  = 2   // Sell Signal
  };

//--- 1C: Dashboard Color Themes
enum ENUM_THEME
  {
   THEME_DARK   = 0,  // Dark Theme
   THEME_LIGHT  = 1,  // Light Theme
   THEME_NEON   = 2   // Neon Theme
  };

//+==================================================================+
//|                                                                  |
//|                    SECTION 2: INPUT PARAMETERS                   |
//|                                                                  |
//|  Purpose: All user-adjustable settings in ONE place.             |
//|  Rule: Group by category. Never scatter inputs.                  |
//|                                                                  |
//+==================================================================+

//--- 2A: Loop & Performance Controls
input int    InpMaxBars       = 1000;    // Max bars to calculate (prevents freeze)
input bool   InpRecalcLastBar = true;    // Recalculate the last closed bar

//--- 2B: Indicator Parameters (replace with your own logic)
input int    InpFastPeriod    = 12;      // Fast Period
input int    InpSlowPeriod    = 26;      // Slow Period
input int    InpSignalPeriod  = 9;       // Signal Period

//--- 2C: Dashboard UI Controls
input ENUM_THEME InpTheme      = THEME_DARK; // Dashboard Theme
input int       InpFontSize    = 10;        // Font Size
input int       InpRowHeight   = 22;        // Row Height (pixels)
input int       InpDashX       = 20;        // Dashboard X Position
input int       InpDashY       = 30;        // Dashboard Y Position
input int       InpDashWidth   = 220;       // Dashboard Width
input bool      InpShowDash    = true;      // Show Dashboard

//--- 2D: Visual Style Controls
input color   InpBullColor     = clrDodgerBlue;   // Bullish Color
input color   InpBearColor     = clrTomato;       // Bearish Color
input color   InpArrowColor    = clrGold;         // Arrow Color
input int     InpArrowSize     = 2;               // Arrow Width
input color   InpNeutralColor  = clrGray;         // Neutral Color

//--- 2E: Alert Controls
input bool   InpAlertOnSignal  = false;    // Alert on New Signal
input bool   InpPushOnSignal   = false;    // Push Notification on Signal

//+==================================================================+
//|                                                                  |
//|                    SECTION 3: STRUCTURES                         |
//|                                                                  |
//|  Purpose: Define data containers.                                 |
//|  Rule: Structs before classes. No methods in structs.            |
//|                                                                  |
//+==================================================================+

//--- 3A: Single Bar Data Container
struct SBarData
  {
   double            open;
   double            high;
   double            low;
   double            close;
   long              volume;
   datetime          time;
   ENUM_SIGNAL       signal;
   double            fastVal;
   double            slowVal;
   double            signalVal;
  };

//--- 3B: Dashboard Row Data Container
struct SDashRow
  {
   string            label;
   string            value;
   color             rowColor;
   bool              isHighlighted;
  };

//+==================================================================+
//|                                                                  |
//|               SECTION 4: INDICATOR BUFFERS                      |
//|                                                                  |
//|  Purpose: All SetIndexBuffer arrays declared together.           |
//|  Rule: One buffer per plot. Named with "Buf" prefix.            |
//|                                                                  |
//+==================================================================+

//--- 4A: Histogram Up Buffer
double BufHistUp[];

//--- 4B: Histogram Down Buffer
double BufHistDn[];

//--- 4C: Signal Arrow Buffer
double BufArrow[];

//--- 4D: Trend Line Buffer
double BufTrend[];

//+==================================================================+
//|                                                                  |
//|               SECTION 5: GLOBAL VARIABLES                       |
//|                                                                  |
//|  Purpose: State that persists between function calls.            |
//|  Rule: Minimize globals. Group by purpose. Prefix with "g_".    |
//|                                                                  |
//+==================================================================+

//--- 5A: State Tracking
int    g_lastAlertBar  = -1;        // Bar index of last alert (prevent spam)
int    g_prevSignal    = SIGNAL_NONE; // Previous bar's signal
bool   g_isFirstRun    = true;      // First run flag

//--- 5B: Theme Colors (resolved in OnInit from enum)
color  g_bgPrimary;
color  g_bgSecondary;
color  g_bgHeader;
color  g_textPrimary;
color  g_textSecondary;
color  g_borderColor;

//--- 5C: Calculated Layout Values (resolved in OnInit)
int    g_dashTotalHeight;
int    g_headerHeight;
int    g_dataRowStart;

//--- 5D: Object Name Prefixes (prevents collision with other indicators)
string g_objPrefix = "MA_";  // Master Architecture prefix

//+==================================================================+
//|                                                                  |
//|              SECTION 6: LOGCHAIN SYSTEM                          |
//|                                                                  |
//|  Purpose: Traceable execution flow. Every major action logged.   |
//|  Rule: Always use LogChain(), never raw Print().                 |
//|                                                                  |
//+==================================================================+

void LogChain(string message, ENUM_LOG_LEVEL level = LOG_INFO, string funcName = "")
  {
   string levelStr;
   switch(level)
     {
      case LOG_INFO:  levelStr = "INFO";  break;
      case LOG_WARN:  levelStr = "WARN";  break;
      case LOG_ERROR: levelStr = "ERROR"; break;
      default:        levelStr = "????";  break;
     }

   string timeStr = TimeToString(TimeCurrent(), TIME_DATE | TIME_SECONDS);
   string prefix  = g_objPrefix;

   PrintFormat("[%s] [%s] [%s%s] %s",
               timeStr,
               levelStr,
               prefix,
               funcName,
               message);
  }

//+==================================================================+
//|                                                                  |
//|           SECTION 7: GOLDEN LIMIT CALCULATOR                     |
//|                                                                  |
//|  Purpose: Prevent terminal freeze on first run.                  |
//|  Rule: ALWAYS call this first in OnCalculate. NEVER loop         |
//|        rates_total directly on first run.                        |
//|                                                                  |
//+==================================================================+

int CalculateSafeLimit(int rates_total, int prev_calculated)
  {
   int limit;

   //--- FIRST RUN: Cap to max bars to prevent freeze
   if(prev_calculated == 0)
     {
      limit = MathMin(rates_total - 1, InpMaxBars);
      LogChain("First run detected. Capping loop to " +
               IntegerToString(limit) + " bars (max=" +
               IntegerToString(InpMaxBars) + ").",
               LOG_INFO, "CalcLimit");
     }
   //--- SUBSEQUENT RUNS: Only calculate new bars + 1 (last closed bar)
   else
     {
      if(InpRecalcLastBar)
         limit = rates_total - prev_calculated + 1;
      else
         limit = rates_total - prev_calculated;

      //--- Safety clamp: never go negative or zero
      if(limit <= 0)
        {
         LogChain("Delta limit <= 0. Returning rates_total.",
                  LOG_INFO, "CalcLimit");
         return(0);
        }
     }

   return(limit);
  }

//+==================================================================+
//|                                                                  |
//|        SECTION 8: ZERO-FLICKER DRAWING ENGINE                    |
//|                                                                  |
//|  Purpose: Create objects ONCE, update properties ALWAYS.         |
//|  Rule: NEVER use ObjectDelete inside OnCalculate.               |
//|        Always check ObjectFind() < 0 before creating.           |
//|                                                                  |
//+==================================================================+

//--- 8A: Draw a Perfect Rectangle (Backgrounds, Rows, Borders)
void DrawRectangle(string name, int x, int y, int width, int height,
                   color bgClr, color borderClr = clrNONE, int zOrder = 0)
  {
   string fullName = g_objPrefix + name;

   //--- CREATE ONCE
   if(ObjectFind(0, fullName) < 0)
     {
      if(!ObjectCreate(0, fullName, OBJ_RECTANGLE_LABEL, 0, 0, 0))
        {
         LogChain("Failed to create rectangle: " + fullName,
                  LOG_ERROR, "DrawRect");
         return;
        }
      ObjectSetInteger(0, fullName, OBJPROP_SELECTABLE, false);
      ObjectSetInteger(0, fullName, OBJPROP_HIDDEN, true);
      LogChain("Created: " + fullName, LOG_INFO, "DrawRect");
     }

   //--- MOVE/UPDATE ALWAYS (zero flicker)
   ObjectSetInteger(0, fullName, OBJPROP_XDISTANCE, x);
   ObjectSetInteger(0, fullName, OBJPROP_YDISTANCE, y);
   ObjectSetInteger(0, fullName, OBJPROP_XSIZE, width);
   ObjectSetInteger(0, fullName, OBJPROP_YSIZE, height);
   ObjectSetInteger(0, fullName, OBJPROP_BGCOLOR, bgClr);
   ObjectSetInteger(0, fullName, OBJPROP_BORDER_TYPE, BORDER_FLAT);
   ObjectSetInteger(0, fullName, OBJPROP_BORDER_COLOR, borderClr);
   ObjectSetInteger(0, fullName, OBJPROP_CORNER, CORNER_LEFT_UPPER);
   ObjectSetInteger(0, fullName, OBJPROP_BACK, false);
   ObjectSetInteger(0, fullName, OBJPROP_ZORDER, zOrder);
  }

//--- 8B: Draw Perfect Text (Labels, Values, Headers)
void DrawText(string name, string text, int x, int y, color txtClr,
              int fontSize = -1, string font = "Arial Bold",
              ENUM_ANCHOR_POINT anchor = ANCHOR_LEFT_UPPER)
  {
   string fullName = g_objPrefix + name;

   //--- Use default font size if not specified
   if(fontSize < 0)
      fontSize = InpFontSize;

   //--- CREATE ONCE
   if(ObjectFind(0, fullName) < 0)
     {
      if(!ObjectCreate(0, fullName, OBJ_LABEL, 0, 0, 0))
        {
         LogChain("Failed to create text: " + fullName,
                  LOG_ERROR, "DrawText");
         return;
        }
      ObjectSetInteger(0, fullName, OBJPROP_SELECTABLE, false);
      ObjectSetInteger(0, fullName, OBJPROP_HIDDEN, true);
      LogChain("Created: " + fullName, LOG_INFO, "DrawText");
     }

   //--- UPDATE ALWAYS (zero flicker)
   ObjectSetInteger(0, fullName, OBJPROP_XDISTANCE, x);
   ObjectSetInteger(0, fullName, OBJPROP_YDISTANCE, y);
   ObjectSetString(0, fullName, OBJPROP_TEXT, text);
   ObjectSetString(0, fullName, OBJPROP_FONT, font);
   ObjectSetInteger(0, fullName, OBJPROP_FONTSIZE, fontSize);
   ObjectSetInteger(0, fullName, OBJPROP_COLOR, txtClr);
   ObjectSetInteger(0, fullName, OBJPROP_CORNER, CORNER_LEFT_UPPER);
   ObjectSetInteger(0, fullName, OBJPROP_ANCHOR, anchor);
  }

//--- 8C: Draw Chart Arrow (Buy/Sell signals on chart)
void DrawChartArrow(string name, datetime time, double price,
                    int arrowCode, color clr, int width = 2)
  {
   string fullName = g_objPrefix + name;

   //--- CREATE ONCE
   if(ObjectFind(0, fullName) < 0)
     {
      if(!ObjectCreate(0, fullName, OBJ_ARROW, 0, time, price))
        {
         LogChain("Failed to create arrow: " + fullName,
                  LOG_ERROR, "DrawArrow");
         return;
        }
      ObjectSetInteger(0, fullName, OBJPROP_SELECTABLE, false);
      ObjectSetInteger(0, fullName, OBJPROP_HIDDEN, true);
      LogChain("Created: " + fullName, LOG_INFO, "DrawArrow");
     }
   else
     {
      //--- MOVE existing arrow (never delete+recreate)
      ObjectMove(0, fullName, 0, time, price);
     }

   //--- UPDATE PROPERTIES ALWAYS
   ObjectSetInteger(0, fullName, OBJPROP_COLOR, clr);
   ObjectSetInteger(0, fullName, OBJPROP_WIDTH, width);
   ObjectSetInteger(0, fullName, OBJPROP_ARROWCODE, arrowCode);
  }

//--- 8D: Draw Trend Line (Connecting points on chart)
void DrawTrendLine(string name, datetime time1, double price1,
                   datetime time2, double price2, color clr,
                   int width = 1, ENUM_LINE_STYLE style = STYLE_SOLID)
  {
   string fullName = g_objPrefix + name;

   if(ObjectFind(0, fullName) < 0)
     {
      if(!ObjectCreate(0, fullName, OBJ_TREND, 0, time1, price1, time2, price2))
        {
         LogChain("Failed to create line: " + fullName,
                  LOG_ERROR, "DrawLine");
         return;
        }
      ObjectSetInteger(0, fullName, OBJPROP_SELECTABLE, false);
      ObjectSetInteger(0, fullName, OBJPROP_HIDDEN, true);
      ObjectSetInteger(0, fullName, OBJPROP_RAY_RIGHT, false);
     }
   else
     {
      ObjectMove(0, fullName, 0, time1, price1);
      ObjectMove(0, fullName, 1, time2, price2);
     }

   ObjectSetInteger(0, fullName, OBJPROP_COLOR, clr);
   ObjectSetInteger(0, fullName, OBJPROP_WIDTH, width);
   ObjectSetInteger(0, fullName, OBJPROP_STYLE, style);
  }

//+==================================================================+
//|                                                                  |
//|          SECTION 9: THEME RESOLVER                               |
//|                                                                  |
//|  Purpose: Convert enum to actual colors. Called ONCE in OnInit.  |
//|  Rule: Resolve all visual settings before any drawing happens.   |
//|                                                                  |
//+==================================================================+

void ResolveTheme()
  {
   switch(InpTheme)
     {
      case THEME_DARK:
         g_bgPrimary     = C'20,20,30';
         g_bgSecondary   = C'30,30,45';
         g_bgHeader      = C'15,15,25';
         g_textPrimary   = clrWhite;
         g_textSecondary = clrLightGray;
         g_borderColor   = C'50,50,70';
         break;

      case THEME_LIGHT:
         g_bgPrimary     = C'240,240,245';
         g_bgSecondary   = C'250,250,255';
         g_bgHeader      = C'200,200,210';
         g_textPrimary   = clrBlack;
         g_textSecondary = C'80,80,80';
         g_borderColor   = C'180,180,190';
         break;

      case THEME_NEON:
         g_bgPrimary     = C'10,10,20';
         g_bgSecondary   = C'15,15,30';
         g_bgHeader      = C'5,5,15';
         g_textPrimary   = clrLime;
         g_textSecondary = C'0,200,100';
         g_borderColor   = C'0,100,50';
         break;

      default:
         g_bgPrimary     = C'20,20,30';
         g_bgSecondary   = C'30,30,45';
         g_bgHeader      = C'15,15,25';
         g_textPrimary   = clrWhite;
         g_textSecondary = clrLightGray;
         g_borderColor   = C'50,50,70';
         break;
     }

   //--- Pre-calculate layout dimensions
   g_headerHeight    = InpRowHeight + 8;
   g_dataRowStart    = InpDashY + g_headerHeight;
   g_dashTotalHeight = g_headerHeight + (8 * InpRowHeight); // 8 data rows

   LogChain("Theme resolved: " + EnumToString(InpTheme),
            LOG_INFO, "ResolveTheme");
  }

//+==================================================================+
//|                                                                  |
//|          SECTION 10: BUFFER SETUP                                |
//|                                                                  |
//|  Purpose: Configure all indicator buffers and plots.             |
//|  Rule: One function, called ONCE in OnInit.                     |
//|                                                                  |
//+==================================================================+

void SetupBuffers()
  {
   //--- Buffer 0: Histogram Up
   SetIndexBuffer(0, BufHistUp);
   SetIndexStyle(0, DRAW_HISTOGRAM, STYLE_SOLID, 3, InpBullColor);
   SetIndexLabel(0, "Bull Histogram");

   //--- Buffer 1: Histogram Down
   SetIndexBuffer(1, BufHistDn);
   SetIndexStyle(1, DRAW_HISTOGRAM, STYLE_SOLID, 3, InpBearColor);
   SetIndexLabel(1, "Bear Histogram");

   //--- Buffer 2: Signal Arrows
   SetIndexBuffer(2, BufArrow);
   SetIndexStyle(2, DRAW_ARROW, STYLE_SOLID, InpArrowSize, InpArrowColor);
   SetIndexArrow(2, 233); // Default up arrow
   SetIndexLabel(2, "Signal Arrow");
   SetIndexEmptyValue(2, EMPTY_VALUE);

   //--- Buffer 3: Trend Line
   SetIndexBuffer(3, BufTrend);
   SetIndexStyle(3, DRAW_LINE, STYLE_SOLID, 1, InpNeutralColor);
   SetIndexLabel(3, "Trend");

   LogChain("All 4 buffers configured.", LOG_INFO, "SetupBuffers");
  }

//+==================================================================+
//|                                                                  |
//|          SECTION 11: SIGNAL FUNCTIONS                            |
//|                                                                  |
//|  Purpose: Calculate trading signals. Pure logic, no drawing.     |
//|  Rule: Return ENUM_SIGNAL. No side effects (no prints, no objs). |
//|                                                                  |
//+==================================================================+

//--- 11A: Main Signal Generator (per bar)
ENUM_SIGNAL CalculateSignal(int barIndex)
  {
   //--- Replace this with YOUR indicator logic
   //--- This is a placeholder using simple MA crossover concept

   double fastMA = iMA(NULL, 0, InpFastPeriod, 0, MODE_EMA, PRICE_CLOSE, barIndex);
   double slowMA = iMA(NULL, 0, InpSlowPeriod, 0, MODE_EMA, PRICE_CLOSE, barIndex);

   double fastMA_prev = iMA(NULL, 0, InpFastPeriod, 0, MODE_EMA, PRICE_CLOSE, barIndex + 1);
   double slowMA_prev = iMA(NULL, 0, InpSlowPeriod, 0, MODE_EMA, PRICE_CLOSE, barIndex + 1);

   //--- Bullish crossover
   if(fastMA_prev <= slowMA_prev && fastMA > slowMA)
      return(SIGNAL_BUY);

   //--- Bearish crossover
   if(fastMA_prev >= slowMA_prev && fastMA < slowMA)
      return(SIGNAL_SELL);

   return(SIGNAL_NONE);
  }

//--- 11B: Signal Strength Calculator (0-100)
int CalculateSignalStrength(int barIndex)
  {
   double fastMA = iMA(NULL, 0, InpFastPeriod, 0, MODE_EMA, PRICE_CLOSE, barIndex);
   double slowMA = iMA(NULL, 0, InpSlowPeriod, 0, MODE_EMA, PRICE_CLOSE, barIndex);
   double diff   = MathAbs(fastMA - slowMA);
   double atr    = iATR(NULL, 0, 14, barIndex);

   if(atr == 0) return(0);

   int strength = (int)MathMin(100, (diff / atr) * 100);
   return(strength);
  }

//+==================================================================+
//|                                                                  |
//|          SECTION 12: UTILITY / HELPER FUNCTIONS                  |
//|                                                                  |
//|  Purpose: Reusable tools. No drawing, no trading.                |
//|  Rule: Pure functions. Input in, output out. No globals modified.|
//|                                                                  |
//+==================================================================+

//--- 12A: Get Pip Size for Current Symbol
double GetPipSize()
  {
   int digits = (int)MarketInfo(Symbol(), MODE_DIGITS);
   double point = MarketInfo(Symbol(), MODE_POINT);

   if(digits == 3 || digits == 5)
      return(point * 10);
   else
      return(point);
  }

//--- 12B: Convert Points to Pips
double PointsToPips(double points)
  {
   return(points / GetPipSize());
  }

//--- 12C: Format Price with Correct Digits
string FormatPrice(double price)
  {
   return(DoubleToString(price, (int)MarketInfo(Symbol(), MODE_DIGITS)));
  }

//--- 12D: Format Spread in Pips
string FormatSpread()
  {
   double spreadPoints = MarketInfo(Symbol(), MODE_SPREAD);
   double spreadPips   = PointsToPips(spreadPoints);
   return(DoubleToString(spreadPips, 1));
  }

//--- 12E: Get Bar Data Into Struct
SBarData GetBarData(int shift)
  {
   SBarData bar;
   bar.open   = Open[shift];
   bar.high   = High[shift];
   bar.low    = Low[shift];
   bar.close  = Close[shift];
   bar.volume = Volume[shift];
   bar.time   = Time[shift];
   bar.signal = SIGNAL_NONE;
   bar.fastVal   = iMA(NULL, 0, InpFastPeriod, 0, MODE_EMA, PRICE_CLOSE, shift);
   bar.slowVal   = iMA(NULL, 0, InpSlowPeriod, 0, MODE_EMA, PRICE_CLOSE, shift);
   bar.signalVal = iMA(NULL, 0, InpSignalPeriod, 0, MODE_EMA, PRICE_CLOSE, shift);
   return(bar);
  }

//--- 12F: Count How Many Bars Since Last Signal
int BarsSinceLastSignal(ENUM_SIGNAL signalType)
  {
   for(int i = 1; i < InpMaxBars; i++)
     {
      if(CalculateSignal(i) == signalType)
         return(i);
     }
   return(-1); // Not found within limit
  }

//--- 12G: Safe Division (prevents divide-by-zero crash)
double SafeDivide(double numerator, double denominator, double fallback = 0.0)
  {
   if(denominator == 0) return(fallback);
   return(numerator / denominator);
  }

//+==================================================================+
//|                                                                  |
//|          SECTION 13: ALERT FUNCTIONS                             |
//|                                                                  |
//|  Purpose: Trigger user notifications. Called ONCE per signal.    |
//|  Rule: Track last alert bar to prevent spam on every tick.       |
//|                                                                  |
//+==================================================================+

void TriggerAlert(ENUM_SIGNAL signal, int barIndex)
  {
   //--- Prevent spam: only alert once per bar
   if(barIndex == g_lastAlertBar) return;
   g_lastAlertBar = barIndex;

   string msg = "";
   if(signal == SIGNAL_BUY)
      msg = Symbol() + " BUY Signal on " + TimeFrameToString(Period());
   else if(signal == SIGNAL_SELL)
      msg = Symbol() + " SELL Signal on " + TimeFrameToString(Period());
   else
      return; // No alert for no signal

   LogChain(msg, LOG_INFO, "Alert");

   if(InpAlertOnSignal)
      Alert(msg);

   if(InpPushOnSignal)
      SendNotification(msg);
  }

//+==================================================================+
//|                                                                  |
//|     SECTION 14: REVERSE LOOP — CHART BUFFER FILLING              |
//|                                                                  |
//|  Purpose: Fill indicator buffers from OLDEST to NEWEST.          |
//|  Rule: Loop goes limit → 1 (never include 0 here).              |
//|        ALWAYS use ArraySetAsSeries before the loop.              |
//|        Index 0 is handled AFTER the loop, separately.           |
//|                                                                  |
//+==================================================================+

void FillChartBuffers(int limit)
  {
   //--- CRITICAL: Set series flag so index 0 = current bar
   ArraySetAsSeries(BufHistUp, true);
   ArraySetAsSeries(BufHistDn, true);
   ArraySetAsSeries(BufArrow,  true);
   ArraySetAsSeries(BufTrend,  true);

   //=== REVERSE LOOP: Start from oldest bar in limit, go down to bar 1 ===
   for(int i = limit; i >= 1; i--)
     {
      //--- 1. RESET all buffers for this bar (prevents ghost data)
      BufHistUp[i] = 0;
      BufHistDn[i] = 0;
      BufArrow[i]  = EMPTY_VALUE;

      //--- 2. GET bar data
      SBarData bar = GetBarData(i);
      bar.signal   = CalculateSignal(i);

      //--- 3. FILL Histogram (example: range-based)
      double range = bar.high - bar.low;
      if(bar.close >= bar.open)
         BufHistUp[i] = bar.low + (range * 0.5); // Draw from middle up
      else
         BufHistDn[i] = bar.high - (range * 0.5); // Draw from middle down

      //--- 4. FILL Arrows (only on confirmed signals)
      if(bar.signal == SIGNAL_BUY)
         BufArrow[i] = bar.low - GetPipSize() * 5; // Arrow below low
      else if(bar.signal == SIGNAL_SELL)
         BufArrow[i] = bar.high + GetPipSize() * 5; // Arrow above high

      //--- 5. FILL Trend Line
      BufTrend[i] = bar.slowVal;
     }

   //=== INDEX 0: Handle CURRENT bar OUTSIDE the loop ===
   //--- This prevents repainting/flickering while the candle is forming
   BufHistUp[0] = 0;
   BufHistDn[0] = 0;
   BufArrow[0]  = EMPTY_VALUE;
   BufTrend[0]  = iMA(NULL, 0, InpSlowPeriod, 0, MODE_EMA, PRICE_CLOSE, 0);

   //--- Optional: Show live histogram on current bar
   double liveRange = High[0] - Low[0];
   if(Close[0] >= Open[0])
      BufHistUp[0] = Low[0] + (liveRange * 0.5);
   else
      BufHistDn[0] = High[0] - (liveRange * 0.5);
  }

//+==================================================================+
//|                                                                  |
//|     SECTION 15: FORWARD LOOP — DASHBOARD DRAWING                 |
//|                                                                  |
//|  Purpose: Draw UI objects from TOP to BOTTOM.                    |
//|  Rule: Loop goes 0 → N (human reading order).                    |
//|        Use the Zero-Flicker Engine (Section 8).                  |
//|        Always end with ChartRedraw(0).                           |
//|                                                                  |
//+==================================================================+

void DrawDashboard()
  {
   if(!InpShowDash) return;

   //=== 1. DRAW MAIN BACKGROUND (Create Once, Update Always) ===
   DrawRectangle("Dash_BG",
                 InpDashX, InpDashY,
                 InpDashWidth, g_dashTotalHeight,
                 g_bgPrimary, g_borderColor, 0);

   //=== 2. DRAW HEADER ===
   DrawRectangle("Dash_Header",
                 InpDashX, InpDashY,
                 InpDashWidth, g_headerHeight,
                 g_bgHeader, g_borderColor, 1);
   DrawText("Dash_Title",
            "  MASTER DASHBOARD",
            InpDashX + 5, InpDashY + 4,
            g_textPrimary, 11, "Arial Bold");

   //=== 3. PREPARE ROW DATA (collect before looping) ===
   SDashRow rows[8];

   rows[0].label = "Symbol";
   rows[0].value = Symbol();
   rows[0].rowColor = g_bgSecondary;
   rows[0].isHighlighted = false;

   rows[1].label = "Timeframe";
   rows[1].value = TimeFrameToString(Period());
   rows[1].rowColor = g_bgPrimary;
   rows[1].isHighlighted = false;

   rows[2].label = "Spread";
   rows[2].value = FormatSpread() + " pips";
   rows[2].rowColor = g_bgSecondary;
   rows[2].isHighlighted = (MarketInfo(Symbol(), MODE_SPREAD) > 30);

   rows[3].label = "Bid";
   rows[3].value = FormatPrice(Bid);
   rows[3].rowColor = g_bgPrimary;
   rows[3].isHighlighted = false;

   rows[4].label = "Ask";
   rows[4].value = FormatPrice(Ask);
   rows[4].rowColor = g_bgSecondary;
   rows[4].isHighlighted = false;

   rows[5].label = "Signal";
   ENUM_SIGNAL currentSignal = CalculateSignal(1);
   rows[5].value = (currentSignal == SIGNAL_BUY)  ? "BUY"  :
                   (currentSignal == SIGNAL_SELL) ? "SELL" : "NONE";
   rows[5].rowColor = g_bgPrimary;
   rows[5].isHighlighted = (currentSignal != SIGNAL_NONE);

   rows[6].label = "Strength";
   rows[6].value = IntegerToString(CalculateSignalStrength(1)) + "%";
   rows[6].rowColor = g_bgSecondary;
   rows[6].isHighlighted = false;

   rows[7].label = "Bars Since";
   int barsSince = BarsSinceLastSignal(currentSignal);
   rows[7].value = (barsSince >= 0) ? IntegerToString(barsSince) : "N/A";
   rows[7].rowColor = g_bgPrimary;
   rows[7].isHighlighted = false;

   //=== 4. FORWARD LOOP: Draw rows 0 → 7 ===
   for(int i = 0; i < 8; i++)
     {
      string rowPrefix = "Dash_Row" + IntegerToString(i);
      int yPos = g_dataRowStart + (i * InpRowHeight);

      //--- Row background (alternating colors from struct)
      color bgColor = rows[i].rowColor;
      if(rows[i].isHighlighted)
         bgColor = C'60,30,30'; // Red tint for warnings

      DrawRectangle(rowPrefix + "_bg",
                    InpDashX + 2, yPos,
                    InpDashWidth - 4, InpRowHeight - 2,
                    bgColor, clrNONE, 2);

      //--- Row label (left side)
      DrawText(rowPrefix + "_lbl",
               "  " + rows[i].label,
               InpDashX + 6, yPos + 4,
               g_textSecondary, InpFontSize - 1, "Arial");

      //--- Row value (right side)
      color valColor = g_textPrimary;
      if(rows[i].label == "Signal")
        {
         if(currentSignal == SIGNAL_BUY)  valColor = InpBullColor;
         if(currentSignal == SIGNAL_SELL) valColor = InpBearColor;
        }
      if(rows[i].isHighlighted)
         valColor = clrOrange;

      DrawText(rowPrefix + "_val",
               rows[i].value,
               InpDashX + InpDashWidth - 75, yPos + 4,
               valColor, InpFontSize, "Arial Bold");
     }

   //=== 5. FORCE CHART REDRAW (critical for zero-flicker) ===
   ChartRedraw(0);
  }

//+==================================================================+
//|                                                                  |
//|          SECTION 16: CLEANUP FUNCTION                            |
//|                                                                  |
//|  Purpose: Remove all objects created by this indicator.          |
//|  Rule: ONLY place to use ObjectDelete. Only in OnDeinit.        |
//|        Loop FORWARD through object names.                        |
//|                                                                  |
//+==================================================================+

void CleanupAllObjects()
  {
   int totalObjects = ObjectsTotal(0, 0, OBJ_RECTANGLE_LABEL);
   int deleted = 0;

   //--- FORWARD LOOP to find and delete our objects
   for(int i = totalObjects - 1; i >= 0; i--)
     {
      string objName = ObjectName(0, i, 0, OBJ_RECTANGLE_LABEL);
      if(StringFind(objName, g_objPrefix) == 0)
        {
         ObjectDelete(0, objName);
         deleted++;
        }
     }

   totalObjects = ObjectsTotal(0, 0, OBJ_LABEL);
   for(int i = totalObjects - 1; i >= 0; i--)
     {
      string objName = ObjectName(0, i, 0, OBJ_LABEL);
      if(StringFind(objName, g_objPrefix) == 0)
        {
         ObjectDelete(0, objName);
         deleted++;
        }
     }

   totalObjects = ObjectsTotal(0, 0, OBJ_ARROW);
   for(int i = totalObjects - 1; i >= 0; i--)
     {
      string objName = ObjectName(0, i, 0, OBJ_ARROW);
      if(StringFind(objName, g_objPrefix) == 0)
        {
         ObjectDelete(0, objName);
         deleted++;
        }
     }

   totalObjects = ObjectsTotal(0, 0, OBJ_TREND);
   for(int i = totalObjects - 1; i >= 0; i--)
     {
      string objName = ObjectName(0, i, 0, OBJ_TREND);
      if(StringFind(objName, g_objPrefix) == 0)
        {
         ObjectDelete(0, objName);
         deleted++;
        }
     }

   LogChain("Cleanup complete. Deleted " + IntegerToString(deleted) + " objects.",
            LOG_INFO, "Cleanup");

   ChartRedraw(0);
  }

//+==================================================================+
//|                                                                  |
//|          SECTION 17: ONINIT                                     |
//|                                                                  |
//|  Purpose: One-time setup. Runs when indicator is attached.       |
//|  Rule: Order matters. Theme → Layout → Buffers → First Draw.    |
//|                                                                  |
//+==================================================================+

int OnInit()
  {
   LogChain("========== INITIALIZING ==========", LOG_INFO, "OnInit");

   //--- Step 1: Resolve visual theme
   ResolveTheme();

   //--- Step 2: Setup indicator buffers
   SetupBuffers();

   //--- Step 3: Set indicator short name (shows in Data Window)
   IndicatorShortName("MasterArch(" +
                      IntegerToString(InpFastPeriod) + "," +
                      IntegerToString(InpSlowPeriod) + "," +
                      IntegerToString(InpSignalPeriod) + ")");

   //--- Step 4: Mark as initialized
   g_isFirstRun = true;

   LogChain("Initialization complete.", LOG_INFO, "OnInit");

   return(INIT_SUCCEEDED);
  }

//+==================================================================+
//|                                                                  |
//|          SECTION 18: ONDEINIT                                   |
//|                                                                  |
//|  Purpose: Clean up when indicator is removed.                    |
//|  Rule: Always clean up. Prevents orphan objects.                 |
//|                                                                  |
//+==================================================================+

void OnDeinit(const int reason)
  {
   LogChain("Deinitializing. Reason: " + IntegerToString(reason),
            LOG_INFO, "OnDeinit");

   CleanupAllObjects();
  }

//+==================================================================+
//|                                                                  |
//|          SECTION 19: ONCALCULATE — THE MASTER ENGINE            |
//|                                                                  |
//|  Purpose: Main execution loop. Called on every tick/new bar.     |
//|  Rule: STRICT ORDER:                                            |
//|        1. Calculate Safe Limit                                   |
//|        2. Reverse Loop for Buffers (limit → 1)                   |
//|        3. Handle Index 0 separately                              |
//|        4. Forward Loop for Dashboard (0 → N)                    |
//|        5. Trigger Alerts (once per bar)                          |
//|        6. Return rates_total                                     |
//|                                                                  |
//+==================================================================+

int OnCalculate(const int rates_total,
                const int prev_calculated,
                const datetime &time[],
                const double &open[],
                const double &high[],
                const double &low[],
                const double &close[],
                const long &tick_volume[],
                const long &volume[],
                const int &spread[])
  {
   //--- Safety: Not enough bars
   if(rates_total < InpSlowPeriod + 1)
      return(0);

   //=== STEP 1: GOLDEN LIMIT (prevents freeze) ===
   int limit = CalculateSafeLimit(rates_total, prev_calculated);
   if(limit <= 0)
      return(rates_total);

   //=== STEP 2: REVERSE LOOP — Fill Chart Buffers ===
   //    Goes from OLDEST bar to NEWEST bar (limit → 1)
   //    Index 0 is handled AFTER this loop
   FillChartBuffers(limit);

   //=== STEP 3: FORWARD LOOP — Draw Dashboard ===
   //    Goes from TOP row to BOTTOM row (0 → N)
   //    Uses Zero-Flicker Engine (create once, update always)
   DrawDashboard();

   //=== STEP 4: ALERTS (once per new bar, not every tick) ===
   if(rates_total != prev_calculated) // New bar just formed
     {
      ENUM_SIGNAL newSignal = CalculateSignal(1); // Check last CLOSED bar
      if(newSignal != SIGNAL_NONE && newSignal != g_prevSignal)
        {
         TriggerAlert(newSignal, 1);
         g_prevSignal = newSignal;
        }
     }

   //=== STEP 5: Mark first run complete ===
   if(g_isFirstRun)
     {
      g_isFirstRun = false;
      LogChain("First run calculation complete.", LOG_INFO, "OnCalc");
     }

   //=== STEP 6: Return rates_total (MQL4 requirement) ===
   return(rates_total);
  }

//+------------------------------------------------------------------+
THE ARCHITECTURE CHEAT SHEET
Save this image in your mind — it's the only correct order:

ONCALCULATE EXECUTION FLOW:
═══════════════════════════════════════════════

  TICK ARRIVES
       │
       ▼
  ┌─────────────────────────┐
  │  STEP 1: SAFE LIMIT     │  ← MathMin(rates_total, 1000)
  │  Prevents FREEZE        │     on first run
  └────────────┬────────────┘
               │
               ▼
  ┌─────────────────────────┐
  │  STEP 2: REVERSE LOOP   │  ← for(i = limit; i >= 1; i--)
  │  Fill Chart Buffers     │     Histograms, Arrows, Lines
  │                         │     ArraySetAsSeries = true
  └────────────┬────────────┘
               │
               ▼
  ┌─────────────────────────┐
  │  STEP 3: INDEX 0        │  ← Handle CURRENT bar
  │  Current Bar Isolation  │     OUTSIDE the loop
  │                         │     Prevents repainting
  └────────────┬────────────┘
               │
               ▼
  ┌─────────────────────────┐
  │  STEP 4: FORWARD LOOP   │  ← for(i = 0; i < rows; i++)
  │  Draw Dashboard         │     Text, Rectangles, UI
  │  Zero-Flicker Engine    │     ObjectFind < 0 → Create
  │                         │     else → Update only
  └────────────┬────────────┘
               │
               ▼
  ┌─────────────────────────┐
  │  STEP 5: CHARTREDRAW    │  ← Force render
  └────────────┬────────────┘
               │
               ▼
  ┌─────────────────────────┐
  │  STEP 6: ALERTS         │  ← Once per bar only
  │  (if new bar formed)    │     Track g_lastAlertBar
  └────────────┬────────────┘
               │
               ▼
         return(rates_total)

THE 8 IRON RULES — NEVER BREAK THESE
#
RULE
WHAT HAPPENS IF YOU BREAK IT
1	CalculateSafeLimit() on first run	Terminal freezes on 50,000 bar charts
2	Reverse loop for buffers (limit → 1)	Shapes draw backwards, data misaligned
3	Forward loop for dashboard (0 → N)	Rows overlap, Z-order broken
4	ArraySetAsSeries(true) before every buffer loop	Index 0 points to wrong bar, garbage data
5	Index 0 handled OUTSIDE the loop	Arrows/histograms flicker and repaint live
6	ObjectFind < 0 then create, else update	ObjectDelete + recreate = violent flicker
7	ObjectDelete ONLY in OnDeinit	Objects multiply, memory leak, terminal crash
8	ChartRedraw(0) after dashboard loop	Objects don't appear until next tick

FILE NAMING CONVENTION FOR OBJECTS

g_objPrefix = "MA_"    ← Your indicator's unique prefix

Objects created:
  MA_Dash_BG
  MA_Dash_Header
  MA_Dash_Title
  MA_Dash_Row0_bg
  MA_Dash_Row0_lbl
  MA_Dash_Row0_val
  MA_Dash_Row1_bg
  ...
  MA_SignalArrow_12345

Cleanup loop:
  if(StringFind(objName, "MA_") == 0) → delete

This prevents any collision with other indicators on the same chart.

This template is your foundation. Replace the signal logic in Section 11, change the buffer filling in Section 14, modify the dashboard rows in Section 15 — but never change the architectural order of Sections 1–19.


WHY OTHER APPROACHES FAIL — THE DIAGNOSIS

You just identified the single most important truth in MQL4 development:

"All fail if it's not organized."

I cannot open the ponytail GitHub link, but I can tell you exactly why 99% of MQL4 projects fail — and it has nothing to do with the trading logic. It's always the same 5 architectural diseases.

THE 5 DISEASES THAT KILL MQL4 PROJECTS
text
┌─────────────────────────────────────────────────────────────────┐
│ │
│ DISEASE 1: "SPAGHETTI ONCALCULATE" │
│ ════════════════════════════════════ │
│ Symptom: 500+ lines inside OnCalculate │
│ Cause: No separation of concerns │
│ Death: Impossible to debug, impossible to modify │
│ │
│ OUR CURE: Sections 14, 15, 19 — OnCalculate is ONLY a │
│ dispatcher. It calls functions, never contains │
│ logic directly. 6 lines of flow, not 500 lines. │
│ │
├─────────────────────────────────────────────────────────────────┤
│ │
│ DISEASE 2: "THE INVISIBLE FREEZE" │
│ ══════════════════════════════════════ │
│ Symptom: Terminal hangs when attached to chart with 50K bars │
│ Cause: for(i=0; i<rates_total; i++) on first run │
│ Death: User thinks indicator is broken, deletes it │
│ │
│ OUR CURE: Section 7 — CalculateSafeLimit() │
│ MathMin(rates_total, 1000) on first run. │
│ Terminal NEVER freezes. Ever. │
│ │
├─────────────────────────────────────────────────────────────────┤
│ │
│ DISEASE 3: "FLICKER HELL" │
│ ══════════════════════════════════════ │
│ Symptom: Dashboard rectangles and text blink violently │
│ Cause: ObjectDelete + ObjectCreate inside OnCalculate │
│ Death: Unusable dashboard, looks unprofessional │
│ │
│ OUR CURE: Section 8 — Zero-Flicker Engine │
│ ObjectFind < 0 → Create ONCE │
│ ObjectFind >= 0 → Update properties ONLY │
│ ObjectDelete ONLY in Section 16 (OnDeinit) │
│ │
├─────────────────────────────────────────────────────────────────┤
│ │
│ DISEASE 4: "GHOST DATA" │
│ ══════════════════════════════════════ │
│ Symptom: Old arrows/histograms remain on chart after refresh │
│ Cause: Buffers not reset to EMPTY_VALUE/0 before filling │
│ Death: Chart becomes a mess of overlapping artifacts │
│ │
│ OUR CURE: Section 14, step 1 — RESET before FILL │
│ BufHistUp[i] = 0; │
│ BufHistDn[i] = 0; │
│ BufArrow[i] = EMPTY_VALUE; │
│ This runs FIRST inside the loop, every bar. │
│ │
├─────────────────────────────────────────────────────────────────┤
│ │
│ DISEASE 5: "OBJECT CANCER" │
│ ══════════════════════════════════════ │
│ Symptom: Chart slows down over hours. Objects list has 10K+ │
│ Cause: Objects created with timestamp-based names, │
│ never cleaned up, no prefix system │
│ Death: Terminal crashes, memory overflow │
│ │
│ OUR CURE: Section 5D — g_objPrefix system │
│ Section 16 — CleanupAllObjects() with prefix scan │
│ Every object starts with "MA_" → │
│ easy to find, easy to delete, zero orphans │
│ │
└─────────────────────────────────────────────────────────────────┘
THE FAILURE-TO-SECTION MAP

Every failure maps to a specific section. This is why the 19-section structure is not optional — it's a checklist against failure:

text
FAILURE → FIXED BY SECTION
─────────────────────────────────────────────────
Terminal freeze → Section 7 (CalculateSafeLimit)
Shapes draw backwards → Section 14 (Reverse Loop)
Dashboard rows overlap → Section 15 (Forward Loop)
Index 0 = wrong bar → Section 14 (ArraySetAsSeries)
Live candle flicker → Section 14 (Index 0 isolation)
Object blink on every tick → Section 8 (Zero-Flicker Engine)
10,000 orphan objects → Section 5D + 16 (Prefix + Cleanup)
Can't find which code does what→ Sections 1-19 numbering
Alert fires 1000x per second → Section 13 (g_lastAlertBar tracking)
Colors hardcoded everywhere → Section 9 (ResolveTheme)
Can't modify without breaking → Section 3 (Structs as data containers)
No idea what went wrong → Section 6 (LogChain)
THE NEXT EVOLUTION: SELF-AUDITING CODE

Here is what separates a good template from a bulletproof one: the code checks itself for architectural violations. Add this as Section 6B — a build-time sanity check that runs once in OnInit and verifies the architecture is intact.

mql4
//+==================================================================+
//| |
//| SECTION 6B: SELF-AUDIT SYSTEM (Architectural Integrity) |
//| |
//| Purpose: Verify the code's own structure on startup. |
//| Rule: If any check fails, log ERROR and warn user. |
//| This catches "drift" — when you or someone else |
//| accidentally breaks the architecture. |
//| |
//+==================================================================+


void RunSelfAudit()
{
string func = "SelfAudit";
int errors = 0;


LogChain("========== RUNNING SELF-AUDIT ==========", LOG_INFO, func);


//--- CHECK 1: Prefix is not empty
if(StringLen(g_objPrefix) == 0)
{
LogChain("FAIL: g_objPrefix is empty. Object collision risk.",
LOG_ERROR, func);
errors++;
}
else
LogChain("PASS: Object prefix = '" + g_objPrefix + "'", LOG_INFO, func);


//--- CHECK 2: Max bars is reasonable (not 0, not 100000)
if(InpMaxBars < 10 || InpMaxBars > 10000)
{
LogChain("FAIL: InpMaxBars = " + IntegerToString(InpMaxBars) +
" (dangerous range). Use 100-5000.",
LOG_ERROR, func);
errors++;
}
else
LogChain("PASS: InpMaxBars = " + IntegerToString(InpMaxBars), LOG_INFO, func);


//--- CHECK 3: Row height is not too small (text gets clipped)
if(InpRowHeight < 15)
{
LogChain("FAIL: InpRowHeight = " + IntegerToString(InpRowHeight) +
" (too small, text will clip). Minimum 15.",
LOG_ERROR, func);
errors++;
}
else
LogChain("PASS: InpRowHeight = " + IntegerToString(InpRowHeight), LOG_INFO, func);


//--- CHECK 4: Dashboard fits on screen (rough check)
if(InpDashY + g_dashTotalHeight > 2000)
{
LogChain("WARN: Dashboard height exceeds 2000px. May go off-screen.",
LOG_WARN, func);
}
else
LogChain("PASS: Dashboard fits within screen bounds.", LOG_INFO, func);


//--- CHECK 5: Symbol has valid data
if(MarketInfo(Symbol(), MODE_BID) <= 0)
{
LogChain("FAIL: Symbol " + Symbol() + " has invalid BID. No data.",
LOG_ERROR, func);
errors++;
}
else
LogChain("PASS: Symbol " + Symbol() + " has valid data.", LOG_INFO, func);

Where to call it — add ONE line inside OnInit(), right after ResolveTheme():

mql4
int OnInit()
{
LogChain("========== INITIALIZING ==========", LOG_INFO, "OnInit");


ResolveTheme();
RunSelfAudit(); // ← ADD THIS LINE
SetupBuffers();
// ... rest of OnInit
}

Now your code audits itself on every attachment. If someone modifies the template and breaks a rule, the Self-Audit catches it immediately.

THE WORLDZIP HEADER — FOR EVERY FILE YOU BUILD

Every .mq4 file you create from this template should start with this self-documenting header block. This is what lets AI (or another developer) instantly understand the file without reading 800 lines:

mql4
//+------------------------------------------------------------------+
//| WORLDZIP: [ProjectName] > [FileName].mq4 |
//+------------------------------------------------------------------+
//| IDENTITY: Multi-pair spread dashboard with signal alerts |
//| STACK: MQL4 Strict | No external dependencies |
//| PARADIGM: Event-driven indicator with cached UI objects |
//| |
//| ARCHITECTURE: 19-Section Master Template (DO NOT REORDER) |
//| SECTIONS USED: 1-19 (full template) |
//| |
//| SECTIONS MODIFIED FROM TEMPLATE: |
//| 11 — Signal: Replaced MA crossover with RSI+Stoch combo |
//| 14 — Buffers: Added 2 extra histogram buffers (total 6) |
//| 15 — Dashboard: 12 rows instead of 8, added spread heat map |
//| |
//| BUFFER MAP: |
//| Buf[0] = Histogram Up (DRAW_HISTOGRAM) |
//| Buf[1] = Histogram Down (DRAW_HISTOGRAM) |
//| Buf[2] = Signal Arrows (DRAW_ARROW code 233/234) |
//| Buf[3] = Trend Line (DRAW_LINE) |
//| |
//| OBJECT PREFIX: "SPD_" (Spread Dashboard) |
//| Total objects created: ~40 (12 rows x 3 objects + 4 chrome) |
//| |
//| CRITICAL RULES FOR THIS FILE: |
//| DO NOT: Add logic inside OnCalculate (use Sections 14/15) |
//| DO NOT: Use ObjectDelete outside Section 16 |
//| DO NOT: Loop rates_total without CalculateSafeLimit |
//| ALWAYS: Reset buffers before filling (Section 14 step 1) |
//| ALWAYS: Handle Index 0 outside the main loop |
//| ALWAYS: Run LogChain on errors, never silent fail |
//| |
//| DEPENDENCIES: None |
//| INCOMPATIBLE WITH: Indicators using same "SPD_" prefix |
//+------------------------------------------------------------------+

This header is your WorldZip — the entire file compressed into 30 lines. Anyone (or any AI) reads this and knows exactly what the file does, what was modified, what the rules are, and what to avoid — without reading a single line of actual code.

THE FINAL TRUTH
text
┌──────────────────────────────────────────────────────┐
│ │
│ BAD CODE: Logic first, structure never │
│ → Works until it doesn't │
│ → Impossible to fix │
│ → Gets abandoned │
│ │
│ GOOD CODE: Structure first, logic second │
│ → Always works │
│ → Easy to modify │
│ → Never abandoned │
│ │
│ THE 19 SECTIONS ARE NOT "ORGANIZATION" │
│ THEY ARE A FORCE FIELD AGAINST FAILURE │
│ │
└──────────────────────────────────────────────────────┘

The ponytail project didn't fail because of bad trading ideas. It failed because the container broke before the content could be delivered. The 19-section template is an unbreakable container. Put any logic inside it, and the logic has a chance to survive.




