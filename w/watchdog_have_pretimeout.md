# Function: <code>watchdog_have_pretimeout</code>

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
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff819edc55)
Location: drivers/watchdog/watchdog_core.h:67
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:wdt_is_visible
```
```
In drivers/watchdog/watchdog_pretimeout.c (ffffffff819ee565)
Location: drivers/watchdog/watchdog_core.h:67
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_unregister_pretimeout
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_pretimeout
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81b5456d)
Location: drivers/watchdog/watchdog_core.h:67
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:wdt_is_visible
  - drivers/watchdog/watchdog_dev.c:wdt_is_visible
```
```
In drivers/watchdog/watchdog_pretimeout.c (ffffffff81b54ed5)
Location: drivers/watchdog/watchdog_core.h:67
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_unregister_pretimeout
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_pretimeout
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81ced2fd)
Location: drivers/watchdog/watchdog_core.h:67
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:wdt_is_visible
  - drivers/watchdog/watchdog_dev.c:wdt_is_visible
```
```
In drivers/watchdog/watchdog_pretimeout.c (ffffffff81cedcf5)
Location: drivers/watchdog/watchdog_core.h:67
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_unregister_pretimeout
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_pretimeout
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81d5602b)
Location: drivers/watchdog/watchdog_core.h:67
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:wdt_is_visible
```
```
In drivers/watchdog/watchdog_pretimeout.c (ffffffff81d56a35)
Location: drivers/watchdog/watchdog_core.h:67
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_unregister_pretimeout
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_pretimeout
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81e0cf3b)
Location: drivers/watchdog/watchdog_core.h:67
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:wdt_is_visible
```
```
In drivers/watchdog/watchdog_pretimeout.c (ffffffff81e0d9a5)
Location: drivers/watchdog/watchdog_core.h:67
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_unregister_pretimeout
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_pretimeout
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
