# Function: <code>addr_hash_set</code>

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
In drivers/net/tun.c (ffffffff815f0be1)
Location: drivers/net/tun.c:672
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
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
In drivers/net/tun.c (ffffffff8165023a)
Location: drivers/net/tun.c:706
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
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
In drivers/net/tun.c (ffffffff81681eb5)
Location: drivers/net/tun.c:706
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
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
In drivers/net/tun.c (ffffffff8169739b)
Location: drivers/net/tun.c:709
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
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
In drivers/net/tun.c (ffffffff81702217)
Location: drivers/net/tun.c:810
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
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
In drivers/net/tun.c (ffffffff81740f78)
Location: drivers/net/tun.c:899
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
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
In drivers/net/tun.c (ffffffff81765062)
Location: drivers/net/tun.c:904
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
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
In drivers/net/tun.c (ffffffff817a2e25)
Location: drivers/net/tun.c:902
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
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
In drivers/net/tun.c (ffffffff817c4fbe)
Location: drivers/net/tun.c:902
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void addr_hash_set(u32 *mask, const u8 *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8188a450)
Location: drivers/net/tun.c:870
Inline: False
Direct callers:
  - drivers/net/tun.c:update_filter
```
**Symbols:**

```
ffffffff8188a450-ffffffff8188a48e: addr_hash_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void addr_hash_set(u32 *mask, const u8 *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81898580)
Location: drivers/net/tun.c:841
Inline: False
Direct callers:
  - drivers/net/tun.c:update_filter
```
**Symbols:**

```
ffffffff81898580-ffffffff818985be: addr_hash_set (STB_LOCAL)
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
In drivers/net/tun.c (ffffffff8187ba01)
Location: drivers/net/tun.c:849
Inline: True
Inline callers:
  - drivers/net/tun.c:update_filter
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
In drivers/net/tun.c (ffffffff8190cf21)
Location: drivers/net/tun.c:855
Inline: True
Inline callers:
  - drivers/net/tun.c:update_filter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81a61937)
Location: drivers/net/tun.c:865
Inline: True
Inline callers:
  - drivers/net/tun.c:update_filter
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81beb6c7)
Location: drivers/net/tun.c:867
Inline: True
Inline callers:
  - drivers/net/tun.c:update_filter
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81c43b1d)
Location: drivers/net/tun.c:867
Inline: True
Inline callers:
  - drivers/net/tun.c:update_filter
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81cf93dd)
Location: drivers/net/tun.c:868
Inline: True
Inline callers:
  - drivers/net/tun.c:update_filter
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
In drivers/net/tun.c (ffff8000109e0234)
Location: drivers/net/tun.c:902
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
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
In drivers/net/tun.c (c0ac7c10)
Location: drivers/net/tun.c:902
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
In drivers/net/tun.c (c000000000aa52c0)
Location: drivers/net/tun.c:902
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
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
In drivers/net/tun.c (ffffffe000629ed4)
Location: drivers/net/tun.c:902
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
In drivers/net/tun.c (ffffffff81789a9e)
Location: drivers/net/tun.c:902
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
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
In drivers/net/tun.c (ffffffff817693ee)
Location: drivers/net/tun.c:902
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
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
In drivers/net/tun.c (ffffffff817b9e3e)
Location: drivers/net/tun.c:902
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
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
In drivers/net/tun.c (ffffffff817d58f6)
Location: drivers/net/tun.c:902
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
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
</ul>
