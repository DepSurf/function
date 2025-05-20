# Function: <code>mctp_ioctl</code>

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
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mctp_ioctl(struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mctp/af_mctp.c (0)
Location: net/mctp/af_mctp.c:430
Inline: False
Direct callers:
  - net/mctp/af_mctp.c:mctp_compat_ioctl
```
**Symbols:**

```
ffffffff81e37710-ffffffff81e37941: mctp_ioctl (STB_LOCAL)
ffffffff81f10cea-ffffffff81f10d0d: mctp_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mctp_ioctl(struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mctp/af_mctp.c (0)
Location: net/mctp/af_mctp.c:439
Inline: False
Direct callers:
  - net/mctp/af_mctp.c:mctp_compat_ioctl
```
**Symbols:**

```
ffffffff82010580-ffffffff820107d4: mctp_ioctl (STB_LOCAL)
ffffffff820b6fad-ffffffff820b6fd0: mctp_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int mctp_ioctl(struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mctp/af_mctp.c (0)
Location: net/mctp/af_mctp.c:439
Inline: False
Direct callers:
  - net/mctp/af_mctp.c:mctp_compat_ioctl
```
**Symbols:**

```
ffffffff8208d950-ffffffff8208dba4: mctp_ioctl (STB_LOCAL)
ffffffff82138379-ffffffff8213839c: mctp_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int mctp_ioctl(struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mctp/af_mctp.c (0)
Location: net/mctp/af_mctp.c:439
Inline: False
Direct callers:
  - net/mctp/af_mctp.c:mctp_compat_ioctl
```
**Symbols:**

```
ffffffff82163e10-ffffffff82164064: mctp_ioctl (STB_LOCAL)
ffffffff8221a216-ffffffff8221a239: mctp_ioctl.cold (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
