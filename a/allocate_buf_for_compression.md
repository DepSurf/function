# Function: <code>allocate_buf_for_compression</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void allocate_buf_for_compression();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff813230be)
Location: fs/pstore/platform.c:197
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_register
```
**Symbols:**

```
ffffffff813230be-ffffffff813231b2: allocate_buf_for_compression (STB_LOCAL)
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
In fs/pstore/platform.c (ffffffff81356277)
Location: fs/pstore/platform.c:429
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_register
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
In fs/pstore/platform.c (ffffffff8136c690)
Location: fs/pstore/platform.c:429
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_register
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff813804c0)
Location: fs/pstore/platform.c:433
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_register
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff813a54d0)
Location: fs/pstore/platform.c:433
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_register
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff813d4699)
Location: fs/pstore/platform.c:259
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void allocate_buf_for_compression();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (ffffffff813eebaa)
Location: fs/pstore/platform.c:299
Inline: True
Direct callers:
  - fs/pstore/platform.c:pstore_init
  - fs/pstore/platform.c:pstore_register
```
**Symbols:**

```
ffffffff813eeb60-ffffffff813eec6b: allocate_buf_for_compression (STB_LOCAL)
ffffffff813ef3fe-ffffffff813ef456: allocate_buf_for_compression.cold.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void allocate_buf_for_compression();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:287
Inline: True
Direct callers:
  - fs/pstore/platform.c:pstore_init
  - fs/pstore/platform.c:pstore_register
```
**Symbols:**

```
ffffffff8141ae30-ffffffff8141aed6: allocate_buf_for_compression.part.0 (STB_LOCAL)
ffffffff8141b680-ffffffff8141b6ef: allocate_buf_for_compression.part.0.cold (STB_LOCAL)
ffffffff8141aee0-ffffffff8141af2c: allocate_buf_for_compression (STB_LOCAL)
ffffffff8141b6ef-ffffffff8141b70b: allocate_buf_for_compression.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void allocate_buf_for_compression();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:287
Inline: True
Direct callers:
  - fs/pstore/platform.c:pstore_init
  - fs/pstore/platform.c:pstore_register
```
**Symbols:**

```
ffffffff81434c80-ffffffff81434d26: allocate_buf_for_compression.part.0 (STB_LOCAL)
ffffffff814354d0-ffffffff8143553f: allocate_buf_for_compression.part.0.cold (STB_LOCAL)
ffffffff81434d30-ffffffff81434d7c: allocate_buf_for_compression (STB_LOCAL)
ffffffff8143553f-ffffffff8143555b: allocate_buf_for_compression.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void allocate_buf_for_compression();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:284
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_init
  - fs/pstore/platform.c:pstore_register
```
**Symbols:**

```
ffffffff81484a40-ffffffff81484b22: allocate_buf_for_compression (STB_LOCAL)
ffffffff8148525c-ffffffff814852e7: allocate_buf_for_compression.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void allocate_buf_for_compression();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:284
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_init
  - fs/pstore/platform.c:pstore_register
```
**Symbols:**

```
ffffffff814a2070-ffffffff814a2152: allocate_buf_for_compression (STB_LOCAL)
ffffffff81bef8cc-ffffffff81bef957: allocate_buf_for_compression.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void allocate_buf_for_compression();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:284
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_init
  - fs/pstore/platform.c:pstore_register
```
**Symbols:**

```
ffffffff814a8110-ffffffff814a81f2: allocate_buf_for_compression (STB_LOCAL)
ffffffff81be1975-ffffffff81be1a00: allocate_buf_for_compression.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void allocate_buf_for_compression();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:284
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_init
  - fs/pstore/platform.c:pstore_register
```
**Symbols:**

```
ffffffff81500430-ffffffff81500512: allocate_buf_for_compression (STB_LOCAL)
ffffffff81cd2610-ffffffff81cd269b: allocate_buf_for_compression.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void allocate_buf_for_compression();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:285
Inline: True
Direct callers:
  - fs/pstore/platform.c:pstore_init
  - fs/pstore/platform.c:pstore_register
```
**Symbols:**

```
ffffffff81591890-ffffffff81591941: allocate_buf_for_compression.part.0 (STB_LOCAL)
ffffffff81e857b4-ffffffff81e85821: allocate_buf_for_compression.part.0.cold (STB_LOCAL)
ffffffff81591950-ffffffff815919b4: allocate_buf_for_compression (STB_LOCAL)
ffffffff81e85821-ffffffff81e8583d: allocate_buf_for_compression.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void allocate_buf_for_compression();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (ffffffff81638f00)
Location: fs/pstore/platform.c:287
Inline: True
Direct callers:
  - fs/pstore/platform.c:pstore_init
  - fs/pstore/platform.c:pstore_register
```
**Symbols:**

```
ffffffff81638f00-ffffffff8163902f: allocate_buf_for_compression.part.0 (STB_LOCAL)
ffffffff81639040-ffffffff816390c5: allocate_buf_for_compression (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void allocate_buf_for_compression();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (ffffffff81671340)
Location: fs/pstore/platform.c:287
Inline: True
Direct callers:
  - fs/pstore/platform.c:pstore_init
  - fs/pstore/platform.c:pstore_register
```
**Symbols:**

```
ffffffff81671340-ffffffff8167146f: allocate_buf_for_compression.part.0 (STB_LOCAL)
ffffffff81671480-ffffffff81671505: allocate_buf_for_compression (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff816ad0cb)
Location: fs/pstore/platform.c:204
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_register
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void allocate_buf_for_compression();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffff80001051ab90)
Location: fs/pstore/platform.c:287
Inline: True
Direct callers:
  - fs/pstore/platform.c:pstore_init
  - fs/pstore/platform.c:pstore_register
```
**Symbols:**

```
ffff80001051ab90-ffff80001051acfc: allocate_buf_for_compression (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void allocate_buf_for_compression();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (c06d4fd0)
Location: fs/pstore/platform.c:287
Inline: True
Direct callers:
  - fs/pstore/platform.c:pstore_init
  - fs/pstore/platform.c:pstore_register
```
**Symbols:**

```
c06d4fd0-c06d5114: allocate_buf_for_compression (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void allocate_buf_for_compression();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (c0000000006647d0)
Location: fs/pstore/platform.c:287
Inline: True
Direct callers:
  - fs/pstore/platform.c:pstore_init
  - fs/pstore/platform.c:pstore_register
```
**Symbols:**

```
c0000000006647d0-c000000000664954: allocate_buf_for_compression.part.0 (STB_LOCAL)
c000000000664960-c000000000664a18: allocate_buf_for_compression (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void allocate_buf_for_compression();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffe000383bee)
Location: fs/pstore/platform.c:287
Inline: True
Direct callers:
  - fs/pstore/platform.c:pstore_init
  - fs/pstore/platform.c:pstore_register
```
**Symbols:**

```
ffffffe000383bee-ffffffe000383d22: allocate_buf_for_compression (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void allocate_buf_for_compression();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:287
Inline: True
Direct callers:
  - fs/pstore/platform.c:pstore_init
  - fs/pstore/platform.c:pstore_register
```
**Symbols:**

```
ffffffff8142d260-ffffffff8142d306: allocate_buf_for_compression.part.0 (STB_LOCAL)
ffffffff8142dab0-ffffffff8142db1f: allocate_buf_for_compression.part.0.cold (STB_LOCAL)
ffffffff8142d310-ffffffff8142d35c: allocate_buf_for_compression (STB_LOCAL)
ffffffff8142db1f-ffffffff8142db3b: allocate_buf_for_compression.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void allocate_buf_for_compression();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:287
Inline: True
Direct callers:
  - fs/pstore/platform.c:pstore_init
  - fs/pstore/platform.c:pstore_register
```
**Symbols:**

```
ffffffff8141dce0-ffffffff8141dd86: allocate_buf_for_compression.part.0 (STB_LOCAL)
ffffffff8141e530-ffffffff8141e59f: allocate_buf_for_compression.part.0.cold (STB_LOCAL)
ffffffff8141dd90-ffffffff8141dddc: allocate_buf_for_compression (STB_LOCAL)
ffffffff8141e59f-ffffffff8141e5bb: allocate_buf_for_compression.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void allocate_buf_for_compression();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:287
Inline: True
Direct callers:
  - fs/pstore/platform.c:pstore_init
  - fs/pstore/platform.c:pstore_register
```
**Symbols:**

```
ffffffff81429400-ffffffff814294a6: allocate_buf_for_compression.part.0 (STB_LOCAL)
ffffffff81429c50-ffffffff81429cbf: allocate_buf_for_compression.part.0.cold (STB_LOCAL)
ffffffff814294b0-ffffffff814294fc: allocate_buf_for_compression (STB_LOCAL)
ffffffff81429cbf-ffffffff81429cdb: allocate_buf_for_compression.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void allocate_buf_for_compression();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:287
Inline: True
Direct callers:
  - fs/pstore/platform.c:pstore_init
  - fs/pstore/platform.c:pstore_register
```
**Symbols:**

```
ffffffff814402c0-ffffffff81440366: allocate_buf_for_compression.part.0 (STB_LOCAL)
ffffffff81440b10-ffffffff81440b7f: allocate_buf_for_compression.part.0.cold (STB_LOCAL)
ffffffff81440370-ffffffff814403bc: allocate_buf_for_compression (STB_LOCAL)
ffffffff81440b7f-ffffffff81440b9b: allocate_buf_for_compression.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
