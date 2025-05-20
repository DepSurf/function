# Function: <code>find_port_by_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct port *find_port_by_id(struct ports_device *portdev, u32 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81515e60)
Location: drivers/char/virtio_console.c:307
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:config_work_handler
```
**Symbols:**

```
ffffffff81515e60-ffffffff81515ec6: find_port_by_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct port *find_port_by_id(struct ports_device *portdev, u32 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81568ac0)
Location: drivers/char/virtio_console.c:313
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:config_work_handler
```
**Symbols:**

```
ffffffff81568ac0-ffffffff81568b25: find_port_by_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct port *find_port_by_id(struct ports_device *portdev, u32 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81595220)
Location: drivers/char/virtio_console.c:312
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:config_work_handler
```
**Symbols:**

```
ffffffff81595220-ffffffff81595285: find_port_by_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct port *find_port_by_id(struct ports_device *portdev, u32 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff815a92f0)
Location: drivers/char/virtio_console.c:312
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:config_work_handler
```
**Symbols:**

```
ffffffff815a92f0-ffffffff815a9356: find_port_by_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct port *find_port_by_id(struct ports_device *portdev, u32 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff8160fbf0)
Location: drivers/char/virtio_console.c:312
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:config_work_handler
```
**Symbols:**

```
ffffffff8160fbf0-ffffffff8160fc56: find_port_by_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct port *find_port_by_id(struct ports_device *portdev, u32 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81649a20)
Location: drivers/char/virtio_console.c:312
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:config_work_handler
```
**Symbols:**

```
ffffffff81649a20-ffffffff81649a86: find_port_by_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct port *find_port_by_id(struct ports_device *portdev, u32 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81667d20)
Location: drivers/char/virtio_console.c:312
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:config_work_handler
```
**Symbols:**

```
ffffffff81667d20-ffffffff81667d86: find_port_by_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct port *find_port_by_id(struct ports_device *portdev, u32 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff8169d7b0)
Location: drivers/char/virtio_console.c:299
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:config_work_handler
```
**Symbols:**

```
ffffffff8169d7b0-ffffffff8169d810: find_port_by_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct port *find_port_by_id(struct ports_device *portdev, u32 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff816c0540)
Location: drivers/char/virtio_console.c:299
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:config_work_handler
```
**Symbols:**

```
ffffffff816c0540-ffffffff816c05a0: find_port_by_id (STB_LOCAL)
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
In drivers/char/virtio_console.c (ffffffff81775004)
Location: drivers/char/virtio_console.c:299
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_work_handler
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
In drivers/char/virtio_console.c (ffffffff8178fd4a)
Location: drivers/char/virtio_console.c:299
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_work_handler
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
In drivers/char/virtio_console.c (ffffffff817728ca)
Location: drivers/char/virtio_console.c:299
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_work_handler
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
In drivers/char/virtio_console.c (ffffffff817f87da)
Location: drivers/char/virtio_console.c:299
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_work_handler
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
In drivers/char/virtio_console.c (ffffffff819369f3)
Location: drivers/char/virtio_console.c:300
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_work_handler
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
In drivers/char/virtio_console.c (ffffffff81a96883)
Location: drivers/char/virtio_console.c:292
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_work_handler
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
In drivers/char/virtio_console.c (ffffffff81ae2093)
Location: drivers/char/virtio_console.c:293
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_work_handler
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
In drivers/char/virtio_console.c (ffffffff81b35483)
Location: drivers/char/virtio_console.c:290
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_work_handler
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
struct port *find_port_by_id(struct ports_device *portdev, u32 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffff8000108b31f8)
Location: drivers/char/virtio_console.c:299
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:config_work_handler
```
**Symbols:**

```
ffff8000108b31f8-ffff8000108b32d4: find_port_by_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct port *find_port_by_id(struct ports_device *portdev, u32 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (c09ad16c)
Location: drivers/char/virtio_console.c:299
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:config_work_handler
```
**Symbols:**

```
c09ad16c-c09ad1dc: find_port_by_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct port *find_port_by_id(struct ports_device *portdev, u32 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (c00000000094b450)
Location: drivers/char/virtio_console.c:299
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:config_work_handler
```
**Symbols:**

```
c00000000094b450-c00000000094b530: find_port_by_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct port *find_port_by_id(struct ports_device *portdev, u32 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffe000564a30)
Location: drivers/char/virtio_console.c:299
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:config_work_handler
```
**Symbols:**

```
ffffffe000564a30-ffffffe000564a9a: find_port_by_id (STB_LOCAL)
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
struct port *find_port_by_id(struct ports_device *portdev, u32 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81685f90)
Location: drivers/char/virtio_console.c:299
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:config_work_handler
```
**Symbols:**

```
ffffffff81685f90-ffffffff81685ff0: find_port_by_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct port *find_port_by_id(struct ports_device *portdev, u32 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81663c30)
Location: drivers/char/virtio_console.c:299
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:config_work_handler
```
**Symbols:**

```
ffffffff81663c30-ffffffff81663c90: find_port_by_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct port *find_port_by_id(struct ports_device *portdev, u32 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff816b4380)
Location: drivers/char/virtio_console.c:299
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:config_work_handler
```
**Symbols:**

```
ffffffff816b4380-ffffffff816b43e0: find_port_by_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct port *find_port_by_id(struct ports_device *portdev, u32 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff816ce8e0)
Location: drivers/char/virtio_console.c:299
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:config_work_handler
```
**Symbols:**

```
ffffffff816ce8e0-ffffffff816ce940: find_port_by_id (STB_LOCAL)
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
