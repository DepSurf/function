# Function: <code>jbd2_journal_set_features</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int jbd2_journal_set_features(journal_t *journal, long unsigned int compat, long unsigned int ro, long unsigned int incompat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff812f1340)
Location: fs/jbd2/journal.c:1819
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffffffff812f1340-ffffffff812f1536: jbd2_journal_set_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int jbd2_journal_set_features(journal_t *journal, long unsigned int compat, long unsigned int ro, long unsigned int incompat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8131eb50)
Location: fs/jbd2/journal.c:1854
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffffffff8131eb50-ffffffff8131ed50: jbd2_journal_set_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int jbd2_journal_set_features(journal_t *journal, long unsigned int compat, long unsigned int ro, long unsigned int incompat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81334bd0)
Location: fs/jbd2/journal.c:1824
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffffffff81334bd0-ffffffff81334dd0: jbd2_journal_set_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int jbd2_journal_set_features(journal_t *journal, long unsigned int compat, long unsigned int ro, long unsigned int incompat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81349990)
Location: fs/jbd2/journal.c:1847
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffffffff81349990-ffffffff81349b76: jbd2_journal_set_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int jbd2_journal_set_features(journal_t *journal, long unsigned int compat, long unsigned int ro, long unsigned int incompat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8136dfe0)
Location: fs/jbd2/journal.c:1863
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffffffff8136dfe0-ffffffff8136e1c6: jbd2_journal_set_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_set_features(journal_t *journal, long unsigned int compat, long unsigned int ro, long unsigned int incompat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1866
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffffffff8139e37d-ffffffff8139e39b: jbd2_journal_set_features.cold.49 (STB_LOCAL)
ffffffff8139c690-ffffffff8139c80e: jbd2_journal_set_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_set_features(journal_t *journal, long unsigned int compat, long unsigned int ro, long unsigned int incompat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813b54a3)
Location: fs/jbd2/journal.c:1866
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffffffff813b70ed-ffffffff813b710b: jbd2_journal_set_features.cold.50 (STB_LOCAL)
ffffffff813b5450-ffffffff813b55ce: jbd2_journal_set_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_set_features(journal_t *journal, long unsigned int compat, long unsigned int ro, long unsigned int incompat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813dfa7a)
Location: fs/jbd2/journal.c:1857
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffffffff813e184f-ffffffff813e186d: jbd2_journal_set_features.cold (STB_LOCAL)
ffffffff813dfa00-ffffffff813dfbdd: jbd2_journal_set_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_set_features(journal_t *journal, long unsigned int compat, long unsigned int ro, long unsigned int incompat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813f9b3a)
Location: fs/jbd2/journal.c:1860
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffffffff813fb8b5-ffffffff813fb8d3: jbd2_journal_set_features.cold (STB_LOCAL)
ffffffff813f9ac0-ffffffff813f9c9d: jbd2_journal_set_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_set_features(journal_t *journal, long unsigned int compat, long unsigned int ro, long unsigned int incompat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff814473b0)
Location: fs/jbd2/journal.c:1898
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:set_journal_csum_feature_set
  - fs/ext4/super.c:set_journal_csum_feature_set
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffffffff81446230-ffffffff814463c9: jbd2_journal_set_features.part.0 (STB_LOCAL)
ffffffff81448f20-ffffffff81448f3e: jbd2_journal_set_features.part.0.cold (STB_LOCAL)
ffffffff814473b0-ffffffff8144747b: jbd2_journal_set_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_set_features(journal_t *journal, long unsigned int compat, long unsigned int ro, long unsigned int incompat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81463910)
Location: fs/jbd2/journal.c:2138
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:set_journal_csum_feature_set
  - fs/ext4/super.c:set_journal_csum_feature_set
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffffffff81462540-ffffffff81462804: jbd2_journal_set_features.part.0 (STB_LOCAL)
ffffffff81bed033-ffffffff81bed051: jbd2_journal_set_features.part.0.cold (STB_LOCAL)
ffffffff81463910-ffffffff814639db: jbd2_journal_set_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_set_features(journal_t *journal, long unsigned int compat, long unsigned int ro, long unsigned int incompat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81468a60)
Location: fs/jbd2/journal.c:2138
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffffffff81467bf0-ffffffff81467eb4: jbd2_journal_set_features.part.0 (STB_LOCAL)
ffffffff81bdf11a-ffffffff81bdf138: jbd2_journal_set_features.part.0.cold (STB_LOCAL)
ffffffff81468a60-ffffffff81468b2b: jbd2_journal_set_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_set_features(journal_t *journal, long unsigned int compat, long unsigned int ro, long unsigned int incompat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff814be510)
Location: fs/jbd2/journal.c:2308
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffffffff814bdc30-ffffffff814bdef4: jbd2_journal_set_features.part.0 (STB_LOCAL)
ffffffff81ccea10-ffffffff81ccea2e: jbd2_journal_set_features.part.0.cold (STB_LOCAL)
ffffffff814be510-ffffffff814be5db: jbd2_journal_set_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int jbd2_journal_set_features(journal_t *journal, long unsigned int compat, long unsigned int ro, long unsigned int incompat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:2311
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffffffff81e81be7-ffffffff81e81c07: jbd2_journal_set_features.cold (STB_LOCAL)
ffffffff81549c80-ffffffff81549ffb: jbd2_journal_set_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int jbd2_journal_set_features(journal_t *journal, long unsigned int compat, long unsigned int ro, long unsigned int incompat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff815ea520)
Location: fs/jbd2/journal.c:2314
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_and_init_journal
  - fs/ext4/super.c:ext4_load_and_init_journal
  - fs/ext4/super.c:ext4_load_and_init_journal
  - fs/ext4/super.c:ext4_load_and_init_journal
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffffffff815ea520-ffffffff815ea8bd: jbd2_journal_set_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int jbd2_journal_set_features(journal_t *journal, long unsigned int compat, long unsigned int ro, long unsigned int incompat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81620c70)
Location: fs/jbd2/journal.c:2314
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_and_init_journal
  - fs/ext4/super.c:ext4_load_and_init_journal
  - fs/ext4/super.c:ext4_load_and_init_journal
  - fs/ext4/super.c:ext4_load_and_init_journal
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffffffff81620c70-ffffffff81620ff7: jbd2_journal_set_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int jbd2_journal_set_features(journal_t *journal, long unsigned int compat, long unsigned int ro, long unsigned int incompat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff816598b0)
Location: fs/jbd2/journal.c:2306
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_and_init_journal
  - fs/ext4/super.c:ext4_load_and_init_journal
  - fs/ext4/super.c:ext4_load_and_init_journal
  - fs/ext4/super.c:ext4_load_and_init_journal
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffffffff816598b0-ffffffff81659c37: jbd2_journal_set_features (STB_GLOBAL)
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
int jbd2_journal_set_features(journal_t *journal, long unsigned int compat, long unsigned int ro, long unsigned int incompat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffff8000104d6240)
Location: fs/jbd2/journal.c:1860
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffff8000104d6240-ffff8000104d6474: jbd2_journal_set_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int jbd2_journal_set_features(journal_t *journal, long unsigned int compat, long unsigned int ro, long unsigned int incompat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (c0697c64)
Location: fs/jbd2/journal.c:1860
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
c0697c64-c0697e58: jbd2_journal_set_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int jbd2_journal_set_features(journal_t *journal, long unsigned int compat, long unsigned int ro, long unsigned int incompat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (c000000000610ec0)
Location: fs/jbd2/journal.c:1860
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
c000000000610ec0-c0000000006111a4: jbd2_journal_set_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int jbd2_journal_set_features(journal_t *journal, long unsigned int compat, long unsigned int ro, long unsigned int incompat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffe00034c71e)
Location: fs/jbd2/journal.c:1860
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffffffe00034c71e-ffffffe00034c96a: jbd2_journal_set_features (STB_GLOBAL)
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
int jbd2_journal_set_features(journal_t *journal, long unsigned int compat, long unsigned int ro, long unsigned int incompat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813f211a)
Location: fs/jbd2/journal.c:1860
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffffffff813f3e95-ffffffff813f3eb3: jbd2_journal_set_features.cold (STB_LOCAL)
ffffffff813f20a0-ffffffff813f227d: jbd2_journal_set_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_set_features(journal_t *journal, long unsigned int compat, long unsigned int ro, long unsigned int incompat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813e2b9a)
Location: fs/jbd2/journal.c:1860
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffffffff813e4915-ffffffff813e4933: jbd2_journal_set_features.cold (STB_LOCAL)
ffffffff813e2b20-ffffffff813e2cfd: jbd2_journal_set_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_set_features(journal_t *journal, long unsigned int compat, long unsigned int ro, long unsigned int incompat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813ef49a)
Location: fs/jbd2/journal.c:1860
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffffffff813f1215-ffffffff813f1233: jbd2_journal_set_features.cold (STB_LOCAL)
ffffffff813ef420-ffffffff813ef5fd: jbd2_journal_set_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_set_features(journal_t *journal, long unsigned int compat, long unsigned int ro, long unsigned int incompat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81404e5a)
Location: fs/jbd2/journal.c:1860
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffffffff81406e10-ffffffff81406e2e: jbd2_journal_set_features.cold (STB_LOCAL)
ffffffff81404de0-ffffffff81404fb7: jbd2_journal_set_features (STB_GLOBAL)
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
