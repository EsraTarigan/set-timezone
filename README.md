# Timezone Framework Laravel
# open file App\Providers\AppServiceProvider

Ubah Method boot()


    public function boot()
    {
         config(['app.locale' => 'id']);
         Carbon::setLocale('id');
    }

# open file config\app.php

Ubah Nilai Varibel berikut di app.php

    'timezone'  => 'Asia/Jakarta',

    'locale'  => 'id',

    'faker_locale'  => 'id_ID',
