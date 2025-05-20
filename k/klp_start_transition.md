# Function: <code>klp_start_transition</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void klp_start_transition();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff810f9000)
Location: kernel/livepatch/transition.c:422
Inline: True
Direct callers:
  - kernel/livepatch/core.c:__klp_disable_patch
  - kernel/livepatch/transition.c:klp_reverse_transition
```
**Symbols:**

```
ffffffff810f9000-ffffffff810f9139: klp_start_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void klp_start_transition();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff81103a00)
Location: kernel/livepatch/transition.c:444
Inline: True
Direct callers:
  - kernel/livepatch/core.c:__klp_disable_patch
  - kernel/livepatch/transition.c:klp_reverse_transition
```
**Symbols:**

```
ffffffff81103a00-ffffffff81103b2f: klp_start_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void klp_start_transition();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/transition.c (0)
Location: kernel/livepatch/transition.c:424
Inline: True
Direct callers:
  - kernel/livepatch/core.c:__klp_disable_patch
  - kernel/livepatch/transition.c:klp_reverse_transition
```
**Symbols:**

```
ffffffff8110c307-ffffffff8110c401: klp_start_transition.cold.9 (STB_LOCAL)
ffffffff8110bf80-ffffffff8110bfab: klp_start_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void klp_start_transition();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff81117b39)
Location: kernel/livepatch/transition.c:417
Inline: True
Direct callers:
  - kernel/livepatch/core.c:__klp_disable_patch
  - kernel/livepatch/transition.c:klp_reverse_transition
```
**Symbols:**

```
ffffffff81117af7-ffffffff81117bf1: klp_start_transition.cold.10 (STB_LOCAL)
ffffffff81117770-ffffffff8111779b: klp_start_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void klp_start_transition();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff81121f62)
Location: kernel/livepatch/transition.c:463
Inline: True
Direct callers:
  - kernel/livepatch/core.c:enabled_store
  - kernel/livepatch/transition.c:klp_reverse_transition
```
**Symbols:**

```
ffffffff81121f27-ffffffff81122020: klp_start_transition.cold (STB_LOCAL)
ffffffff81121ba0-ffffffff81121bc8: klp_start_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void klp_start_transition();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff8112e582)
Location: kernel/livepatch/transition.c:463
Inline: True
Direct callers:
  - kernel/livepatch/core.c:enabled_store
  - kernel/livepatch/transition.c:klp_reverse_transition
```
**Symbols:**

```
ffffffff8112e547-ffffffff8112e640: klp_start_transition.cold (STB_LOCAL)
ffffffff8112e1c0-ffffffff8112e1e8: klp_start_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void klp_start_transition();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff8113cde6)
Location: kernel/livepatch/transition.c:463
Inline: True
Direct callers:
  - kernel/livepatch/core.c:__klp_enable_patch
  - kernel/livepatch/core.c:enabled_store
  - kernel/livepatch/transition.c:klp_reverse_transition
```
**Symbols:**

```
ffffffff8113cde6-ffffffff8113ceb8: klp_start_transition.part.0 (STB_LOCAL)
ffffffff8113cf0f-ffffffff8113cf51: klp_start_transition.cold (STB_LOCAL)
ffffffff8113cab0-ffffffff8113cad6: klp_start_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void klp_start_transition();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff81be3391)
Location: kernel/livepatch/transition.c:463
Inline: True
Direct callers:
  - kernel/livepatch/core.c:__klp_enable_patch
  - kernel/livepatch/core.c:enabled_store
  - kernel/livepatch/transition.c:klp_reverse_transition
```
**Symbols:**

```
ffffffff81be3391-ffffffff81be3463: klp_start_transition.part.0 (STB_LOCAL)
ffffffff81be34ba-ffffffff81be34fc: klp_start_transition.cold (STB_LOCAL)
ffffffff811371c0-ffffffff811371e6: klp_start_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void klp_start_transition();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff81bd52fa)
Location: kernel/livepatch/transition.c:462
Inline: True
Direct callers:
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:enabled_store
  - kernel/livepatch/transition.c:klp_reverse_transition
```
**Symbols:**

```
ffffffff81bd52b8-ffffffff81bd53b7: klp_start_transition.cold (STB_LOCAL)
ffffffff81137f70-ffffffff81137f9b: klp_start_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void klp_start_transition();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff8115afbb)
Location: kernel/livepatch/transition.c:462
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
Direct callers:
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:enabled_store
  - kernel/livepatch/transition.c:klp_reverse_transition
```
**Symbols:**

```
ffffffff81caffec-ffffffff81cb00be: klp_start_transition.part.0 (STB_LOCAL)
ffffffff81cb016f-ffffffff81cb01b1: klp_start_transition.cold (STB_LOCAL)
ffffffff8115ace0-ffffffff8115ad06: klp_start_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void klp_start_transition();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff811848c0)
Location: kernel/livepatch/transition.c:462
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
Direct callers:
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:enabled_store
  - kernel/livepatch/transition.c:klp_reverse_transition
```
**Symbols:**

```
ffffffff81e60c03-ffffffff81e60ce2: klp_start_transition.part.0 (STB_LOCAL)
ffffffff81e60da4-ffffffff81e60df2: klp_start_transition.cold (STB_LOCAL)
ffffffff811845d0-ffffffff811845f6: klp_start_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void klp_start_transition();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff811bf8b0)
Location: kernel/livepatch/transition.c:462
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:enabled_store
  - kernel/livepatch/transition.c:klp_reverse_transition
```
**Symbols:**

```
ffffffff811bf8b0-ffffffff811bf9f7: klp_start_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void klp_start_transition();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff811d2390)
Location: kernel/livepatch/transition.c:530
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:enabled_store
  - kernel/livepatch/transition.c:klp_reverse_transition
```
**Symbols:**

```
ffffffff811d2390-ffffffff811d24dc: klp_start_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void klp_start_transition();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff811e7010)
Location: kernel/livepatch/transition.c:530
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:enabled_store
  - kernel/livepatch/transition.c:klp_reverse_transition
```
**Symbols:**

```
ffffffff811e7010-ffffffff811e715c: klp_start_transition (STB_GLOBAL)
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
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void klp_start_transition();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (c0000000001f3390)
Location: kernel/livepatch/transition.c:463
Inline: True
Direct callers:
  - kernel/livepatch/core.c:enabled_store
  - kernel/livepatch/transition.c:klp_reverse_transition
```
**Symbols:**

```
c0000000001f3390-c0000000001f3560: klp_start_transition (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void klp_start_transition();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff81126b62)
Location: kernel/livepatch/transition.c:463
Inline: True
Direct callers:
  - kernel/livepatch/core.c:enabled_store
  - kernel/livepatch/transition.c:klp_reverse_transition
```
**Symbols:**

```
ffffffff81126b27-ffffffff81126c20: klp_start_transition.cold (STB_LOCAL)
ffffffff811267a0-ffffffff811267c8: klp_start_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void klp_start_transition();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff811195c2)
Location: kernel/livepatch/transition.c:463
Inline: True
Direct callers:
  - kernel/livepatch/core.c:enabled_store
  - kernel/livepatch/transition.c:klp_reverse_transition
```
**Symbols:**

```
ffffffff81119587-ffffffff81119680: klp_start_transition.cold (STB_LOCAL)
ffffffff81119200-ffffffff81119228: klp_start_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void klp_start_transition();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff81124a52)
Location: kernel/livepatch/transition.c:463
Inline: True
Direct callers:
  - kernel/livepatch/core.c:enabled_store
  - kernel/livepatch/transition.c:klp_reverse_transition
```
**Symbols:**

```
ffffffff81124a17-ffffffff81124b10: klp_start_transition.cold (STB_LOCAL)
ffffffff81124690-ffffffff811246b8: klp_start_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void klp_start_transition();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff811310a2)
Location: kernel/livepatch/transition.c:463
Inline: True
Direct callers:
  - kernel/livepatch/core.c:enabled_store
  - kernel/livepatch/transition.c:klp_reverse_transition
```
**Symbols:**

```
ffffffff81131067-ffffffff8113115f: klp_start_transition.cold (STB_LOCAL)
ffffffff81130ce0-ffffffff81130d08: klp_start_transition (STB_GLOBAL)
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
