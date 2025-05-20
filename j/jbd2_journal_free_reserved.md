# Function: <code>jbd2_journal_free_reserved</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void jbd2_journal_free_reserved(handle_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff812e6e90)
Location: fs/jbd2/transaction.c:481
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
**Symbols:**

```
ffffffff812e6e90-ffffffff812e6eda: jbd2_journal_free_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void jbd2_journal_free_reserved(handle_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813149f0)
Location: fs/jbd2/transaction.c:478
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
**Symbols:**

```
ffffffff813149f0-ffffffff81314a3a: jbd2_journal_free_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void jbd2_journal_free_reserved(handle_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8132a9d0)
Location: fs/jbd2/transaction.c:480
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
**Symbols:**

```
ffffffff8132a9d0-ffffffff8132aa1a: jbd2_journal_free_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void jbd2_journal_free_reserved(handle_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8133fc10)
Location: fs/jbd2/transaction.c:487
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
**Symbols:**

```
ffffffff8133fc10-ffffffff8133fc44: jbd2_journal_free_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void jbd2_journal_free_reserved(handle_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81364220)
Location: fs/jbd2/transaction.c:487
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
**Symbols:**

```
ffffffff81364220-ffffffff81364254: jbd2_journal_free_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void jbd2_journal_free_reserved(handle_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813929d0)
Location: fs/jbd2/transaction.c:482
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
**Symbols:**

```
ffffffff813929d0-ffffffff81392a04: jbd2_journal_free_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void jbd2_journal_free_reserved(handle_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813ab630)
Location: fs/jbd2/transaction.c:515
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
**Symbols:**

```
ffffffff813ab630-ffffffff813ab664: jbd2_journal_free_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void jbd2_journal_free_reserved(handle_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:515
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
**Symbols:**

```
ffffffff813d8395-ffffffff813d83a8: jbd2_journal_free_reserved.cold (STB_LOCAL)
ffffffff813d5880-ffffffff813d58bf: jbd2_journal_free_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void jbd2_journal_free_reserved(handle_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813ef8b0)
Location: fs/jbd2/transaction.c:515
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
**Symbols:**

```
ffffffff813ef8b0-ffffffff813ef8ea: jbd2_journal_free_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void jbd2_journal_free_reserved(handle_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8143cb10)
Location: fs/jbd2/transaction.c:554
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
**Symbols:**

```
ffffffff8143cb10-ffffffff8143cb55: jbd2_journal_free_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void jbd2_journal_free_reserved(handle_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81458e90)
Location: fs/jbd2/transaction.c:556
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
**Symbols:**

```
ffffffff81458e90-ffffffff81458ed5: jbd2_journal_free_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void jbd2_journal_free_reserved(handle_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8145e880)
Location: fs/jbd2/transaction.c:561
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
**Symbols:**

```
ffffffff8145e880-ffffffff8145e8c5: jbd2_journal_free_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void jbd2_journal_free_reserved(handle_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff814b3bf0)
Location: fs/jbd2/transaction.c:578
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
**Symbols:**

```
ffffffff814b3bf0-ffffffff814b3c35: jbd2_journal_free_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void jbd2_journal_free_reserved(handle_t *handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8153eae0)
Location: fs/jbd2/transaction.c:573
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
```
**Symbols:**

```
ffffffff8153d2c0-ffffffff8153d312: jbd2_journal_free_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void jbd2_journal_free_reserved(handle_t *handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff815dd480)
Location: fs/jbd2/transaction.c:573
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
```
**Symbols:**

```
ffffffff815dbad0-ffffffff815dbb22: jbd2_journal_free_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void jbd2_journal_free_reserved(handle_t *handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81614f20)
Location: fs/jbd2/transaction.c:573
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
```
**Symbols:**

```
ffffffff81613590-ffffffff816135e2: jbd2_journal_free_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void jbd2_journal_free_reserved(handle_t *handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8164dd10)
Location: fs/jbd2/transaction.c:573
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
```
**Symbols:**

```
ffffffff8164c390-ffffffff8164c3e2: jbd2_journal_free_reserved (STB_GLOBAL)
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
void jbd2_journal_free_reserved(handle_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffff8000104c8ae0)
Location: fs/jbd2/transaction.c:515
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
**Symbols:**

```
ffff8000104c8ae0-ffff8000104c8b30: jbd2_journal_free_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void jbd2_journal_free_reserved(handle_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (c068c760)
Location: fs/jbd2/transaction.c:515
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
**Symbols:**

```
c068c760-c068c7c4: jbd2_journal_free_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void jbd2_journal_free_reserved(handle_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (c000000000601bb0)
Location: fs/jbd2/transaction.c:515
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
**Symbols:**

```
c000000000601bb0-c000000000601c44: jbd2_journal_free_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void jbd2_journal_free_reserved(handle_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffe000342746)
Location: fs/jbd2/transaction.c:515
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
**Symbols:**

```
ffffffe000342746-ffffffe0003427a4: jbd2_journal_free_reserved (STB_GLOBAL)
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
void jbd2_journal_free_reserved(handle_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813e7e90)
Location: fs/jbd2/transaction.c:515
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
**Symbols:**

```
ffffffff813e7e90-ffffffff813e7eca: jbd2_journal_free_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void jbd2_journal_free_reserved(handle_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813d8910)
Location: fs/jbd2/transaction.c:515
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
**Symbols:**

```
ffffffff813d8910-ffffffff813d894a: jbd2_journal_free_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void jbd2_journal_free_reserved(handle_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813e5210)
Location: fs/jbd2/transaction.c:515
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
**Symbols:**

```
ffffffff813e5210-ffffffff813e524a: jbd2_journal_free_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void jbd2_journal_free_reserved(handle_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813fa790)
Location: fs/jbd2/transaction.c:515
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
**Symbols:**

```
ffffffff813fa790-ffffffff813fa7ca: jbd2_journal_free_reserved (STB_GLOBAL)
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
