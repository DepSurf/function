# Function: <code>klp_try_complete_transition</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void klp_try_complete_transition();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff810f8e20)
Location: kernel/livepatch/transition.c:352
Inline: False
Direct callers:
  - kernel/livepatch/core.c:__klp_disable_patch
  - kernel/livepatch/transition.c:klp_transition_work_fn
```
**Symbols:**

```
ffffffff810f8e20-ffffffff810f8fb9: klp_try_complete_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void klp_try_complete_transition();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff81103840)
Location: kernel/livepatch/transition.c:377
Inline: False
Direct callers:
  - kernel/livepatch/core.c:__klp_disable_patch
  - kernel/livepatch/transition.c:klp_transition_work_fn
```
**Symbols:**

```
ffffffff81103840-ffffffff811039b1: klp_try_complete_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void klp_try_complete_transition();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff8110bde0)
Location: kernel/livepatch/transition.c:365
Inline: False
Direct callers:
  - kernel/livepatch/core.c:__klp_disable_patch
  - kernel/livepatch/transition.c:klp_transition_work_fn
```
**Symbols:**

```
ffffffff8110bde0-ffffffff8110bf3c: klp_try_complete_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void klp_try_complete_transition();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff811175d0)
Location: kernel/livepatch/transition.c:358
Inline: False
Direct callers:
  - kernel/livepatch/core.c:__klp_disable_patch
  - kernel/livepatch/transition.c:klp_transition_work_fn
```
**Symbols:**

```
ffffffff811175d0-ffffffff8111772c: klp_try_complete_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void klp_try_complete_transition();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/transition.c (0)
Location: kernel/livepatch/transition.c:388
Inline: False
Direct callers:
  - kernel/livepatch/core.c:enabled_store
  - kernel/livepatch/transition.c:klp_transition_work_fn
```
**Symbols:**

```
ffffffff81121f16-ffffffff81121f27: klp_try_complete_transition.cold (STB_LOCAL)
ffffffff81121870-ffffffff81121b5c: klp_try_complete_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void klp_try_complete_transition();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/transition.c (0)
Location: kernel/livepatch/transition.c:388
Inline: False
Direct callers:
  - kernel/livepatch/core.c:enabled_store
  - kernel/livepatch/transition.c:klp_transition_work_fn
```
**Symbols:**

```
ffffffff8112e536-ffffffff8112e547: klp_try_complete_transition.cold (STB_LOCAL)
ffffffff8112de90-ffffffff8112e17c: klp_try_complete_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void klp_try_complete_transition();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff8113c870)
Location: kernel/livepatch/transition.c:388
Inline: False
Direct callers:
  - kernel/livepatch/core.c:__klp_enable_patch
  - kernel/livepatch/core.c:enabled_store
  - kernel/livepatch/transition.c:klp_transition_work_fn
```
**Symbols:**

```
ffffffff8113c870-ffffffff8113ca68: klp_try_complete_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void klp_try_complete_transition();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff81136f80)
Location: kernel/livepatch/transition.c:388
Inline: False
Direct callers:
  - kernel/livepatch/core.c:__klp_enable_patch
  - kernel/livepatch/core.c:enabled_store
  - kernel/livepatch/transition.c:klp_transition_work_fn
```
**Symbols:**

```
ffffffff81136f80-ffffffff81137178: klp_try_complete_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void klp_try_complete_transition();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/transition.c (0)
Location: kernel/livepatch/transition.c:387
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:enabled_store
  - kernel/livepatch/transition.c:klp_transition_work_fn
```
**Symbols:**

```
ffffffff81bd52a7-ffffffff81bd52b8: klp_try_complete_transition.cold (STB_LOCAL)
ffffffff81137c50-ffffffff81137f30: klp_try_complete_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void klp_try_complete_transition();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/transition.c (0)
Location: kernel/livepatch/transition.c:387
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:enabled_store
  - kernel/livepatch/transition.c:klp_transition_work_fn
```
**Symbols:**

```
ffffffff81cb0136-ffffffff81cb016f: klp_try_complete_transition.cold (STB_LOCAL)
ffffffff8115a9a0-ffffffff8115ac9f: klp_try_complete_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void klp_try_complete_transition();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/transition.c (0)
Location: kernel/livepatch/transition.c:384
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:enabled_store
  - kernel/livepatch/transition.c:klp_transition_work_fn
```
**Symbols:**

```
ffffffff81e60d69-ffffffff81e60da4: klp_try_complete_transition.cold (STB_LOCAL)
ffffffff81184280-ffffffff8118458b: klp_try_complete_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void klp_try_complete_transition();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/transition.c (0)
Location: kernel/livepatch/transition.c:384
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:enabled_store
  - kernel/livepatch/transition.c:klp_transition_work_fn
```
**Symbols:**

```
ffffffff8205a6cc-ffffffff8205a6f6: klp_try_complete_transition.cold (STB_LOCAL)
ffffffff811bf520-ffffffff811bf846: klp_try_complete_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void klp_try_complete_transition();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/transition.c (0)
Location: kernel/livepatch/transition.c:451
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:enabled_store
  - kernel/livepatch/transition.c:klp_transition_work_fn
```
**Symbols:**

```
ffffffff820d8f40-ffffffff820d8f6a: klp_try_complete_transition.cold (STB_LOCAL)
ffffffff811d2000-ffffffff811d232b: klp_try_complete_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void klp_try_complete_transition();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/transition.c (0)
Location: kernel/livepatch/transition.c:451
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:enabled_store
  - kernel/livepatch/transition.c:klp_transition_work_fn
```
**Symbols:**

```
ffffffff821b4679-ffffffff821b46a3: klp_try_complete_transition.cold (STB_LOCAL)
ffffffff811e6c80-ffffffff811e6fab: klp_try_complete_transition (STB_GLOBAL)
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
void klp_try_complete_transition();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (c0000000001f2e90)
Location: kernel/livepatch/transition.c:388
Inline: False
Direct callers:
  - kernel/livepatch/core.c:enabled_store
  - kernel/livepatch/transition.c:klp_transition_work_fn
```
**Symbols:**

```
c0000000001f2e90-c0000000001f3314: klp_try_complete_transition (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void klp_try_complete_transition();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/transition.c (0)
Location: kernel/livepatch/transition.c:388
Inline: False
Direct callers:
  - kernel/livepatch/core.c:enabled_store
  - kernel/livepatch/transition.c:klp_transition_work_fn
```
**Symbols:**

```
ffffffff81126b16-ffffffff81126b27: klp_try_complete_transition.cold (STB_LOCAL)
ffffffff81126470-ffffffff8112675c: klp_try_complete_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void klp_try_complete_transition();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/transition.c (0)
Location: kernel/livepatch/transition.c:388
Inline: False
Direct callers:
  - kernel/livepatch/core.c:enabled_store
  - kernel/livepatch/transition.c:klp_transition_work_fn
```
**Symbols:**

```
ffffffff81119576-ffffffff81119587: klp_try_complete_transition.cold (STB_LOCAL)
ffffffff81118ed0-ffffffff811191b2: klp_try_complete_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void klp_try_complete_transition();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/transition.c (0)
Location: kernel/livepatch/transition.c:388
Inline: False
Direct callers:
  - kernel/livepatch/core.c:enabled_store
  - kernel/livepatch/transition.c:klp_transition_work_fn
```
**Symbols:**

```
ffffffff81124a06-ffffffff81124a17: klp_try_complete_transition.cold (STB_LOCAL)
ffffffff81124360-ffffffff8112464c: klp_try_complete_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void klp_try_complete_transition();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/transition.c (0)
Location: kernel/livepatch/transition.c:388
Inline: False
Direct callers:
  - kernel/livepatch/core.c:enabled_store
  - kernel/livepatch/transition.c:klp_transition_work_fn
```
**Symbols:**

```
ffffffff81131056-ffffffff81131067: klp_try_complete_transition.cold (STB_LOCAL)
ffffffff811309c0-ffffffff81130c9d: klp_try_complete_transition (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
