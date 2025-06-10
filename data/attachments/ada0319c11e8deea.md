# Test info

- Name: TC005_@sanity_Clinical Trial Landing Page_Validate the UI of the archive grid on clinical trial landing page.
- Location: C:\Deloitte_Duke_Project\Duke_Cancer_Institute_Automation\tests\Clinical_Trial_Landing\Clinical_Trial_Landing.spec.ts:95:5

# Error details

```
Error: locator.boundingBox: Test timeout of 300000ms exceeded.
Call log:
  - waiting for locator('//article[@class=\'content card clinical-trial clinical-trial--card\']').first()

    at Clinical_Trial_Landing_Page.validateClinicalTrialGridDesktop (C:\Deloitte_Duke_Project\Duke_Cancer_Institute_Automation\pages\Clinical_Trial_Landing_Page.ts:596:63)
    at C:\Deloitte_Duke_Project\Duke_Cancer_Institute_Automation\tests\Clinical_Trial_Landing\Clinical_Trial_Landing.spec.ts:100:9
```

# Page snapshot

```yaml
- link "Skip to main content":
  - /url: "#main-content"
- region "header":
  - heading "Duke Cancer Institute" [level=1]
- banner:
  - link "Duke Cancer Institute Logo":
    - /url: /
    - img "Duke Cancer Institute Logo"
  - navigation:
    - list:
      - listitem:
        - link "DCI Blog":
          - /url: /blogs
      - listitem:
        - link "Events":
          - /url: /events
      - listitem:
        - link "DCI Members":
          - /url: /dci-members
      - listitem:
        - link "Contact":
          - /url: /contact-us
      - listitem:
        - link "Give ":
          - /url: https://www.gifts.duke.edu/dci?technique_code=CCCWBDNN
  - form "Search":
    - searchbox "Search"
    - button "Search Icon":
      - img "Search Icon"
  - navigation "main-menu":
    - button "Cancer Types and Programs "
    - button "Supportive Care "
    - button "Research "
    - button "Education and Training "
    - button "About DCI "
    - button "Get Involved"
    - link "Make an Appointment ":
      - /url: https://www.dukehealth.org/treatments/cancer
- main:
  - navigation "Breadcrumbs navigation":
    - list:
      - listitem:
        - link "Home":
          - /url: /
          - text: 
  - heading "Clinical Trials" [level=1]
  - paragraph: Our experts across all cancer specialties participate in national clinical trials and perform the most advanced treatment methods using the latest technology available. As a result, we offer a broader selection of medical, surgical and minimally invasive options to more people, including those who are not considered candidates for treatment elsewhere. We offer unprecedented access to clinical trials.
  - heading "Search" [level=2]
  - textbox "Enter search term"
  - button "Search"
  - heading "Enrollment Status" [level=2]
  - combobox "Filter by Enrollment Status" [disabled]
  - text: Filter by Enrollment Status
  - button "Filter by Enrollment Status"
  - heading "CATEGORIES" [level=2]
  - combobox "Select Category" [disabled]
  - text: Select Category
  - button "Select Category"
  - heading "Age Group" [level=2]
  - combobox "Filter by Age Group" [disabled]
  - text: Filter by Age Group
  - button "Filter by Age Group"
  - heading "VIEW BY" [level=2]
  - combobox "VIEW BY" [disabled]: Date
  - text: Date
  - button "VIEW BY"
- contentinfo:
  - img "Duke Cancer Institute"
  - link "Visit us on Facebook":
    - /url: https://www.facebook.com/DukeCancerInstitute/
    - img "facebook-icon icon":
      - img "Facebook"
  - link "Visit us on Instagram":
    - /url: https://www.instagram.com/dukecancerinstitute
    - img "instagram icon":
      - img
  - link "Visit us on X":
    - /url: https://twitter.com/dukecancer
    - img "x-icon icon":
      - img
  - link "Visit us on Youtube":
    - /url: https://www.youtube.com/user/dukecancerinstitute
    - img "youtube-icon icon":
      - img "YouTube"
  - link "Subscribe to our RSS Feed":
    - /url: https://www.dukecancerinstitute.org/rss.xml
    - img "rss-icon icon":
      - img "RSS"
  - navigation "Footer navigation":
    - list:
      - listitem: Cancer Types
      - listitem:
        - link "Primary Brain Cancer":
          - /url: /center/preston-robert-tisch-brain-tumor-center
      - listitem:
        - link "Brain and Spine Metastasis":
          - /url: /center/duke-center-brain-and-spine-metastasis
      - listitem:
        - link "Breast Cancer":
          - /url: /cancer-types/breast-cancer
      - listitem:
        - link "Endocrine Neoplasia":
          - /url: /cancer-types/endocrine-neoplasia
      - listitem:
        - link "Gastrointestinal Cancer":
          - /url: /cancer-types/gastrointestinal-cancer
      - listitem:
        - link "Gynecologic Cancer":
          - /url: /cancer-types/gynecologic-cancer
      - listitem:
        - link "Head and Neck Cancer":
          - /url: /cancer-types/head-and-neck-cancer
      - listitem:
        - link "Hematologic Malignancies and Cellular Therapy":
          - /url: /cancer-types/hematologic-malignancies-and-cellular-therapy
      - listitem:
        - link "Melanoma and Advanced Skin Cancers":
          - /url: /cancer-types/melanoma-and-advanced-skin-cancers
      - listitem:
        - link "Pediatric Cancers":
          - /url: /cancer-types/pediatric-cancers
      - listitem:
        - link "Prostate and Urologic Cancers":
          - /url: /center/center-prostate-and-urologic-cancers
      - listitem:
        - link "Sarcoma":
          - /url: /center/duke-sarcoma-center
      - listitem:
        - link "Thoracic Cancer":
          - /url: /cancer-types/thoracic-cancer
      - listitem: Cancer Therapies
      - listitem:
        - link "Immunotherapy":
          - /url: /center/center-cancer-immunotherapy
      - listitem:
        - link "Molecular Tumor Board":
          - /url: /center/molecular-tumor-board-precision-cancer-medicine
      - listitem: Supportive Care
      - listitem:
        - link "Supportive Care and Survivorship Center":
          - /url: /center/supportive-care-and-survivorship-center
      - listitem: Research
      - listitem:
        - link "Cancer Registry":
          - /url: /research/cancer-registry
      - listitem:
        - link "Clinical Trials":
          - /url: /clinical-trials
      - listitem:
        - link "Research Programs":
          - /url: /research-programs
      - listitem:
        - link "Shared Resources":
          - /url: /research-programs/shared-resources
      - listitem:
        - link "Education and Training":
          - /url: /cancer-research-training-and-education-coordination
      - listitem:
        - link "About DCI":
          - /url: /about-dci
      - listitem:
        - link "DCI Members":
          - /url: /about-dci/dci-members
      - listitem:
        - link "Nursing":
          - /url: /AboutDCI/nursing
      - listitem:
        - link "Careers":
          - /url: /about-dci?tab=Careers
      - listitem:
        - link "Community Outreach, Engagement, and Equity":
          - /url: /community-outreach-engagement-and-equity
      - listitem:
        - link "Give To DCI":
          - /url: /give-duke-cancer-institute
      - listitem:
        - link "Benefits and Special Events":
          - /url: /give-duke-cancer-institute?tab=events
      - listitem:
        - link "Breakthroughs Magazine":
          - /url: /give-duke-cancer-institute/breakthroughs
  - navigation "Sub Footer navigation":
    - list:
      - listitem:
        - link "Website Privacy Policy ":
          - /url: https://www.dukehealth.org/privacy/website-privacy-policy
      - listitem:
        - link "Sitemap":
          - /url: /sitemap.xml
      - listitem:
        - 'link "Leading with Heart: Serving Humanity "':
          - /url: https://www.dukehealth.org/leading-with-heart-serving-humanity-pledge
      - listitem:
        - link "Notice of Nondiscrimination ":
          - /url: https://www.dukehealth.org/notice-of-nondiscrimination
      - listitem:
        - link "Notice of Privacy Practices ":
          - /url: https://www.dukehealth.org/privacy
      - listitem:
        - link "Terms and Conditions ":
          - /url: https://www.dukehealth.org/terms-and-conditions-of-use
      - listitem:
        - link "Accessibility ":
          - /url: https://accessibility.duke.edu/
      - listitem: © DUKE CANCER INSTITUTE 2025
```

# Test source

```ts
  496 |     }
  497 |
  498 |
  499 |     /**
  500 |  * Applies a filter and validates the summary count.
  501 |  * @param filterName - The filter to apply (e.g., "Search", "Enrollment Status", etc.)
  502 |  * @param value - The value to select or enter
  503 |  * @param total - The original total count to compare against
  504 |  */
  505 |     async applyFilterAndValidate(filterName: string, value: string, total: number) {
  506 |         await this.page.waitForLoadState();
  507 |         await this.applyFilter(filterName, value);
  508 |         const filteredSummary = await this.getCountSummaryText();
  509 |         expect(filteredSummary).toMatch(/^\d+-\d+ of \d+ Clinical Trials$/);
  510 |         const filteredMatch = filteredSummary.match(/^(\d+)-(\d+) of (\d+) Clinical Trials$/);
  511 |         expect(filteredMatch).not.toBeNull();
  512 |         const filteredTotal = Number(filteredMatch![3]);
  513 |         //console.log("Filtered Total "+filteredTotal+" Total "+total+" filter name "+filterName);
  514 |         expect(filteredTotal).toBeLessThanOrEqual(Number(total));
  515 |         const clinicalTrialCount = await this.clinicalTrialCards.count();
  516 |         expect(clinicalTrialCount).toBeLessThanOrEqual(12);
  517 |     }
  518 |
  519 |
  520 |     /*
  521 |     * Click on the Filter Close button to clear the filter on the Clinical Trial landing page
  522 |     */
  523 |     async clickOnCloseButton_resetFilter() {
  524 |         const closeFilterButton = await this.filterCloseButton_desktop;
  525 |         await closeFilterButton.scrollIntoViewIfNeeded();
  526 |         await closeFilterButton.click({ force: true });
  527 |
  528 |     }
  529 |
  530 |     /**************************************
  531 |      * Resets all filters to their default state.
  532 |      * Handles both mobile and desktop views.
  533 |      **************************************/
  534 |
  535 |     async resetFilters() {
  536 |         if (this.isMobile) {
  537 |             // Mobile: Use the "Clear Filters" button if available
  538 |             if (await this.clearfilters_mobile.isVisible() && !(await this.clearfilters_mobile.isDisabled())) {
  539 |                 await this.clearfilters_mobile.click();
  540 |                 await this.page.waitForLoadState('networkidle');
  541 |             }
  542 |         } else {
  543 |             await this.page.waitForTimeout(5000);
  544 |             // Desktop: Reset search box (clear text)
  545 |             const searchBox = this.page.locator("//input[@placeholder='Enter search term']");
  546 |             if (await searchBox.isVisible()) {
  547 |                 await searchBox.fill('');
  548 |                 if (await this.searchFilter.isVisible()) {
  549 |                     await this.searchFilter.click();
  550 |                 }
  551 |             }
  552 |             // Helper to reset a dropdown if not at default
  553 |             const resetDropdown = async (labelLocator: Locator, defaultValue: string) => {
  554 |                 const currentValue = await labelLocator.textContent();
  555 |                 if (currentValue && currentValue.trim() !== defaultValue) {
  556 |                     await this.page.waitForLoadState('networkidle');
  557 |                     await this.clickOnCloseButton_resetFilter();
  558 |                     await this.page.waitForLoadState('networkidle');
  559 |                 }
  560 |             };
  561 |             // Reset all dropdowns using the helper
  562 |             await resetDropdown(this.enrollmentstatus_label, 'Filter by Enrollment Status');
  563 |             await resetDropdown(this.category_label, 'Select Category');
  564 |             await resetDropdown(this.ageGroup_label, 'Filter by Age Group');
  565 |             // Reset View By dropdown (if it's a native select)
  566 |             const viewByDropdown = this.page.locator('select[name="viewBy"]');
  567 |             if (await viewByDropdown.isVisible()) {
  568 |                 await viewByDropdown.selectOption({ label: 'Date' });
  569 |             }
  570 |             await this.page.waitForLoadState('networkidle');
  571 |         }
  572 |     }
  573 |
  574 |
  575 |     async validateClinicalTrialGridDesktop() {
  576 |         // Verify that a maximum of 12 clinical trials are displayed on a single page
  577 |         const clinicalTrialCount = await this.clinicalTrialCards.count();
  578 |         expect(clinicalTrialCount).toBeLessThanOrEqual(12);
  579 |
  580 |         // Check if there are a max of 3 clinical content in a single row
  581 |         const rows = await this.page.locator("//div[@class='row']").count();
  582 |         for (let i = 0; i < rows; i++) {
  583 |             const columns = await this.page.locator(`//div[@class='row']:nth-child(${i + 1})//article`).count();
  584 |             expect(columns).toBeLessThanOrEqual(3);
  585 |         }
  586 |
  587 |         // Check if each clinical trial is displayed inside a box with title and its respective updated date
  588 |         for (let i = 0; i < clinicalTrialCount; i++) {
  589 |             const title = await this.clinicalTrialCards.nth(i).locator("h3").textContent();
  590 |             const date = await this.clinicalTrialCards.nth(i).locator("time").textContent();
  591 |             expect(title).not.toBeNull();
  592 |             expect(date).not.toBeNull();
  593 |         }
  594 |
  595 |         // Check if the padding space is equal between each clinical trial box (gap - 20 px)
> 596 |         const firstBox = await this.clinicalTrialCards.nth(0).boundingBox();
      |                                                               ^ Error: locator.boundingBox: Test timeout of 300000ms exceeded.
  597 |         const secondBox = await this.clinicalTrialCards.nth(1).boundingBox();
  598 |         if (firstBox && secondBox) {
  599 |             const gap = secondBox.x - (firstBox.x + firstBox.width);
  600 |             expect(gap).toBe(20);
  601 |         }
  602 |
  603 |         // Check if pagination is added if the content is more than 12
  604 |         if (clinicalTrialCount > 12) {
  605 |             expect(await this.pagination.isVisible()).toBe(true);
  606 |         }
  607 |     }
  608 |
  609 |
  610 |     async validateTitleOnClinicalTrialLandingPage() {
  611 |         // Check if the title appears in the UI
  612 |         await expect(this.title).toBeVisible();
  613 |
  614 |         // Check if the color is #153b6b
  615 |         const color = await this.title.evaluate((element) => window.getComputedStyle(element).color);
  616 |         expect(color).toBe("rgb(21, 59, 107)");
  617 |
  618 |         // Check if the font weight is 800
  619 |         const fontWeight = await this.title.evaluate((element) => window.getComputedStyle(element).fontWeight);
  620 |         expect(fontWeight).toBe("800");
  621 |
  622 |         // Check if the text is left aligned
  623 |         const textAlign = await this.title.evaluate((element) => window.getComputedStyle(element).textAlign);
  624 |         expect(['left', 'start']).toContain(textAlign);
  625 |     }
  626 |
  627 |
  628 |     async validateAuthoredTitlePresenceOnClinicalTrialPage(authoredTitle: string) {
  629 |         expect(await this.title.textContent()).toBe(authoredTitle);
  630 |     }
  631 |
  632 |
  633 |     /**
  634 |      * Validates that the archive side image is present and on the right side of the banner (desktop only)
  635 |      */
  636 |     async validateArchiveSideImageOnDesktop() {
  637 |         // Check if the image is visible
  638 |         await expect(this.archiveSideImage).toBeVisible();
  639 |
  640 |         // Check if the image is positioned on the right side of the banner
  641 |         const bannerBox = await this.achiveHeroBanner.boundingBox();
  642 |         const imageBox = await this.archiveSideImage.boundingBox();
  643 |         expect(bannerBox).not.toBeNull();
  644 |         expect(imageBox).not.toBeNull();
  645 |         // The image's left edge should be to the right of the banner's center
  646 |         if (bannerBox && imageBox) {
  647 |             const bannerCenterX = bannerBox.x + bannerBox.width / 2;
  648 |             expect(imageBox.x).toBeGreaterThan(bannerCenterX);
  649 |         }
  650 |     }
  651 |
  652 |
  653 |     async validateArchiveBodyContentUI() {
  654 |         // Ensure the body content is visible
  655 |         await expect(this.archiveBodyContent).toBeVisible();
  656 |
  657 |         // Check color
  658 |         const color = await this.archiveBodyContent.evaluate(el => window.getComputedStyle(el).color);
  659 |         expect(color).toBe("rgb(38, 38, 38)");
  660 |
  661 |         // Check font size
  662 |         const fontSize = await this.archiveBodyContent.evaluate(el => window.getComputedStyle(el).fontSize);
  663 |         expect(fontSize).toBe("16px");
  664 |
  665 |         // Check font weight
  666 |         const fontWeight = await this.archiveBodyContent.evaluate(el => window.getComputedStyle(el).fontWeight);
  667 |         expect(fontWeight === "400" || fontWeight === "normal").toBeTruthy();
  668 |
  669 |         // Check text alignment
  670 |         const textAlign = await this.archiveBodyContent.evaluate(el => window.getComputedStyle(el).textAlign);
  671 |         expect(['left', 'start']).toContain(textAlign);
  672 |
  673 |         // Check that the body content is below the title
  674 |         const titleBox = await this.title.boundingBox();
  675 |         const bodyBox = await this.archiveBodyContent.boundingBox();
  676 |         expect(titleBox).not.toBeNull();
  677 |         expect(bodyBox).not.toBeNull();
  678 |         if (titleBox && bodyBox) {
  679 |             expect(bodyBox.y).toBeGreaterThan(titleBox.y + titleBox.height - 1);
  680 |         }
  681 |     }
  682 |
  683 |
  684 |
  685 |     async validateClinicalTrialGridMobile() {
  686 |         // Verify that a maximum of 12 clinical trials are displayed on a single page
  687 |         const clinicalTrialCount = await this.clinicalTrialCards.count();
  688 |         expect(clinicalTrialCount).toBeLessThanOrEqual(12);
  689 |
  690 |         // Check if each clinical trial is displayed in sequence (by index)
  691 |         let previousTitle: string | null = null;
  692 |         for (let i = 0; i < clinicalTrialCount; i++) {
  693 |             const title = await this.clinicalTrialCards.nth(i).locator("h3").textContent();
  694 |             expect(title).not.toBeNull();
  695 |             if (previousTitle !== null) {
  696 |                 // Optionally, add more checks for sequence if you have a way to compare order
```