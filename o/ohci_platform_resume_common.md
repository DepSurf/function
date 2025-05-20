# Function: <code>ohci_platform_resume_common</code>

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
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ohci_platform_resume_common(struct device *dev, bool hibernated);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-platform.c (ffffffff81c6c660)
Location: drivers/usb/host/ohci-platform.c:290
Inline: False
Direct callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_restore
  - drivers/usb/host/ohci-platform.c:ohci_platform_resume
```
**Symbols:**

```
ffffffff81c6c660-ffffffff81c6c6ce: ohci_platform_resume_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ohci_platform_resume_common(struct device *dev, bool hibernated);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-platform.c (ffffffff81cd3c50)
Location: drivers/usb/host/ohci-platform.c:288
Inline: False
Direct callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_restore
  - drivers/usb/host/ohci-platform.c:ohci_platform_resume
```
**Symbols:**

```
ffffffff81cd3c50-ffffffff81cd3cbe: ohci_platform_resume_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ohci_platform_resume_common(struct device *dev, bool hibernated);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-platform.c (ffffffff81d88c10)
Location: drivers/usb/host/ohci-platform.c:287
Inline: False
Direct callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_restore
  - drivers/usb/host/ohci-platform.c:ohci_platform_resume
```
**Symbols:**

```
ffffffff81d88c10-ffffffff81d88c7e: ohci_platform_resume_common (STB_LOCAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
