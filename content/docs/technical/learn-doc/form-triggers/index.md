---
title: Form Triggers
menu:
  sidebar:
    name: Form Triggers
    identifier: form-triggers
    parent: learn-platform-doc
    weight: 700
---

##### Component path:

`app/components/common/container/index.jsx`

#### Forms triggers hierarchy:

1.  ##### Mentor Rating

        Function:: checkMeeting();

        Api url:: https://interactions.kraftshala.com/api/is_pending_feedback/608134ea686bd729013aa1f2

        Conditions:: if ( res.data.meeting_id !== null) redirectTo /app/mentor-rating/${res.data.meeting_id}`
                    else:: checkWebinarFeedback();

2.  ##### Webinar Feedback

        Function:: checkWebinarFeedback();

        Api url:: https://api.kraftshala.com/fetchWebinarFeedback/{email}

        Conditions:: if ( res.data.user_email && res.data.webinar_id && res.data.webinar_name)  redirectTo  `/app/webinar-feedback/${res.data.webinar_id}/${res.data.user_email}/${res.data.webinar_name}`

        else:: checkExpertMeeting();

3.  ##### Webinar Feedback

        Function:: checkExpertMeeting();

        Api url:: https://api.kraftshala.com/fetchWebinarFeedback/{email}

        Conditions:: if ( res.data.user_email &&
        res.data.webinar_id &&
        res.data.webinar_name)  redirectTo  `/app/webinar-feedback/${res.data.webinar_id}/${res.data.user_email}/${res.data.webinar_name}`

        else:: checkExpertMeeting();

4.  ##### Webinar Feedback

        Function:: checkWebinarFeedback();

        Api url:: https://api.kraftshala.com/fetchWebinarFeedback/{email}

        Conditions:: if ( res.data.user_email &&
        res.data.webinar_id &&
        res.data.webinar_name)  redirectTo  `/app/webinar-feedback/${res.data.webinar_id}/${res.data.user_email}/${res.data.webinar_name}`

        else:: checkExpertMeeting();

5.  ##### Webinar Feedback

        Function:: checkWebinarFeedback();

        Api url:: https://api.kraftshala.com/fetchWebinarFeedback/{email}

        Conditions:: if ( res.data.user_email &&
        res.data.webinar_id &&
        res.data.webinar_name)  redirectTo  `/app/webinar-feedback/${res.data.webinar_id}/${res.data.user_email}/${res.data.webinar_name}`

        else:: checkExpertMeeting();

6.  ##### Webinar Feedback

        Function:: checkWebinarFeedback();

        Api url:: https://api.kraftshala.com/fetchWebinarFeedback/{email}

        Conditions:: if ( res.data.user_email &&
        res.data.webinar_id &&
        res.data.webinar_name)  redirectTo  `/app/webinar-feedback/${res.data.webinar_id}/${res.data.user_email}/${res.data.webinar_name}`

        else:: checkExpertMeeting();

7.  ##### Webinar Feedback

        Function:: checkWebinarFeedback();

        Api url:: https://api.kraftshala.com/fetchWebinarFeedback/{email}

        Conditions:: if ( res.data.user_email &&
        res.data.webinar_id &&
        res.data.webinar_name)  redirectTo  `/app/webinar-feedback/${res.data.webinar_id}/${res.data.user_email}/${res.data.webinar_name}`

        else:: checkExpertMeeting();

8.  ##### Webinar Feedback

        Function:: checkWebinarFeedback();

        Api url:: https://api.kraftshala.com/fetchWebinarFeedback/{email}

        Conditions:: if ( res.data.user_email &&
        res.data.webinar_id &&
        res.data.webinar_name)  redirectTo  `/app/webinar-feedback/${res.data.webinar_id}/${res.data.user_email}/${res.data.webinar_name}`

        else:: checkExpertMeeting();

9.  ##### Webinar Feedback

        Function:: checkWebinarFeedback();

        Api url:: https://api.kraftshala.com/fetchWebinarFeedback/{email}

        Conditions:: if ( res.data.user_email &&
        res.data.webinar_id &&
        res.data.webinar_name)  redirectTo  `/app/webinar-feedback/${res.data.webinar_id}/${res.data.user_email}/${res.data.webinar_name}`

        else:: checkExpertMeeting();

10. ##### Webinar Feedback

        Function:: checkWebinarFeedback();

        Api url:: https://api.kraftshala.com/fetchWebinarFeedback/{email}

        Conditions:: if ( res.data.user_email &&
        res.data.webinar_id &&
        res.data.webinar_name)  redirectTo  `/app/webinar-feedback/${res.data.webinar_id}/${res.data.user_email}/${res.data.webinar_name}`

        else:: checkExpertMeeting();

11. ##### Webinar Feedback

        Function:: checkWebinarFeedback();

        Api url:: https://api.kraftshala.com/fetchWebinarFeedback/{email}

        Conditions:: if ( res.data.user_email &&
        res.data.webinar_id &&
        res.data.webinar_name)  redirectTo  `/app/webinar-feedback/${res.data.webinar_id}/${res.data.user_email}/${res.data.webinar_name}`

        else:: checkExpertMeeting();
