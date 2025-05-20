# Function: <code>tun_napi_alloc_frags</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff816fecdf)
Location: drivers/net/tun.c:1292
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
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
In drivers/net/tun.c (ffffffff8173e990)
Location: drivers/net/tun.c:1480
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
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
In drivers/net/tun.c (ffffffff817625f6)
Location: drivers/net/tun.c:1471
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
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
In drivers/net/tun.c (ffffffff817a0338)
Location: drivers/net/tun.c:1462
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
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
In drivers/net/tun.c (ffffffff817c52e8)
Location: drivers/net/tun.c:1462
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *tun_napi_alloc_frags(struct tun_file *tfile, size_t len, const struct iov_iter *it);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8188b4a0)
Location: drivers/net/tun.c:1427
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff8188b4a0-ffffffff8188b6f6: tun_napi_alloc_frags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *tun_napi_alloc_frags(struct tun_file *tfile, size_t len, const struct iov_iter *it);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81899640)
Location: drivers/net/tun.c:1358
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff81899640-ffffffff818998af: tun_napi_alloc_frags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *tun_napi_alloc_frags(struct tun_file *tfile, size_t len, const struct iov_iter *it);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8187bab0)
Location: drivers/net/tun.c:1369
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff8187bab0-ffffffff8187bd24: tun_napi_alloc_frags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *tun_napi_alloc_frags(struct tun_file *tfile, size_t len, const struct iov_iter *it);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8190cfe0)
Location: drivers/net/tun.c:1425
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff8190cfe0-ffffffff8190d253: tun_napi_alloc_frags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *tun_napi_alloc_frags(struct tun_file *tfile, size_t len, const struct iov_iter *it);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81a629c0)
Location: drivers/net/tun.c:1453
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff81a629c0-ffffffff81a62ce0: tun_napi_alloc_frags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *tun_napi_alloc_frags(struct tun_file *tfile, size_t len, const struct iov_iter *it);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81beee80)
Location: drivers/net/tun.c:1455
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff81beee80-ffffffff81bef18e: tun_napi_alloc_frags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *tun_napi_alloc_frags(struct tun_file *tfile, size_t len, const struct iov_iter *it);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81c46f10)
Location: drivers/net/tun.c:1460
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff81c46f10-ffffffff81c4726b: tun_napi_alloc_frags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *tun_napi_alloc_frags(struct tun_file *tfile, size_t len, const struct iov_iter *it);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81cfc830)
Location: drivers/net/tun.c:1461
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff81cfc830-ffffffff81cfcb6e: tun_napi_alloc_frags (STB_LOCAL)
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
In drivers/net/tun.c (ffff8000109e056c)
Location: drivers/net/tun.c:1462
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
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
In drivers/net/tun.c (c0ac46c4)
Location: drivers/net/tun.c:1462
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
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
In drivers/net/tun.c (c000000000aa18f8)
Location: drivers/net/tun.c:1462
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
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
In drivers/net/tun.c (ffffffe00062a430)
Location: drivers/net/tun.c:1462
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
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
In drivers/net/tun.c (ffffffff81789dc8)
Location: drivers/net/tun.c:1462
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
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
In drivers/net/tun.c (ffffffff81769718)
Location: drivers/net/tun.c:1462
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
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
In drivers/net/tun.c (ffffffff817ba168)
Location: drivers/net/tun.c:1462
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
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
In drivers/net/tun.c (ffffffff817d2668)
Location: drivers/net/tun.c:1462
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
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
