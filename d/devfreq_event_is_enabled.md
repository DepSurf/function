# Function: <code>devfreq_event_is_enabled</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool devfreq_event_is_enabled(struct devfreq_event_dev *edev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq-event.c (ffffffff816ed590)
Location: drivers/devfreq/devfreq-event.c:109
Inline: False
Direct callers:
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
```
**Symbols:**

```
ffffffff816ed590-ffffffff816ed5d9: devfreq_event_is_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool devfreq_event_is_enabled(struct devfreq_event_dev *edev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq-event.c (ffffffff817524f0)
Location: drivers/devfreq/devfreq-event.c:109
Inline: False
Direct callers:
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
```
**Symbols:**

```
ffffffff817524f0-ffffffff81752539: devfreq_event_is_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool devfreq_event_is_enabled(struct devfreq_event_dev *edev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq-event.c (ffffffff8177e2e0)
Location: drivers/devfreq/devfreq-event.c:109
Inline: False
Direct callers:
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
```
**Symbols:**

```
ffffffff8177e2e0-ffffffff8177e329: devfreq_event_is_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool devfreq_event_is_enabled(struct devfreq_event_dev *edev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq-event.c (ffffffff8179d220)
Location: drivers/devfreq/devfreq-event.c:109
Inline: True
Inline callers:
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
Direct callers:
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
```
**Symbols:**

```
ffffffff8179d060-ffffffff8179d09c: devfreq_event_is_enabled.part.6 (STB_LOCAL)
ffffffff8179d0a0-ffffffff8179d0c3: devfreq_event_is_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool devfreq_event_is_enabled(struct devfreq_event_dev *edev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq-event.c (ffffffff81814350)
Location: drivers/devfreq/devfreq-event.c:109
Inline: True
Inline callers:
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
Direct callers:
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
```
**Symbols:**

```
ffffffff81814190-ffffffff818141cc: devfreq_event_is_enabled.part.6 (STB_LOCAL)
ffffffff818141d0-ffffffff818141f3: devfreq_event_is_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool devfreq_event_is_enabled(struct devfreq_event_dev *edev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq-event.c (ffffffff8185e220)
Location: drivers/devfreq/devfreq-event.c:109
Inline: True
Inline callers:
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
Direct callers:
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
```
**Symbols:**

```
ffffffff8185e060-ffffffff8185e09c: devfreq_event_is_enabled.part.8 (STB_LOCAL)
ffffffff8185e0a0-ffffffff8185e0c3: devfreq_event_is_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool devfreq_event_is_enabled(struct devfreq_event_dev *edev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq-event.c (ffffffff8187dc40)
Location: drivers/devfreq/devfreq-event.c:109
Inline: True
Inline callers:
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
Direct callers:
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
```
**Symbols:**

```
ffffffff8187da80-ffffffff8187dabc: devfreq_event_is_enabled.part.8 (STB_LOCAL)
ffffffff8187dac0-ffffffff8187dae3: devfreq_event_is_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool devfreq_event_is_enabled(struct devfreq_event_dev *edev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq-event.c (ffffffff818c81f1)
Location: drivers/devfreq/devfreq-event.c:106
Inline: True
Inline callers:
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
Direct callers:
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
```
**Symbols:**

```
ffffffff818c8020-ffffffff818c805e: devfreq_event_is_enabled.part.0 (STB_LOCAL)
ffffffff818c8060-ffffffff818c8083: devfreq_event_is_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool devfreq_event_is_enabled(struct devfreq_event_dev *edev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq-event.c (ffffffff818fa681)
Location: drivers/devfreq/devfreq-event.c:106
Inline: True
Inline callers:
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
Direct callers:
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
```
**Symbols:**

```
ffffffff818fa4b0-ffffffff818fa4ee: devfreq_event_is_enabled.part.0 (STB_LOCAL)
ffffffff818fa4f0-ffffffff818fa513: devfreq_event_is_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool devfreq_event_is_enabled(struct devfreq_event_dev *edev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq-event.c (ffffffff819d1215)
Location: drivers/devfreq/devfreq-event.c:106
Inline: True
Inline callers:
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
```
**Symbols:**

```
ffffffff819d0f50-ffffffff819d0fad: devfreq_event_is_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool devfreq_event_is_enabled(struct devfreq_event_dev *edev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq-event.c (ffffffff819d0ed5)
Location: drivers/devfreq/devfreq-event.c:106
Inline: True
Inline callers:
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
```
**Symbols:**

```
ffffffff819d0c10-ffffffff819d0c6d: devfreq_event_is_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool devfreq_event_is_enabled(struct devfreq_event_dev *edev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq-event.c (ffffffff819b6145)
Location: drivers/devfreq/devfreq-event.c:106
Inline: True
Inline callers:
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
```
**Symbols:**

```
ffffffff819b5e80-ffffffff819b5edd: devfreq_event_is_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool devfreq_event_is_enabled(struct devfreq_event_dev *edev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq-event.c (ffffffff81a64cf5)
Location: drivers/devfreq/devfreq-event.c:106
Inline: True
Inline callers:
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
```
**Symbols:**

```
ffffffff81a649f0-ffffffff81a64a4d: devfreq_event_is_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool devfreq_event_is_enabled(struct devfreq_event_dev *edev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq-event.c (ffffffff81bd59f8)
Location: drivers/devfreq/devfreq-event.c:106
Inline: True
Inline callers:
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
```
**Symbols:**

```
ffffffff81bd56d0-ffffffff81bd5739: devfreq_event_is_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool devfreq_event_is_enabled(struct devfreq_event_dev *edev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq-event.c (ffffffff81d82048)
Location: drivers/devfreq/devfreq-event.c:106
Inline: True
Inline callers:
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
```
**Symbols:**

```
ffffffff81d81ce0-ffffffff81d81d49: devfreq_event_is_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool devfreq_event_is_enabled(struct devfreq_event_dev *edev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq-event.c (ffffffff81df0408)
Location: drivers/devfreq/devfreq-event.c:106
Inline: True
Inline callers:
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
```
**Symbols:**

```
ffffffff81df00a0-ffffffff81df0109: devfreq_event_is_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool devfreq_event_is_enabled(struct devfreq_event_dev *edev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq-event.c (ffffffff81ea69f8)
Location: drivers/devfreq/devfreq-event.c:106
Inline: True
Inline callers:
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
```
**Symbols:**

```
ffffffff81ea6660-ffffffff81ea66c9: devfreq_event_is_enabled (STB_GLOBAL)
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
bool devfreq_event_is_enabled(struct devfreq_event_dev *edev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq-event.c (ffff800010b86ff4)
Location: drivers/devfreq/devfreq-event.c:106
Inline: True
Inline callers:
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
Direct callers:
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
```
**Symbols:**

```
ffff800010b86e00-ffff800010b86e48: devfreq_event_is_enabled.part.0 (STB_LOCAL)
ffff800010b86e48-ffff800010b86e98: devfreq_event_is_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool devfreq_event_is_enabled(struct devfreq_event_dev *edev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq-event.c (c0c69f64)
Location: drivers/devfreq/devfreq-event.c:106
Inline: True
Inline callers:
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
Direct callers:
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
```
**Symbols:**

```
c0c69d90-c0c69dd0: devfreq_event_is_enabled.part.0 (STB_LOCAL)
c0c69dd0-c0c69e08: devfreq_event_is_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool devfreq_event_is_enabled(struct devfreq_event_dev *edev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq-event.c (c000000000c65de0)
Location: drivers/devfreq/devfreq-event.c:106
Inline: True
Inline callers:
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
Direct callers:
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
```
**Symbols:**

```
c000000000c65b10-c000000000c65b78: devfreq_event_is_enabled.part.0 (STB_LOCAL)
c000000000c65b80-c000000000c65bb8: devfreq_event_is_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool devfreq_event_is_enabled(struct devfreq_event_dev *edev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq-event.c (ffffffe00072ff3c)
Location: drivers/devfreq/devfreq-event.c:106
Inline: True
Inline callers:
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
Direct callers:
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
```
**Symbols:**

```
ffffffe00072fd9c-ffffffe00072fde2: devfreq_event_is_enabled.part.0 (STB_LOCAL)
ffffffe00072fde2-ffffffe00072fe22: devfreq_event_is_enabled (STB_GLOBAL)
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
bool devfreq_event_is_enabled(struct devfreq_event_dev *edev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq-event.c (ffffffff8189b9b1)
Location: drivers/devfreq/devfreq-event.c:106
Inline: True
Inline callers:
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
Direct callers:
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
```
**Symbols:**

```
ffffffff8189b7e0-ffffffff8189b81e: devfreq_event_is_enabled.part.0 (STB_LOCAL)
ffffffff8189b820-ffffffff8189b843: devfreq_event_is_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool devfreq_event_is_enabled(struct devfreq_event_dev *edev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq-event.c (ffffffff81858e81)
Location: drivers/devfreq/devfreq-event.c:106
Inline: True
Inline callers:
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
Direct callers:
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
```
**Symbols:**

```
ffffffff81858cb0-ffffffff81858cee: devfreq_event_is_enabled.part.0 (STB_LOCAL)
ffffffff81858cf0-ffffffff81858d13: devfreq_event_is_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool devfreq_event_is_enabled(struct devfreq_event_dev *edev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq-event.c (ffffffff818eb0a1)
Location: drivers/devfreq/devfreq-event.c:106
Inline: True
Inline callers:
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
Direct callers:
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
```
**Symbols:**

```
ffffffff818eaed0-ffffffff818eaf0e: devfreq_event_is_enabled.part.0 (STB_LOCAL)
ffffffff818eaf10-ffffffff818eaf33: devfreq_event_is_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool devfreq_event_is_enabled(struct devfreq_event_dev *edev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq-event.c (ffffffff8190c121)
Location: drivers/devfreq/devfreq-event.c:106
Inline: True
Inline callers:
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
Direct callers:
  - drivers/devfreq/devfreq-event.c:devfreq_event_reset_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_event
  - drivers/devfreq/devfreq-event.c:devfreq_event_set_event
```
**Symbols:**

```
ffffffff8190bf50-ffffffff8190bf8e: devfreq_event_is_enabled.part.0 (STB_LOCAL)
ffffffff8190bf90-ffffffff8190bfb3: devfreq_event_is_enabled (STB_GLOBAL)
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
