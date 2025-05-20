# Function: <code>jbd2_journal_load</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int jbd2_journal_load(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff812f2670)
Location: fs/jbd2/journal.c:1613
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff812f2670-ffffffff812f29d1: jbd2_journal_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int jbd2_journal_load(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81320070)
Location: fs/jbd2/journal.c:1642
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff81320070-ffffffff813203d1: jbd2_journal_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int jbd2_journal_load(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81335f30)
Location: fs/jbd2/journal.c:1611
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff81335f30-ffffffff81336286: jbd2_journal_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int jbd2_journal_load(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8134ac60)
Location: fs/jbd2/journal.c:1634
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff8134ac60-ffffffff8134afb3: jbd2_journal_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int jbd2_journal_load(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8136f2b0)
Location: fs/jbd2/journal.c:1650
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff8136f2b0-ffffffff8136f603: jbd2_journal_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_load(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1653
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff8139e4cc-ffffffff8139e551: jbd2_journal_load.cold.54 (STB_LOCAL)
ffffffff8139d870-ffffffff8139db2a: jbd2_journal_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_load(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813b66cb)
Location: fs/jbd2/journal.c:1653
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff813b723c-ffffffff813b72c1: jbd2_journal_load.cold.55 (STB_LOCAL)
ffffffff813b65e0-ffffffff813b689a: jbd2_journal_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_load(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813e0dd5)
Location: fs/jbd2/journal.c:1644
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff813e19c7-ffffffff813e1a35: jbd2_journal_load.cold (STB_LOCAL)
ffffffff813e0d40-ffffffff813e0f5c: jbd2_journal_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_load(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813fae25)
Location: fs/jbd2/journal.c:1643
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff813fba04-ffffffff813fba72: jbd2_journal_load.cold (STB_LOCAL)
ffffffff813fad90-ffffffff813fafaf: jbd2_journal_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_load(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8144871b)
Location: fs/jbd2/journal.c:1681
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff814491cf-ffffffff81449218: jbd2_journal_load.cold (STB_LOCAL)
ffffffff814486c0-ffffffff81448787: jbd2_journal_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_load(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81465224)
Location: fs/jbd2/journal.c:1891
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff81bed2f1-ffffffff81bed354: jbd2_journal_load.cold (STB_LOCAL)
ffffffff814651f0-ffffffff8146533c: jbd2_journal_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_load(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8146a9b4)
Location: fs/jbd2/journal.c:1891
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff81bdf3d5-ffffffff81bdf438: jbd2_journal_load.cold (STB_LOCAL)
ffffffff8146a980-ffffffff8146aac9: jbd2_journal_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_load(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff814c1136)
Location: fs/jbd2/journal.c:2047
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff81cced4a-ffffffff81ccedad: jbd2_journal_load.cold (STB_LOCAL)
ffffffff814c1100-ffffffff814c12d4: jbd2_journal_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_load(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8154ba44)
Location: fs/jbd2/journal.c:2050
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff81e81d9d-ffffffff81e81df8: jbd2_journal_load.cold (STB_LOCAL)
ffffffff8154ba10-ffffffff8154bbe9: jbd2_journal_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int jbd2_journal_load(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff815eb760)
Location: fs/jbd2/journal.c:2053
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff815eb760-ffffffff815eb97a: jbd2_journal_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int jbd2_journal_load(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81623240)
Location: fs/jbd2/journal.c:2057
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff81623240-ffffffff8162345f: jbd2_journal_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int jbd2_journal_load(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8165c2c0)
Location: fs/jbd2/journal.c:2071
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff8165c2c0-ffffffff8165c4b8: jbd2_journal_load (STB_GLOBAL)
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
int jbd2_journal_load(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffff8000104d8288)
Location: fs/jbd2/journal.c:1643
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffff8000104d8288-ffff8000104d84d8: jbd2_journal_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int jbd2_journal_load(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (c069a0e0)
Location: fs/jbd2/journal.c:1643
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
c069a0e0-c069a434: jbd2_journal_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int jbd2_journal_load(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (c000000000612fe0)
Location: fs/jbd2/journal.c:1643
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
c000000000612fe0-c0000000006132d0: jbd2_journal_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int jbd2_journal_load(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffe00034dd7c)
Location: fs/jbd2/journal.c:1643
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffe00034dd7c-ffffffe00034e004: jbd2_journal_load (STB_GLOBAL)
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
int jbd2_journal_load(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813f3405)
Location: fs/jbd2/journal.c:1643
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff813f3fe4-ffffffff813f4052: jbd2_journal_load.cold (STB_LOCAL)
ffffffff813f3370-ffffffff813f358f: jbd2_journal_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_load(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813e3e85)
Location: fs/jbd2/journal.c:1643
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff813e4a64-ffffffff813e4ad2: jbd2_journal_load.cold (STB_LOCAL)
ffffffff813e3df0-ffffffff813e400f: jbd2_journal_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_load(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813f0785)
Location: fs/jbd2/journal.c:1643
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff813f1364-ffffffff813f13d2: jbd2_journal_load.cold (STB_LOCAL)
ffffffff813f06f0-ffffffff813f090f: jbd2_journal_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_load(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff814061f5)
Location: fs/jbd2/journal.c:1643
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff81406f6f-ffffffff81406fdd: jbd2_journal_load.cold (STB_LOCAL)
ffffffff81406160-ffffffff81406374: jbd2_journal_load (STB_GLOBAL)
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
