# Function: <code>devlink_port_notify</code>

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
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void devlink_port_notify(struct devlink_port *devlink_port, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:602
Inline: False
Direct callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_port_unregister
  - net/core/devlink.c:devlink_port_register
  - net/core/devlink.c:devlink_nl_cmd_port_set_doit
```
**Symbols:**

```
ffffffff8194cff0-ffffffff8194d0b5: devlink_port_notify (STB_LOCAL)
ffffffff8195236c-ffffffff8195237f: devlink_port_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void devlink_port_notify(struct devlink_port *devlink_port, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81982950)
Location: net/core/devlink.c:604
Inline: False
Direct callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_port_unregister
  - net/core/devlink.c:devlink_port_register
  - net/core/devlink.c:devlink_nl_cmd_port_set_doit
```
**Symbols:**

```
ffffffff81982950-ffffffff81982a1d: devlink_port_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void devlink_port_notify(struct devlink_port *devlink_port, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5aa90)
Location: net/core/devlink.c:621
Inline: False
Direct callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_port_unregister
  - net/core/devlink.c:devlink_port_register
  - net/core/devlink.c:devlink_nl_cmd_port_set_doit
```
**Symbols:**

```
ffffffff81a5aa90-ffffffff81a5ab49: devlink_port_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void devlink_port_notify(struct devlink_port *devlink_port, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a66350)
Location: net/core/devlink.c:821
Inline: False
Direct callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_port_unregister
  - net/core/devlink.c:devlink_port_register
  - net/core/devlink.c:devlink_nl_cmd_port_set_doit
  - net/core/devlink.c:devlink_nl_cmd_port_set_doit
```
**Symbols:**

```
ffffffff81a66350-ffffffff81a6640b: devlink_port_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void devlink_port_notify(struct devlink_port *devlink_port, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a46630)
Location: net/core/devlink.c:895
Inline: False
Direct callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_port_unregister
  - net/core/devlink.c:devlink_port_register
  - net/core/devlink.c:devlink_nl_cmd_port_set_doit
  - net/core/devlink.c:devlink_port_function_set
```
**Symbols:**

```
ffffffff81a46630-ffffffff81a466e6: devlink_port_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void devlink_port_notify(struct devlink_port *devlink_port, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81b013b0)
Location: net/core/devlink.c:1040
Inline: False
Direct callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_port_unregister
  - net/core/devlink.c:devlink_port_register
  - net/core/devlink.c:devlink_nl_cmd_port_set_doit
  - net/core/devlink.c:devlink_port_function_set
```
**Symbols:**

```
ffffffff81b013b0-ffffffff81b01457: devlink_port_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void devlink_port_notify(struct devlink_port *devlink_port, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c808d0)
Location: net/core/devlink.c:1262
Inline: False
Direct callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devl_port_unregister
  - net/core/devlink.c:devl_port_register
  - net/core/devlink.c:devlink_unregister
  - net/core/devlink.c:devlink_register
  - net/core/devlink.c:devlink_nl_cmd_port_set_doit
  - net/core/devlink.c:devlink_port_function_set
```
**Symbols:**

```
ffffffff81c808d0-ffffffff81c809e5: devlink_port_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void devlink_port_notify(struct devlink_port *devlink_port, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e3d6d0)
Location: net/core/devlink.c:1488
Inline: False
Direct callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devl_port_unregister
  - net/core/devlink.c:devl_port_register
  - net/core/devlink.c:devlink_notify_unregister
  - net/core/devlink.c:devlink_notify_register
  - net/core/devlink.c:devlink_nl_cmd_port_set_doit
  - net/core/devlink.c:devlink_port_function_set
```
**Symbols:**

```
ffffffff81e3d6d0-ffffffff81e3d7e5: devlink_port_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void devlink_port_notify(struct devlink_port *devlink_port, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff8203d2f0)
Location: net/devlink/leftover.c:955
Inline: False
Direct callers:
  - net/devlink/leftover.c:__devlink_port_type_set
  - net/devlink/leftover.c:devl_port_unregister
  - net/devlink/leftover.c:devl_port_register_with_ops
  - net/devlink/leftover.c:devlink_notify_unregister
  - net/devlink/leftover.c:devlink_notify_register
  - net/devlink/leftover.c:devlink_nl_cmd_port_set_doit
  - net/devlink/leftover.c:devlink_port_function_set
```
**Symbols:**

```
ffffffff8203d2f0-ffffffff8203d406: devlink_port_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void devlink_port_notify(struct devlink_port *devlink_port, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/port.c (ffffffff82106bd0)
Location: net/devlink/port.c:506
Inline: False
Direct callers:
  - net/devlink/port.c:devlink_port_rel_notify_cb
  - net/devlink/port.c:__devlink_port_type_set
  - net/devlink/port.c:devl_port_unregister
  - net/devlink/port.c:devl_port_register_with_ops
  - net/devlink/port.c:devlink_nl_port_set_doit
  - net/devlink/port.c:devlink_port_function_set
  - net/devlink/port.c:devlink_ports_notify
```
**Symbols:**

```
ffffffff82106bd0-ffffffff82106db6: devlink_port_notify (STB_LOCAL)
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
void devlink_port_notify(struct devlink_port *devlink_port, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c2aa48)
Location: net/core/devlink.c:604
Inline: False
Direct callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_port_unregister
  - net/core/devlink.c:devlink_port_register
  - net/core/devlink.c:devlink_nl_cmd_port_set_doit
```
**Symbols:**

```
ffff800010c2aa48-ffff800010c2ab24: devlink_port_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void devlink_port_notify(struct devlink_port *devlink_port, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d41e98)
Location: net/core/devlink.c:604
Inline: False
Direct callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_port_unregister
  - net/core/devlink.c:devlink_port_register
  - net/core/devlink.c:devlink_nl_cmd_port_set_doit
```
**Symbols:**

```
c0d41e98-c0d41f8c: devlink_port_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void devlink_port_notify(struct devlink_port *devlink_port, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d1fe80)
Location: net/core/devlink.c:604
Inline: False
Direct callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_port_unregister
  - net/core/devlink.c:devlink_port_register
  - net/core/devlink.c:devlink_nl_cmd_port_set_doit
```
**Symbols:**

```
c000000000d1fe80-c000000000d1ffb8: devlink_port_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void devlink_port_notify(struct devlink_port *devlink_port, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe0007a210e)
Location: net/core/devlink.c:604
Inline: False
Direct callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_port_unregister
  - net/core/devlink.c:devlink_port_register
  - net/core/devlink.c:devlink_nl_cmd_port_set_doit
```
**Symbols:**

```
ffffffe0007a210e-ffffffe0007a21b4: devlink_port_notify (STB_LOCAL)
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
void devlink_port_notify(struct devlink_port *devlink_port, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819227c0)
Location: net/core/devlink.c:604
Inline: False
Direct callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_port_unregister
  - net/core/devlink.c:devlink_port_register
  - net/core/devlink.c:devlink_nl_cmd_port_set_doit
```
**Symbols:**

```
ffffffff819227c0-ffffffff8192288d: devlink_port_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void devlink_port_notify(struct devlink_port *devlink_port, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818dc570)
Location: net/core/devlink.c:604
Inline: False
Direct callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_port_unregister
  - net/core/devlink.c:devlink_port_register
  - net/core/devlink.c:devlink_nl_cmd_port_set_doit
```
**Symbols:**

```
ffffffff818dc570-ffffffff818dc63d: devlink_port_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void devlink_port_notify(struct devlink_port *devlink_port, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81973950)
Location: net/core/devlink.c:604
Inline: False
Direct callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_port_unregister
  - net/core/devlink.c:devlink_port_register
  - net/core/devlink.c:devlink_nl_cmd_port_set_doit
```
**Symbols:**

```
ffffffff81973950-ffffffff81973a1d: devlink_port_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void devlink_port_notify(struct devlink_port *devlink_port, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81995e40)
Location: net/core/devlink.c:604
Inline: False
Direct callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_port_unregister
  - net/core/devlink.c:devlink_port_register
  - net/core/devlink.c:devlink_nl_cmd_port_set_doit
```
**Symbols:**

```
ffffffff81995e40-ffffffff81995f0d: devlink_port_notify (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
