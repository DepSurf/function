# Function: <code>nhmex_mbox_get_shared_reg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool nhmex_mbox_get_shared_reg(struct intel_uncore_box *box, int idx, u64 config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81017bb0)
Location: arch/x86/events/intel/uncore_nhmex.c:546
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
```
**Symbols:**

```
ffffffff81017bb0-ffffffff81017d9a: nhmex_mbox_get_shared_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool nhmex_mbox_get_shared_reg(struct intel_uncore_box *box, int idx, u64 config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81016df0)
Location: arch/x86/events/intel/uncore_nhmex.c:552
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
```
**Symbols:**

```
ffffffff81016df0-ffffffff81016fd2: nhmex_mbox_get_shared_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool nhmex_mbox_get_shared_reg(struct intel_uncore_box *box, int idx, u64 config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81017000)
Location: arch/x86/events/intel/uncore_nhmex.c:552
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
```
**Symbols:**

```
ffffffff81017000-ffffffff810171e2: nhmex_mbox_get_shared_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool nhmex_mbox_get_shared_reg(struct intel_uncore_box *box, int idx, u64 config);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81015e00)
Location: arch/x86/events/intel/uncore_nhmex.c:552
Inline: True
Direct callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
```
**Symbols:**

```
ffffffff81015e00-ffffffff81015fc3: nhmex_mbox_get_shared_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool nhmex_mbox_get_shared_reg(struct intel_uncore_box *box, int idx, u64 config);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810161c0)
Location: arch/x86/events/intel/uncore_nhmex.c:553
Inline: True
Direct callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
```
**Symbols:**

```
ffffffff810161c0-ffffffff81016383: nhmex_mbox_get_shared_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool nhmex_mbox_get_shared_reg(struct intel_uncore_box *box, int idx, u64 config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81015ff0)
Location: arch/x86/events/intel/uncore_nhmex.c:553
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
```
**Symbols:**

```
ffffffff81015ff0-ffffffff810161a8: nhmex_mbox_get_shared_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool nhmex_mbox_get_shared_reg(struct intel_uncore_box *box, int idx, u64 config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81016770)
Location: arch/x86/events/intel/uncore_nhmex.c:553
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
```
**Symbols:**

```
ffffffff81016770-ffffffff81016928: nhmex_mbox_get_shared_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool nhmex_mbox_get_shared_reg(struct intel_uncore_box *box, int idx, u64 config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810184b0)
Location: arch/x86/events/intel/uncore_nhmex.c:553
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
```
**Symbols:**

```
ffffffff810184b0-ffffffff81018663: nhmex_mbox_get_shared_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool nhmex_mbox_get_shared_reg(struct intel_uncore_box *box, int idx, u64 config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81018e40)
Location: arch/x86/events/intel/uncore_nhmex.c:553
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
```
**Symbols:**

```
ffffffff81018e40-ffffffff81018ff3: nhmex_mbox_get_shared_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool nhmex_mbox_get_shared_reg(struct intel_uncore_box *box, int idx, u64 config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101a660)
Location: arch/x86/events/intel/uncore_nhmex.c:553
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
```
**Symbols:**

```
ffffffff8101a660-ffffffff8101a818: nhmex_mbox_get_shared_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool nhmex_mbox_get_shared_reg(struct intel_uncore_box *box, int idx, u64 config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101ab50)
Location: arch/x86/events/intel/uncore_nhmex.c:553
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
```
**Symbols:**

```
ffffffff8101ab50-ffffffff8101ad08: nhmex_mbox_get_shared_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool nhmex_mbox_get_shared_reg(struct intel_uncore_box *box, int idx, u64 config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101bef0)
Location: arch/x86/events/intel/uncore_nhmex.c:553
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
```
**Symbols:**

```
ffffffff8101bef0-ffffffff8101c0a6: nhmex_mbox_get_shared_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool nhmex_mbox_get_shared_reg(struct intel_uncore_box *box, int idx, u64 config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore_nhmex.c (0)
Location: arch/x86/events/intel/uncore_nhmex.c:553
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
```
**Symbols:**

```
ffffffff8101f160-ffffffff8101f351: nhmex_mbox_get_shared_reg (STB_LOCAL)
ffffffff81c969f2-ffffffff81c96a64: nhmex_mbox_get_shared_reg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool nhmex_mbox_get_shared_reg(struct intel_uncore_box *box, int idx, u64 config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore_nhmex.c (0)
Location: arch/x86/events/intel/uncore_nhmex.c:553
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
```
**Symbols:**

```
ffffffff81021e80-ffffffff81022098: nhmex_mbox_get_shared_reg (STB_LOCAL)
ffffffff81e45e90-ffffffff81e45ee9: nhmex_mbox_get_shared_reg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool nhmex_mbox_get_shared_reg(struct intel_uncore_box *box, int idx, u64 config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore_nhmex.c (0)
Location: arch/x86/events/intel/uncore_nhmex.c:553
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
```
**Symbols:**

```
ffffffff81026a20-ffffffff81026c38: nhmex_mbox_get_shared_reg (STB_LOCAL)
ffffffff820514d3-ffffffff8205152c: nhmex_mbox_get_shared_reg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool nhmex_mbox_get_shared_reg(struct intel_uncore_box *box, int idx, u64 config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore_nhmex.c (0)
Location: arch/x86/events/intel/uncore_nhmex.c:553
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
```
**Symbols:**

```
ffffffff81026a00-ffffffff81026c1e: nhmex_mbox_get_shared_reg (STB_LOCAL)
ffffffff820cf9db-ffffffff820cfa38: nhmex_mbox_get_shared_reg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool nhmex_mbox_get_shared_reg(struct intel_uncore_box *box, int idx, u64 config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore_nhmex.c (0)
Location: arch/x86/events/intel/uncore_nhmex.c:553
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
```
**Symbols:**

```
ffffffff8102cb60-ffffffff8102cd7e: nhmex_mbox_get_shared_reg (STB_LOCAL)
ffffffff821aa349-ffffffff821aa3a6: nhmex_mbox_get_shared_reg.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
bool nhmex_mbox_get_shared_reg(struct intel_uncore_box *box, int idx, u64 config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81018e40)
Location: arch/x86/events/intel/uncore_nhmex.c:553
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
```
**Symbols:**

```
ffffffff81018e40-ffffffff81018ff3: nhmex_mbox_get_shared_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool nhmex_mbox_get_shared_reg(struct intel_uncore_box *box, int idx, u64 config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81018210)
Location: arch/x86/events/intel/uncore_nhmex.c:553
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
```
**Symbols:**

```
ffffffff81018210-ffffffff810183c3: nhmex_mbox_get_shared_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool nhmex_mbox_get_shared_reg(struct intel_uncore_box *box, int idx, u64 config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81018e00)
Location: arch/x86/events/intel/uncore_nhmex.c:553
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
```
**Symbols:**

```
ffffffff81018e00-ffffffff81018fb3: nhmex_mbox_get_shared_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool nhmex_mbox_get_shared_reg(struct intel_uncore_box *box, int idx, u64 config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81019040)
Location: arch/x86/events/intel/uncore_nhmex.c:553
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_constraint
```
**Symbols:**

```
ffffffff81019040-ffffffff810191f3: nhmex_mbox_get_shared_reg (STB_LOCAL)
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
No changes between <code>5.0</code> and <code>5.3</code> ✅
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
