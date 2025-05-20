# Function: <code>relay_alloc_buf</code>

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
In kernel/relay.c (ffffffff8113d4b3)
Location: kernel/relay.c:123
Inline: True
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
In kernel/relay.c (ffffffff81145c92)
Location: kernel/relay.c:123
Inline: True
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
In kernel/relay.c (ffffffff8114f9c2)
Location: kernel/relay.c:123
Inline: True
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
In kernel/relay.c (ffffffff81152113)
Location: kernel/relay.c:123
Inline: True
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
In kernel/relay.c (ffffffff8115e7c3)
Location: kernel/relay.c:123
Inline: True
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
In kernel/relay.c (ffffffff8116d69c)
Location: kernel/relay.c:123
Inline: True
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
In kernel/relay.c (ffffffff8117b0e3)
Location: kernel/relay.c:123
Inline: True
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
In kernel/relay.c (ffffffff81188083)
Location: kernel/relay.c:123
Inline: True
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
In kernel/relay.c (ffffffff81193fc3)
Location: kernel/relay.c:123
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *relay_alloc_buf(struct rchan_buf *buf, size_t *size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff811a8020)
Location: kernel/relay.c:123
Inline: False
Direct callers:
  - kernel/relay.c:relay_create_buf
```
**Symbols:**

```
ffffffff811a8020-ffffffff811a81b4: relay_alloc_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *relay_alloc_buf(struct rchan_buf *buf, size_t *size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff811a55a0)
Location: kernel/relay.c:111
Inline: False
Direct callers:
  - kernel/relay.c:relay_create_buf
```
**Symbols:**

```
ffffffff811a55a0-ffffffff811a5734: relay_alloc_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff811a6b7f)
Location: kernel/relay.c:111
Inline: True
Inline callers:
  - kernel/relay.c:relay_create_buf
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff811d039f)
Location: kernel/relay.c:111
Inline: True
Inline callers:
  - kernel/relay.c:relay_create_buf
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *relay_alloc_buf(struct rchan_buf *buf, size_t *size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff81203c20)
Location: kernel/relay.c:111
Inline: False
Direct callers:
  - kernel/relay.c:relay_create_buf
```
**Symbols:**

```
ffffffff81203c20-ffffffff81203db4: relay_alloc_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *relay_alloc_buf(struct rchan_buf *buf, size_t *size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff8124b840)
Location: kernel/relay.c:108
Inline: False
Direct callers:
  - kernel/relay.c:relay_create_buf
```
**Symbols:**

```
ffffffff8124b840-ffffffff8124b9c0: relay_alloc_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *relay_alloc_buf(struct rchan_buf *buf, size_t *size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff81262ac0)
Location: kernel/relay.c:108
Inline: False
Direct callers:
  - kernel/relay.c:relay_create_buf
```
**Symbols:**

```
ffffffff81262ac0-ffffffff81262c40: relay_alloc_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *relay_alloc_buf(struct rchan_buf *buf, size_t *size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff8127cce0)
Location: kernel/relay.c:108
Inline: False
Direct callers:
  - kernel/relay.c:relay_create_buf
```
**Symbols:**

```
ffffffff8127cce0-ffffffff8127ce60: relay_alloc_buf (STB_LOCAL)
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
In kernel/relay.c (ffff80001020b9cc)
Location: kernel/relay.c:123
Inline: True
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
In kernel/relay.c (c044aabc)
Location: kernel/relay.c:123
Inline: True
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
In kernel/relay.c (c0000000002899cc)
Location: kernel/relay.c:123
Inline: True
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
In kernel/relay.c (ffffffe00016d3a4)
Location: kernel/relay.c:123
Inline: True
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
In kernel/relay.c (ffffffff8118c5e3)
Location: kernel/relay.c:123
Inline: True
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
In kernel/relay.c (ffffffff8117f6c3)
Location: kernel/relay.c:123
Inline: True
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
In kernel/relay.c (ffffffff8118a3b3)
Location: kernel/relay.c:123
Inline: True
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
In kernel/relay.c (ffffffff81197d23)
Location: kernel/relay.c:123
Inline: True
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
