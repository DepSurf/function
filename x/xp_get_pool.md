# Function: <code>xp_get_pool</code>

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
void xp_get_pool(struct xsk_buff_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81bb9bb0)
Location: net/xdp/xsk_buff_pool.c:250
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff81bb9bb0-ffffffff81bb9bf2: xp_get_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xp_get_pool(struct xsk_buff_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81ba8d50)
Location: net/xdp/xsk_buff_pool.c:244
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff81ba8d50-ffffffff81ba8d92: xp_get_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xp_get_pool(struct xsk_buff_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81c76b10)
Location: net/xdp/xsk_buff_pool.c:244
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff81c76b10-ffffffff81c76b52: xp_get_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xp_get_pool(struct xsk_buff_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81e1b490)
Location: net/xdp/xsk_buff_pool.c:265
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff81e1b490-ffffffff81e1b4fc: xp_get_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xp_get_pool(struct xsk_buff_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81ff2a40)
Location: net/xdp/xsk_buff_pool.c:266
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff81ff2a40-ffffffff81ff2aac: xp_get_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xp_get_pool(struct xsk_buff_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff8206ec60)
Location: net/xdp/xsk_buff_pool.c:269
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff8206ec60-ffffffff8206eccc: xp_get_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xp_get_pool(struct xsk_buff_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff82142d40)
Location: net/xdp/xsk_buff_pool.c:293
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff82142d40-ffffffff82142dac: xp_get_pool (STB_GLOBAL)
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
