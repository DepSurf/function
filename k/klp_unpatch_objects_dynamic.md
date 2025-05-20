# Function: <code>klp_unpatch_objects_dynamic</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void klp_unpatch_objects_dynamic(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff81120d70)
Location: kernel/livepatch/patch.c:293
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_discard_nops
```
**Symbols:**

```
ffffffff81120d70-ffffffff81120d85: klp_unpatch_objects_dynamic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void klp_unpatch_objects_dynamic(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff8112d460)
Location: kernel/livepatch/patch.c:293
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_discard_nops
```
**Symbols:**

```
ffffffff8112d460-ffffffff8112d475: klp_unpatch_objects_dynamic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void klp_unpatch_objects_dynamic(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff8113bb90)
Location: kernel/livepatch/patch.c:294
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_discard_nops
```
**Symbols:**

```
ffffffff8113bb90-ffffffff8113bbe2: klp_unpatch_objects_dynamic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void klp_unpatch_objects_dynamic(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff81136330)
Location: kernel/livepatch/patch.c:301
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_discard_nops
```
**Symbols:**

```
ffffffff81136330-ffffffff81136382: klp_unpatch_objects_dynamic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void klp_unpatch_objects_dynamic(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff81137130)
Location: kernel/livepatch/patch.c:301
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_discard_nops
```
**Symbols:**

```
ffffffff81137130-ffffffff81137182: klp_unpatch_objects_dynamic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void klp_unpatch_objects_dynamic(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/patch.c (0)
Location: kernel/livepatch/patch.c:301
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_discard_nops
```
**Symbols:**

```
ffffffff81caffa8-ffffffff81caffbd: klp_unpatch_objects_dynamic.cold (STB_LOCAL)
ffffffff81159dd0-ffffffff81159e35: klp_unpatch_objects_dynamic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void klp_unpatch_objects_dynamic(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/patch.c (0)
Location: kernel/livepatch/patch.c:286
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_discard_nops
```
**Symbols:**

```
ffffffff81e60bb8-ffffffff81e60bcd: klp_unpatch_objects_dynamic.cold (STB_LOCAL)
ffffffff81183400-ffffffff8118346f: klp_unpatch_objects_dynamic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void klp_unpatch_objects_dynamic(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/patch.c (0)
Location: kernel/livepatch/patch.c:286
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_discard_nops
```
**Symbols:**

```
ffffffff8205a65d-ffffffff8205a672: klp_unpatch_objects_dynamic.cold (STB_LOCAL)
ffffffff811be560-ffffffff811be5cf: klp_unpatch_objects_dynamic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void klp_unpatch_objects_dynamic(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/patch.c (0)
Location: kernel/livepatch/patch.c:286
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_discard_nops
```
**Symbols:**

```
ffffffff820d8ed1-ffffffff820d8ee6: klp_unpatch_objects_dynamic.cold (STB_LOCAL)
ffffffff811d0f90-ffffffff811d0fff: klp_unpatch_objects_dynamic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void klp_unpatch_objects_dynamic(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/patch.c (0)
Location: kernel/livepatch/patch.c:286
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_discard_nops
```
**Symbols:**

```
ffffffff821b460a-ffffffff821b461f: klp_unpatch_objects_dynamic.cold (STB_LOCAL)
ffffffff811e5c10-ffffffff811e5c7f: klp_unpatch_objects_dynamic (STB_GLOBAL)
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void klp_unpatch_objects_dynamic(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (c0000000001f1fc0)
Location: kernel/livepatch/patch.c:293
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_discard_nops
```
**Symbols:**

```
c0000000001f1fc0-c0000000001f1fd8: klp_unpatch_objects_dynamic (STB_GLOBAL)
```
</details>
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
void klp_unpatch_objects_dynamic(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff81125a40)
Location: kernel/livepatch/patch.c:293
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_discard_nops
```
**Symbols:**

```
ffffffff81125a40-ffffffff81125a55: klp_unpatch_objects_dynamic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void klp_unpatch_objects_dynamic(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff811184a0)
Location: kernel/livepatch/patch.c:293
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_discard_nops
```
**Symbols:**

```
ffffffff811184a0-ffffffff811184b5: klp_unpatch_objects_dynamic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void klp_unpatch_objects_dynamic(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff81123930)
Location: kernel/livepatch/patch.c:293
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_discard_nops
```
**Symbols:**

```
ffffffff81123930-ffffffff81123945: klp_unpatch_objects_dynamic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void klp_unpatch_objects_dynamic(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff8112ff50)
Location: kernel/livepatch/patch.c:293
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_discard_nops
```
**Symbols:**

```
ffffffff8112ff50-ffffffff8112ff65: klp_unpatch_objects_dynamic (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
