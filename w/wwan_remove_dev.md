# Function: <code>wwan_remove_dev</code>

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
In drivers/net/wwan/wwan_core.c (ffffffff81888450)
Location: drivers/net/wwan/wwan_core.c:149
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_remove_port
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void wwan_remove_dev(struct wwan_device *wwandev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/wwan/wwan_core.c (ffffffff81919780)
Location: drivers/net/wwan/wwan_core.c:203
Inline: False
Direct callers:
  - drivers/net/wwan/wwan_core.c:wwan_unregister_ops
  - drivers/net/wwan/wwan_core.c:wwan_register_ops
  - drivers/net/wwan/wwan_core.c:wwan_remove_port
```
**Symbols:**

```
ffffffff81919780-ffffffff819197e1: wwan_remove_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void wwan_remove_dev(struct wwan_device *wwandev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/wwan/wwan_core.c (ffffffff81a6e920)
Location: drivers/net/wwan/wwan_core.c:265
Inline: False
Direct callers:
  - drivers/net/wwan/wwan_core.c:wwan_unregister_ops
  - drivers/net/wwan/wwan_core.c:wwan_register_ops
  - drivers/net/wwan/wwan_core.c:wwan_remove_port
  - drivers/net/wwan/wwan_core.c:wwan_create_port
```
**Symbols:**

```
ffffffff81a6e920-ffffffff81a6e999: wwan_remove_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void wwan_remove_dev(struct wwan_device *wwandev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/wwan/wwan_core.c (ffffffff81c018c0)
Location: drivers/net/wwan/wwan_core.c:266
Inline: False
Direct callers:
  - drivers/net/wwan/wwan_core.c:wwan_unregister_ops
  - drivers/net/wwan/wwan_core.c:wwan_register_ops
  - drivers/net/wwan/wwan_core.c:wwan_remove_port
  - drivers/net/wwan/wwan_core.c:wwan_create_port
```
**Symbols:**

```
ffffffff81c018c0-ffffffff81c01939: wwan_remove_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void wwan_remove_dev(struct wwan_device *wwandev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/wwan/wwan_core.c (ffffffff81c66e00)
Location: drivers/net/wwan/wwan_core.c:270
Inline: False
Direct callers:
  - drivers/net/wwan/wwan_core.c:wwan_unregister_ops
  - drivers/net/wwan/wwan_core.c:wwan_register_ops
  - drivers/net/wwan/wwan_core.c:wwan_remove_port
  - drivers/net/wwan/wwan_core.c:wwan_create_port
```
**Symbols:**

```
ffffffff81c66e00-ffffffff81c66e79: wwan_remove_dev (STB_LOCAL)
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
