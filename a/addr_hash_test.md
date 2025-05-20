# Function: <code>addr_hash_test</code>

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
In drivers/net/tun.c (ffffffff815eea21)
Location: drivers/net/tun.c:678
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
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
In drivers/net/tun.c (ffffffff8164d63a)
Location: drivers/net/tun.c:712
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
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
In drivers/net/tun.c (ffffffff8167f363)
Location: drivers/net/tun.c:712
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
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
In drivers/net/tun.c (ffffffff81694576)
Location: drivers/net/tun.c:715
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
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
In drivers/net/tun.c (ffffffff816fe6b0)
Location: drivers/net/tun.c:816
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
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
In drivers/net/tun.c (ffffffff8173d63a)
Location: drivers/net/tun.c:905
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
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
In drivers/net/tun.c (ffffffff8176124f)
Location: drivers/net/tun.c:910
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
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
In drivers/net/tun.c (ffffffff8179efec)
Location: drivers/net/tun.c:908
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
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
In drivers/net/tun.c (ffffffff817c361f)
Location: drivers/net/tun.c:908
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int addr_hash_test(const u32 *mask, const u8 *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8188b460)
Location: drivers/net/tun.c:876
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
```
**Symbols:**

```
ffffffff8188b460-ffffffff8188b4a0: addr_hash_test (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int addr_hash_test(const u32 *mask, const u8 *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81899600)
Location: drivers/net/tun.c:847
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
```
**Symbols:**

```
ffffffff81899600-ffffffff81899640: addr_hash_test (STB_LOCAL)
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
In drivers/net/tun.c (ffffffff8187fb2c)
Location: drivers/net/tun.c:855
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
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
In drivers/net/tun.c (ffffffff81910d8c)
Location: drivers/net/tun.c:861
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
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
In drivers/net/tun.c (ffffffff81a60bba)
Location: drivers/net/tun.c:871
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
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
In drivers/net/tun.c (ffffffff81bed1a1)
Location: drivers/net/tun.c:873
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
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
In drivers/net/tun.c (ffffffff81c4569a)
Location: drivers/net/tun.c:873
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
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
In drivers/net/tun.c (ffffffff81cfafb2)
Location: drivers/net/tun.c:874
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
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
In drivers/net/tun.c (ffff8000109df094)
Location: drivers/net/tun.c:908
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
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
In drivers/net/tun.c (c0ac2cf0)
Location: drivers/net/tun.c:908
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
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
In drivers/net/tun.c (c000000000aa0c00)
Location: drivers/net/tun.c:908
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
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
In drivers/net/tun.c (ffffffe00062831e)
Location: drivers/net/tun.c:908
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
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
In drivers/net/tun.c (ffffffff817880b0)
Location: drivers/net/tun.c:908
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
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
In drivers/net/tun.c (ffffffff81767a00)
Location: drivers/net/tun.c:908
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
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
In drivers/net/tun.c (ffffffff817b849f)
Location: drivers/net/tun.c:908
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
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
In drivers/net/tun.c (ffffffff817d079d)
Location: drivers/net/tun.c:908
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
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
