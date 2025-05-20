# Function: <code>platform_device_del</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void platform_device_del(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8154dd50)
Location: drivers/base/platform.c:412
Inline: False
Direct callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_add_devices
```
**Symbols:**

```
ffffffff8154dd50-ffffffff8154dde3: platform_device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void platform_device_del(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8159fb70)
Location: drivers/base/platform.c:432
Inline: False
Direct callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_add_devices
```
**Symbols:**

```
ffffffff8159fb70-ffffffff8159fbf6: platform_device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void platform_device_del(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff815ce1b0)
Location: drivers/base/platform.c:447
Inline: False
Direct callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_add_devices
```
**Symbols:**

```
ffffffff815ce1b0-ffffffff815ce238: platform_device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void platform_device_del(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (ffffffff815e3576)
Location: drivers/base/platform.c:447
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_unregister
Direct callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_unregister
```
**Symbols:**

```
ffffffff815e30f0-ffffffff815e3172: platform_device_del.part.12 (STB_LOCAL)
ffffffff815e3180-ffffffff815e3197: platform_device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void platform_device_del(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (ffffffff8164a726)
Location: drivers/base/platform.c:447
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_unregister
Direct callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_unregister
```
**Symbols:**

```
ffffffff8164a2a0-ffffffff8164a322: platform_device_del.part.12 (STB_LOCAL)
ffffffff8164a330-ffffffff8164a347: platform_device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void platform_device_del(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (ffffffff81685c96)
Location: drivers/base/platform.c:446
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_unregister
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_unregister
```
**Symbols:**

```
ffffffff816856b0-ffffffff81685732: platform_device_del.part.13 (STB_LOCAL)
ffffffff81685740-ffffffff81685756: platform_device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void platform_device_del(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (ffffffff816a591c)
Location: drivers/base/platform.c:447
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_unregister
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_unregister
```
**Symbols:**

```
ffffffff816a5320-ffffffff816a5397: platform_device_del.part.14 (STB_LOCAL)
ffffffff816a53a0-ffffffff816a53bf: platform_device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void platform_device_del(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (ffffffff816de8ec)
Location: drivers/base/platform.c:487
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_unregister
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_unregister
```
**Symbols:**

```
ffffffff816de2b0-ffffffff816de327: platform_device_del.part.0 (STB_LOCAL)
ffffffff816de330-ffffffff816de34f: platform_device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void platform_device_del(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (ffffffff81702b6c)
Location: drivers/base/platform.c:565
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_unregister
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_unregister
```
**Symbols:**

```
ffffffff817024a0-ffffffff81702516: platform_device_del.part.0 (STB_LOCAL)
ffffffff81702520-ffffffff8170253f: platform_device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void platform_device_del(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (ffffffff817bce2c)
Location: drivers/base/platform.c:626
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_add_devices
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_add_devices
```
**Symbols:**

```
ffffffff817bc230-ffffffff817bc2a6: platform_device_del.part.0 (STB_LOCAL)
ffffffff817bc2b0-ffffffff817bc2cf: platform_device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void platform_device_del(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (ffffffff817d1d18)
Location: drivers/base/platform.c:778
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_add_devices
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_add_devices
```
**Symbols:**

```
ffffffff817d0e70-ffffffff817d0ee6: platform_device_del.part.0 (STB_LOCAL)
ffffffff817d0ef0-ffffffff817d0f0f: platform_device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void platform_device_del(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (ffffffff817b5748)
Location: drivers/base/platform.c:777
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_add_devices
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_add_devices
```
**Symbols:**

```
ffffffff817b4890-ffffffff817b4906: platform_device_del.part.0 (STB_LOCAL)
ffffffff817b4910-ffffffff817b492f: platform_device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void platform_device_del(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (ffffffff8183ec58)
Location: drivers/base/platform.c:741
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_add_devices
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_add_devices
```
**Symbols:**

```
ffffffff8183de80-ffffffff8183df02: platform_device_del.part.0 (STB_LOCAL)
ffffffff81d0330c-ffffffff81d03320: platform_device_del.part.0.cold (STB_LOCAL)
ffffffff8183df10-ffffffff8183df2f: platform_device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void platform_device_del(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (ffffffff81981b81)
Location: drivers/base/platform.c:746
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_add_devices
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_add_devices
```
**Symbols:**

```
ffffffff81980c60-ffffffff81980cec: platform_device_del.part.0 (STB_LOCAL)
ffffffff81ecba85-ffffffff81ecba99: platform_device_del.part.0.cold (STB_LOCAL)
ffffffff81980cf0-ffffffff81980d1b: platform_device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void platform_device_del(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (ffffffff81aef841)
Location: drivers/base/platform.c:746
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_add_devices
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_add_devices
```
**Symbols:**

```
ffffffff81aee7d0-ffffffff81aee85c: platform_device_del.part.0 (STB_LOCAL)
ffffffff82098736-ffffffff8209874a: platform_device_del.part.0.cold (STB_LOCAL)
ffffffff81aee870-ffffffff81aee89b: platform_device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void platform_device_del(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (ffffffff81b3dc21)
Location: drivers/base/platform.c:746
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_add_devices
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_add_devices
```
**Symbols:**

```
ffffffff81b3cb90-ffffffff81b3cc1e: platform_device_del.part.0 (STB_LOCAL)
ffffffff82119722-ffffffff82119736: platform_device_del.part.0.cold (STB_LOCAL)
ffffffff81b3cc30-ffffffff81b3cc5b: platform_device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void platform_device_del(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (ffffffff81b95761)
Location: drivers/base/platform.c:746
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_add_devices
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_add_devices
```
**Symbols:**

```
ffffffff81b946c0-ffffffff81b9474e: platform_device_del.part.0 (STB_LOCAL)
ffffffff821f76e4-ffffffff821f76f8: platform_device_del.part.0.cold (STB_LOCAL)
ffffffff81b94760-ffffffff81b9478b: platform_device_del (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void platform_device_del(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (ffff8000108ee6a8)
Location: drivers/base/platform.c:565
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_unregister
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_unregister
```
**Symbols:**

```
ffff8000108ede20-ffff8000108edeac: platform_device_del.part.0 (STB_LOCAL)
ffff8000108edeb0-ffff8000108edee8: platform_device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void platform_device_del(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (c09dc200)
Location: drivers/base/platform.c:565
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_unregister
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_unregister
```
**Symbols:**

```
c09dbca4-c09dbd28: platform_device_del.part.0 (STB_LOCAL)
c09dbd28-c09dbd54: platform_device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void platform_device_del(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (c00000000098722c)
Location: drivers/base/platform.c:565
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_unregister
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_unregister
```
**Symbols:**

```
c000000000986500-c0000000009865c0: platform_device_del.part.0 (STB_LOCAL)
c0000000009865c0-c0000000009865e8: platform_device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void platform_device_del(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (ffffffe0005815fe)
Location: drivers/base/platform.c:565
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_unregister
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_unregister
```
**Symbols:**

```
ffffffe000581074-ffffffe0005810f8: platform_device_del.part.0 (STB_LOCAL)
ffffffe0005810f8-ffffffe00058112a: platform_device_del (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void platform_device_del(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (ffffffff816c82bc)
Location: drivers/base/platform.c:565
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_unregister
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_unregister
```
**Symbols:**

```
ffffffff816c7bf0-ffffffff816c7c66: platform_device_del.part.0 (STB_LOCAL)
ffffffff816c7c70-ffffffff816c7c8f: platform_device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void platform_device_del(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (ffffffff816a35bc)
Location: drivers/base/platform.c:565
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_unregister
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_unregister
```
**Symbols:**

```
ffffffff816a2ef0-ffffffff816a2f66: platform_device_del.part.0 (STB_LOCAL)
ffffffff816a2f70-ffffffff816a2f8f: platform_device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void platform_device_del(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (ffffffff816f682c)
Location: drivers/base/platform.c:565
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_unregister
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_unregister
```
**Symbols:**

```
ffffffff816f6160-ffffffff816f61d6: platform_device_del.part.0 (STB_LOCAL)
ffffffff816f61e0-ffffffff816f61ff: platform_device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void platform_device_del(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (ffffffff817110cc)
Location: drivers/base/platform.c:565
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_unregister
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_unregister
```
**Symbols:**

```
ffffffff817109f0-ffffffff81710a66: platform_device_del.part.0 (STB_LOCAL)
ffffffff81710a70-ffffffff81710a8f: platform_device_del (STB_GLOBAL)
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
