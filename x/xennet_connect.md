# Function: <code>xennet_connect</code>

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
In drivers/net/xen-netfront.c (ffffffff815fd1cc)
Location: drivers/net/xen-netfront.c:1958
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
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
In drivers/net/xen-netfront.c (ffffffff8165d0e1)
Location: drivers/net/xen-netfront.c:1949
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xennet_connect(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff8168a310)
Location: drivers/net/xen-netfront.c:1943
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:netback_changed
```
**Symbols:**

```
ffffffff8168a310-ffffffff8168af75: xennet_connect (STB_LOCAL)
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
In drivers/net/xen-netfront.c (ffffffff816a014c)
Location: drivers/net/xen-netfront.c:1941
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
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
In drivers/net/xen-netfront.c (ffffffff8170b312)
Location: drivers/net/xen-netfront.c:1943
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
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
In drivers/net/xen-netfront.c (ffffffff81749d77)
Location: drivers/net/xen-netfront.c:1946
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
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
In drivers/net/xen-netfront.c (ffffffff8176df07)
Location: drivers/net/xen-netfront.c:1945
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
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
In drivers/net/xen-netfront.c (ffffffff817ac121)
Location: drivers/net/xen-netfront.c:1944
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
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
In drivers/net/xen-netfront.c (ffffffff817cfb61)
Location: drivers/net/xen-netfront.c:1945
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int xennet_connect(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:1950
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:netback_changed
```
**Symbols:**

```
ffffffff8189a3c0-ffffffff8189a525: xennet_connect (STB_LOCAL)
ffffffff8189a89e-ffffffff8189a8e9: xennet_connect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int xennet_connect(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:2246
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:netback_changed
```
**Symbols:**

```
ffffffff818a8390-ffffffff818a8502: xennet_connect (STB_LOCAL)
ffffffff81c19e3b-ffffffff81c19e97: xennet_connect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int xennet_connect(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:2244
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:netback_changed
```
**Symbols:**

```
ffffffff8188b810-ffffffff8188b96e: xennet_connect (STB_LOCAL)
ffffffff81c0bc3b-ffffffff81c0bc98: xennet_connect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xennet_connect(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:2396
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:netback_changed
```
**Symbols:**

```
ffffffff8191f290-ffffffff8191f4f9: xennet_connect (STB_LOCAL)
ffffffff81d1154a-ffffffff81d115bd: xennet_connect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xennet_connect(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:2410
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:netback_changed
```
**Symbols:**

```
ffffffff81a73600-ffffffff81a737c1: xennet_connect (STB_LOCAL)
ffffffff81edc06e-ffffffff81edc110: xennet_connect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int xennet_connect(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:2415
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:netback_changed
```
**Symbols:**

```
ffffffff81c07890-ffffffff81c07aa0: xennet_connect (STB_LOCAL)
ffffffff8209dc3c-ffffffff8209dc64: xennet_connect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int xennet_connect(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:2417
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:netback_changed
```
**Symbols:**

```
ffffffff81c6cfb0-ffffffff81c6d1c0: xennet_connect (STB_LOCAL)
ffffffff8211f1b4-ffffffff8211f1dc: xennet_connect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int xennet_connect(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:2418
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:netback_changed
```
**Symbols:**

```
ffffffff81d218f0-ffffffff81d21b0c: xennet_connect (STB_LOCAL)
ffffffff8220098a-ffffffff822009b2: xennet_connect.cold (STB_LOCAL)
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
In drivers/net/xen-netfront.c (ffff800010a090e4)
Location: drivers/net/xen-netfront.c:1945
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff817947a1)
Location: drivers/net/xen-netfront.c:2023
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff817c49e1)
Location: drivers/net/xen-netfront.c:1945
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
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
In drivers/net/xen-netfront.c (ffffffff817dec91)
Location: drivers/net/xen-netfront.c:1945
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
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
