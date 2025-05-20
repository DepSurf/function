# Function: <code>platform_probe</code>

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
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int platform_probe(struct device *_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (0)
Location: drivers/base/platform.c:1423
Inline: False
```
**Symbols:**

```
ffffffff817d0b60-ffffffff817d0bfc: platform_probe (STB_LOCAL)
ffffffff81c0e576-ffffffff81c0e590: platform_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int platform_probe(struct device *_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (0)
Location: drivers/base/platform.c:1422
Inline: False
```
**Symbols:**

```
ffffffff817b4580-ffffffff817b461c: platform_probe (STB_LOCAL)
ffffffff81c0098a-ffffffff81c009a4: platform_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int platform_probe(struct device *_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (0)
Location: drivers/base/platform.c:1386
Inline: False
```
**Symbols:**

```
ffffffff8183dc60-ffffffff8183dd1d: platform_probe (STB_LOCAL)
ffffffff81d032de-ffffffff81d0330c: platform_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int platform_probe(struct device *_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (0)
Location: drivers/base/platform.c:1375
Inline: False
```
**Symbols:**

```
ffffffff81980a50-ffffffff81980b22: platform_probe (STB_LOCAL)
ffffffff81ecba56-ffffffff81ecba85: platform_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int platform_probe(struct device *_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (0)
Location: drivers/base/platform.c:1375
Inline: False
```
**Symbols:**

```
ffffffff81aee5a0-ffffffff81aee65e: platform_probe (STB_LOCAL)
ffffffff82098721-ffffffff82098736: platform_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int platform_probe(struct device *_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (0)
Location: drivers/base/platform.c:1379
Inline: False
```
**Symbols:**

```
ffffffff81b3c960-ffffffff81b3ca1e: platform_probe (STB_LOCAL)
ffffffff8211970d-ffffffff82119722: platform_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int platform_probe(struct device *_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (0)
Location: drivers/base/platform.c:1379
Inline: False
```
**Symbols:**

```
ffffffff81b94490-ffffffff81b9454e: platform_probe (STB_LOCAL)
ffffffff821f76cf-ffffffff821f76e4: platform_probe.cold (STB_LOCAL)
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
