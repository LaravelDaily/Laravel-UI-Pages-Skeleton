## Laravel UI: Bootstrap Pages Skeleton

Laravel boilerplate repository to create simple demo-projects. It allows to quickly add new routes/pages, and has examples of a table page, and a form page.

It uses the Starter Kit [Laravel UI](https://github.com/laravel/ui) based on Bootstrap framework.

![Laravel UI Table page](https://laraveldaily.com/wp-content/uploads/2021/09/Screenshot-2021-09-19-at-09.45.09.png)

![Laravel UI Form page](https://laraveldaily.com/wp-content/uploads/2021/09/Screenshot-2021-09-19-at-09.44.58.png)

-----

### How to use

Clone this project to your local computer.

```ps
git clone https://github.com/LaravelDaily/Laravel-UI-Pages-Skeleton.git
```

Navigate to the project folder.

```ps
cd Laravel-UI-Pages-Skeleton/
```

Install required packages.

```ps
composer install
```

create new .env file and edit database credentials there.

```ps
cp .env.example .env
```

Generate new app key.

```ps
php artisan key:generate
```

Run migrations. (it has some seeded data for your testing)

```ps
php artisan migrate --seed
```

That's it: launch the main URL

---

## More from our LaravelDaily Team

- Enroll in our [Laravel Online Courses](https://laraveldaily.teachable.com/)
- Check out our adminpanel generator [QuickAdminPanel](https://quickadminpanel.com)
- Purchase our [Livewire Kit](https://livewirekit.com)
- Subscribe to our [YouTube channel Laravel Daily](https://www.youtube.com/channel/UCTuplgOBi6tJIlesIboymGA)
