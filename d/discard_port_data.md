# Function: <code>discard_port_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void discard_port_data(struct port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81516fd0)
Location: drivers/char/virtio_console.c:518
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:port_fops_release
  - drivers/char/virtio_console.c:remove_port_data
```
**Symbols:**

```
ffffffff81516fd0-ffffffff81517074: discard_port_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void discard_port_data(struct port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81569c80)
Location: drivers/char/virtio_console.c:524
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
ffffffff81569c80-ffffffff81569d24: discard_port_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void discard_port_data(struct port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81596110)
Location: drivers/char/virtio_console.c:523
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
ffffffff81596110-ffffffff815961b4: discard_port_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void discard_port_data(struct port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff815a9ef0)
Location: drivers/char/virtio_console.c:523
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
ffffffff815a9ef0-ffffffff815a9fa0: discard_port_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void discard_port_data(struct port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81610860)
Location: drivers/char/virtio_console.c:520
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
ffffffff81610860-ffffffff81610910: discard_port_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void discard_port_data(struct port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff8164a3f0)
Location: drivers/char/virtio_console.c:519
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
ffffffff8164a3f0-ffffffff8164a49f: discard_port_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void discard_port_data(struct port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff816683a0)
Location: drivers/char/virtio_console.c:519
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
ffffffff816683a0-ffffffff8166844f: discard_port_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void discard_port_data(struct port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (0)
Location: drivers/char/virtio_console.c:506
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
ffffffff8169de30-ffffffff8169dec4: discard_port_data (STB_LOCAL)
ffffffff816a0754-ffffffff816a076f: discard_port_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void discard_port_data(struct port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (0)
Location: drivers/char/virtio_console.c:506
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
ffffffff816c0ba0-ffffffff816c0c34: discard_port_data (STB_LOCAL)
ffffffff816c3510-ffffffff816c352b: discard_port_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void discard_port_data(struct port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (0)
Location: drivers/char/virtio_console.c:506
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
ffffffff81775830-ffffffff81775977: discard_port_data (STB_LOCAL)
ffffffff81777b4d-ffffffff81777b68: discard_port_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void discard_port_data(struct port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (0)
Location: drivers/char/virtio_console.c:506
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
ffffffff81790570-ffffffff817906b0: discard_port_data (STB_LOCAL)
ffffffff81c08740-ffffffff81c0875b: discard_port_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void discard_port_data(struct port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (0)
Location: drivers/char/virtio_console.c:506
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
ffffffff81773270-ffffffff817733cd: discard_port_data (STB_LOCAL)
ffffffff81bfa305-ffffffff81bfa320: discard_port_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void discard_port_data(struct port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (0)
Location: drivers/char/virtio_console.c:506
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
ffffffff817f8da0-ffffffff817f8efd: discard_port_data (STB_LOCAL)
ffffffff81cfab76-ffffffff81cfab91: discard_port_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81937df3)
Location: drivers/char/virtio_console.c:507
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:port_fops_release
Direct callers:
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
ffffffff81937990-ffffffff81937b32: discard_port_data.part.0 (STB_LOCAL)
ffffffff81ec3341-ffffffff81ec335d: discard_port_data.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81a97ab3)
Location: drivers/char/virtio_console.c:499
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:port_fops_release
Direct callers:
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
ffffffff81a97620-ffffffff81a977d6: discard_port_data.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81ae32c3)
Location: drivers/char/virtio_console.c:500
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:port_fops_release
Direct callers:
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
ffffffff81ae2e30-ffffffff81ae2fe6: discard_port_data.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81b36683)
Location: drivers/char/virtio_console.c:497
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:port_fops_release
Direct callers:
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
ffffffff81b361f0-ffffffff81b363a6: discard_port_data.part.0 (STB_LOCAL)
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
void discard_port_data(struct port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffff8000108b4668)
Location: drivers/char/virtio_console.c:506
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
ffff8000108b4668-ffff8000108b473c: discard_port_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void discard_port_data(struct port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (c09ad82c)
Location: drivers/char/virtio_console.c:506
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
c09ad82c-c09ad8ec: discard_port_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void discard_port_data(struct port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (c00000000094bf30)
Location: drivers/char/virtio_console.c:506
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
c00000000094bf30-c00000000094c050: discard_port_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void discard_port_data(struct port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffe000564fe2)
Location: drivers/char/virtio_console.c:506
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
ffffffe000564fe2-ffffffe000565098: discard_port_data (STB_LOCAL)
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
void discard_port_data(struct port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (0)
Location: drivers/char/virtio_console.c:506
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
ffffffff816865f0-ffffffff81686684: discard_port_data (STB_LOCAL)
ffffffff81688f60-ffffffff81688f7b: discard_port_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void discard_port_data(struct port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (0)
Location: drivers/char/virtio_console.c:506
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
ffffffff81664420-ffffffff816644b2: discard_port_data (STB_LOCAL)
ffffffff81666a09-ffffffff81666a24: discard_port_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void discard_port_data(struct port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (0)
Location: drivers/char/virtio_console.c:506
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
ffffffff816b4b70-ffffffff816b4c02: discard_port_data (STB_LOCAL)
ffffffff816b71df-ffffffff816b71fa: discard_port_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void discard_port_data(struct port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (0)
Location: drivers/char/virtio_console.c:506
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
ffffffff816cef40-ffffffff816cefd4: discard_port_data (STB_LOCAL)
ffffffff816d180e-ffffffff816d1829: discard_port_data.cold (STB_LOCAL)
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
