# Function: <code>hub_activate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void hub_activate(struct usb_hub *hub, enum hub_activation_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816073f0)
Location: drivers/usb/core/hub.c:1041
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_init_func3
  - drivers/usb/core/hub.c:hub_init_func2
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_configure
```
**Symbols:**

```
ffffffff816073f0-ffffffff81607a5c: hub_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void hub_activate(struct usb_hub *hub, enum hub_activation_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81667130)
Location: drivers/usb/core/hub.c:1043
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_init_func3
  - drivers/usb/core/hub.c:hub_init_func2
```
**Symbols:**

```
ffffffff81667130-ffffffff81667766: hub_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void hub_activate(struct usb_hub *hub, enum hub_activation_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81694e50)
Location: drivers/usb/core/hub.c:964
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_init_func3
  - drivers/usb/core/hub.c:hub_init_func2
```
**Symbols:**

```
ffffffff81694e50-ffffffff81695483: hub_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void hub_activate(struct usb_hub *hub, enum hub_activation_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816aa2a0)
Location: drivers/usb/core/hub.c:973
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_init_func3
  - drivers/usb/core/hub.c:hub_init_func2
```
**Symbols:**

```
ffffffff816aa2a0-ffffffff816aa8d6: hub_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void hub_activate(struct usb_hub *hub, enum hub_activation_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817156f0)
Location: drivers/usb/core/hub.c:973
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_init_func3
  - drivers/usb/core/hub.c:hub_init_func2
```
**Symbols:**

```
ffffffff817156f0-ffffffff81715d11: hub_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void hub_activate(struct usb_hub *hub, enum hub_activation_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81754500)
Location: drivers/usb/core/hub.c:981
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_init_func3
  - drivers/usb/core/hub.c:hub_init_func2
```
**Symbols:**

```
ffffffff81754500-ffffffff81754b37: hub_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void hub_activate(struct usb_hub *hub, enum hub_activation_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81778960)
Location: drivers/usb/core/hub.c:982
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_init_func3
  - drivers/usb/core/hub.c:hub_init_func2
```
**Symbols:**

```
ffffffff81778960-ffffffff81778fcc: hub_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void hub_activate(struct usb_hub *hub, enum hub_activation_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:1009
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_init_func3
  - drivers/usb/core/hub.c:hub_init_func2
```
**Symbols:**

```
ffffffff817b67d0-ffffffff817b6e3b: hub_activate (STB_LOCAL)
ffffffff817ba66c-ffffffff817ba6b9: hub_activate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void hub_activate(struct usb_hub *hub, enum hub_activation_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:1015
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_init_func3
  - drivers/usb/core/hub.c:hub_init_func2
```
**Symbols:**

```
ffffffff817e6ef0-ffffffff817e7556: hub_activate (STB_LOCAL)
ffffffff817eaeba-ffffffff817eaf07: hub_activate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void hub_activate(struct usb_hub *hub, enum hub_activation_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:1017
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_init_func3
  - drivers/usb/core/hub.c:hub_init_func2
```
**Symbols:**

```
ffffffff818b47b0-ffffffff818b4f8f: hub_activate (STB_LOCAL)
ffffffff818b9fee-ffffffff818ba03f: hub_activate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void hub_activate(struct usb_hub *hub, enum hub_activation_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:1017
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_init_func3
  - drivers/usb/core/hub.c:hub_init_func2
```
**Symbols:**

```
ffffffff818c3110-ffffffff818c38ef: hub_activate (STB_LOCAL)
ffffffff81c1ab14-ffffffff81c1ab65: hub_activate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void hub_activate(struct usb_hub *hub, enum hub_activation_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:1024
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_init_func3
  - drivers/usb/core/hub.c:hub_init_func2
```
**Symbols:**

```
ffffffff818a61e0-ffffffff818a69ba: hub_activate (STB_LOCAL)
ffffffff81c0c95a-ffffffff81c0c9ab: hub_activate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void hub_activate(struct usb_hub *hub, enum hub_activation_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:1024
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_init_func3
  - drivers/usb/core/hub.c:hub_init_func2
```
**Symbols:**

```
ffffffff8193b040-ffffffff8193b84e: hub_activate (STB_LOCAL)
ffffffff81d138c8-ffffffff81d1392e: hub_activate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void hub_activate(struct usb_hub *hub, enum hub_activation_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:1024
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_init_func3
  - drivers/usb/core/hub.c:hub_init_func2
```
**Symbols:**

```
ffffffff81a92c60-ffffffff81a934ea: hub_activate (STB_LOCAL)
ffffffff81ede66a-ffffffff81ede6dc: hub_activate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void hub_activate(struct usb_hub *hub, enum hub_activation_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:1028
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_init_func3
  - drivers/usb/core/hub.c:hub_init_func2
```
**Symbols:**

```
ffffffff81c14e10-ffffffff81c156c9: hub_activate (STB_LOCAL)
ffffffff8209e761-ffffffff8209e776: hub_activate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void hub_activate(struct usb_hub *hub, enum hub_activation_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:1028
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_init_func3
  - drivers/usb/core/hub.c:hub_init_func2
```
**Symbols:**

```
ffffffff81c7bc10-ffffffff81c7c4e2: hub_activate (STB_LOCAL)
ffffffff8211fccc-ffffffff8211fce1: hub_activate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void hub_activate(struct usb_hub *hub, enum hub_activation_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:1048
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_init_func3
  - drivers/usb/core/hub.c:hub_init_func2
```
**Symbols:**

```
ffffffff81d30860-ffffffff81d31132: hub_activate (STB_LOCAL)
ffffffff822014b2-ffffffff822014c7: hub_activate.cold (STB_LOCAL)
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
void hub_activate(struct usb_hub *hub, enum hub_activation_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffff800010a15e18)
Location: drivers/usb/core/hub.c:1015
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_init_func3
  - drivers/usb/core/hub.c:hub_init_func2
```
**Symbols:**

```
ffff800010a15e18-ffff800010a164d8: hub_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void hub_activate(struct usb_hub *hub, enum hub_activation_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c0aee16c)
Location: drivers/usb/core/hub.c:1015
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_init_func3
  - drivers/usb/core/hub.c:hub_init_func2
```
**Symbols:**

```
c0aee16c-c0aee86c: hub_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void hub_activate(struct usb_hub *hub, enum hub_activation_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c000000000ace510)
Location: drivers/usb/core/hub.c:1015
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_init_func3
  - drivers/usb/core/hub.c:hub_init_func2
```
**Symbols:**

```
c000000000ace510-c000000000acee88: hub_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void hub_activate(struct usb_hub *hub, enum hub_activation_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffe00063b03e)
Location: drivers/usb/core/hub.c:1015
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_init_func3
  - drivers/usb/core/hub.c:hub_init_func2
```
**Symbols:**

```
ffffffe00063b03e-ffffffe00063b694: hub_activate (STB_LOCAL)
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
void hub_activate(struct usb_hub *hub, enum hub_activation_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:1015
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_init_func3
  - drivers/usb/core/hub.c:hub_init_func2
```
**Symbols:**

```
ffffffff8179f2d0-ffffffff8179f936: hub_activate (STB_LOCAL)
ffffffff817a329a-ffffffff817a32e7: hub_activate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void hub_activate(struct usb_hub *hub, enum hub_activation_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:1015
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_init_func3
  - drivers/usb/core/hub.c:hub_init_func2
```
**Symbols:**

```
ffffffff81790f50-ffffffff817915b6: hub_activate (STB_LOCAL)
ffffffff817950da-ffffffff81795127: hub_activate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void hub_activate(struct usb_hub *hub, enum hub_activation_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:1015
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_init_func3
  - drivers/usb/core/hub.c:hub_init_func2
```
**Symbols:**

```
ffffffff817dbd70-ffffffff817dc3d6: hub_activate (STB_LOCAL)
ffffffff817dfd3a-ffffffff817dfd87: hub_activate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void hub_activate(struct usb_hub *hub, enum hub_activation_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:1015
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_init_func3
  - drivers/usb/core/hub.c:hub_init_func2
```
**Symbols:**

```
ffffffff817f6000-ffffffff817f6666: hub_activate (STB_LOCAL)
ffffffff817fa02a-ffffffff817fa077: hub_activate.cold (STB_LOCAL)
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
