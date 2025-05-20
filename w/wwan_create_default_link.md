# Function: <code>wwan_create_default_link</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void wwan_create_default_link(struct wwan_device *wwandev, u32 def_link_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/wwan/wwan_core.c (ffffffff8191a8c0)
Location: drivers/net/wwan/wwan_core.c:940
Inline: False
Direct callers:
  - drivers/net/wwan/wwan_core.c:wwan_register_ops
```
**Symbols:**

```
ffffffff8191a8c0-ffffffff8191abcd: wwan_create_default_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void wwan_create_default_link(struct wwan_device *wwandev, u32 def_link_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/wwan/wwan_core.c (ffffffff81a6fcd0)
Location: drivers/net/wwan/wwan_core.c:1006
Inline: False
Direct callers:
  - drivers/net/wwan/wwan_core.c:wwan_register_ops
```
**Symbols:**

```
ffffffff81a6fcd0-ffffffff81a7002b: wwan_create_default_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void wwan_create_default_link(struct wwan_device *wwandev, u32 def_link_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/wwan/wwan_core.c (ffffffff81c02b60)
Location: drivers/net/wwan/wwan_core.c:1011
Inline: False
Direct callers:
  - drivers/net/wwan/wwan_core.c:wwan_register_ops
```
**Symbols:**

```
ffffffff81c02b60-ffffffff81c02ebf: wwan_create_default_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void wwan_create_default_link(struct wwan_device *wwandev, u32 def_link_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/wwan/wwan_core.c (ffffffff81c68210)
Location: drivers/net/wwan/wwan_core.c:1044
Inline: False
Direct callers:
  - drivers/net/wwan/wwan_core.c:wwan_register_ops
```
**Symbols:**

```
ffffffff81c68210-ffffffff81c6856f: wwan_create_default_link (STB_LOCAL)
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
