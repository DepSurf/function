# Function: <code>devfreq_update_interval</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void devfreq_update_interval(struct devfreq *devfreq, unsigned int *delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff819ce0c0)
Location: drivers/devfreq/devfreq.c:557
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_handler
```
**Symbols:**

```
ffffffff819ce0c0-ffffffff819ce1cb: devfreq_update_interval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void devfreq_update_interval(struct devfreq *devfreq, unsigned int *delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff819cda90)
Location: drivers/devfreq/devfreq.c:598
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_handler
```
**Symbols:**

```
ffffffff819cda90-ffffffff819cdb9a: devfreq_update_interval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void devfreq_update_interval(struct devfreq *devfreq, unsigned int *delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff819b2d00)
Location: drivers/devfreq/devfreq.c:599
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_handler
```
**Symbols:**

```
ffffffff819b2d00-ffffffff819b2e0a: devfreq_update_interval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void devfreq_update_interval(struct devfreq *devfreq, unsigned int *delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:599
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_handler
```
**Symbols:**

```
ffffffff81d32fe9-ffffffff81d33013: devfreq_update_interval.cold (STB_LOCAL)
ffffffff81a62680-ffffffff81a627ac: devfreq_update_interval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void devfreq_update_interval(struct devfreq *devfreq, unsigned int *delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:596
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_handler
```
**Symbols:**

```
ffffffff81eff475-ffffffff81eff49f: devfreq_update_interval.cold (STB_LOCAL)
ffffffff81bd37c0-ffffffff81bd38fe: devfreq_update_interval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void devfreq_update_interval(struct devfreq *devfreq, unsigned int *delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:596
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_handler
```
**Symbols:**

```
ffffffff820aa462-ffffffff820aa48c: devfreq_update_interval.cold (STB_LOCAL)
ffffffff81d7f710-ffffffff81d7f84e: devfreq_update_interval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void devfreq_update_interval(struct devfreq *devfreq, unsigned int *delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:596
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_handler
```
**Symbols:**

```
ffffffff8212b94d-ffffffff8212b977: devfreq_update_interval.cold (STB_LOCAL)
ffffffff81dedaa0-ffffffff81dedbde: devfreq_update_interval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void devfreq_update_interval(struct devfreq *devfreq, unsigned int *delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:617
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_handler
```
**Symbols:**

```
ffffffff8220d5a4-ffffffff8220d5ce: devfreq_update_interval.cold (STB_LOCAL)
ffffffff81ea3e40-ffffffff81ea3f7e: devfreq_update_interval (STB_GLOBAL)
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
