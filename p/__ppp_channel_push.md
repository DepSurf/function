# Function: <code>__ppp_channel_push</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81685cfe)
Location: drivers/net/ppp/ppp_generic.c:1882
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __ppp_channel_push(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff8169b0c0)
Location: drivers/net/ppp/ppp_generic.c:1896
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
```
**Symbols:**

```
ffffffff8169b0c0-ffffffff8169b15b: __ppp_channel_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __ppp_channel_push(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff817058a0)
Location: drivers/net/ppp/ppp_generic.c:1923
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
```
**Symbols:**

```
ffffffff817058a0-ffffffff81705943: __ppp_channel_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __ppp_channel_push(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81744d40)
Location: drivers/net/ppp/ppp_generic.c:1906
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
```
**Symbols:**

```
ffffffff81744d40-ffffffff81744de3: __ppp_channel_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __ppp_channel_push(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81768e30)
Location: drivers/net/ppp/ppp_generic.c:1906
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
```
**Symbols:**

```
ffffffff81768e30-ffffffff81768ed3: __ppp_channel_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __ppp_channel_push(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff817a6910)
Location: drivers/net/ppp/ppp_generic.c:1902
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
```
**Symbols:**

```
ffffffff817a6910-ffffffff817a69b3: __ppp_channel_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __ppp_channel_push(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff817ca370)
Location: drivers/net/ppp/ppp_generic.c:1902
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
```
**Symbols:**

```
ffffffff817ca370-ffffffff817ca413: __ppp_channel_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __ppp_channel_push(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff818953c0)
Location: drivers/net/ppp/ppp_generic.c:1990
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
```
**Symbols:**

```
ffffffff818953c0-ffffffff81895463: __ppp_channel_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __ppp_channel_push(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff818a3af0)
Location: drivers/net/ppp/ppp_generic.c:2100
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
```
**Symbols:**

```
ffffffff818a3af0-ffffffff818a3b93: __ppp_channel_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __ppp_channel_push(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81885800)
Location: drivers/net/ppp/ppp_generic.c:2133
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
```
**Symbols:**

```
ffffffff81885800-ffffffff818858a3: __ppp_channel_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __ppp_channel_push(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81917190)
Location: drivers/net/ppp/ppp_generic.c:2138
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
```
**Symbols:**

```
ffffffff81917190-ffffffff81917233: __ppp_channel_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __ppp_channel_push(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81a6b560)
Location: drivers/net/ppp/ppp_generic.c:2139
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
```
**Symbols:**

```
ffffffff81a6b560-ffffffff81a6b62b: __ppp_channel_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __ppp_channel_push(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfe410)
Location: drivers/net/ppp/ppp_generic.c:2141
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
```
**Symbols:**

```
ffffffff81bfe410-ffffffff81bfe4db: __ppp_channel_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __ppp_channel_push(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81c63a50)
Location: drivers/net/ppp/ppp_generic.c:2141
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
```
**Symbols:**

```
ffffffff81c63a50-ffffffff81c63b1b: __ppp_channel_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __ppp_channel_push(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81d1a470)
Location: drivers/net/ppp/ppp_generic.c:2141
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
```
**Symbols:**

```
ffffffff81d1a470-ffffffff81d1a540: __ppp_channel_push (STB_LOCAL)
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
void __ppp_channel_push(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffff800010a01eb8)
Location: drivers/net/ppp/ppp_generic.c:1902
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
```
**Symbols:**

```
ffff800010a01eb8-ffff800010a01fe8: __ppp_channel_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __ppp_channel_push(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (c0adf0ec)
Location: drivers/net/ppp/ppp_generic.c:1902
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
```
**Symbols:**

```
c0adf0ec-c0adf1ac: __ppp_channel_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __ppp_channel_push(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (c000000000aaa850)
Location: drivers/net/ppp/ppp_generic.c:1902
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
```
**Symbols:**

```
c000000000aaa850-c000000000aaa9e0: __ppp_channel_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __ppp_channel_push(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffe00062e9e4)
Location: drivers/net/ppp/ppp_generic.c:1902
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
```
**Symbols:**

```
ffffffe00062e9e4-ffffffe00062eac6: __ppp_channel_push (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void __ppp_channel_push(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff8178ee50)
Location: drivers/net/ppp/ppp_generic.c:1902
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
```
**Symbols:**

```
ffffffff8178ee50-ffffffff8178eef3: __ppp_channel_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __ppp_channel_push(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81777c20)
Location: drivers/net/ppp/ppp_generic.c:1902
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
```
**Symbols:**

```
ffffffff81777c20-ffffffff81777cc3: __ppp_channel_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __ppp_channel_push(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff817bf1f0)
Location: drivers/net/ppp/ppp_generic.c:1902
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
```
**Symbols:**

```
ffffffff817bf1f0-ffffffff817bf293: __ppp_channel_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __ppp_channel_push(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff817d9480)
Location: drivers/net/ppp/ppp_generic.c:1902
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
```
**Symbols:**

```
ffffffff817d9480-ffffffff817d952d: __ppp_channel_push (STB_LOCAL)
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
