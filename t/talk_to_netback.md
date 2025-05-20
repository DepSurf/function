# Function: <code>talk_to_netback</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int talk_to_netback(struct xenbus_device *dev, struct netfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff815fc5a0)
Location: drivers/net/xen-netfront.c:1803
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:netback_changed
```
**Symbols:**

```
ffffffff815fc5a0-ffffffff815fd121: talk_to_netback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int talk_to_netback(struct xenbus_device *dev, struct netfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff8165c500)
Location: drivers/net/xen-netfront.c:1794
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:netback_changed
```
**Symbols:**

```
ffffffff8165c500-ffffffff8165d018: talk_to_netback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff8168a360)
Location: drivers/net/xen-netfront.c:1800
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int talk_to_netback(struct xenbus_device *dev, struct netfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff8169f620)
Location: drivers/net/xen-netfront.c:1799
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:netback_changed
```
**Symbols:**

```
ffffffff8169f620-ffffffff816a0091: talk_to_netback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int talk_to_netback(struct xenbus_device *dev, struct netfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff8170a7c0)
Location: drivers/net/xen-netfront.c:1801
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:netback_changed
```
**Symbols:**

```
ffffffff8170a7c0-ffffffff8170b223: talk_to_netback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int talk_to_netback(struct xenbus_device *dev, struct netfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:1799
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:netback_changed
```
**Symbols:**

```
ffffffff81749290-ffffffff81749ce7: talk_to_netback (STB_LOCAL)
ffffffff8174a420-ffffffff8174a480: talk_to_netback.cold.44 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int talk_to_netback(struct xenbus_device *dev, struct netfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff8176d520)
Location: drivers/net/xen-netfront.c:1798
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:netback_changed
```
**Symbols:**

```
ffffffff8176d520-ffffffff8176de75: talk_to_netback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int talk_to_netback(struct xenbus_device *dev, struct netfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff817ab770)
Location: drivers/net/xen-netfront.c:1797
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:netback_changed
```
**Symbols:**

```
ffffffff817ab770-ffffffff817ac05e: talk_to_netback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int talk_to_netback(struct xenbus_device *dev, struct netfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff817cf1b0)
Location: drivers/net/xen-netfront.c:1798
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:netback_changed
```
**Symbols:**

```
ffffffff817cf1b0-ffffffff817cfa9e: talk_to_netback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int talk_to_netback(struct xenbus_device *dev, struct netfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81898940)
Location: drivers/net/xen-netfront.c:1803
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_connect
```
**Symbols:**

```
ffffffff81898940-ffffffff81898dd7: talk_to_netback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int talk_to_netback(struct xenbus_device *dev, struct netfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:2088
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_connect
```
**Symbols:**

```
ffffffff818a6eb0-ffffffff818a7397: talk_to_netback (STB_LOCAL)
ffffffff81c19da7-ffffffff81c19db8: talk_to_netback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int talk_to_netback(struct xenbus_device *dev, struct netfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:2086
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_connect
```
**Symbols:**

```
ffffffff8188a650-ffffffff8188ab3b: talk_to_netback (STB_LOCAL)
ffffffff81c0bbe7-ffffffff81c0bbf8: talk_to_netback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int talk_to_netback(struct xenbus_device *dev, struct netfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:2235
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_connect
```
**Symbols:**

```
ffffffff8191d150-ffffffff8191d659: talk_to_netback (STB_LOCAL)
ffffffff81d11303-ffffffff81d11332: talk_to_netback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int talk_to_netback(struct xenbus_device *dev, struct netfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:2243
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_connect
```
**Symbols:**

```
ffffffff81a73060-ffffffff81a735f5: talk_to_netback (STB_LOCAL)
ffffffff81edc02a-ffffffff81edc06e: talk_to_netback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int talk_to_netback(struct xenbus_device *dev, struct netfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:2248
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_connect
```
**Symbols:**

```
ffffffff81c05820-ffffffff81c05dc6: talk_to_netback (STB_LOCAL)
ffffffff8209daf8-ffffffff8209db2b: talk_to_netback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int talk_to_netback(struct xenbus_device *dev, struct netfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:2250
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_connect
```
**Symbols:**

```
ffffffff81c6af30-ffffffff81c6b4b4: talk_to_netback (STB_LOCAL)
ffffffff8211f080-ffffffff8211f0b3: talk_to_netback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int talk_to_netback(struct xenbus_device *dev, struct netfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:2251
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_connect
```
**Symbols:**

```
ffffffff81d1f910-ffffffff81d1fe94: talk_to_netback (STB_LOCAL)
ffffffff82200856-ffffffff82200889: talk_to_netback.cold (STB_LOCAL)
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
int talk_to_netback(struct xenbus_device *dev, struct netfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffff800010a07d38)
Location: drivers/net/xen-netfront.c:1798
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:netback_changed
```
**Symbols:**

```
ffff800010a07d38-ffff800010a08498: talk_to_netback (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int talk_to_netback(struct xenbus_device *dev, struct netfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81793dd0)
Location: drivers/net/xen-netfront.c:1876
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:netback_changed
```
**Symbols:**

```
ffffffff81793dd0-ffffffff817946be: talk_to_netback (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int talk_to_netback(struct xenbus_device *dev, struct netfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff817c4030)
Location: drivers/net/xen-netfront.c:1798
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:netback_changed
```
**Symbols:**

```
ffffffff817c4030-ffffffff817c491e: talk_to_netback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int talk_to_netback(struct xenbus_device *dev, struct netfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff817de2e0)
Location: drivers/net/xen-netfront.c:1798
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:netback_changed
```
**Symbols:**

```
ffffffff817de2e0-ffffffff817debce: talk_to_netback (STB_LOCAL)
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
