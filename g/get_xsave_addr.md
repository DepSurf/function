# Function: <code>get_xsave_addr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *get_xsave_addr(struct xregs_state *xsave, int xstate_feature);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103b490)
Location: arch/x86/kernel/fpu/xstate.c:688
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr
```
**Symbols:**

```
ffffffff8103b490-ffffffff8103b516: get_xsave_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *get_xsave_addr(struct xregs_state *xsave, int xstate_feature);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103b230)
Location: arch/x86/kernel/fpu/xstate.c:804
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr
```
**Symbols:**

```
ffffffff8103b230-ffffffff8103b2a8: get_xsave_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *get_xsave_addr(struct xregs_state *xsave, int xstate_feature);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103ab10)
Location: arch/x86/kernel/fpu/xstate.c:809
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr
```
**Symbols:**

```
ffffffff8103ab10-ffffffff8103ab88: get_xsave_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *get_xsave_addr(struct xregs_state *xsave, int xstate_feature);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff810385b0)
Location: arch/x86/kernel/fpu/xstate.c:816
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr
```
**Symbols:**

```
ffffffff810385b0-ffffffff81038656: get_xsave_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *get_xsave_addr(struct xregs_state *xsave, int xstate_feature);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103a7f0)
Location: arch/x86/kernel/fpu/xstate.c:843
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr
```
**Symbols:**

```
ffffffff8103a7f0-ffffffff8103a896: get_xsave_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *get_xsave_addr(struct xregs_state *xsave, int xstate_feature);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103bcf0)
Location: arch/x86/kernel/fpu/xstate.c:843
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr
```
**Symbols:**

```
ffffffff8103bcf0-ffffffff8103bd96: get_xsave_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *get_xsave_addr(struct xregs_state *xsave, int xstate_feature);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103d1b0)
Location: arch/x86/kernel/fpu/xstate.c:841
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr
```
**Symbols:**

```
ffffffff8103d1b0-ffffffff8103d256: get_xsave_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *get_xsave_addr(struct xregs_state *xsave, int xfeature_nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103fa80)
Location: arch/x86/kernel/fpu/xstate.c:833
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/mm/pkeys.c:init_pkru_write_file
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
**Symbols:**

```
ffffffff8103fa80-ffffffff8103fb22: get_xsave_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void *get_xsave_addr(struct xregs_state *xsave, int xfeature_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff810401a0)
Location: arch/x86/kernel/fpu/xstate.c:833
Inline: True
Direct callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/mm/pkeys.c:init_pkru_write_file
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
**Symbols:**

```
ffffffff810401a0-ffffffff81040242: get_xsave_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *get_xsave_addr(struct xregs_state *xsave, int xfeature_nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81043450)
Location: arch/x86/kernel/fpu/xstate.c:886
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/mm/pkeys.c:init_pkru_write_file
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
**Symbols:**

```
ffffffff81043450-ffffffff810434ec: get_xsave_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *get_xsave_addr(struct xregs_state *xsave, int xfeature_nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81043420)
Location: arch/x86/kernel/fpu/xstate.c:926
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/fpu/xstate.c:update_pasid
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/mm/pkeys.c:init_pkru_write_file
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
**Symbols:**

```
ffffffff81043420-ffffffff810434bc: get_xsave_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *get_xsave_addr(struct xregs_state *xsave, int xfeature_nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81044d20)
Location: arch/x86/kernel/fpu/xstate.c:961
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/mm/pkeys.c:init_pkru_write_file
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
**Symbols:**

```
ffffffff81044d20-ffffffff81044dbc: get_xsave_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *get_xsave_addr(struct xregs_state *xsave, int xfeature_nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (0)
Location: arch/x86/kernel/fpu/xstate.c:877
Inline: False
```
**Symbols:**

```
ffffffff81c99f62-ffffffff81c9a020: get_xsave_addr.cold (STB_LOCAL)
ffffffff8104b400-ffffffff8104b4e2: get_xsave_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *get_xsave_addr(struct xregs_state *xsave, int xfeature_nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (0)
Location: arch/x86/kernel/fpu/xstate.c:964
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:fpu_copy_uabi_to_guest_fpstate
  - arch/x86/kernel/fpu/xstate.c:fpstate_clear_xstate_component
```
**Symbols:**

```
ffffffff81e49965-ffffffff81e499a5: get_xsave_addr.cold (STB_LOCAL)
ffffffff81056250-ffffffff810562cf: get_xsave_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *get_xsave_addr(struct xregs_state *xsave, int xfeature_nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (0)
Location: arch/x86/kernel/fpu/xstate.c:959
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:fpstate_clear_xstate_component
```
**Symbols:**

```
ffffffff8205268a-ffffffff820526ca: get_xsave_addr.cold (STB_LOCAL)
ffffffff81063ec0-ffffffff81063f3f: get_xsave_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *get_xsave_addr(struct xregs_state *xsave, int xfeature_nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (0)
Location: arch/x86/kernel/fpu/xstate.c:966
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:fpstate_clear_xstate_component
```
**Symbols:**

```
ffffffff820d0b5b-ffffffff820d0b98: get_xsave_addr.cold (STB_LOCAL)
ffffffff81065810-ffffffff81065881: get_xsave_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *get_xsave_addr(struct xregs_state *xsave, int xfeature_nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (0)
Location: arch/x86/kernel/fpu/xstate.c:962
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/regset.c:ssp_set
  - arch/x86/kernel/fpu/regset.c:ssp_get
  - arch/x86/kernel/fpu/xstate.c:fpstate_clear_xstate_component
```
**Symbols:**

```
ffffffff821ab684-ffffffff821ab6c1: get_xsave_addr.cold (STB_LOCAL)
ffffffff8106cc70-ffffffff8106cce1: get_xsave_addr (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void *get_xsave_addr(struct xregs_state *xsave, int xfeature_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040320)
Location: arch/x86/kernel/fpu/xstate.c:833
Inline: True
Direct callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/mm/pkeys.c:init_pkru_write_file
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
**Symbols:**

```
ffffffff81040320-ffffffff810403c2: get_xsave_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void *get_xsave_addr(struct xregs_state *xsave, int xfeature_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8102fb20)
Location: arch/x86/kernel/fpu/xstate.c:833
Inline: True
Direct callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/mm/pkeys.c:init_pkru_write_file
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
**Symbols:**

```
ffffffff8102fb20-ffffffff8102fbc2: get_xsave_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void *get_xsave_addr(struct xregs_state *xsave, int xfeature_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040160)
Location: arch/x86/kernel/fpu/xstate.c:833
Inline: True
Direct callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/mm/pkeys.c:init_pkru_write_file
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
**Symbols:**

```
ffffffff81040160-ffffffff81040202: get_xsave_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void *get_xsave_addr(struct xregs_state *xsave, int xfeature_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81041530)
Location: arch/x86/kernel/fpu/xstate.c:833
Inline: True
Direct callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/mm/pkeys.c:init_pkru_write_file
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
**Symbols:**

```
ffffffff81041530-ffffffff810415d2: get_xsave_addr (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int xfeature_nr</code>
</li>
<li>
<b>Param removed. </b>
<code>int xstate_feature</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
