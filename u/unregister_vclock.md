# Function: <code>unregister_vclock</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int unregister_vclock(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_sysfs.c (ffffffff81d261c2)
Location: drivers/ptp/ptp_sysfs.c:152
Inline: False
```
**Symbols:**

```
ffffffff81d261c2-ffffffff81d26217: unregister_vclock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
int unregister_vclock(struct device *dev, void *data);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff81b3bb80)
Location: drivers/ptp/ptp_clock.c:346
Inline: False
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff81ef1f5d)
Location: drivers/ptp/ptp_sysfs.c:152
Inline: False
```
**Symbols:**

```
ffffffff81b3bb80-ffffffff81b3bba7: unregister_vclock (STB_LOCAL)
ffffffff81ef1f5d-ffffffff81ef1fbc: unregister_vclock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
int unregister_vclock(struct device *dev, void *data);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff81cd1aa0)
Location: drivers/ptp/ptp_clock.c:343
Inline: False
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff81cd3ae0)
Location: drivers/ptp/ptp_sysfs.c:152
Inline: False
```
**Symbols:**

```
ffffffff81cd1aa0-ffffffff81cd1ac7: unregister_vclock (STB_LOCAL)
ffffffff81cd3ae0-ffffffff81cd3b40: unregister_vclock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
int unregister_vclock(struct device *dev, void *data);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff81d394e0)
Location: drivers/ptp/ptp_clock.c:347
Inline: False
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff81d3b6f0)
Location: drivers/ptp/ptp_sysfs.c:163
Inline: False
```
**Symbols:**

```
ffffffff81d394e0-ffffffff81d39507: unregister_vclock (STB_LOCAL)
ffffffff81d3b6f0-ffffffff81d3b750: unregister_vclock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
int unregister_vclock(struct device *dev, void *data);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff81def7f0)
Location: drivers/ptp/ptp_clock.c:379
Inline: False
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff81df2020)
Location: drivers/ptp/ptp_sysfs.c:167
Inline: False
```
**Symbols:**

```
ffffffff81def7f0-ffffffff81def817: unregister_vclock (STB_LOCAL)
ffffffff81df2020-ffffffff81df2080: unregister_vclock (STB_LOCAL)
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
