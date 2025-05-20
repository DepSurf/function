# Function: <code>user_space_bind</code>

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
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int user_space_bind(struct thermal_zone_device *tz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/gov_user_space.c (0)
Location: drivers/thermal/gov_user_space.c:18
Inline: False
```
**Symbols:**

```
ffffffff81b4ee90-ffffffff81b4eec3: user_space_bind (STB_LOCAL)
ffffffff81ef2e3e-ffffffff81ef2e6a: user_space_bind.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int user_space_bind(struct thermal_zone_device *tz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/gov_user_space.c (0)
Location: drivers/thermal/gov_user_space.c:18
Inline: False
```
**Symbols:**

```
ffffffff81ce6ca0-ffffffff81ce6cf2: user_space_bind (STB_LOCAL)
ffffffff820a7b33-ffffffff820a7b47: user_space_bind.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int user_space_bind(struct thermal_zone_device *tz);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/gov_user_space.c (ffffffff81d4f48f)
Location: drivers/thermal/gov_user_space.c:18
Inline: True
```
**Symbols:**

```
ffffffff81d4f460-ffffffff81d4f4b2: user_space_bind (STB_LOCAL)
ffffffff82128f11-ffffffff82128f25: user_space_bind.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int user_space_bind(struct thermal_zone_device *tz);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/gov_user_space.c (ffffffff81e05ebf)
Location: drivers/thermal/gov_user_space.c:18
Inline: True
```
**Symbols:**

```
ffffffff81e05e90-ffffffff81e05ee2: user_space_bind (STB_LOCAL)
ffffffff8220a8fa-ffffffff8220a90e: user_space_bind.cold (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
