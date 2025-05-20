# Function: <code>bad_io_access</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bad_io_access(long unsigned int port, const char *access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81402670)
Location: lib/iomap.c:38
Inline: False
Direct callers:
  - lib/iomap.c:ioread8
  - lib/iomap.c:ioread16
  - lib/iomap.c:ioread32
  - lib/iomap.c:iowrite8
  - lib/iomap.c:iowrite16
  - lib/iomap.c:iowrite32
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread32be
  - lib/iomap.c:pci_iounmap
```
**Symbols:**

```
ffffffff81402670-ffffffff814026a8: bad_io_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void bad_io_access(long unsigned int port, const char *access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8144a320)
Location: lib/iomap.c:38
Inline: False
Direct callers:
  - lib/iomap.c:pci_iounmap
  - lib/iomap.c:iowrite32be
  - lib/iomap.c:iowrite32
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
  - lib/iomap.c:iowrite8
  - lib/iomap.c:ioread32be
  - lib/iomap.c:ioread32
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
  - lib/iomap.c:ioread8
```
**Symbols:**

```
ffffffff8144a320-ffffffff8144a358: bad_io_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bad_io_access(long unsigned int port, const char *access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81468ce0)
Location: lib/iomap.c:38
Inline: False
Direct callers:
  - lib/iomap.c:pci_iounmap
  - lib/iomap.c:iowrite32be
  - lib/iomap.c:iowrite32
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
  - lib/iomap.c:iowrite8
  - lib/iomap.c:ioread32be
  - lib/iomap.c:ioread32
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
  - lib/iomap.c:ioread8
```
**Symbols:**

```
ffffffff81468ce0-ffffffff81468d18: bad_io_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bad_io_access(long unsigned int port, const char *access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8146e3d0)
Location: lib/iomap.c:38
Inline: False
Direct callers:
  - lib/iomap.c:pci_iounmap
  - lib/iomap.c:iowrite32be
  - lib/iomap.c:iowrite32
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
  - lib/iomap.c:iowrite8
  - lib/iomap.c:ioread32be
  - lib/iomap.c:ioread32
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
  - lib/iomap.c:ioread8
```
**Symbols:**

```
ffffffff8146e3d0-ffffffff8146e3ff: bad_io_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bad_io_access(long unsigned int port, const char *access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8149a700)
Location: lib/iomap.c:39
Inline: False
Direct callers:
  - lib/iomap.c:pci_iounmap
  - lib/iomap.c:iowrite32be
  - lib/iomap.c:iowrite32
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
  - lib/iomap.c:iowrite8
  - lib/iomap.c:ioread32be
  - lib/iomap.c:ioread32
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
  - lib/iomap.c:ioread8
```
**Symbols:**

```
ffffffff8149a700-ffffffff8149a72f: bad_io_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void bad_io_access(long unsigned int port, const char *access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff814cf9b0)
Location: lib/iomap.c:39
Inline: False
Direct callers:
  - lib/iomap.c:pci_iounmap
  - lib/iomap.c:iowrite32be
  - lib/iomap.c:iowrite32
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
  - lib/iomap.c:iowrite8
  - lib/iomap.c:ioread32be
  - lib/iomap.c:ioread32
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
  - lib/iomap.c:ioread8
```
**Symbols:**

```
ffffffff814cf9b0-ffffffff814cf9de: bad_io_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bad_io_access(long unsigned int port, const char *access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff814e42c0)
Location: lib/iomap.c:39
Inline: False
Direct callers:
  - lib/iomap.c:pci_iounmap
  - lib/iomap.c:iowrite32be
  - lib/iomap.c:iowrite32
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
  - lib/iomap.c:iowrite8
  - lib/iomap.c:ioread32be
  - lib/iomap.c:ioread32
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
  - lib/iomap.c:ioread8
```
**Symbols:**

```
ffffffff814e42c0-ffffffff814e42ee: bad_io_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bad_io_access(long unsigned int port, const char *access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81510a20)
Location: lib/iomap.c:39
Inline: False
Direct callers:
  - lib/iomap.c:pci_iounmap
  - lib/iomap.c:iowrite32_rep
  - lib/iomap.c:iowrite16_rep
  - lib/iomap.c:iowrite8_rep
  - lib/iomap.c:ioread32_rep
  - lib/iomap.c:ioread16_rep
  - lib/iomap.c:ioread8_rep
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_lo_hi
  - lib/iomap.c:iowrite32be
  - lib/iomap.c:iowrite32
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
  - lib/iomap.c:iowrite8
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_lo_hi
  - lib/iomap.c:ioread32be
  - lib/iomap.c:ioread32
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
  - lib/iomap.c:ioread8
```
**Symbols:**

```
ffffffff81510a20-ffffffff81510a4e: bad_io_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bad_io_access(long unsigned int port, const char *access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81531490)
Location: lib/iomap.c:39
Inline: False
Direct callers:
  - lib/iomap.c:pci_iounmap
  - lib/iomap.c:iowrite32_rep
  - lib/iomap.c:iowrite16_rep
  - lib/iomap.c:iowrite8_rep
  - lib/iomap.c:ioread32_rep
  - lib/iomap.c:ioread16_rep
  - lib/iomap.c:ioread8_rep
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_lo_hi
  - lib/iomap.c:iowrite32be
  - lib/iomap.c:iowrite32
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
  - lib/iomap.c:iowrite8
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_lo_hi
  - lib/iomap.c:ioread32be
  - lib/iomap.c:ioread32
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
  - lib/iomap.c:ioread8
```
**Symbols:**

```
ffffffff81531490-ffffffff815314be: bad_io_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81595728)
Location: lib/iomap.c:39
Inline: True
Inline callers:
  - lib/iomap.c:pci_iounmap
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_lo_hi
  - lib/iomap.c:iowrite32be
  - lib/iomap.c:iowrite32
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
  - lib/iomap.c:iowrite8
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_lo_hi
  - lib/iomap.c:ioread32be
  - lib/iomap.c:ioread32
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
  - lib/iomap.c:ioread8
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff815b11b8)
Location: lib/iomap.c:39
Inline: True
Inline callers:
  - lib/iomap.c:pci_iounmap
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_lo_hi
  - lib/iomap.c:iowrite32be
  - lib/iomap.c:iowrite32
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
  - lib/iomap.c:iowrite8
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_lo_hi
  - lib/iomap.c:ioread32be
  - lib/iomap.c:ioread32
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
  - lib/iomap.c:ioread8
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
In lib/iomap.c (ffffffff815bbfc8)
Location: lib/iomap.c:39
Inline: True
Inline callers:
  - lib/iomap.c:pci_iounmap
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_lo_hi
  - lib/iomap.c:iowrite32be
  - lib/iomap.c:iowrite32
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
  - lib/iomap.c:iowrite8
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_lo_hi
  - lib/iomap.c:ioread32be
  - lib/iomap.c:ioread32
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
  - lib/iomap.c:ioread8
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
In lib/iomap.c (ffffffff81622e18)
Location: lib/iomap.c:39
Inline: True
Inline callers:
  - lib/iomap.c:pci_iounmap
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_lo_hi
  - lib/iomap.c:iowrite32be
  - lib/iomap.c:iowrite32
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
  - lib/iomap.c:iowrite8
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_lo_hi
  - lib/iomap.c:ioread32be
  - lib/iomap.c:ioread32
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
  - lib/iomap.c:ioread8
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
In lib/iomap.c (ffffffff816f2d94)
Location: lib/iomap.c:39
Inline: True
Inline callers:
  - lib/iomap.c:pci_iounmap
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_lo_hi
  - lib/iomap.c:iowrite32be
  - lib/iomap.c:iowrite32
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
  - lib/iomap.c:iowrite8
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_lo_hi
  - lib/iomap.c:ioread32be
  - lib/iomap.c:ioread32
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
  - lib/iomap.c:ioread8
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
In lib/iomap.c (ffffffff817e4c34)
Location: lib/iomap.c:40
Inline: True
Inline callers:
  - lib/iomap.c:pci_iounmap
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_lo_hi
  - lib/iomap.c:iowrite32be
  - lib/iomap.c:iowrite32
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
  - lib/iomap.c:iowrite8
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_lo_hi
  - lib/iomap.c:ioread32be
  - lib/iomap.c:ioread32
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
  - lib/iomap.c:ioread8
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
In lib/iomap.c (ffffffff81824c74)
Location: lib/iomap.c:40
Inline: True
Inline callers:
  - lib/iomap.c:pci_iounmap
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_lo_hi
  - lib/iomap.c:iowrite32be
  - lib/iomap.c:iowrite32
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
  - lib/iomap.c:iowrite8
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_lo_hi
  - lib/iomap.c:ioread32be
  - lib/iomap.c:ioread32
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
  - lib/iomap.c:ioread8
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
In lib/iomap.c (ffffffff81876684)
Location: lib/iomap.c:40
Inline: True
Inline callers:
  - lib/iomap.c:pci_iounmap
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_lo_hi
  - lib/iomap.c:iowrite32be
  - lib/iomap.c:iowrite32
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
  - lib/iomap.c:iowrite8
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_lo_hi
  - lib/iomap.c:ioread32be
  - lib/iomap.c:ioread32
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
  - lib/iomap.c:ioread8
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
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/iomap.c (c0000000007e4f40)
Location: lib/iomap.c:39
Inline: True
```
**Symbols:**

```
c0000000007e4f40-c0000000007e4f9c: bad_io_access.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void bad_io_access(long unsigned int port, const char *access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81529a70)
Location: lib/iomap.c:39
Inline: False
Direct callers:
  - lib/iomap.c:pci_iounmap
  - lib/iomap.c:iowrite32_rep
  - lib/iomap.c:iowrite16_rep
  - lib/iomap.c:iowrite8_rep
  - lib/iomap.c:ioread32_rep
  - lib/iomap.c:ioread16_rep
  - lib/iomap.c:ioread8_rep
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_lo_hi
  - lib/iomap.c:iowrite32be
  - lib/iomap.c:iowrite32
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
  - lib/iomap.c:iowrite8
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_lo_hi
  - lib/iomap.c:ioread32be
  - lib/iomap.c:ioread32
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
  - lib/iomap.c:ioread8
```
**Symbols:**

```
ffffffff81529a70-ffffffff81529a9e: bad_io_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bad_io_access(long unsigned int port, const char *access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81519d50)
Location: lib/iomap.c:39
Inline: False
Direct callers:
  - lib/iomap.c:pci_iounmap
  - lib/iomap.c:iowrite32_rep
  - lib/iomap.c:iowrite16_rep
  - lib/iomap.c:iowrite8_rep
  - lib/iomap.c:ioread32_rep
  - lib/iomap.c:ioread16_rep
  - lib/iomap.c:ioread8_rep
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_lo_hi
  - lib/iomap.c:iowrite32be
  - lib/iomap.c:iowrite32
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
  - lib/iomap.c:iowrite8
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_lo_hi
  - lib/iomap.c:ioread32be
  - lib/iomap.c:ioread32
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
  - lib/iomap.c:ioread8
```
**Symbols:**

```
ffffffff81519d50-ffffffff81519d7e: bad_io_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bad_io_access(long unsigned int port, const char *access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81525b00)
Location: lib/iomap.c:39
Inline: False
Direct callers:
  - lib/iomap.c:pci_iounmap
  - lib/iomap.c:iowrite32_rep
  - lib/iomap.c:iowrite16_rep
  - lib/iomap.c:iowrite8_rep
  - lib/iomap.c:ioread32_rep
  - lib/iomap.c:ioread16_rep
  - lib/iomap.c:ioread8_rep
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_lo_hi
  - lib/iomap.c:iowrite32be
  - lib/iomap.c:iowrite32
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
  - lib/iomap.c:iowrite8
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_lo_hi
  - lib/iomap.c:ioread32be
  - lib/iomap.c:ioread32
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
  - lib/iomap.c:ioread8
```
**Symbols:**

```
ffffffff81525b00-ffffffff81525b2e: bad_io_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bad_io_access(long unsigned int port, const char *access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8153f480)
Location: lib/iomap.c:39
Inline: False
Direct callers:
  - lib/iomap.c:pci_iounmap
  - lib/iomap.c:iowrite32_rep
  - lib/iomap.c:iowrite16_rep
  - lib/iomap.c:iowrite8_rep
  - lib/iomap.c:ioread32_rep
  - lib/iomap.c:ioread16_rep
  - lib/iomap.c:ioread8_rep
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_lo_hi
  - lib/iomap.c:iowrite32be
  - lib/iomap.c:iowrite32
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
  - lib/iomap.c:iowrite8
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_lo_hi
  - lib/iomap.c:ioread32be
  - lib/iomap.c:ioread32
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
  - lib/iomap.c:ioread8
```
**Symbols:**

```
ffffffff8153f480-ffffffff8153f4ae: bad_io_access (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
