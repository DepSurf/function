# Function: <code>config_endpoint_is_duplicate</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:224
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool config_endpoint_is_duplicate(struct usb_host_config *config, int inum, int asnum, struct usb_endpoint_descriptor *d);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff818c60d0)
Location: drivers/usb/core/config.c:224
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
```
**Symbols:**

```
ffffffff818c60d0-ffffffff818c61b2: config_endpoint_is_duplicate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool config_endpoint_is_duplicate(struct usb_host_config *config, int inum, int asnum, struct usb_endpoint_descriptor *d);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff818d1d30)
Location: drivers/usb/core/config.c:224
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
```
**Symbols:**

```
ffffffff818d1d30-ffffffff818d1e12: config_endpoint_is_duplicate (STB_LOCAL)
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
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:224
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
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
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:224
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
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
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:224
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
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
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:224
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
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
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:224
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
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
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:224
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
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
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:224
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
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
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:224
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
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
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:224
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
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
In drivers/usb/core/config.c (ffffffe000648fc4)
Location: drivers/usb/core/config.c:224
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
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
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:224
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
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
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:224
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
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
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:224
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
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
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:224
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
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
