# Function: <code>klp_reverse_transition</code>

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
void klp_reverse_transition();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff810f92b0)
Location: kernel/livepatch/transition.c:545
Inline: False
Direct callers:
  - kernel/livepatch/core.c:enabled_store
```
**Symbols:**

```
ffffffff810f92b0-ffffffff810f939f: klp_reverse_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void klp_reverse_transition();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff81103ce0)
Location: kernel/livepatch/transition.c:571
Inline: False
Direct callers:
  - kernel/livepatch/core.c:enabled_store
```
**Symbols:**

```
ffffffff81103ce0-ffffffff81103e09: klp_reverse_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void klp_reverse_transition();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff8110c140)
Location: kernel/livepatch/transition.c:537
Inline: False
Direct callers:
  - kernel/livepatch/core.c:enabled_store
```
**Symbols:**

```
ffffffff8110c140-ffffffff8110c269: klp_reverse_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void klp_reverse_transition();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff81117930)
Location: kernel/livepatch/transition.c:530
Inline: False
Direct callers:
  - kernel/livepatch/core.c:enabled_store
```
**Symbols:**

```
ffffffff81117930-ffffffff81117a59: klp_reverse_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void klp_reverse_transition();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff81121d70)
Location: kernel/livepatch/transition.c:578
Inline: False
Direct callers:
  - kernel/livepatch/core.c:enabled_store
```
**Symbols:**

```
ffffffff81121d70-ffffffff81121ea6: klp_reverse_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void klp_reverse_transition();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff8112e390)
Location: kernel/livepatch/transition.c:578
Inline: False
Direct callers:
  - kernel/livepatch/core.c:enabled_store
```
**Symbols:**

```
ffffffff8112e390-ffffffff8112e4c6: klp_reverse_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void klp_reverse_transition();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff8113cc80)
Location: kernel/livepatch/transition.c:578
Inline: False
Direct callers:
  - kernel/livepatch/core.c:enabled_store
```
**Symbols:**

```
ffffffff8113cc80-ffffffff8113cdbb: klp_reverse_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void klp_reverse_transition();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff81137390)
Location: kernel/livepatch/transition.c:578
Inline: False
Direct callers:
  - kernel/livepatch/core.c:enabled_store
```
**Symbols:**

```
ffffffff81137390-ffffffff811374cb: klp_reverse_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void klp_reverse_transition();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff81138140)
Location: kernel/livepatch/transition.c:577
Inline: False
Direct callers:
  - kernel/livepatch/core.c:enabled_store
```
**Symbols:**

```
ffffffff81138140-ffffffff8113827b: klp_reverse_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void klp_reverse_transition();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/transition.c (0)
Location: kernel/livepatch/transition.c:577
Inline: False
Direct callers:
  - kernel/livepatch/core.c:enabled_store
```
**Symbols:**

```
ffffffff81cb01b1-ffffffff81cb0213: klp_reverse_transition.cold (STB_LOCAL)
ffffffff8115aeb0-ffffffff8115b017: klp_reverse_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void klp_reverse_transition();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/transition.c (0)
Location: kernel/livepatch/transition.c:577
Inline: False
Direct callers:
  - kernel/livepatch/core.c:enabled_store
```
**Symbols:**

```
ffffffff81e60df2-ffffffff81e60e61: klp_reverse_transition.cold (STB_LOCAL)
ffffffff811847c0-ffffffff8118491c: klp_reverse_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void klp_reverse_transition();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/transition.c (0)
Location: kernel/livepatch/transition.c:577
Inline: False
Direct callers:
  - kernel/livepatch/core.c:enabled_store
```
**Symbols:**

```
ffffffff8205a6f6-ffffffff8205a711: klp_reverse_transition.cold (STB_LOCAL)
ffffffff811bfbe0-ffffffff811bfd3d: klp_reverse_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void klp_reverse_transition();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/transition.c (0)
Location: kernel/livepatch/transition.c:648
Inline: False
Direct callers:
  - kernel/livepatch/core.c:enabled_store
```
**Symbols:**

```
ffffffff820d8f6a-ffffffff820d8f85: klp_reverse_transition.cold (STB_LOCAL)
ffffffff811d26c0-ffffffff811d281d: klp_reverse_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void klp_reverse_transition();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/transition.c (0)
Location: kernel/livepatch/transition.c:648
Inline: False
Direct callers:
  - kernel/livepatch/core.c:enabled_store
```
**Symbols:**

```
ffffffff821b46a3-ffffffff821b46be: klp_reverse_transition.cold (STB_LOCAL)
ffffffff811e7340-ffffffff811e749d: klp_reverse_transition (STB_GLOBAL)
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
void klp_reverse_transition();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (c0000000001f37d0)
Location: kernel/livepatch/transition.c:578
Inline: False
Direct callers:
  - kernel/livepatch/core.c:enabled_store
```
**Symbols:**

```
c0000000001f37d0-c0000000001f39ac: klp_reverse_transition (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void klp_reverse_transition();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff81126970)
Location: kernel/livepatch/transition.c:578
Inline: False
Direct callers:
  - kernel/livepatch/core.c:enabled_store
```
**Symbols:**

```
ffffffff81126970-ffffffff81126aa6: klp_reverse_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void klp_reverse_transition();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff811193d0)
Location: kernel/livepatch/transition.c:578
Inline: False
Direct callers:
  - kernel/livepatch/core.c:enabled_store
```
**Symbols:**

```
ffffffff811193d0-ffffffff81119506: klp_reverse_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void klp_reverse_transition();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff81124860)
Location: kernel/livepatch/transition.c:578
Inline: False
Direct callers:
  - kernel/livepatch/core.c:enabled_store
```
**Symbols:**

```
ffffffff81124860-ffffffff81124996: klp_reverse_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void klp_reverse_transition();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff81130eb0)
Location: kernel/livepatch/transition.c:578
Inline: False
Direct callers:
  - kernel/livepatch/core.c:enabled_store
```
**Symbols:**

```
ffffffff81130eb0-ffffffff81130fe5: klp_reverse_transition (STB_GLOBAL)
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
