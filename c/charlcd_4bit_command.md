# Function: <code>charlcd_4bit_command</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
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
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void charlcd_4bit_command(struct charlcd *lcd, u8 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/auxdisplay/arm-charlcd.c (c0ae8720)
Location: drivers/auxdisplay/arm-charlcd.c:186
Inline: False
Direct callers:
  - drivers/auxdisplay/arm-charlcd.c:charlcd_resume
  - drivers/auxdisplay/arm-charlcd.c:charlcd_suspend
  - drivers/auxdisplay/arm-charlcd.c:charlcd_init_work
  - drivers/auxdisplay/arm-charlcd.c:charlcd_init_work
  - drivers/auxdisplay/arm-charlcd.c:charlcd_init_work
  - drivers/auxdisplay/arm-charlcd.c:charlcd_init_work
  - drivers/auxdisplay/arm-charlcd.c:charlcd_init_work
  - drivers/auxdisplay/arm-charlcd.c:charlcd_init_work
  - drivers/auxdisplay/arm-charlcd.c:charlcd_init_work
```
**Symbols:**

```
c0ae8720-c0ae8788: charlcd_4bit_command (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
