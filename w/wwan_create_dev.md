# Function: <code>wwan_create_dev</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/wwan/wwan_core.c (ffffffff818880c7)
Location: drivers/net/wwan/wwan_core.c:100
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct wwan_device *wwan_create_dev(struct device *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/wwan/wwan_core.c (ffffffff8191a3c0)
Location: drivers/net/wwan/wwan_core.c:150
Inline: False
Direct callers:
  - drivers/net/wwan/wwan_core.c:wwan_register_ops
```
**Symbols:**

```
ffffffff8191a3c0-ffffffff8191a4d5: wwan_create_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct wwan_device *wwan_create_dev(struct device *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/wwan/wwan_core.c (ffffffff81a6f6f0)
Location: drivers/net/wwan/wwan_core.c:206
Inline: False
Direct callers:
  - drivers/net/wwan/wwan_core.c:wwan_register_ops
  - drivers/net/wwan/wwan_core.c:wwan_create_port
```
**Symbols:**

```
ffffffff81a6f6f0-ffffffff81a6f826: wwan_create_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct wwan_device *wwan_create_dev(struct device *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/wwan/wwan_core.c (ffffffff81c02520)
Location: drivers/net/wwan/wwan_core.c:207
Inline: False
Direct callers:
  - drivers/net/wwan/wwan_core.c:wwan_register_ops
  - drivers/net/wwan/wwan_core.c:wwan_create_port
```
**Symbols:**

```
ffffffff81c02520-ffffffff81c02656: wwan_create_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct wwan_device *wwan_create_dev(struct device *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/wwan/wwan_core.c (ffffffff81c67a80)
Location: drivers/net/wwan/wwan_core.c:211
Inline: False
Direct callers:
  - drivers/net/wwan/wwan_core.c:wwan_register_ops
  - drivers/net/wwan/wwan_core.c:wwan_create_port
```
**Symbols:**

```
ffffffff81c67a80-ffffffff81c67bb6: wwan_create_dev (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
