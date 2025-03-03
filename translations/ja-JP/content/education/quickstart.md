---
title: GitHub Educatorsのクイックスタート
intro: 'およそ15分で、教師は割引を適用して{% data variables.product.company_short %}に取りかかり、トレーニングを受け、ツールを獲得し、{% data variables.product.prodname_classroom %}を使用してソフトウェア開発のコースで学生用のクラスルームを作成できます。'
allowTitleToDifferFromFilename: true
versions:
  fpt: '*'
shortTitle: クイックスタート
---

## はじめに

ソフトウェア開発コースで教える教育者は、{% data variables.product.prodname_education %}からの割引、パートナーシップ、トレーニング、およびツールを活用して、重要なスキルを学生に対して効果的に教えることができます。

このガイドでは、{% data variables.product.product_name %}を使い始めて、アカウントと{% data variables.product.prodname_education %}を通じた割引にサインアップし、{% data variables.product.prodname_classroom %}.でコースと課題のためのスペースを作成します。

{% tip %}

**Tip**: If you're a student and you'd like to take advantage of an academic discount, see "[Apply to {% data variables.product.prodname_global_campus %} as a student](/education/explore-the-benefits-of-teaching-and-learning-with-github-education/github-global-campus-for-students/apply-to-github-global-campus-as-a-student)."

{% endtip %}

## {% data variables.product.product_name %}でアカウントを作成する

First, you'll need to create a free personal account on {% data variables.product.product_name %}.

{% data reusables.accounts.create-account %}
1. Follow the prompts to create your free personal account.

After you create your personal account, create a free organization account. {% data variables.product.prodname_classroom %}でクラスルームを作成および管理するには、Organizationアカウントを使用します。

{% data reusables.user-settings.access_settings %}
{% data reusables.user-settings.organizations %}
{% data reusables.organizations.new-organization %}
4. プロンプトに従って無料Organizationを作成します。

詳しい情報については、「[{% data variables.product.prodname_dotcom %}アカウントの種類](/github/getting-started-with-github/types-of-github-accounts)」を参照してください。"

## Applying for teacher benefits

Next, you'll sign up for teacher benefits and resources from {% data variables.product.company_short %} by applying to {% data variables.product.prodname_global_campus %}, a portal that allows you to access your education benefits all in one place.  {% data reusables.education.educator-requirements %}

{% tip %}

**ヒント** 個別の割引の他に、{% data variables.product.company_short %}では{% data variables.product.prodname_campus_program %}を通じて教育機関との提携も行っています。 詳しい情報については、 [{% data variables.product.prodname_campus_program %}](https://education.github.com/schools)のウェブサイトを参照してください。

{% endtip %}

{% data reusables.education.benefits-page %}
{% data reusables.education.click-get-teacher-benefits %}
{% data reusables.education.select-email-address %}
{% data reusables.education.upload-proof-status %}
{% data reusables.education.school-name %}
{% data reusables.education.plan-to-use-github %}
{% data reusables.education.submit-application %}

Once you are a verified {% data variables.product.prodname_global_campus %} educator, you can access {% data variables.product.prodname_global_campus %} anytime by going to the [{% data variables.product.prodname_education %} website](https://education.github.com).

## {% data variables.product.prodname_classroom %}をセットアップする

With your personal account and organization account, you're ready to get started with {% data variables.product.prodname_classroom %}. {% data variables.product.prodname_classroom %}の使用は無料です。 課題の追跡および管理、課題の自動採点、および学生へのフィードバックを行うことができます。

{% data reusables.classroom.sign-into-github-classroom %}
1. To authorize {% data variables.product.prodname_classroom %} to access your personal account on {% data variables.product.prodname_dotcom %}, review the information, then click **Authorize {% data variables.product.prodname_classroom %}**. !["Authorize {% data variables.product.prodname_classroom %}" button for personal account](/assets/images/help/classroom/setup-click-authorize-github-classroom.png)
1. 情報を確認します。 {% data variables.product.prodname_classroom %}を認可して{% data variables.product.prodname_dotcom %}のOrganizationアカウントにアクセスするには、[**Allow**] をクリックします。 ![Organization用の [Grant] ボタン](/assets/images/help/classroom/setup-click-grant.png)

  {% tip %}

  **ヒント**: [**Grant**] ボタンではなく [**Request**] ボタンが表示されている場合、あなたはOrganizationのメンバーであり、オーナーではありません。 オーナーは、あなたの{% data variables.product.prodname_classroom %}へのリクエストを承認する必要があります。 {% data variables.product.prodname_classroom %}でクラスルームや課題を作成および管理するには、Organizationのオーナーである必要があります。 詳しい情報については、「[OAuth App を認証する](/github/authenticating-to-github/authorizing-oauth-apps#oauth-apps-and-organizations)」を参照してください。

  {% endtip %}

1. [**Authorize github**] をクリックします。 ![Organization用の [Authorize] ボタン](/assets/images/help/classroom/setup-click-authorize-github.png)

## クラスルームを作成する

{% data reusables.classroom.about-classrooms %}

{% data reusables.classroom.sign-into-github-classroom %}
1. [**Create your first classroom**] または [**New classroom**] をクリックします。
{% data reusables.classroom.guide-create-new-classroom %}

## 次のステップ

クラスルームが作成できました。これで{% data variables.product.product_name %}と{% data variables.product.prodname_classroom %}を使ってコースを充実させる準備が整いました！  🎉

- {% data variables.product.prodname_classroom %}についてのビデオを見てみましょう。 詳しい情報については、「[{% data variables.product.prodname_classroom %}のセットアップの基本](/education/manage-coursework-with-github-classroom/basics-of-setting-up-github-classroom)」を参照してください。
- クラスルームおよびクラスルームの管理者を管理し、クラスルームの学生名簿を作成しましょう。 詳しい情報については、「[クラスルームの管理](/education/manage-coursework-with-github-classroom/manage-classrooms)」を参照してください。
- Use the Git and {% data variables.product.company_short %} starter assignment to give students an overview of Git and {% data variables.product.product_name %} fundamentals. For more information, see "[Use the Git and {% data variables.product.company_short %} starter assignment](/education/manage-coursework-with-github-classroom/use-the-git-and-github-starter-assignment)."
- 個々の学生またはチームの課題を作成しましょう。 {% data reusables.classroom.for-more-information-about-assignment-creation %}
- 課題リポジトリで直接、学生へのフィードバックをすみやかに行うため、自動テストを作成して実装しましょう。 詳しい情報については「[自動採点の利用](/education/manage-coursework-with-github-classroom/use-autograding)」を参照してください。
- {% data variables.product.prodname_education_community_with_url %}に参加しましょう。
