# Function: <code>xsk_uses_need_wakeup</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool xsk_uses_need_wakeup(struct xsk_buff_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81bb5660)
Location: net/xdp/xsk.c:91
Inline: False
```
**Symbols:**

```
ffffffff81bb5660-ffffffff81bb5672: xsk_uses_need_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool xsk_uses_need_wakeup(struct xsk_buff_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ba4650)
Location: net/xdp/xsk.c:91
Inline: False
```
**Symbols:**

```
ffffffff81ba4650-ffffffff81ba4662: xsk_uses_need_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool xsk_uses_need_wakeup(struct xsk_buff_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (0)
Location: net/xdp/xsk.c:91
Inline: False
```
**Symbols:**

```
ffffffff81d42f7d-ffffffff81d42f9d: xsk_uses_need_wakeup.cold (STB_LOCAL)
ffffffff81c723d0-ffffffff81c723e8: xsk_uses_need_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool xsk_uses_need_wakeup(struct xsk_buff_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (0)
Location: net/xdp/xsk.c:91
Inline: False
```
**Symbols:**

```
ffffffff81f0f91a-ffffffff81f0f944: xsk_uses_need_wakeup.cold (STB_LOCAL)
ffffffff81e161f0-ffffffff81e16212: xsk_uses_need_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool xsk_uses_need_wakeup(struct xsk_buff_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (0)
Location: net/xdp/xsk.c:91
Inline: False
```
**Symbols:**

```
ffffffff820b5cb0-ffffffff820b5cda: xsk_uses_need_wakeup.cold (STB_LOCAL)
ffffffff81fed260-ffffffff81fed282: xsk_uses_need_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool xsk_uses_need_wakeup(struct xsk_buff_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (0)
Location: net/xdp/xsk.c:92
Inline: False
```
**Symbols:**

```
ffffffff821371f7-ffffffff82137221: xsk_uses_need_wakeup.cold (STB_LOCAL)
ffffffff82069400-ffffffff82069422: xsk_uses_need_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool xsk_uses_need_wakeup(struct xsk_buff_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (0)
Location: net/xdp/xsk.c:94
Inline: False
```
**Symbols:**

```
ffffffff82219059-ffffffff82219083: xsk_uses_need_wakeup.cold (STB_LOCAL)
ffffffff8213c6a0-ffffffff8213c6c2: xsk_uses_need_wakeup (STB_GLOBAL)
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
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
