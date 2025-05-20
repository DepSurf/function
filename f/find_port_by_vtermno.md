# Function: <code>find_port_by_vtermno</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct port *find_port_by_vtermno(u32 vtermno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81515e00)
Location: drivers/char/virtio_console.c:250
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:put_chars
  - drivers/char/virtio_console.c:notifier_add_vio
```
**Symbols:**

```
ffffffff81515e00-ffffffff81515e5d: find_port_by_vtermno (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct port *find_port_by_vtermno(u32 vtermno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81568a60)
Location: drivers/char/virtio_console.c:256
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:notifier_add_vio
  - drivers/char/virtio_console.c:put_chars
```
**Symbols:**

```
ffffffff81568a60-ffffffff81568abd: find_port_by_vtermno (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct port *find_port_by_vtermno(u32 vtermno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff815951c0)
Location: drivers/char/virtio_console.c:255
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:notifier_add_vio
  - drivers/char/virtio_console.c:put_chars
```
**Symbols:**

```
ffffffff815951c0-ffffffff8159521d: find_port_by_vtermno (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct port *find_port_by_vtermno(u32 vtermno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff815a9290)
Location: drivers/char/virtio_console.c:255
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:notifier_add_vio
  - drivers/char/virtio_console.c:put_chars
```
**Symbols:**

```
ffffffff815a9290-ffffffff815a92ed: find_port_by_vtermno (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct port *find_port_by_vtermno(u32 vtermno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff8160fb90)
Location: drivers/char/virtio_console.c:255
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:notifier_add_vio
  - drivers/char/virtio_console.c:put_chars
```
**Symbols:**

```
ffffffff8160fb90-ffffffff8160fbed: find_port_by_vtermno (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct port *find_port_by_vtermno(u32 vtermno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff816499c0)
Location: drivers/char/virtio_console.c:255
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:notifier_add_vio
  - drivers/char/virtio_console.c:put_chars
```
**Symbols:**

```
ffffffff816499c0-ffffffff81649a1d: find_port_by_vtermno (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct port *find_port_by_vtermno(u32 vtermno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81667cc0)
Location: drivers/char/virtio_console.c:255
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:notifier_add_vio
  - drivers/char/virtio_console.c:put_chars
```
**Symbols:**

```
ffffffff81667cc0-ffffffff81667d1d: find_port_by_vtermno (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct port *find_port_by_vtermno(u32 vtermno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff8169d750)
Location: drivers/char/virtio_console.c:242
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:notifier_add_vio
  - drivers/char/virtio_console.c:put_chars
```
**Symbols:**

```
ffffffff8169d750-ffffffff8169d7ad: find_port_by_vtermno (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct port *find_port_by_vtermno(u32 vtermno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff816c04e0)
Location: drivers/char/virtio_console.c:242
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:notifier_add_vio
  - drivers/char/virtio_console.c:put_chars
```
**Symbols:**

```
ffffffff816c04e0-ffffffff816c053d: find_port_by_vtermno (STB_LOCAL)
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
In drivers/char/virtio_console.c (ffffffff81775176)
Location: drivers/char/virtio_console.c:242
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:notifier_add_vio
  - drivers/char/virtio_console.c:put_chars
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
In drivers/char/virtio_console.c (ffffffff8178feb6)
Location: drivers/char/virtio_console.c:242
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:notifier_add_vio
  - drivers/char/virtio_console.c:put_chars
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
In drivers/char/virtio_console.c (ffffffff81772ba6)
Location: drivers/char/virtio_console.c:242
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:notifier_add_vio
  - drivers/char/virtio_console.c:put_chars
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
In drivers/char/virtio_console.c (ffffffff817f8946)
Location: drivers/char/virtio_console.c:242
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:notifier_add_vio
  - drivers/char/virtio_console.c:get_chars
  - drivers/char/virtio_console.c:put_chars
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
In drivers/char/virtio_console.c (ffffffff819370f5)
Location: drivers/char/virtio_console.c:243
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:notifier_add_vio
  - drivers/char/virtio_console.c:get_chars
  - drivers/char/virtio_console.c:put_chars
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
In drivers/char/virtio_console.c (ffffffff81a96fe5)
Location: drivers/char/virtio_console.c:235
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:notifier_add_vio
  - drivers/char/virtio_console.c:get_chars
  - drivers/char/virtio_console.c:put_chars
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
In drivers/char/virtio_console.c (ffffffff81ae27f5)
Location: drivers/char/virtio_console.c:236
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:notifier_add_vio
  - drivers/char/virtio_console.c:get_chars
  - drivers/char/virtio_console.c:put_chars
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
In drivers/char/virtio_console.c (ffffffff81b35be5)
Location: drivers/char/virtio_console.c:233
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:notifier_add_vio
  - drivers/char/virtio_console.c:get_chars
  - drivers/char/virtio_console.c:put_chars
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct port *find_port_by_vtermno(u32 vtermno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffff8000108b32d8)
Location: drivers/char/virtio_console.c:242
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:notifier_add_vio
  - drivers/char/virtio_console.c:put_chars
```
**Symbols:**

```
ffff8000108b32d8-ffff8000108b33bc: find_port_by_vtermno (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct port *find_port_by_vtermno(u32 vtermno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (c09ad0f4)
Location: drivers/char/virtio_console.c:242
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:notifier_add_vio
  - drivers/char/virtio_console.c:put_chars
```
**Symbols:**

```
c09ad0f4-c09ad16c: find_port_by_vtermno (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct port *find_port_by_vtermno(u32 vtermno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (c00000000094b370)
Location: drivers/char/virtio_console.c:242
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:notifier_add_vio
  - drivers/char/virtio_console.c:get_chars
  - drivers/char/virtio_console.c:put_chars
```
**Symbols:**

```
c00000000094b370-c00000000094b44c: find_port_by_vtermno (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct port *find_port_by_vtermno(u32 vtermno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffe0005649c2)
Location: drivers/char/virtio_console.c:242
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:notifier_add_vio
  - drivers/char/virtio_console.c:put_chars
```
**Symbols:**

```
ffffffe0005649c2-ffffffe000564a30: find_port_by_vtermno (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct port *find_port_by_vtermno(u32 vtermno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81685f30)
Location: drivers/char/virtio_console.c:242
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:notifier_add_vio
  - drivers/char/virtio_console.c:put_chars
```
**Symbols:**

```
ffffffff81685f30-ffffffff81685f8d: find_port_by_vtermno (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct port *find_port_by_vtermno(u32 vtermno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81663bd0)
Location: drivers/char/virtio_console.c:242
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:notifier_add_vio
  - drivers/char/virtio_console.c:put_chars
```
**Symbols:**

```
ffffffff81663bd0-ffffffff81663c2d: find_port_by_vtermno (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct port *find_port_by_vtermno(u32 vtermno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff816b4320)
Location: drivers/char/virtio_console.c:242
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:notifier_add_vio
  - drivers/char/virtio_console.c:put_chars
```
**Symbols:**

```
ffffffff816b4320-ffffffff816b437d: find_port_by_vtermno (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct port *find_port_by_vtermno(u32 vtermno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff816ce880)
Location: drivers/char/virtio_console.c:242
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:notifier_add_vio
  - drivers/char/virtio_console.c:put_chars
```
**Symbols:**

```
ffffffff816ce880-ffffffff816ce8dd: find_port_by_vtermno (STB_LOCAL)
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
