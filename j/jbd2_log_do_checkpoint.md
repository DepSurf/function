# Function: <code>jbd2_log_do_checkpoint</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int jbd2_log_do_checkpoint(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/checkpoint.c (ffffffff812ecc30)
Location: fs/jbd2/checkpoint.c:208
Inline: False
Direct callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_flush
```
**Symbols:**

```
ffffffff812ecc30-ffffffff812ed089: jbd2_log_do_checkpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int jbd2_log_do_checkpoint(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/checkpoint.c (ffffffff8131a6a0)
Location: fs/jbd2/checkpoint.c:208
Inline: False
Direct callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffff8131a6a0-ffffffff8131ab00: jbd2_log_do_checkpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int jbd2_log_do_checkpoint(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/checkpoint.c (ffffffff81330690)
Location: fs/jbd2/checkpoint.c:208
Inline: False
Direct callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffff81330690-ffffffff81330aec: jbd2_log_do_checkpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int jbd2_log_do_checkpoint(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/checkpoint.c (ffffffff813455b0)
Location: fs/jbd2/checkpoint.c:208
Inline: False
Direct callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffff813455b0-ffffffff81345a51: jbd2_log_do_checkpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int jbd2_log_do_checkpoint(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/checkpoint.c (ffffffff81369c60)
Location: fs/jbd2/checkpoint.c:208
Inline: False
Direct callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffff81369c60-ffffffff8136a0f3: jbd2_log_do_checkpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int jbd2_log_do_checkpoint(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/checkpoint.c (0)
Location: fs/jbd2/checkpoint.c:205
Inline: False
Direct callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffff81398b23-ffffffff81398b49: jbd2_log_do_checkpoint.cold.9 (STB_LOCAL)
ffffffff813983e0-ffffffff8139881c: jbd2_log_do_checkpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int jbd2_log_do_checkpoint(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/checkpoint.c (0)
Location: fs/jbd2/checkpoint.c:205
Inline: False
Direct callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffff813b1893-ffffffff813b18b9: jbd2_log_do_checkpoint.cold.10 (STB_LOCAL)
ffffffff813b1150-ffffffff813b158c: jbd2_log_do_checkpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int jbd2_log_do_checkpoint(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/checkpoint.c (0)
Location: fs/jbd2/checkpoint.c:204
Inline: False
Direct callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffff813dbeb2-ffffffff813dbed6: jbd2_log_do_checkpoint.cold (STB_LOCAL)
ffffffff813db7c0-ffffffff813dbbbf: jbd2_log_do_checkpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int jbd2_log_do_checkpoint(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/checkpoint.c (0)
Location: fs/jbd2/checkpoint.c:204
Inline: False
Direct callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffff813f5f22-ffffffff813f5f46: jbd2_log_do_checkpoint.cold (STB_LOCAL)
ffffffff813f5810-ffffffff813f5c0f: jbd2_log_do_checkpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int jbd2_log_do_checkpoint(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/checkpoint.c (0)
Location: fs/jbd2/checkpoint.c:204
Inline: False
Direct callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffff814432c5-ffffffff814432e9: jbd2_log_do_checkpoint.cold (STB_LOCAL)
ffffffff81442bb0-ffffffff81442fb2: jbd2_log_do_checkpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int jbd2_log_do_checkpoint(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/checkpoint.c (0)
Location: fs/jbd2/checkpoint.c:206
Inline: False
Direct callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffff81becee1-ffffffff81becf05: jbd2_log_do_checkpoint.cold (STB_LOCAL)
ffffffff8145ed50-ffffffff8145f112: jbd2_log_do_checkpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int jbd2_log_do_checkpoint(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/checkpoint.c (0)
Location: fs/jbd2/checkpoint.c:206
Inline: False
Direct callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffff81bdefc7-ffffffff81bdefeb: jbd2_log_do_checkpoint.cold (STB_LOCAL)
ffffffff814645d0-ffffffff8146498c: jbd2_log_do_checkpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int jbd2_log_do_checkpoint(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/checkpoint.c (0)
Location: fs/jbd2/checkpoint.c:198
Inline: False
Direct callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffff81cce811-ffffffff81cce835: jbd2_log_do_checkpoint.cold (STB_LOCAL)
ffffffff814b9c40-ffffffff814ba00d: jbd2_log_do_checkpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int jbd2_log_do_checkpoint(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/checkpoint.c (0)
Location: fs/jbd2/checkpoint.c:198
Inline: False
Direct callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffff81e818b9-ffffffff81e818d6: jbd2_log_do_checkpoint.cold (STB_LOCAL)
ffffffff815439a0-ffffffff81543da2: jbd2_log_do_checkpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int jbd2_log_do_checkpoint(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/checkpoint.c (ffffffff815e2910)
Location: fs/jbd2/checkpoint.c:198
Inline: False
Direct callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffff815e2910-ffffffff815e2d1a: jbd2_log_do_checkpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int jbd2_log_do_checkpoint(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/checkpoint.c (ffffffff8161a250)
Location: fs/jbd2/checkpoint.c:160
Inline: False
Direct callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffff8161a250-ffffffff8161a594: jbd2_log_do_checkpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int jbd2_log_do_checkpoint(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/checkpoint.c (ffffffff81653190)
Location: fs/jbd2/checkpoint.c:148
Inline: False
Direct callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffff81653190-ffffffff816534ce: jbd2_log_do_checkpoint (STB_GLOBAL)
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
int jbd2_log_do_checkpoint(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/checkpoint.c (ffff8000104d1290)
Location: fs/jbd2/checkpoint.c:204
Inline: False
Direct callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffff8000104d1290-ffff8000104d17b8: jbd2_log_do_checkpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int jbd2_log_do_checkpoint(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/checkpoint.c (c0693de4)
Location: fs/jbd2/checkpoint.c:204
Inline: False
Direct callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
c0693de4-c06942b8: jbd2_log_do_checkpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int jbd2_log_do_checkpoint(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/checkpoint.c (c00000000060a650)
Location: fs/jbd2/checkpoint.c:204
Inline: False
Direct callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
c00000000060a650-c00000000060acec: jbd2_log_do_checkpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int jbd2_log_do_checkpoint(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/checkpoint.c (ffffffe0003486a6)
Location: fs/jbd2/checkpoint.c:204
Inline: False
Direct callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffe0003486a6-ffffffe000348b7c: jbd2_log_do_checkpoint (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int jbd2_log_do_checkpoint(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/checkpoint.c (0)
Location: fs/jbd2/checkpoint.c:204
Inline: False
Direct callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffff813ee502-ffffffff813ee526: jbd2_log_do_checkpoint.cold (STB_LOCAL)
ffffffff813eddf0-ffffffff813ee1ef: jbd2_log_do_checkpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int jbd2_log_do_checkpoint(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/checkpoint.c (0)
Location: fs/jbd2/checkpoint.c:204
Inline: False
Direct callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffff813def82-ffffffff813defa6: jbd2_log_do_checkpoint.cold (STB_LOCAL)
ffffffff813de870-ffffffff813dec6f: jbd2_log_do_checkpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int jbd2_log_do_checkpoint(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/checkpoint.c (0)
Location: fs/jbd2/checkpoint.c:204
Inline: False
Direct callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffff813eb882-ffffffff813eb8a6: jbd2_log_do_checkpoint.cold (STB_LOCAL)
ffffffff813eb170-ffffffff813eb56f: jbd2_log_do_checkpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int jbd2_log_do_checkpoint(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/checkpoint.c (0)
Location: fs/jbd2/checkpoint.c:204
Inline: False
Direct callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffff81401229-ffffffff81401245: jbd2_log_do_checkpoint.cold (STB_LOCAL)
ffffffff81400b00-ffffffff81400f18: jbd2_log_do_checkpoint (STB_GLOBAL)
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
