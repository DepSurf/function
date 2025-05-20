# Function: <code>aa_listener_unotif_recv</code>

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
long int aa_listener_unotif_recv(struct aa_listener *listener, void *buf, u16 max_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/notify.c (ffffffff816eb4e0)
Location: security/apparmor/notify.c:569
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:listener_ioctl
```
**Symbols:**

```
ffffffff816eb4e0-ffffffff816eb7d5: aa_listener_unotif_recv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int aa_listener_unotif_recv(struct aa_listener *listener, void *buf, u16 max_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/notify.c (ffffffff817259b0)
Location: security/apparmor/notify.c:1017
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:listener_ioctl
```
**Symbols:**

```
ffffffff817259b0-ffffffff81725c07: aa_listener_unotif_recv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int aa_listener_unotif_recv(struct aa_listener *listener, void *buf, u16 max_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/notify.c (ffffffff81766bb0)
Location: security/apparmor/notify.c:1024
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:listener_ioctl
```
**Symbols:**

```
ffffffff81766bb0-ffffffff81766dff: aa_listener_unotif_recv (STB_GLOBAL)
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
