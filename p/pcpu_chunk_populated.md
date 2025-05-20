# Function: <code>pcpu_chunk_populated</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811b14c2)
Location: mm/percpu.c:770
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_balance_workfn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811cad19)
Location: mm/percpu.c:765
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811dae39)
Location: mm/percpu.c:765
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pcpu_chunk_populated(struct pcpu_chunk *chunk, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811e2b30)
Location: mm/percpu.c:756
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff811e2b30-ffffffff811e2b5c: pcpu_chunk_populated (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pcpu_chunk_populated(struct pcpu_chunk *chunk, int page_start, int page_end, bool for_alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811f81c0)
Location: mm/percpu.c:1229
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff811f81c0-ffffffff811f81fd: pcpu_chunk_populated (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pcpu_chunk_populated(struct pcpu_chunk *chunk, int page_start, int page_end, bool for_alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81219470)
Location: mm/percpu.c:1226
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff81219470-ffffffff812194ad: pcpu_chunk_populated (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pcpu_chunk_populated(struct pcpu_chunk *chunk, int page_start, int page_end, bool for_alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8122c3d0)
Location: mm/percpu.c:1235
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff8122c3d0-ffffffff8122c417: pcpu_chunk_populated (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pcpu_chunk_populated(struct pcpu_chunk *chunk, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8123c170)
Location: mm/percpu.c:1472
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff8123c170-ffffffff8123c1b4: pcpu_chunk_populated (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pcpu_chunk_populated(struct pcpu_chunk *chunk, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8124a5c0)
Location: mm/percpu.c:1472
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff8124a5c0-ffffffff8124a604: pcpu_chunk_populated (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pcpu_chunk_populated(struct pcpu_chunk *chunk, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81278820)
Location: mm/percpu.c:1444
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff81278820-ffffffff81278864: pcpu_chunk_populated (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pcpu_chunk_populated(struct pcpu_chunk *chunk, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81283090)
Location: mm/percpu.c:1481
Inline: False
Direct callers:
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff81283090-ffffffff812830da: pcpu_chunk_populated (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pcpu_chunk_populated(struct pcpu_chunk *chunk, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81289260)
Location: mm/percpu.c:1482
Inline: False
Direct callers:
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff81289260-ffffffff812892b5: pcpu_chunk_populated (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pcpu_chunk_populated(struct pcpu_chunk *chunk, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/percpu.c (0)
Location: mm/percpu.c:1523
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff812c8e50-ffffffff812c8eac: pcpu_chunk_populated (STB_LOCAL)
ffffffff81cbafd7-ffffffff81cbafeb: pcpu_chunk_populated.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pcpu_chunk_populated(struct pcpu_chunk *chunk, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/percpu.c (0)
Location: mm/percpu.c:1523
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff81326af0-ffffffff81326b58: pcpu_chunk_populated (STB_LOCAL)
ffffffff81e6cb8c-ffffffff81e6cba0: pcpu_chunk_populated.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void pcpu_chunk_populated(struct pcpu_chunk *chunk, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/percpu.c (0)
Location: mm/percpu.c:1520
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff8139b780-ffffffff8139b7e8: pcpu_chunk_populated (STB_LOCAL)
ffffffff8206302c-ffffffff82063040: pcpu_chunk_populated.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void pcpu_chunk_populated(struct pcpu_chunk *chunk, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/percpu.c (0)
Location: mm/percpu.c:1520
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff813ce760-ffffffff813ce7c8: pcpu_chunk_populated (STB_LOCAL)
ffffffff820e28c9-ffffffff820e28dd: pcpu_chunk_populated.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void pcpu_chunk_populated(struct pcpu_chunk *chunk, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/percpu.c (0)
Location: mm/percpu.c:1520
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff813f92c0-ffffffff813f9328: pcpu_chunk_populated (STB_LOCAL)
ffffffff821bf2ba-ffffffff821bf2ce: pcpu_chunk_populated.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void pcpu_chunk_populated(struct pcpu_chunk *chunk, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffff8000102e0320)
Location: mm/percpu.c:1472
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffff8000102e0320-ffff8000102e03a4: pcpu_chunk_populated (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pcpu_chunk_populated(struct pcpu_chunk *chunk, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (c0504b1c)
Location: mm/percpu.c:1472
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
c0504b1c-c0504b90: pcpu_chunk_populated (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pcpu_chunk_populated(struct pcpu_chunk *chunk, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (c00000000039fb20)
Location: mm/percpu.c:1472
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
c00000000039fb20-c00000000039fbcc: pcpu_chunk_populated (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pcpu_chunk_populated(struct pcpu_chunk *chunk, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffe0001f7ce2)
Location: mm/percpu.c:1472
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffe0001f7ce2-ffffffe0001f7d60: pcpu_chunk_populated (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void pcpu_chunk_populated(struct pcpu_chunk *chunk, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81242c10)
Location: mm/percpu.c:1472
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff81242c10-ffffffff81242c54: pcpu_chunk_populated (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pcpu_chunk_populated(struct pcpu_chunk *chunk, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81235be0)
Location: mm/percpu.c:1472
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff81235be0-ffffffff81235c24: pcpu_chunk_populated (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pcpu_chunk_populated(struct pcpu_chunk *chunk, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812409b0)
Location: mm/percpu.c:1472
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff812409b0-ffffffff812409f4: pcpu_chunk_populated (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pcpu_chunk_populated(struct pcpu_chunk *chunk, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81250130)
Location: mm/percpu.c:1472
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff81250130-ffffffff81250174: pcpu_chunk_populated (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool for_alloc</code>
</li>
</ul>
</details>
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
<b>Param removed. </b>
<code>bool for_alloc</code>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
