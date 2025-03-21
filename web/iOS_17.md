---
title: 17
platform: iOS
---

# iOS/iPadOS 17 <Badge type="tip" text="Current Version (N-0)" />

::: tip RECOMMENDED RELEASE FOR MOST UP-TO-DATE SECURITY
This is the latest version of iOS/iPadOS that receives the most up-to-date security patches and updates, making it the recommended choice to protect your devices.
:::


<script setup>
import LatestFeatures from './components/LatestFeatures.vue';
import SecurityInfo from './components/SecurityInfo.vue';
import ForcedUpdateDeferralIndicator from './components/ForcedUpdateDeferralIndicator.vue'; 
import LinksComponent from './components/LinksComponent.vue';

const frontmatter = {
  title: 'iOS 17',
  platform: 'iOS'
};
</script>

## Latest Release Info
<LatestFeatures :title="frontmatter.title" :platform="frontmatter.platform" :stage="frontmatter.stage" />

## Update Deferral Indicator
<ForcedUpdateDeferralIndicator :osVersion="frontmatter.title" :platform="frontmatter.platform" :stage="frontmatter.stage" />

## Essential Apple Resources
<LinksComponent :title="frontmatter.title" :platform="frontmatter.platform" :stage="frontmatter.stage" />

## Security Information
<SecurityInfo :title="frontmatter.title" :platform="frontmatter.platform" :stage="frontmatter.stage" />
