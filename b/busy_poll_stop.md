# Function: <code>busy_poll_stop</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
void busy_poll_stop(struct napi_struct *napi, void *have_poll_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817aeba0)
Location: net/core/dev.c:5051
Inline: False
Direct callers:
  - net/core/dev.c:sk_busy_loop
  - net/core/dev.c:sk_busy_loop
```
**Symbols:**

```
ffffffff817aeba0-ffffffff817aec12: busy_poll_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void busy_poll_stop(struct napi_struct *napi, void *have_poll_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817cd510)
Location: net/core/dev.c:5270
Inline: False
Direct callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff817cd510-ffffffff817cd5c7: busy_poll_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void busy_poll_stop(struct napi_struct *napi, void *have_poll_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81846c40)
Location: net/core/dev.c:5411
Inline: False
Direct callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff81846c40-ffffffff81846cff: busy_poll_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void busy_poll_stop(struct napi_struct *napi, void *have_poll_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818902b0)
Location: net/core/dev.c:5541
Inline: False
Direct callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff818902b0-ffffffff8189036f: busy_poll_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void busy_poll_stop(struct napi_struct *napi, void *have_poll_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b0b60)
Location: net/core/dev.c:6094
Inline: False
Direct callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff818b0b60-ffffffff818b0c1f: busy_poll_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void busy_poll_stop(struct napi_struct *napi, void *have_poll_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818fd900)
Location: net/core/dev.c:6104
Inline: False
Direct callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff818fd900-ffffffff818fd9bc: busy_poll_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void busy_poll_stop(struct napi_struct *napi, void *have_poll_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81935650)
Location: net/core/dev.c:6030
Inline: False
Direct callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff81935650-ffffffff8193572d: busy_poll_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void busy_poll_stop(struct napi_struct *napi, void *have_poll_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0a2e0)
Location: net/core/dev.c:6420
Inline: False
Direct callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff81a0a2e0-ffffffff81a0a3e1: busy_poll_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void busy_poll_stop(struct napi_struct *napi, void *have_poll_lock, bool prefer_busy_poll, u16 budget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0c570)
Location: net/core/dev.c:6539
Inline: False
Direct callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff81a0c570-ffffffff81a0c70c: busy_poll_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void busy_poll_stop(struct napi_struct *napi, void *have_poll_lock, bool prefer_busy_poll, u16 budget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819f2850)
Location: net/core/dev.c:6660
Inline: False
Direct callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff819f2850-ffffffff819f29ec: busy_poll_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void busy_poll_stop(struct napi_struct *napi, void *have_poll_lock, bool prefer_busy_poll, u16 budget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81aa4720)
Location: net/core/dev.c:6646
Inline: False
Direct callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff81aa4720-ffffffff81aa48b9: busy_poll_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void busy_poll_stop(struct napi_struct *napi, void *have_poll_lock, bool prefer_busy_poll, u16 budget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c1be60)
Location: net/core/dev.c:6132
Inline: False
Direct callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff81c1be60-ffffffff81c1c011: busy_poll_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void busy_poll_stop(struct napi_struct *napi, void *have_poll_lock, bool prefer_busy_poll, u16 budget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dcce30)
Location: net/core/dev.c:6121
Inline: False
Direct callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff81dcce30-ffffffff81dccfe1: busy_poll_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void busy_poll_stop(struct napi_struct *napi, void *have_poll_lock, bool prefer_busy_poll, u16 budget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e3d990)
Location: net/core/dev.c:6098
Inline: False
Direct callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff81e3d990-ffffffff81e3db41: busy_poll_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void busy_poll_stop(struct napi_struct *napi, void *have_poll_lock, bool prefer_busy_poll, u16 budget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81efc230)
Location: net/core/dev.c:6180
Inline: False
Direct callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff81efc230-ffffffff81efc3e4: busy_poll_stop (STB_LOCAL)
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
void busy_poll_stop(struct napi_struct *napi, void *have_poll_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd3970)
Location: net/core/dev.c:6030
Inline: False
Direct callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffff800010bd3970-ffff800010bd3aec: busy_poll_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void busy_poll_stop(struct napi_struct *napi, void *have_poll_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0cee6a0)
Location: net/core/dev.c:6030
Inline: False
Direct callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
c0cee6a0-c0cee7e4: busy_poll_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void busy_poll_stop(struct napi_struct *napi, void *have_poll_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cb2660)
Location: net/core/dev.c:6030
Inline: False
Direct callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
c000000000cb2660-c000000000cb2824: busy_poll_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void busy_poll_stop(struct napi_struct *napi, void *have_poll_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075db0e)
Location: net/core/dev.c:6030
Inline: False
Direct callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffe00075db0e-ffffffe00075dc0e: busy_poll_stop (STB_LOCAL)
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
void busy_poll_stop(struct napi_struct *napi, void *have_poll_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d5620)
Location: net/core/dev.c:6030
Inline: False
Direct callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff818d5620-ffffffff818d56fd: busy_poll_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void busy_poll_stop(struct napi_struct *napi, void *have_poll_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188f490)
Location: net/core/dev.c:6030
Inline: False
Direct callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff8188f490-ffffffff8188f56d: busy_poll_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void busy_poll_stop(struct napi_struct *napi, void *have_poll_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81926650)
Location: net/core/dev.c:6030
Inline: False
Direct callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff81926650-ffffffff8192672d: busy_poll_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void busy_poll_stop(struct napi_struct *napi, void *have_poll_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81947c30)
Location: net/core/dev.c:6030
Inline: False
Direct callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff81947c30-ffffffff81947d28: busy_poll_stop (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool prefer_busy_poll</code>
</li>
<li>
<b>Param added. </b>
<code>u16 budget</code>
</li>
</ul>
</details>
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
