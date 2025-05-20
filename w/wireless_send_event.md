# Function: <code>wireless_send_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void wireless_send_event(struct net_device *dev, unsigned int cmd, union iwreq_data *wrqu, const char *extra);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (ffffffff81809c70)
Location: net/wireless/wext-core.c:450
Inline: False
Direct callers:
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-core.c:ioctl_standard_call
  - net/wireless/wext-spy.c:iw_send_thrspy_event
```
**Symbols:**

```
ffffffff81809c70-ffffffff8180a06d: wireless_send_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void wireless_send_event(struct net_device *dev, unsigned int cmd, union iwreq_data *wrqu, const char *extra);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (ffffffff8187b770)
Location: net/wireless/wext-core.c:453
Inline: False
Direct callers:
  - net/wireless/wext-core.c:ioctl_standard_call
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-spy.c:iw_send_thrspy_event
```
**Symbols:**

```
ffffffff8187b770-ffffffff8187bb70: wireless_send_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void wireless_send_event(struct net_device *dev, unsigned int cmd, union iwreq_data *wrqu, const char *extra);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (ffffffff818b0030)
Location: net/wireless/wext-core.c:453
Inline: False
Direct callers:
  - net/wireless/wext-core.c:ioctl_standard_call
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-spy.c:iw_send_thrspy_event
```
**Symbols:**

```
ffffffff818b0030-ffffffff818b0430: wireless_send_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void wireless_send_event(struct net_device *dev, unsigned int cmd, union iwreq_data *wrqu, const char *extra);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (ffffffff818d69f0)
Location: net/wireless/wext-core.c:453
Inline: False
Direct callers:
  - net/wireless/wext-core.c:ioctl_standard_call
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-spy.c:iw_send_thrspy_event
```
**Symbols:**

```
ffffffff818d69f0-ffffffff818d6dc8: wireless_send_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void wireless_send_event(struct net_device *dev, unsigned int cmd, union iwreq_data *wrqu, const char *extra);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (ffffffff8195c5c0)
Location: net/wireless/wext-core.c:453
Inline: False
Direct callers:
  - net/wireless/wext-core.c:ioctl_standard_call
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-spy.c:iw_send_thrspy_event
```
**Symbols:**

```
ffffffff8195c5c0-ffffffff8195c998: wireless_send_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void wireless_send_event(struct net_device *dev, unsigned int cmd, union iwreq_data *wrqu, const char *extra);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/wireless/wext-core.c (0)
Location: net/wireless/wext-core.c:451
Inline: False
Direct callers:
  - net/wireless/wext-core.c:ioctl_standard_call
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-spy.c:iw_send_thrspy_event
```
**Symbols:**

```
ffffffff819b69de-ffffffff819b69ea: wireless_send_event.cold.13 (STB_LOCAL)
ffffffff819b5de0-ffffffff819b61ab: wireless_send_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void wireless_send_event(struct net_device *dev, unsigned int cmd, union iwreq_data *wrqu, const char *extra);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/wireless/wext-core.c (0)
Location: net/wireless/wext-core.c:451
Inline: False
Direct callers:
  - net/wireless/wext-core.c:ioctl_standard_call
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-spy.c:iw_send_thrspy_event
```
**Symbols:**

```
ffffffff819edc9e-ffffffff819edcaa: wireless_send_event.cold.13 (STB_LOCAL)
ffffffff819ed0a0-ffffffff819ed46b: wireless_send_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void wireless_send_event(struct net_device *dev, unsigned int cmd, union iwreq_data *wrqu, const char *extra);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/wireless/wext-core.c (0)
Location: net/wireless/wext-core.c:451
Inline: False
Direct callers:
  - net/wireless/wext-core.c:ioctl_standard_call
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-spy.c:iw_send_thrspy_event
```
**Symbols:**

```
ffffffff81a5ce38-ffffffff81a5ceea: wireless_send_event.cold (STB_LOCAL)
ffffffff81a5c290-ffffffff81a5c5ec: wireless_send_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void wireless_send_event(struct net_device *dev, unsigned int cmd, union iwreq_data *wrqu, const char *extra);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/wireless/wext-core.c (0)
Location: net/wireless/wext-core.c:451
Inline: False
Direct callers:
  - net/wireless/wext-core.c:ioctl_standard_call
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-spy.c:iw_send_thrspy_event
```
**Symbols:**

```
ffffffff81a93a9e-ffffffff81a93af2: wireless_send_event.cold (STB_LOCAL)
ffffffff81a92ec0-ffffffff81a93250: wireless_send_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void wireless_send_event(struct net_device *dev, unsigned int cmd, union iwreq_data *wrqu, const char *extra);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/wireless/wext-core.c (0)
Location: net/wireless/wext-core.c:451
Inline: False
Direct callers:
  - net/wireless/wext-core.c:ioctl_standard_call
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-spy.c:iw_send_thrspy_event
```
**Symbols:**

```
ffffffff81b8f002-ffffffff81b8f056: wireless_send_event.cold (STB_LOCAL)
ffffffff81b8e1d0-ffffffff81b8e55b: wireless_send_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void wireless_send_event(struct net_device *dev, unsigned int cmd, union iwreq_data *wrqu, const char *extra);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/wireless/wext-core.c (0)
Location: net/wireless/wext-core.c:451
Inline: False
Direct callers:
  - net/wireless/wext-core.c:ioctl_standard_call
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-spy.c:iw_send_thrspy_event
```
**Symbols:**

```
ffffffff81c332fc-ffffffff81c33350: wireless_send_event.cold (STB_LOCAL)
ffffffff81b9de70-ffffffff81b9e1fb: wireless_send_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void wireless_send_event(struct net_device *dev, unsigned int cmd, union iwreq_data *wrqu, const char *extra);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/wireless/wext-core.c (0)
Location: net/wireless/wext-core.c:451
Inline: False
Direct callers:
  - net/wireless/wext-core.c:ioctl_standard_call
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-spy.c:iw_send_thrspy_event
```
**Symbols:**

```
ffffffff81c2561b-ffffffff81c25675: wireless_send_event.cold (STB_LOCAL)
ffffffff81b8cf70-ffffffff81b8d2f8: wireless_send_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void wireless_send_event(struct net_device *dev, unsigned int cmd, union iwreq_data *wrqu, const char *extra);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/wireless/wext-core.c (0)
Location: net/wireless/wext-core.c:451
Inline: False
Direct callers:
  - net/wireless/wext-core.c:ioctl_standard_call
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-spy.c:iw_send_thrspy_event
```
**Symbols:**

```
ffffffff81d41b5c-ffffffff81d41bb6: wireless_send_event.cold (STB_LOCAL)
ffffffff81c59310-ffffffff81c59715: wireless_send_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void wireless_send_event(struct net_device *dev, unsigned int cmd, union iwreq_data *wrqu, const char *extra);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/wireless/wext-core.c (0)
Location: net/wireless/wext-core.c:451
Inline: False
Direct callers:
  - net/wireless/wext-core.c:ioctl_standard_call
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-spy.c:iw_send_thrspy_event
```
**Symbols:**

```
ffffffff81f0e488-ffffffff81f0e4e2: wireless_send_event.cold (STB_LOCAL)
ffffffff81dfaa70-ffffffff81dfaec2: wireless_send_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void wireless_send_event(struct net_device *dev, unsigned int cmd, union iwreq_data *wrqu, const char *extra);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/wireless/wext-core.c (0)
Location: net/wireless/wext-core.c:451
Inline: False
Direct callers:
  - net/wireless/wext-core.c:ioctl_standard_call
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-spy.c:iw_send_thrspy_event
```
**Symbols:**

```
ffffffff820b54e5-ffffffff820b5510: wireless_send_event.cold (STB_LOCAL)
ffffffff81fcf240-ffffffff81fcf71d: wireless_send_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void wireless_send_event(struct net_device *dev, unsigned int cmd, union iwreq_data *wrqu, const char *extra);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/wireless/wext-core.c (0)
Location: net/wireless/wext-core.c:451
Inline: False
Direct callers:
  - net/wireless/wext-core.c:ioctl_standard_call
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-spy.c:iw_send_thrspy_event
```
**Symbols:**

```
ffffffff82136a33-ffffffff82136a5e: wireless_send_event.cold (STB_LOCAL)
ffffffff8204ae70-ffffffff8204b361: wireless_send_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void wireless_send_event(struct net_device *dev, unsigned int cmd, union iwreq_data *wrqu, const char *extra);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/wireless/wext-core.c (0)
Location: net/wireless/wext-core.c:451
Inline: False
Direct callers:
  - net/wireless/wext-core.c:ioctl_standard_call
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-spy.c:iw_send_thrspy_event
```
**Symbols:**

```
ffffffff8221881f-ffffffff8221884a: wireless_send_event.cold (STB_LOCAL)
ffffffff8211d2f0-ffffffff8211d7e1: wireless_send_event (STB_GLOBAL)
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
void wireless_send_event(struct net_device *dev, unsigned int cmd, union iwreq_data *wrqu, const char *extra);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (ffff800010d60cd0)
Location: net/wireless/wext-core.c:451
Inline: False
Direct callers:
  - net/wireless/wext-core.c:ioctl_standard_call
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-spy.c:iw_send_thrspy_event
```
**Symbols:**

```
ffff800010d60cd0-ffff800010d610b0: wireless_send_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void wireless_send_event(struct net_device *dev, unsigned int cmd, union iwreq_data *wrqu, const char *extra);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (c0e60378)
Location: net/wireless/wext-core.c:451
Inline: False
Direct callers:
  - net/wireless/wext-core.c:ioctl_standard_call
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-spy.c:iw_send_thrspy_event
```
**Symbols:**

```
c0e60378-c0e606c4: wireless_send_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void wireless_send_event(struct net_device *dev, unsigned int cmd, union iwreq_data *wrqu, const char *extra);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (c000000000e9c090)
Location: net/wireless/wext-core.c:451
Inline: False
Direct callers:
  - net/wireless/wext-core.c:ioctl_standard_call
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-spy.c:iw_send_thrspy_event
```
**Symbols:**

```
c000000000e9c090-c000000000e9c558: wireless_send_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void wireless_send_event(struct net_device *dev, unsigned int cmd, union iwreq_data *wrqu, const char *extra);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (ffffffe000895db2)
Location: net/wireless/wext-core.c:451
Inline: False
Direct callers:
  - net/wireless/wext-core.c:ioctl_standard_call
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-spy.c:iw_send_thrspy_event
```
**Symbols:**

```
ffffffe000895db2-ffffffe000896062: wireless_send_event (STB_GLOBAL)
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
void wireless_send_event(struct net_device *dev, unsigned int cmd, union iwreq_data *wrqu, const char *extra);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/wireless/wext-core.c (0)
Location: net/wireless/wext-core.c:451
Inline: False
Direct callers:
  - net/wireless/wext-core.c:ioctl_standard_call
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-core.c:ioctl_standard_iw_point
```
**Symbols:**

```
ffffffff81a3312e-ffffffff81a33182: wireless_send_event.cold (STB_LOCAL)
ffffffff81a32550-ffffffff81a328e0: wireless_send_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void wireless_send_event(struct net_device *dev, unsigned int cmd, union iwreq_data *wrqu, const char *extra);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/wireless/wext-core.c (0)
Location: net/wireless/wext-core.c:451
Inline: False
Direct callers:
  - net/wireless/wext-core.c:ioctl_standard_call
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-core.c:ioctl_standard_iw_point
```
**Symbols:**

```
ffffffff819f0217-ffffffff819f026b: wireless_send_event.cold (STB_LOCAL)
ffffffff819ef740-ffffffff819efad0: wireless_send_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void wireless_send_event(struct net_device *dev, unsigned int cmd, union iwreq_data *wrqu, const char *extra);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/wireless/wext-core.c (0)
Location: net/wireless/wext-core.c:451
Inline: False
Direct callers:
  - net/wireless/wext-core.c:ioctl_standard_call
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-spy.c:iw_send_thrspy_event
```
**Symbols:**

```
ffffffff81a9ecde-ffffffff81a9ed32: wireless_send_event.cold (STB_LOCAL)
ffffffff81a9e100-ffffffff81a9e490: wireless_send_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void wireless_send_event(struct net_device *dev, unsigned int cmd, union iwreq_data *wrqu, const char *extra);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/wireless/wext-core.c (0)
Location: net/wireless/wext-core.c:451
Inline: False
Direct callers:
  - net/wireless/wext-core.c:ioctl_standard_call
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-spy.c:iw_send_thrspy_event
```
**Symbols:**

```
ffffffff81aaaede-ffffffff81aaaf32: wireless_send_event.cold (STB_LOCAL)
ffffffff81aaa300-ffffffff81aaa690: wireless_send_event (STB_GLOBAL)
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
