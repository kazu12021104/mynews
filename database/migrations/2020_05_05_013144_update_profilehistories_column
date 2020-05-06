<?php

use Illuminate\Support\Facades\Schema;
use Illuminate\Database\Schema\Blueprint;
use Illuminate\Database\Migrations\Migration;

class UpdateProfilehistoriesColumn extends Migration
{
    /**
     * Run the migrations.
     *
     * @return void
     */
    public function up()
    {
         Schema::table('profilehistories', function (Blueprint $table) {
            $table->renameColumn('plofiles_id', 'profile_id');//<-記述
        });
    }

    /**
     * Reverse the migrations.
     *
     * @return void
     */
    public function down()
    {
        Schema::table('profilehistories', function (Blueprint $table) {
            $table->renameColumn('profile_id', 'plofiles_id');//<-記述
        });
    }
}
