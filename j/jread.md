# Function: <code>jread</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int jread(struct buffer_head **bhp, journal_t *journal, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/recovery.c (ffffffff812eb510)
Location: fs/jbd2/recovery.c:132
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff812eb510-ffffffff812eb7aa: jread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int jread(struct buffer_head **bhp, journal_t *journal, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/recovery.c (ffffffff81318f60)
Location: fs/jbd2/recovery.c:132
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff81318f60-ffffffff81319211: jread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int jread(struct buffer_head **bhp, journal_t *journal, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/recovery.c (ffffffff8132ef50)
Location: fs/jbd2/recovery.c:132
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff8132ef50-ffffffff8132f201: jread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int jread(struct buffer_head **bhp, journal_t *journal, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/recovery.c (ffffffff81343fe0)
Location: fs/jbd2/recovery.c:132
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff81343fe0-ffffffff813442ce: jread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int jread(struct buffer_head **bhp, journal_t *journal, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/recovery.c (ffffffff81368680)
Location: fs/jbd2/recovery.c:132
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff81368680-ffffffff8136896e: jread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int jread(struct buffer_head **bhp, journal_t *journal, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/recovery.c (0)
Location: fs/jbd2/recovery.c:129
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff81396f10-ffffffff81397165: jread (STB_LOCAL)
ffffffff81397e96-ffffffff81397eff: jread.cold.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int jread(struct buffer_head **bhp, journal_t *journal, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/recovery.c (0)
Location: fs/jbd2/recovery.c:129
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff813afc80-ffffffff813afed5: jread (STB_LOCAL)
ffffffff813b0c16-ffffffff813b0c7f: jread.cold.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int jread(struct buffer_head **bhp, journal_t *journal, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/recovery.c (0)
Location: fs/jbd2/recovery.c:129
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff813da1e0-ffffffff813da464: jread (STB_LOCAL)
ffffffff813db1c6-ffffffff813db226: jread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int jread(struct buffer_head **bhp, journal_t *journal, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/recovery.c (0)
Location: fs/jbd2/recovery.c:129
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff813f4230-ffffffff813f44b4: jread (STB_LOCAL)
ffffffff813f5216-ffffffff813f5276: jread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int jread(struct buffer_head **bhp, journal_t *journal, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/recovery.c (0)
Location: fs/jbd2/recovery.c:129
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:calc_chksums
```
**Symbols:**

```
ffffffff81441740-ffffffff8144182e: jread (STB_LOCAL)
ffffffff814425b9-ffffffff81442606: jread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int jread(struct buffer_head **bhp, journal_t *journal, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/recovery.c (0)
Location: fs/jbd2/recovery.c:128
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:calc_chksums
```
**Symbols:**

```
ffffffff8145d930-ffffffff8145da1e: jread (STB_LOCAL)
ffffffff81becd44-ffffffff81becd91: jread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int jread(struct buffer_head **bhp, journal_t *journal, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/recovery.c (0)
Location: fs/jbd2/recovery.c:128
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff81463240-ffffffff8146332e: jread (STB_LOCAL)
ffffffff81bdee04-ffffffff81bdee51: jread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int jread(struct buffer_head **bhp, journal_t *journal, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/recovery.c (0)
Location: fs/jbd2/recovery.c:128
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff814b8780-ffffffff814b886e: jread (STB_LOCAL)
ffffffff81cce648-ffffffff81cce695: jread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int jread(struct buffer_head **bhp, journal_t *journal, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/recovery.c (0)
Location: fs/jbd2/recovery.c:128
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff815422c0-ffffffff815423bf: jread (STB_LOCAL)
ffffffff81e816fb-ffffffff81e81748: jread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int jread(struct buffer_head **bhp, journal_t *journal, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/recovery.c (ffffffff815e0f20)
Location: fs/jbd2/recovery.c:128
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff815e0f20-ffffffff815e10bd: jread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int jread(struct buffer_head **bhp, journal_t *journal, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/recovery.c (ffffffff81618810)
Location: fs/jbd2/recovery.c:129
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff81618810-ffffffff816189ad: jread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int jread(struct buffer_head **bhp, journal_t *journal, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/recovery.c (ffffffff81651780)
Location: fs/jbd2/recovery.c:129
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff81651780-ffffffff8165192c: jread (STB_LOCAL)
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
int jread(struct buffer_head **bhp, journal_t *journal, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/recovery.c (ffff8000104cfb28)
Location: fs/jbd2/recovery.c:129
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffff8000104cfb28-ffff8000104cfdc0: jread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int jread(struct buffer_head **bhp, journal_t *journal, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/recovery.c (c06925dc)
Location: fs/jbd2/recovery.c:129
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
c06925dc-c0692884: jread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int jread(struct buffer_head **bhp, journal_t *journal, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/recovery.c (c0000000006089c0)
Location: fs/jbd2/recovery.c:129
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
c0000000006089c0-c000000000608d4c: jread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int jread(struct buffer_head **bhp, journal_t *journal, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/recovery.c (ffffffe0003471e2)
Location: fs/jbd2/recovery.c:129
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffe0003471e2-ffffffe000347424: jread (STB_LOCAL)
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
int jread(struct buffer_head **bhp, journal_t *journal, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/recovery.c (0)
Location: fs/jbd2/recovery.c:129
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff813ec810-ffffffff813eca94: jread (STB_LOCAL)
ffffffff813ed7f6-ffffffff813ed856: jread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int jread(struct buffer_head **bhp, journal_t *journal, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/recovery.c (0)
Location: fs/jbd2/recovery.c:129
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff813dd290-ffffffff813dd514: jread (STB_LOCAL)
ffffffff813de276-ffffffff813de2d6: jread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int jread(struct buffer_head **bhp, journal_t *journal, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/recovery.c (0)
Location: fs/jbd2/recovery.c:129
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff813e9b90-ffffffff813e9e14: jread (STB_LOCAL)
ffffffff813eab76-ffffffff813eabd6: jread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int jread(struct buffer_head **bhp, journal_t *journal, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/recovery.c (0)
Location: fs/jbd2/recovery.c:129
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff813ff4e0-ffffffff813ff75f: jread (STB_LOCAL)
ffffffff814004d6-ffffffff81400536: jread.cold (STB_LOCAL)
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
