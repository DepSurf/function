# Function: <code>init_port_console</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int init_port_console(struct port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81517e10)
Location: drivers/char/virtio_console.c:1230
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:add_port
```
**Symbols:**

```
ffffffff81517e10-ffffffff81517f15: init_port_console (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int init_port_console(struct port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff8156ab50)
Location: drivers/char/virtio_console.c:1237
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:add_port
```
**Symbols:**

```
ffffffff8156ab50-ffffffff8156ac40: init_port_console (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int init_port_console(struct port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff815972c0)
Location: drivers/char/virtio_console.c:1236
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:add_port
```
**Symbols:**

```
ffffffff815972c0-ffffffff815973b0: init_port_console (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int init_port_console(struct port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff815ab2e0)
Location: drivers/char/virtio_console.c:1244
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:add_port
```
**Symbols:**

```
ffffffff815ab2e0-ffffffff815ab3d0: init_port_console (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int init_port_console(struct port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81611c70)
Location: drivers/char/virtio_console.c:1241
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:add_port
```
**Symbols:**

```
ffffffff81611c70-ffffffff81611d60: init_port_console (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int init_port_console(struct port *port);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff8164b5e0)
Location: drivers/char/virtio_console.c:1240
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:add_port
```
**Symbols:**

```
ffffffff8164b5e0-ffffffff8164b6cd: init_port_console (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int init_port_console(struct port *port);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81669930)
Location: drivers/char/virtio_console.c:1240
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:add_port
```
**Symbols:**

```
ffffffff81669930-ffffffff81669a1d: init_port_console (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int init_port_console(struct port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (0)
Location: drivers/char/virtio_console.c:1227
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:add_port
```
**Symbols:**

```
ffffffff8169f030-ffffffff8169f0f5: init_port_console (STB_LOCAL)
ffffffff816a0787-ffffffff816a07ac: init_port_console.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int init_port_console(struct port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (0)
Location: drivers/char/virtio_console.c:1227
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:add_port
```
**Symbols:**

```
ffffffff816c1dc0-ffffffff816c1e85: init_port_console (STB_LOCAL)
ffffffff816c3543-ffffffff816c3568: init_port_console.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int init_port_console(struct port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (0)
Location: drivers/char/virtio_console.c:1225
Inline: False
```
**Symbols:**

```
ffffffff81775c20-ffffffff81775d03: init_port_console (STB_LOCAL)
ffffffff81777b8b-ffffffff81777bb0: init_port_console.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int init_port_console(struct port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (0)
Location: drivers/char/virtio_console.c:1225
Inline: False
```
**Symbols:**

```
ffffffff81790950-ffffffff81790a33: init_port_console (STB_LOCAL)
ffffffff81c0877e-ffffffff81c087a3: init_port_console.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int init_port_console(struct port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (0)
Location: drivers/char/virtio_console.c:1225
Inline: False
```
**Symbols:**

```
ffffffff81773aa0-ffffffff81773b69: init_port_console (STB_LOCAL)
ffffffff81bfa320-ffffffff81bfa345: init_port_console.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int init_port_console(struct port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (0)
Location: drivers/char/virtio_console.c:1225
Inline: False
```
**Symbols:**

```
ffffffff817f98e0-ffffffff817f99a9: init_port_console (STB_LOCAL)
ffffffff81cfac43-ffffffff81cfac68: init_port_console.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int init_port_console(struct port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (0)
Location: drivers/char/virtio_console.c:1226
Inline: False
```
**Symbols:**

```
ffffffff81937270-ffffffff8193733d: init_port_console (STB_LOCAL)
ffffffff81ec3289-ffffffff81ec32af: init_port_console.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int init_port_console(struct port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81a97180)
Location: drivers/char/virtio_console.c:1218
Inline: False
```
**Symbols:**

```
ffffffff81a97180-ffffffff81a9729b: init_port_console (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int init_port_console(struct port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81ae2990)
Location: drivers/char/virtio_console.c:1219
Inline: False
```
**Symbols:**

```
ffffffff81ae2990-ffffffff81ae2aab: init_port_console (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int init_port_console(struct port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81b35d80)
Location: drivers/char/virtio_console.c:1194
Inline: False
```
**Symbols:**

```
ffffffff81b35d80-ffffffff81b35e7e: init_port_console (STB_LOCAL)
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
int init_port_console(struct port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffff8000108b30b0)
Location: drivers/char/virtio_console.c:1227
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:add_port
```
**Symbols:**

```
ffff8000108b30b0-ffff8000108b31f8: init_port_console (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int init_port_console(struct port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (c09ae594)
Location: drivers/char/virtio_console.c:1227
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:add_port
```
**Symbols:**

```
c09ae594-c09ae6a8: init_port_console (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int init_port_console(struct port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (c00000000094dc50)
Location: drivers/char/virtio_console.c:1227
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:add_port
```
**Symbols:**

```
c00000000094dc50-c00000000094ddb8: init_port_console (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int init_port_console(struct port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffe0005662c4)
Location: drivers/char/virtio_console.c:1227
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:add_port
```
**Symbols:**

```
ffffffe0005662c4-ffffffe0005663d8: init_port_console (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int init_port_console(struct port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (0)
Location: drivers/char/virtio_console.c:1227
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:add_port
```
**Symbols:**

```
ffffffff81687810-ffffffff816878d5: init_port_console (STB_LOCAL)
ffffffff81688f93-ffffffff81688fb8: init_port_console.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int init_port_console(struct port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (0)
Location: drivers/char/virtio_console.c:1227
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:add_port
```
**Symbols:**

```
ffffffff816653e0-ffffffff8166549f: init_port_console (STB_LOCAL)
ffffffff81666a24-ffffffff81666a49: init_port_console.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int init_port_console(struct port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (0)
Location: drivers/char/virtio_console.c:1227
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:add_port
```
**Symbols:**

```
ffffffff816b5b50-ffffffff816b5c15: init_port_console (STB_LOCAL)
ffffffff816b71fa-ffffffff816b721f: init_port_console.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int init_port_console(struct port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (0)
Location: drivers/char/virtio_console.c:1227
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:add_port
```
**Symbols:**

```
ffffffff816cfae0-ffffffff816cfb9c: init_port_console (STB_LOCAL)
ffffffff816d1841-ffffffff816d1866: init_port_console.cold (STB_LOCAL)
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
