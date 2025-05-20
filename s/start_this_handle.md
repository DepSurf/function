# Function: <code>start_this_handle</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int start_this_handle(journal_t *journal, handle_t *handle, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff812e6ee0)
Location: fs/jbd2/transaction.c:271
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
**Symbols:**

```
ffffffff812e6ee0-ffffffff812e72d8: start_this_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int start_this_handle(journal_t *journal, handle_t *handle, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81314a40)
Location: fs/jbd2/transaction.c:273
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
**Symbols:**

```
ffffffff81314a40-ffffffff81314e3e: start_this_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int start_this_handle(journal_t *journal, handle_t *handle, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8132aa20)
Location: fs/jbd2/transaction.c:275
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
**Symbols:**

```
ffffffff8132aa20-ffffffff8132ae09: start_this_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int start_this_handle(journal_t *journal, handle_t *handle, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8133fc50)
Location: fs/jbd2/transaction.c:276
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
**Symbols:**

```
ffffffff8133fc50-ffffffff8134003b: start_this_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int start_this_handle(journal_t *journal, handle_t *handle, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81364260)
Location: fs/jbd2/transaction.c:276
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
**Symbols:**

```
ffffffff81364260-ffffffff8136464b: start_this_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int start_this_handle(journal_t *journal, handle_t *handle, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:271
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
**Symbols:**

```
ffffffff81392a10-ffffffff81392dbe: start_this_handle (STB_LOCAL)
ffffffff81395253-ffffffff81395283: start_this_handle.cold.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int start_this_handle(journal_t *journal, handle_t *handle, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:298
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
**Symbols:**

```
ffffffff813ab670-ffffffff813abadd: start_this_handle (STB_LOCAL)
ffffffff813adfc3-ffffffff813adff2: start_this_handle.cold.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int start_this_handle(journal_t *journal, handle_t *handle, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:298
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
**Symbols:**

```
ffffffff813d58c0-ffffffff813d5cf4: start_this_handle (STB_LOCAL)
ffffffff813d83a8-ffffffff813d83f6: start_this_handle.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int start_this_handle(journal_t *journal, handle_t *handle, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:298
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
**Symbols:**

```
ffffffff813ef8f0-ffffffff813efd2b: start_this_handle (STB_LOCAL)
ffffffff813f2415-ffffffff813f2444: start_this_handle.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int start_this_handle(journal_t *journal, handle_t *handle, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:323
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2__journal_start
```
**Symbols:**

```
ffffffff8143d020-ffffffff8143d3d1: start_this_handle (STB_LOCAL)
ffffffff8143f7c0-ffffffff8143f7ef: start_this_handle.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int start_this_handle(journal_t *journal, handle_t *handle, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:325
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2__journal_start
```
**Symbols:**

```
ffffffff814593a0-ffffffff8145975a: start_this_handle (STB_LOCAL)
ffffffff81becb64-ffffffff81becb93: start_this_handle.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int start_this_handle(journal_t *journal, handle_t *handle, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:325
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2__journal_start
```
**Symbols:**

```
ffffffff8145ec60-ffffffff8145f01a: start_this_handle (STB_LOCAL)
ffffffff81bdebe9-ffffffff81bdec18: start_this_handle.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int start_this_handle(journal_t *journal, handle_t *handle, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:336
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2__journal_start
```
**Symbols:**

```
ffffffff814b3fd0-ffffffff814b44d5: start_this_handle (STB_LOCAL)
ffffffff81cce445-ffffffff81cce474: start_this_handle.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int start_this_handle(journal_t *journal, handle_t *handle, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:331
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2__journal_start
```
**Symbols:**

```
ffffffff8153d820-ffffffff8153dd9f: start_this_handle (STB_LOCAL)
ffffffff81e814d1-ffffffff81e81500: start_this_handle.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int start_this_handle(journal_t *journal, handle_t *handle, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff815dc090)
Location: fs/jbd2/transaction.c:331
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2__journal_start
```
**Symbols:**

```
ffffffff815dc090-ffffffff815dc63e: start_this_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int start_this_handle(journal_t *journal, handle_t *handle, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81613b50)
Location: fs/jbd2/transaction.c:331
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2__journal_start
```
**Symbols:**

```
ffffffff81613b50-ffffffff816140df: start_this_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int start_this_handle(journal_t *journal, handle_t *handle, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8164c940)
Location: fs/jbd2/transaction.c:331
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2__journal_start
```
**Symbols:**

```
ffffffff8164c940-ffffffff8164cecf: start_this_handle (STB_LOCAL)
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
int start_this_handle(journal_t *journal, handle_t *handle, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffff8000104c9318)
Location: fs/jbd2/transaction.c:298
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
**Symbols:**

```
ffff8000104c9318-ffff8000104c9808: start_this_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int start_this_handle(journal_t *journal, handle_t *handle, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (c068cad4)
Location: fs/jbd2/transaction.c:298
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
**Symbols:**

```
c068cad4-c068d384: start_this_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int start_this_handle(journal_t *journal, handle_t *handle, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (c000000000601c50)
Location: fs/jbd2/transaction.c:298
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2__journal_start
```
**Symbols:**

```
c000000000601c50-c0000000006021f0: start_this_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int start_this_handle(journal_t *journal, handle_t *handle, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffe0003427a4)
Location: fs/jbd2/transaction.c:298
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
**Symbols:**

```
ffffffe0003427a4-ffffffe000342b52: start_this_handle (STB_LOCAL)
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
int start_this_handle(journal_t *journal, handle_t *handle, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:298
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
**Symbols:**

```
ffffffff813e7ed0-ffffffff813e830b: start_this_handle (STB_LOCAL)
ffffffff813ea9f5-ffffffff813eaa24: start_this_handle.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int start_this_handle(journal_t *journal, handle_t *handle, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:298
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
**Symbols:**

```
ffffffff813d8950-ffffffff813d8d8b: start_this_handle (STB_LOCAL)
ffffffff813db475-ffffffff813db4a4: start_this_handle.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int start_this_handle(journal_t *journal, handle_t *handle, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:298
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
**Symbols:**

```
ffffffff813e5250-ffffffff813e568b: start_this_handle (STB_LOCAL)
ffffffff813e7d75-ffffffff813e7da4: start_this_handle.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int start_this_handle(journal_t *journal, handle_t *handle, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:298
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
**Symbols:**

```
ffffffff813fa7d0-ffffffff813fac13: start_this_handle (STB_LOCAL)
ffffffff813fd594-ffffffff813fd5c3: start_this_handle.cold (STB_LOCAL)
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
