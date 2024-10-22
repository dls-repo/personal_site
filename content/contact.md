+++
title = 'My Contact'
date = 2024-10-14T19:31:50-07:00
+++

If you have any questions, feel free to reach out!

        Mail::send('emails.contact', $data, function($message) use ($data){
        $message->from($data['email']);
        $message->to('example@domain.com');
        $message->subject($data['subject']);
    });
