# Function: <code>__reset_isolation_pfn</code>

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
bool __reset_isolation_pfn(struct zone *zone, long unsigned int pfn, bool check_source, bool check_target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81245b40)
Location: mm/compaction.c:241
Inline: False
Direct callers:
  - mm/compaction.c:__reset_isolation_suitable
  - mm/compaction.c:__reset_isolation_suitable
```
**Symbols:**

```
ffffffff81245b40-ffffffff81245e4e: __reset_isolation_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool __reset_isolation_pfn(struct zone *zone, long unsigned int pfn, bool check_source, bool check_target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81254000)
Location: mm/compaction.c:241
Inline: False
Direct callers:
  - mm/compaction.c:__reset_isolation_suitable
  - mm/compaction.c:__reset_isolation_suitable
```
**Symbols:**

```
ffffffff81254000-ffffffff8125432b: __reset_isolation_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool __reset_isolation_pfn(struct zone *zone, long unsigned int pfn, bool check_source, bool check_target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81280ba0)
Location: mm/compaction.c:241
Inline: False
Direct callers:
  - mm/compaction.c:__reset_isolation_suitable
  - mm/compaction.c:__reset_isolation_suitable
```
**Symbols:**

```
ffffffff81280ba0-ffffffff81280ed4: __reset_isolation_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool __reset_isolation_pfn(struct zone *zone, long unsigned int pfn, bool check_source, bool check_target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8128aeb0)
Location: mm/compaction.c:258
Inline: False
Direct callers:
  - mm/compaction.c:__reset_isolation_suitable
  - mm/compaction.c:__reset_isolation_suitable
```
**Symbols:**

```
ffffffff8128aeb0-ffffffff8128b1d7: __reset_isolation_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool __reset_isolation_pfn(struct zone *zone, long unsigned int pfn, bool check_source, bool check_target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812902f0)
Location: mm/compaction.c:257
Inline: False
Direct callers:
  - mm/compaction.c:__reset_isolation_suitable
  - mm/compaction.c:__reset_isolation_suitable
```
**Symbols:**

```
ffffffff812902f0-ffffffff81290504: __reset_isolation_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool __reset_isolation_pfn(struct zone *zone, long unsigned int pfn, bool check_source, bool check_target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812d0340)
Location: mm/compaction.c:257
Inline: False
Direct callers:
  - mm/compaction.c:__reset_isolation_suitable
  - mm/compaction.c:__reset_isolation_suitable
```
**Symbols:**

```
ffffffff812d0340-ffffffff812d058d: __reset_isolation_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool __reset_isolation_pfn(struct zone *zone, long unsigned int pfn, bool check_source, bool check_target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813301b0)
Location: mm/compaction.c:257
Inline: False
Direct callers:
  - mm/compaction.c:__reset_isolation_suitable
  - mm/compaction.c:__reset_isolation_suitable
```
**Symbols:**

```
ffffffff813301b0-ffffffff813304e3: __reset_isolation_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __reset_isolation_pfn(struct zone *zone, long unsigned int pfn, bool check_source, bool check_target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813a6e50)
Location: mm/compaction.c:252
Inline: False
Direct callers:
  - mm/compaction.c:__reset_isolation_suitable
  - mm/compaction.c:__reset_isolation_suitable
```
**Symbols:**

```
ffffffff813a6e50-ffffffff813a70ca: __reset_isolation_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool __reset_isolation_pfn(struct zone *zone, long unsigned int pfn, bool check_source, bool check_target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813da640)
Location: mm/compaction.c:278
Inline: False
Direct callers:
  - mm/compaction.c:__reset_isolation_suitable
  - mm/compaction.c:__reset_isolation_suitable
```
**Symbols:**

```
ffffffff813da640-ffffffff813da8cf: __reset_isolation_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool __reset_isolation_pfn(struct zone *zone, long unsigned int pfn, bool check_source, bool check_target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81404530)
Location: mm/compaction.c:303
Inline: False
Direct callers:
  - mm/compaction.c:__reset_isolation_suitable
  - mm/compaction.c:__reset_isolation_suitable
```
**Symbols:**

```
ffffffff81404530-ffffffff814047b8: __reset_isolation_pfn (STB_LOCAL)
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
bool __reset_isolation_pfn(struct zone *zone, long unsigned int pfn, bool check_source, bool check_target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffff8000102e99a0)
Location: mm/compaction.c:241
Inline: False
Direct callers:
  - mm/compaction.c:__reset_isolation_suitable
  - mm/compaction.c:__reset_isolation_suitable
  - mm/compaction.c:__reset_isolation_suitable
```
**Symbols:**

```
ffff8000102e99a0-ffff8000102e9c98: __reset_isolation_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool __reset_isolation_pfn(struct zone *zone, long unsigned int pfn, bool check_source, bool check_target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (c050d260)
Location: mm/compaction.c:241
Inline: False
Direct callers:
  - mm/compaction.c:__reset_isolation_suitable
  - mm/compaction.c:__reset_isolation_suitable
```
**Symbols:**

```
c050d260-c050d4dc: __reset_isolation_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool __reset_isolation_pfn(struct zone *zone, long unsigned int pfn, bool check_source, bool check_target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (c0000000003ae800)
Location: mm/compaction.c:241
Inline: False
Direct callers:
  - mm/compaction.c:__reset_isolation_suitable
  - mm/compaction.c:__reset_isolation_suitable
```
**Symbols:**

```
c0000000003ae800-c0000000003aec04: __reset_isolation_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool __reset_isolation_pfn(struct zone *zone, long unsigned int pfn, bool check_source, bool check_target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffe000200070)
Location: mm/compaction.c:241
Inline: False
Direct callers:
  - mm/compaction.c:__reset_isolation_suitable
  - mm/compaction.c:__reset_isolation_suitable
```
**Symbols:**

```
ffffffe000200070-ffffffe0002002d4: __reset_isolation_pfn (STB_LOCAL)
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
bool __reset_isolation_pfn(struct zone *zone, long unsigned int pfn, bool check_source, bool check_target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8124c650)
Location: mm/compaction.c:241
Inline: False
Direct callers:
  - mm/compaction.c:__reset_isolation_suitable
  - mm/compaction.c:__reset_isolation_suitable
```
**Symbols:**

```
ffffffff8124c650-ffffffff8124c97b: __reset_isolation_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool __reset_isolation_pfn(struct zone *zone, long unsigned int pfn, bool check_source, bool check_target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8123f5f0)
Location: mm/compaction.c:241
Inline: False
Direct callers:
  - mm/compaction.c:__reset_isolation_suitable
  - mm/compaction.c:__reset_isolation_suitable
```
**Symbols:**

```
ffffffff8123f5f0-ffffffff8123f91b: __reset_isolation_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool __reset_isolation_pfn(struct zone *zone, long unsigned int pfn, bool check_source, bool check_target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8124a3f0)
Location: mm/compaction.c:241
Inline: False
Direct callers:
  - mm/compaction.c:__reset_isolation_suitable
  - mm/compaction.c:__reset_isolation_suitable
```
**Symbols:**

```
ffffffff8124a3f0-ffffffff8124a71b: __reset_isolation_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool __reset_isolation_pfn(struct zone *zone, long unsigned int pfn, bool check_source, bool check_target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81259c50)
Location: mm/compaction.c:241
Inline: False
Direct callers:
  - mm/compaction.c:__reset_isolation_suitable
  - mm/compaction.c:__reset_isolation_suitable
```
**Symbols:**

```
ffffffff81259c50-ffffffff81259f7b: __reset_isolation_pfn (STB_LOCAL)
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
