# Function: <code>xennet_poll</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xennet_poll(struct napi_struct *napi, int budget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff815fb380)
Location: drivers/net/xen-netfront.c:963
Inline: False
```
**Symbols:**

```
ffffffff815fb380-ffffffff815fbefa: xennet_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xennet_poll(struct napi_struct *napi, int budget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff8165b2a0)
Location: drivers/net/xen-netfront.c:954
Inline: False
```
**Symbols:**

```
ffffffff8165b2a0-ffffffff8165be56: xennet_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xennet_poll(struct napi_struct *napi, int budget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff816890c0)
Location: drivers/net/xen-netfront.c:977
Inline: False
```
**Symbols:**

```
ffffffff816890c0-ffffffff81689c7d: xennet_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xennet_poll(struct napi_struct *napi, int budget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff8169e800)
Location: drivers/net/xen-netfront.c:978
Inline: False
```
**Symbols:**

```
ffffffff8169e800-ffffffff8169f3c9: xennet_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xennet_poll(struct napi_struct *napi, int budget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff817099a0)
Location: drivers/net/xen-netfront.c:980
Inline: False
```
**Symbols:**

```
ffffffff817099a0-ffffffff8170a563: xennet_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int xennet_poll(struct napi_struct *napi, int budget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:987
Inline: False
```
**Symbols:**

```
ffffffff81748440-ffffffff8174900d: xennet_poll (STB_LOCAL)
ffffffff8174a3fa-ffffffff8174a420: xennet_poll.cold.43 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int xennet_poll(struct napi_struct *napi, int budget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:986
Inline: False
```
**Symbols:**

```
ffffffff8176c4f0-ffffffff8176d0a8: xennet_poll (STB_LOCAL)
ffffffff8176e580-ffffffff8176e5a6: xennet_poll.cold.43 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int xennet_poll(struct napi_struct *napi, int budget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:985
Inline: False
```
**Symbols:**

```
ffffffff817aa310-ffffffff817aae79: xennet_poll (STB_LOCAL)
ffffffff817ac278-ffffffff817ac377: xennet_poll.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int xennet_poll(struct napi_struct *napi, int budget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:987
Inline: False
```
**Symbols:**

```
ffffffff817cdd70-ffffffff817ce8bc: xennet_poll (STB_LOCAL)
ffffffff817cfcb8-ffffffff817cfdb7: xennet_poll.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int xennet_poll(struct napi_struct *napi, int budget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:989
Inline: False
```
**Symbols:**

```
ffffffff81899e50-ffffffff8189a31a: xennet_poll (STB_LOCAL)
ffffffff8189a85c-ffffffff8189a89e: xennet_poll.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int xennet_poll(struct napi_struct *napi, int budget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:1138
Inline: False
```
**Symbols:**

```
ffffffff818a8f90-ffffffff818a949f: xennet_poll (STB_LOCAL)
ffffffff81c19f2e-ffffffff81c19f70: xennet_poll.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int xennet_poll(struct napi_struct *napi, int budget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:1136
Inline: False
```
**Symbols:**

```
ffffffff8188c200-ffffffff8188c863: xennet_poll (STB_LOCAL)
ffffffff81c0bd92-ffffffff81c0bdb8: xennet_poll.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xennet_poll(struct napi_struct *napi, int budget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:1217
Inline: False
```
**Symbols:**

```
ffffffff8191f5c0-ffffffff8191fd75: xennet_poll (STB_LOCAL)
ffffffff81d115bd-ffffffff81d11641: xennet_poll.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xennet_poll(struct napi_struct *napi, int budget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:1256
Inline: False
```
**Symbols:**

```
ffffffff81a745f0-ffffffff81a74e98: xennet_poll (STB_LOCAL)
ffffffff81edc288-ffffffff81edc308: xennet_poll.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int xennet_poll(struct napi_struct *napi, int budget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:1256
Inline: False
```
**Symbols:**

```
ffffffff81c08850-ffffffff81c09147: xennet_poll (STB_LOCAL)
ffffffff8209dc7f-ffffffff8209dca8: xennet_poll.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int xennet_poll(struct napi_struct *napi, int budget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:1256
Inline: False
```
**Symbols:**

```
ffffffff81c6dfb0-ffffffff81c6e903: xennet_poll (STB_LOCAL)
ffffffff8211f1f7-ffffffff8211f220: xennet_poll.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int xennet_poll(struct napi_struct *napi, int budget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:1257
Inline: False
```
**Symbols:**

```
ffffffff81d228a0-ffffffff81d2319a: xennet_poll (STB_LOCAL)
ffffffff822009cd-ffffffff822009f6: xennet_poll.cold (STB_LOCAL)
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
int xennet_poll(struct napi_struct *napi, int budget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffff800010a08608)
Location: drivers/net/xen-netfront.c:987
Inline: False
```
**Symbols:**

```
ffff800010a08608-ffff800010a09000: xennet_poll (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
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
int xennet_poll(struct napi_struct *napi, int budget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:1019
Inline: False
```
**Symbols:**

```
ffffffff81792990-ffffffff817934dc: xennet_poll (STB_LOCAL)
ffffffff8179492c-ffffffff81794a2b: xennet_poll.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int xennet_poll(struct napi_struct *napi, int budget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:987
Inline: False
```
**Symbols:**

```
ffffffff817c2bf0-ffffffff817c373c: xennet_poll (STB_LOCAL)
ffffffff817c4b38-ffffffff817c4c37: xennet_poll.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int xennet_poll(struct napi_struct *napi, int budget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:987
Inline: False
```
**Symbols:**

```
ffffffff817dceb0-ffffffff817dd9fa: xennet_poll (STB_LOCAL)
ffffffff817deddf-ffffffff817deede: xennet_poll.cold (STB_LOCAL)
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
