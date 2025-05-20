# Function: <code>jbd2_journal_wipe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int jbd2_journal_wipe(journal_t *journal, int write);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff812f1e10)
Location: fs/jbd2/journal.c:2004
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff812f1e10-ffffffff812f1eb9: jbd2_journal_wipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int jbd2_journal_wipe(journal_t *journal, int write);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8131f6d0)
Location: fs/jbd2/journal.c:2039
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff8131f6d0-ffffffff8131f77e: jbd2_journal_wipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int jbd2_journal_wipe(journal_t *journal, int write);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81335750)
Location: fs/jbd2/journal.c:2009
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff81335750-ffffffff813357fe: jbd2_journal_wipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int jbd2_journal_wipe(journal_t *journal, int write);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8134a4f0)
Location: fs/jbd2/journal.c:2032
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff8134a4f0-ffffffff8134a59e: jbd2_journal_wipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int jbd2_journal_wipe(journal_t *journal, int write);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8136eb40)
Location: fs/jbd2/journal.c:2048
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff8136eb40-ffffffff8136ebee: jbd2_journal_wipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_wipe(journal_t *journal, int write);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:2051
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff8139e428-ffffffff8139e497: jbd2_journal_wipe.cold.52 (STB_LOCAL)
ffffffff8139d180-ffffffff8139d1c9: jbd2_journal_wipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_wipe(journal_t *journal, int write);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813b7198)
Location: fs/jbd2/journal.c:2051
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff813b7198-ffffffff813b7207: jbd2_journal_wipe.cold.53 (STB_LOCAL)
ffffffff813b5ef0-ffffffff813b5f39: jbd2_journal_wipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_wipe(journal_t *journal, int write);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813e1910)
Location: fs/jbd2/journal.c:2042
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff813e1910-ffffffff813e197f: jbd2_journal_wipe.cold (STB_LOCAL)
ffffffff813e0620-ffffffff813e066d: jbd2_journal_wipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_wipe(journal_t *journal, int write);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813fb960)
Location: fs/jbd2/journal.c:2045
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff813fb960-ffffffff813fb9cf: jbd2_journal_wipe.cold (STB_LOCAL)
ffffffff813fa660-ffffffff813fa6ad: jbd2_journal_wipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_wipe(journal_t *journal, int write);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81447bbe)
Location: fs/jbd2/journal.c:2087
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff814490d3-ffffffff81449142: jbd2_journal_wipe.cold (STB_LOCAL)
ffffffff81447b50-ffffffff81447bd4: jbd2_journal_wipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_wipe(journal_t *journal, int write);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81464551)
Location: fs/jbd2/journal.c:2334
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff81bed221-ffffffff81bed290: jbd2_journal_wipe.cold (STB_LOCAL)
ffffffff81464520-ffffffff8146456d: jbd2_journal_wipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_wipe(journal_t *journal, int write);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81469ce1)
Location: fs/jbd2/journal.c:2334
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff81bdf305-ffffffff81bdf374: jbd2_journal_wipe.cold (STB_LOCAL)
ffffffff81469cb0-ffffffff81469cfd: jbd2_journal_wipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_wipe(journal_t *journal, int write);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81ccec3d)
Location: fs/jbd2/journal.c:2513
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff81ccec3d-ffffffff81ccecac: jbd2_journal_wipe.cold (STB_LOCAL)
ffffffff814bfe70-ffffffff814bfebd: jbd2_journal_wipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_wipe(journal_t *journal, int write);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81e81ca3)
Location: fs/jbd2/journal.c:2516
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff81e81ca3-ffffffff81e81d12: jbd2_journal_wipe.cold (STB_LOCAL)
ffffffff8154a650-ffffffff8154a6a1: jbd2_journal_wipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int jbd2_journal_wipe(journal_t *journal, int write);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff815ea0d0)
Location: fs/jbd2/journal.c:2519
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff815ea0d0-ffffffff815ea197: jbd2_journal_wipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int jbd2_journal_wipe(journal_t *journal, int write);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81621ec0)
Location: fs/jbd2/journal.c:2519
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff81621ec0-ffffffff81621f86: jbd2_journal_wipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int jbd2_journal_wipe(journal_t *journal, int write);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8165a400)
Location: fs/jbd2/journal.c:2511
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff8165a400-ffffffff8165a4b0: jbd2_journal_wipe (STB_GLOBAL)
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
int jbd2_journal_wipe(journal_t *journal, int write);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffff8000104d7700)
Location: fs/jbd2/journal.c:2045
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffff8000104d7700-ffff8000104d77d8: jbd2_journal_wipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int jbd2_journal_wipe(journal_t *journal, int write);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (c0699768)
Location: fs/jbd2/journal.c:2045
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
c0699768-c0699834: jbd2_journal_wipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int jbd2_journal_wipe(journal_t *journal, int write);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (c000000000612330)
Location: fs/jbd2/journal.c:2045
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
c000000000612330-c000000000612440: jbd2_journal_wipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int jbd2_journal_wipe(journal_t *journal, int write);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffe00034d4b2)
Location: fs/jbd2/journal.c:2045
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffe00034d4b2-ffffffe00034d584: jbd2_journal_wipe (STB_GLOBAL)
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
int jbd2_journal_wipe(journal_t *journal, int write);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813f3f40)
Location: fs/jbd2/journal.c:2045
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff813f3f40-ffffffff813f3faf: jbd2_journal_wipe.cold (STB_LOCAL)
ffffffff813f2c40-ffffffff813f2c8d: jbd2_journal_wipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_wipe(journal_t *journal, int write);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813e49c0)
Location: fs/jbd2/journal.c:2045
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff813e49c0-ffffffff813e4a2f: jbd2_journal_wipe.cold (STB_LOCAL)
ffffffff813e36c0-ffffffff813e370d: jbd2_journal_wipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_wipe(journal_t *journal, int write);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813f12c0)
Location: fs/jbd2/journal.c:2045
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff813f12c0-ffffffff813f132f: jbd2_journal_wipe.cold (STB_LOCAL)
ffffffff813effc0-ffffffff813f000d: jbd2_journal_wipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_wipe(journal_t *journal, int write);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81406ecb)
Location: fs/jbd2/journal.c:2045
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff81406ecb-ffffffff81406f3a: jbd2_journal_wipe.cold (STB_LOCAL)
ffffffff814059c0-ffffffff81405a0d: jbd2_journal_wipe (STB_GLOBAL)
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
