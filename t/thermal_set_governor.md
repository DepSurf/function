# Function: <code>thermal_set_governor</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int thermal_set_governor(struct thermal_zone_device *tz, struct thermal_governor *new_gov);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff816833d0)
Location: drivers/thermal/thermal_core.c:111
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_unregister
  - drivers/thermal/thermal_core.c:thermal_unregister_governor
Direct callers:
  - drivers/thermal/thermal_core.c:policy_store
  - drivers/thermal/thermal_core.c:thermal_register_governor
```
**Symbols:**

```
ffffffff816833d0-ffffffff81683473: thermal_set_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int thermal_set_governor(struct thermal_zone_device *tz, struct thermal_governor *new_gov);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff816e611a)
Location: drivers/thermal/thermal_core.c:111
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_unregister
  - drivers/thermal/thermal_core.c:thermal_unregister_governor
Direct callers:
  - drivers/thermal/thermal_core.c:policy_store
  - drivers/thermal/thermal_core.c:thermal_register_governor
```
**Symbols:**

```
ffffffff816e48c0-ffffffff816e4963: thermal_set_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int thermal_set_governor(struct thermal_zone_device *tz, struct thermal_governor *new_gov);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8171595c)
Location: drivers/thermal/thermal_core.c:105
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_unregister
  - drivers/thermal/thermal_core.c:thermal_unregister_governor
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
  - drivers/thermal/thermal_core.c:thermal_register_governor
```
**Symbols:**

```
ffffffff817153e0-ffffffff81715483: thermal_set_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int thermal_set_governor(struct thermal_zone_device *tz, struct thermal_governor *new_gov);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff817303be)
Location: drivers/thermal/thermal_core.c:106
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_unregister_governor
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
  - drivers/thermal/thermal_core.c:thermal_register_governor
```
**Symbols:**

```
ffffffff8172d0d0-ffffffff8172d173: thermal_set_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int thermal_set_governor(struct thermal_zone_device *tz, struct thermal_governor *new_gov);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff817a142e)
Location: drivers/thermal/thermal_core.c:106
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_unregister_governor
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
  - drivers/thermal/thermal_core.c:thermal_register_governor
```
**Symbols:**

```
ffffffff8179e720-ffffffff8179e7cc: thermal_set_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int thermal_set_governor(struct thermal_zone_device *tz, struct thermal_governor *new_gov);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff817e89c2)
Location: drivers/thermal/thermal_core.c:103
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_unregister_governor
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
  - drivers/thermal/thermal_core.c:thermal_register_governor
```
**Symbols:**

```
ffffffff817e5cf0-ffffffff817e5d9c: thermal_set_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int thermal_set_governor(struct thermal_zone_device *tz, struct thermal_governor *new_gov);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81814872)
Location: drivers/thermal/thermal_core.c:103
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_unregister_governor
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
  - drivers/thermal/thermal_core.c:thermal_register_governor
```
**Symbols:**

```
ffffffff81811ba0-ffffffff81811c4c: thermal_set_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int thermal_set_governor(struct thermal_zone_device *tz, struct thermal_governor *new_gov);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81854e76)
Location: drivers/thermal/thermal_core.c:103
Inline: True
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
  - drivers/thermal/thermal_core.c:thermal_register_governor
```
**Symbols:**

```
ffffffff81853c00-ffffffff81853c87: thermal_set_governor (STB_LOCAL)
ffffffff81856de9-ffffffff81856e17: thermal_set_governor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int thermal_set_governor(struct thermal_zone_device *tz, struct thermal_governor *new_gov);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff818868d6)
Location: drivers/thermal/thermal_core.c:103
Inline: True
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
  - drivers/thermal/thermal_core.c:thermal_register_governor
```
**Symbols:**

```
ffffffff81885660-ffffffff818856e7: thermal_set_governor (STB_LOCAL)
ffffffff81888839-ffffffff81888867: thermal_set_governor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int thermal_set_governor(struct thermal_zone_device *tz, struct thermal_governor *new_gov);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81955d63)
Location: drivers/thermal/thermal_core.c:97
Inline: True
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
  - drivers/thermal/thermal_core.c:thermal_register_governor
```
**Symbols:**

```
ffffffff81954120-ffffffff819541a7: thermal_set_governor (STB_LOCAL)
ffffffff81957269-ffffffff81957297: thermal_set_governor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int thermal_set_governor(struct thermal_zone_device *tz, struct thermal_governor *new_gov);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8195ba73)
Location: drivers/thermal/thermal_core.c:97
Inline: True
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
  - drivers/thermal/thermal_core.c:thermal_register_governor
```
**Symbols:**

```
ffffffff81959170-ffffffff819591f7: thermal_set_governor (STB_LOCAL)
ffffffff81c259d8-ffffffff81c25a06: thermal_set_governor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int thermal_set_governor(struct thermal_zone_device *tz, struct thermal_governor *new_gov);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8193e8a3)
Location: drivers/thermal/thermal_core.c:97
Inline: True
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
  - drivers/thermal/thermal_core.c:thermal_register_governor
```
**Symbols:**

```
ffffffff8193cc90-ffffffff8193cd17: thermal_set_governor (STB_LOCAL)
ffffffff81c17b64-ffffffff81c17b92: thermal_set_governor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int thermal_set_governor(struct thermal_zone_device *tz, struct thermal_governor *new_gov);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff819e3163)
Location: drivers/thermal/thermal_core.c:95
Inline: True
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
  - drivers/thermal/thermal_core.c:thermal_register_governor
```
**Symbols:**

```
ffffffff819e1530-ffffffff819e15b7: thermal_set_governor (STB_LOCAL)
ffffffff81d26c80-ffffffff81d26cae: thermal_set_governor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int thermal_set_governor(struct thermal_zone_device *tz, struct thermal_governor *new_gov);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81b48843)
Location: drivers/thermal/thermal_core.c:95
Inline: True
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
  - drivers/thermal/thermal_core.c:thermal_register_governor
```
**Symbols:**

```
ffffffff81b46630-ffffffff81b466c6: thermal_set_governor (STB_LOCAL)
ffffffff81ef2ae1-ffffffff81ef2b0d: thermal_set_governor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int thermal_set_governor(struct thermal_zone_device *tz, struct thermal_governor *new_gov);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81cdd9f0)
Location: drivers/thermal/thermal_core.c:95
Inline: True
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
  - drivers/thermal/thermal_core.c:thermal_register_governor
```
**Symbols:**

```
ffffffff81cdd9f0-ffffffff81cddaab: thermal_set_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int thermal_set_governor(struct thermal_zone_device *tz, struct thermal_governor *new_gov);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81d45ee0)
Location: drivers/thermal/thermal_core.c:95
Inline: True
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
  - drivers/thermal/thermal_core.c:thermal_register_governor
```
**Symbols:**

```
ffffffff81d45ee0-ffffffff81d45f9b: thermal_set_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int thermal_set_governor(struct thermal_zone_device *tz, struct thermal_governor *new_gov);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81dfc8f0)
Location: drivers/thermal/thermal_core.c:93
Inline: True
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
  - drivers/thermal/thermal_core.c:thermal_register_governor
```
**Symbols:**

```
ffffffff81dfc8f0-ffffffff81dfc9ab: thermal_set_governor (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int thermal_set_governor(struct thermal_zone_device *tz, struct thermal_governor *new_gov);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffff800010ad2760)
Location: drivers/thermal/thermal_core.c:103
Inline: True
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
  - drivers/thermal/thermal_core.c:thermal_register_governor
```
**Symbols:**

```
ffff800010ad2760-ffff800010ad2810: thermal_set_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int thermal_set_governor(struct thermal_zone_device *tz, struct thermal_governor *new_gov);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (c0bb300c)
Location: drivers/thermal/thermal_core.c:103
Inline: True
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
  - drivers/thermal/thermal_core.c:thermal_register_governor
```
**Symbols:**

```
c0bb300c-c0bb30d4: thermal_set_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int thermal_set_governor(struct thermal_zone_device *tz, struct thermal_governor *new_gov);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (c000000000bb7240)
Location: drivers/thermal/thermal_core.c:103
Inline: True
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
  - drivers/thermal/thermal_core.c:thermal_register_governor
```
**Symbols:**

```
c000000000bb7240-c000000000bb7370: thermal_set_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int thermal_set_governor(struct thermal_zone_device *tz, struct thermal_governor *new_gov);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffe0006ceed4)
Location: drivers/thermal/thermal_core.c:103
Inline: True
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
  - drivers/thermal/thermal_core.c:thermal_register_governor
```
**Symbols:**

```
ffffffe0006ceed4-ffffffe0006cef5a: thermal_set_governor (STB_LOCAL)
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
int thermal_set_governor(struct thermal_zone_device *tz, struct thermal_governor *new_gov);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8182c756)
Location: drivers/thermal/thermal_core.c:103
Inline: True
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
  - drivers/thermal/thermal_core.c:thermal_register_governor
```
**Symbols:**

```
ffffffff8182b4e0-ffffffff8182b567: thermal_set_governor (STB_LOCAL)
ffffffff8182e6b9-ffffffff8182e6e7: thermal_set_governor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int thermal_set_governor(struct thermal_zone_device *tz, struct thermal_governor *new_gov);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff817f3de6)
Location: drivers/thermal/thermal_core.c:103
Inline: True
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
  - drivers/thermal/thermal_core.c:thermal_register_governor
```
**Symbols:**

```
ffffffff817f2b70-ffffffff817f2bf7: thermal_set_governor (STB_LOCAL)
ffffffff817f5d49-ffffffff817f5d77: thermal_set_governor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int thermal_set_governor(struct thermal_zone_device *tz, struct thermal_governor *new_gov);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8187bd86)
Location: drivers/thermal/thermal_core.c:103
Inline: True
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
  - drivers/thermal/thermal_core.c:thermal_register_governor
```
**Symbols:**

```
ffffffff8187ab10-ffffffff8187ab97: thermal_set_governor (STB_LOCAL)
ffffffff8187dce9-ffffffff8187dd17: thermal_set_governor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int thermal_set_governor(struct thermal_zone_device *tz, struct thermal_governor *new_gov);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff818977b6)
Location: drivers/thermal/thermal_core.c:103
Inline: True
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
  - drivers/thermal/thermal_core.c:thermal_register_governor
```
**Symbols:**

```
ffffffff81896510-ffffffff81896597: thermal_set_governor (STB_LOCAL)
ffffffff81899719-ffffffff81899747: thermal_set_governor.cold (STB_LOCAL)
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
