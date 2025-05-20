# Function: <code>poll_one_napi</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (ffffffff81738f76)
Location: net/core/netpoll.c:143
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (ffffffff817a522d)
Location: net/core/netpoll.c:143
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (ffffffff817d3c9b)
Location: net/core/netpoll.c:143
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (ffffffff817f3013)
Location: net/core/netpoll.c:149
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (ffffffff8186e406)
Location: net/core/netpoll.c:149
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (ffffffff818bf592)
Location: net/core/netpoll.c:149
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (ffffffff818e83ba)
Location: net/core/netpoll.c:137
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (ffffffff81937bca)
Location: net/core/netpoll.c:138
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (ffffffff8196aa8a)
Location: net/core/netpoll.c:138
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void poll_one_napi(struct napi_struct *napi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (ffffffff81a3e480)
Location: net/core/netpoll.c:139
Inline: False
Direct callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff81a3e480-ffffffff81a3e526: poll_one_napi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void poll_one_napi(struct napi_struct *napi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (ffffffff81a41230)
Location: net/core/netpoll.c:140
Inline: False
Direct callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff81a41230-ffffffff81a412c5: poll_one_napi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void poll_one_napi(struct napi_struct *napi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (ffffffff81a25e90)
Location: net/core/netpoll.c:139
Inline: False
Direct callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff81a25e90-ffffffff81a25f25: poll_one_napi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void poll_one_napi(struct napi_struct *napi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/netpoll.c (0)
Location: net/core/netpoll.c:140
Inline: False
Direct callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff81adabf0-ffffffff81adac96: poll_one_napi (STB_LOCAL)
ffffffff81d37c54-ffffffff81d37c6f: poll_one_napi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void poll_one_napi(struct napi_struct *napi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/netpoll.c (0)
Location: net/core/netpoll.c:140
Inline: False
Direct callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff81c5baa0-ffffffff81c5bb7c: poll_one_napi (STB_LOCAL)
ffffffff81f04429-ffffffff81f0443e: poll_one_napi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void poll_one_napi(struct napi_struct *napi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/netpoll.c (0)
Location: net/core/netpoll.c:140
Inline: False
Direct callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff81e11ed0-ffffffff81e11fac: poll_one_napi (STB_LOCAL)
ffffffff820ac940-ffffffff820ac955: poll_one_napi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void poll_one_napi(struct napi_struct *napi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/netpoll.c (0)
Location: net/core/netpoll.c:154
Inline: False
Direct callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff81e857e0-ffffffff81e858c2: poll_one_napi (STB_LOCAL)
ffffffff8212e037-ffffffff8212e052: poll_one_napi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void poll_one_napi(struct napi_struct *napi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/netpoll.c (0)
Location: net/core/netpoll.c:154
Inline: False
Direct callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff81f47710-ffffffff81f477f2: poll_one_napi (STB_LOCAL)
ffffffff8220fe16-ffffffff8220fe31: poll_one_napi.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (ffff800010c11048)
Location: net/core/netpoll.c:138
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (c0d28ef0)
Location: net/core/netpoll.c:138
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (c000000000cfd508)
Location: net/core/netpoll.c:138
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (ffffffe00078d0e2)
Location: net/core/netpoll.c:138
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (ffffffff8190aa5a)
Location: net/core/netpoll.c:138
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (ffffffff818c464a)
Location: net/core/netpoll.c:138
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (ffffffff8195ba8a)
Location: net/core/netpoll.c:138
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (ffffffff8197de7a)
Location: net/core/netpoll.c:138
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
